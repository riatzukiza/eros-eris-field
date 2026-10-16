# Owning plan: a physical field that changes character memory

License: GPL-3.0-or-later (this process document).

## Context and acknowledgement

This is the `eros-eris-field` owning source plan for the character loop:

**Encounter → field change → independent mood and attention → physical
associative recall → choice → observed outcome → memory.**

It acknowledges the selection and numeric proposal at Foresight
[`6a4438982fdf1eca98f856748bb23b19ab017c0a`](https://github.com/riatzukiza/foresight/blob/6a4438982fdf1eca98f856748bb23b19ab017c0a/docs/notes/2026-10-07-cephalon-field-kernel-selection.md),
based on character plan `1069d4c9bcba29ef55e6c72c7c597de101f0520b`.
Their actual planning review evidence remains in
[Foresight PR26](https://github.com/riatzukiza/foresight/pull/26) and
[PR22](https://github.com/riatzukiza/foresight/pull/22). No approval, round,
cooldown or readiness transfers to this source PR.

Accountable source implementation is in personal `riatzukiza/eros-eris-field`;
the organization is a separately qualified release destination. Its initial
base is `3af779f3ec306834710719ccb46f49370343eed9`. The isolated personal
checkout preserves the original donor checkout and its divergent local branch.
The accompanying [source manifest](../../.ημ/plan-evidence/cephalon-field-source-manifest.json)
binds the inspected source and the acknowledged selection document to actual
Git blobs and SHA256 values. It is an observation, not source acceptance.

The workspace task remains Foresight UUID
`ff3e628b-cd5c-4a89-a397-42cc88dbde70` (physical field, provisional 8 points),
with owner-selection predecessor `b5f2ba9e-8d67-4c73-9919-e275983aca87`
(provisional 3 points) and epic `63a0e4ff-353f-4c90-ab8a-7241d958d54c`.
This repository does not create a second board or copy those task identities.
All current cards are incoming; Markdown references do not prove admission.

## Outcome

One portable kernel supplies the actual motion, retained environmental fields,
intent bonds and contacts used by scoped recall. Its trace explains why an
authorized memory was encountered and included. It remains replayable across a
checkpoint and quiet elapsed time on the selected compiled Node target.

The kernel does not own the character's mood, social account, identity, grants,
or persistent memory store. Knoxx composes an independent, persistent mood model,
attention, slow traits, relationships and choices. OpenPlanner owns trusted
storage/query projection. Their integration must prove the complete loop;
successful layout motion cannot establish it.

## Source map and observed drift

| Inspected source at the bound base | Durable seam | Required correction or boundary |
| --- | --- | --- |
| `src/types.ts` | Particle, force and configuration vocabulary | Add explicit kind, provenance, units, revisions, safe integer wallets and validated bounds in portable shapes. Existing fields alone do not supply them. |
| `src/quadtree.ts` | Barnes–Hut partition and accumulation | Pure canonical entity ordering, finite bounds and deterministic accumulation; no authority from array insertion order. |
| `src/sim.ts` | Repulsion, springs, semantic charge, boundary pressure | Its `dt` clamp, per-call damping, in-place mutation, separate spring/semantic loops and node-only recentering do not meet the selected time, topology or field law. |
| `src/semantic.ts` | Local cosine and provider seam | Separate pure validated scoring from HTTP/Vexx and fallback. Explicit intent bonds survive dissimilarity. No provider request in a physical transition. |
| `src/graph-ant.ts` | An existing graph exploration experiment | Its `Math.random`, visit counts and graph-only pheromone are not seeded physical recall. Do not rename this implementation to satisfy the motion/contact law. |
| `src/index.ts`, `dist/` | Current package exports and checked artifacts | Retain compatibility deliberately; a future facade delegates to one qualified compiled kernel. Current checked artifacts are historical and unchanged by this plan. |
| `package.json`, `tsconfig.json` | Private package and compiler seam | The base has no package license or tracked license file. `tsconfig` extends a missing external monorepo path in an isolated clone. Standalone build and licensing remain explicit adoption work. |

Fork Tales' later correction at
[`f4c43d7b9c832a54bc5d224cb4d5d2497c04423b`](https://github.com/octave-commons/fork_tales/blob/f4c43d7b9c832a54bc5d224cb4d5d2497c04423b/docs/notes/system_design/2026-02-20-design-hole-responses-field-and-collisions.md)
controls the recovered sparse winds, immutable emitted ownership, intent
exchange and differing friction. Its older identity noise permutation and
owner-handoff behavior are evidence of drift, not implementation defaults.
OpenPlanner's donor variant and current graph route at `07085d6557b75834ce6f50e6c54b8ca47e1c7c08`
remain storage/integration evidence, not a competing physical kernel.

## Scope and proposed module boundary

| Proposed module | Owns | Cannot own |
| --- | --- | --- |
| `eros-eris-field.shape` (`.cljc`) | Domain-local revisioned state/input/result shapes, using canonical external contracts where defined | A second Katamorph registry or authorization law |
| `eros-eris-field.law` (`.cljc`) | Admission decisions, numeric/time/order/conservation/replay invariants | Host clocks, storage or public effects |
| `eros-eris-field.domain` (`.cljc`) | Pure advance, forces, sparse buffers, seeded motion/contact and projected recall results | Network semantic scoring or mood-model inference |
| Compiled CLJS Node adapter | Validated conversion and one compiled artifact ABI | Another force implementation in TS or Python |
| TypeScript compatibility facade | Explicit old-export migration and outward provider adapters | Silent behavior changes or a duplicated solver |
| OpenPlanner integration | Trusted visible projection, checkpoints and truthful idempotent persistence | Product identity/grant shortcuts or a new gateway |
| Knoxx integration | Encounter intake, independent mood/attention/traits, actor and grounded social choices | Re-embedding stable content or inventing observed outcomes |

No common Foresight law promotion is implied. A kernel catch-up worker is an
explicitly owned adapter and cannot become a second creative clock/event owner.
The existing native fifteen-minute creative clock remains the scheduler.

## Proposed ABI

The companion [ABI declaration](cephalon-physical-kernel-abi.edn) is proposed
data, not an implemented schema, executable validator or published package API.
Its exact names and fields require this source plan's review.

- `admit-state` takes the prior state (or an explicit empty state), a trusted,
  sealed visible projection and complete revisioned physical configuration, plus
  the explicit qualified producing-identity input described below.
  It returns either an admitted kernel state
  or a refusal with unchanged prior state and specific reason.
- `advance` takes that state, an exact integer-microsecond elapsed interval and
  ordered boundary events. It returns a new state, actual emitted observations,
  residual/backlog and explicit completeness. Zero elapsed input is always an
  exact no-op and cannot secretly drain backlog.
- `catch-up` explicitly drains already admitted backlog, with the same 100-step
  work cap, without admitting more elapsed time. It is a distinct operation from
  `advance(0)`. Repeated calls reproduce the already recorded quantum/event
  schedule. Backlog contains whole unexecuted quanta; residual is less than one
  quantum. Their combined safe-integer accounting cannot double-count time.
- `emit-recall` takes a scoped immutable request identity, validated seed
  snapshot, budget, Knoxx mood/lens revision and explicit new-particle contact
  profile bindings. It emits once or returns the authorized current retained
  request result on an exact immutable-input retry. Malformed requests or the
  same ID with different input/principal/scope return exactly refused/
  invalid-recall-request/reason-revision1, with exact unchanged prior state and
  no request result. Exact retries create no new particle, binding, time, draw,
  feedback or budget reset. Authority and finite-limit failures keep their own
  codes. Original matching input includes the contact-profile entries; identical
  polling never emits or reinforces.
- `read-recall` exposes the admitted request's retained motion/contact/bond
  result and authorized memory IDs with reasons, without mutation, emission,
  RNG advance or time advance. Its successful statuses are admitted, no-contact,
  complete, incomplete and exhausted; refusals use the closed ABI reason/status
  union and expose no recall payload. After qualified current-authority admission,
  the existing outer public read facade catches an actual unexpected local read-
  evaluation throw and returns exactly `{:status :failed :reason
  :recall-evaluation-failed :reason-revision 1}`. Pure kernel results remain
  success/refusal; this public invocation failure neither records nor synthesizes
  a failed request, returns prior state or recall payload, nor reinforces memory.
  Returned refusals and existing typed refusal mappings pass through unchanged
  before this unexpected-exception branch. Authority acquisition, policy,
  finite-limit and exposure-freshness failures retain their own contracts and
  are never converted to evaluation failure; provider/storage I/O and uncaught
  process termination also remain outside this catch. No exception-prose parsing,
  raw message/stack/private identifier or partial payload is returned or retained.
  Future actual-facade controls inject a genuine evaluator throw after valid
  authority, assert the exact three-key result and unchanged state, and preserve
  each ordinary success/refusal. No production fault-injection flag is required.
- `rebuild-revocation` privately reconstructs the complete permitted world from
  a compatible independently established clean checkpoint, separate trusted
  checkpoint evidence and complete ordered immutable history under current
  Axxium authority, plus an independently trusted current Clio provenance
  horizon. Snapshot state cursors may rewind; the main history range runs from
  the owner-attested checkpoint covered prefix through that unrewound tip.
  The checkpoint's storage position is not proof of the prefix it represents.
  Its exact inputs, replacement-history closure, pending and
  completed recall obligations and bounded refusal union are owned by
  `cephalon-physical-kernel-abi.edn#functions/rebuild-revocation` and
  `cephalon-finite-field-coupling.edn#retained-revocation`. A successful result
  replaces the complete state atomically; incomplete history or exhausted
  bounds preserves the prior state. No new elapsed time, random draw, storage,
  outcome execution or publication is admitted by this pure operation.
- `apply-outcome` takes an immutable observed choice/outcome identity and the
  admitted prior recall reference. It proposes attributed semantic feedback
  once, retaining effect/outcome identity, payload hash, scope and recall reference
  in pending state. The outer writer returns success only after actual storage
  success;
  refusal/failure never becomes a success receipt. Pending feedback and confirmed
  feedback are distinct. Retrying a failed outer write uses the same effect ID;
  only an actual writer acknowledgement admits the completed outcome and its
  persistent reinforcement. A prepared proposal is not success or permission to
  emit a second effect.
- `confirm-feedback` takes that state and a trusted outer writer acknowledgement
  carrying observation ID, writer principal, effect ID, outcome ID, payload hash,
  scope revision and actual storage result. It matches the retained pending
  effect/outcome/payload/scope, current scope and authorized writer before confirming
  that existing feedback once. The adapter resolves writer authority through
  the existing authorization boundary; a model assertion is not a trusted ack.
  A failed storage result leaves feedback pending without reinforcement; the
  shared transition union returns the explicit `feedback-storage-failed`
  refusal with the exact unchanged prior state and no confirmation. The actual
  failed writer observation remains outer Clio provenance; retry keeps the same
  pending effect ID with a new actual authorized writer observation. Repeated matching success acknowledgements
  return the existing confirmation without a second reinforcement. Conflicting,
  mismatched, revoked-scope or untrusted acknowledgements refuse unchanged state.
  The confirmation retains effect/outcome/payload/scope/writer/ack provenance so
  checkpoint/restart preserves idempotency; storage results are `persisted` or
  `failed`, never an attempted-write success.
  This pure operation records the independently observed result; it performs no
  write/publication, admits no time and draws no RNG.
- `checkpoint` encodes a canonical snapshot and transition/event cursor.
  This candidate binds the proposed `finite-field-snapshot/1` contract in
  `cephalon-finite-field-coupling.edn#snapshot-codec`: a closed domain map with
  codec, complete validated state and SHA256, reusing the exact existing
  field trace tagged-value algebra. It is not an already qualified runtime
  codec or a replacement for Clio event authority. Source qualification of
  the specified bytes/hash and continuation bounds is required before use.
- `restore` takes the prior state (or an explicit empty state), that snapshot and
  cursor, separately trusted checkpoint evidence, the independently current Clio
  provenance horizon and complete counted post-checkpoint history/replacement
  closure, the current trusted visible projection and physical configuration.
  The complete validated calibration is
  retained as `:physical-configuration` in the canonical state and snapshot,
  alongside its revision and canonical hash. `advance`, `catch-up` and every
  causal operation consume those actual values without an external cache or
  default; explicit restore/rebuild configuration must match them exactly.
  The snapshot's unkeyed SHA256 proves byte integrity only. Existing qualified
  Clio/OpenPlanner/Axxium adapters must independently admit the committed atomic
  effect record binding its expected snapshot digest, cursor, field revision,
  checkpoint effect ID, stored principal and scope. Restore/rebuild compare that
  separately admitted expected digest with the actual payload and wrapper
  digest, snapshot-state cursor, principal/scope and existing artifact/config
  bindings before admission. Field revision remains authenticated outer record
  metadata: qualified owners validate its actual record/effect, expected graph/
  field revisions and independently read back the committed component association.
  No field-revision value is invented in the closed snapshot state, compared
  to its graph projection revision or minted by the pure kernel. Pure digest
  comparison alone does not establish outer record authority.
  Separate checkpoint covered-provenance evidence and qualified Clio admission/
  fencing retain the independent current horizon through replacement exposure;
  missing capability refuses rather than creating a local event/fence engine.
  Changing a velocity, cell or fold and recomputing a self-hash
  cannot replace that authority. Missing, stale, foreign or conflicting evidence
  returns `:status :refused`, `:reason :checkpoint-evidence-unestablished` and
  `:reason-revision 1` with the exact unchanged prior state, before admitting any
  restored or rebuilt state/cursor. The same code applies to checkpoint admission
  during rebuild; it is distinct from an invalid snapshot or causal-authority
  refusal. Future fixtures include a genuinely qualified independent atomic
  record and matching snapshot as the positive control, plus each missing,
  stale, foreign and mismatched evidence case with this exact refusal.
  Pure checkpoint does not create persistence authority;
  no new signature system, event engine or policy evaluator is introduced.
  Before any causal use it validates kernel/config/hash/scope/projection
  revisions, current grants, snapshot/cursor agreement, exact time accounting,
  seed state/draw counter and attributed causal contributions. It returns the
  fully reconciled current state and cursor, or refuses with unchanged prior state and a specific
  reason. A mismatched or revoked scope refuses the snapshot; filtering its
  displayed memories cannot authorize retained pressure or trails. The adapter
  may separately admit a fresh current projection through `admit-state`.
  Restore/2 keeps the decoded checkpoint private until the existing bounded
  history/replacement reconstruction reconciles every operation after its
  owner-attested covered prefix through the independently current Clio tip.
  Retain later recall IDs, pending feedback, actual acknowledgement facts and
  confirmed outcome IDs, as well as physical state, both cursors and the pending
  queue; an old checkpoint cannot enable a second outcome/write/reinforcement.
  Replay only the original consumed physical and seed schedule. Reconstruct a
  historical nested replacement through its own recorded preceding horizon,
  never the outer current tip; shared checkpoint decoding does not call public
  restore recursively. All work and closure count under existing reconstruction
  limits and any stricter ordinary-call cap, without a budget reset or increase.
  Missing, stale, truncated, conflicting or changing history returns revision1
  `missing-or-ambiguous-rebuild-history` with exact unchanged prior state and no
  exposed restored result. Qualified owners retain admission/fencing through
  exposure; unsupported capability refuses. Restore admits no new elapsed time
  or random draw, performs no storage/publication and never reexecutes an
  external outcome or acknowledgement. Original immutable admitted facts are
  reconstructed once, not republished. Pending feedback retains its original
  effect identity and still requires an actual writer acknowledgement.

JS strings/arrays/objects convert at the adapter boundary to Clojure data. Native
provider and storage output is untrusted input. Both sides of replaceable seams
are validated. ABI refusal reason names remain explicit and revisioned.

All nine operations listed in `:state-transition-result :applies-to` use the
shared revision1 transition result: `admit-state`, `advance`, `catch-up`,
`emit-recall`, `apply-outcome`, `confirm-feedback`, `checkpoint`, `restore` and
`rebuild-revocation`. This is a result-shape list, not a claim that the pure
`checkpoint` operation changes state. The separate `read-recall` union remains
read-only. For the shared transition result,
success carries the operation's declared result; refusal carries the exact
unchanged prior state, an operation-specific reason and reason revision1.
The required reasons include `invalid-elapsed-us`, `unsafe-arithmetic` and
`overflow`; these three do not replace the other specific admission, revision,
scope, identity or writer refusal reasons. `admit-state` receives an explicit
empty prior state on first admission, so refusal has no implicit host state.
The ABI preserves the advancement observation, residual, backlog and completeness
fields inside the successful operation result. Its `catch-up` declaration
explicitly drains existing backlog only and reproduces the recorded quantum and
event schedule; it cannot admit new elapsed time or select a new schedule.

## Numeric, temporal and replay commitments

1. The authoritative initial target is compiled CLJS on Node with finite
   binary64 scalars in 2D world units. No f32 packing or JVM/browser/Python
   numerical parity claim. Velocities are wu/s, accelerations wu/s², mass
   positive dimensionless inertia; friction and decay are s⁻¹. Embeddings stay
   immutable and model/dimension-revision-bound, not spatial coordinates.
2. Counts, wallets, elapsed time, residuals, backlog and RNG counters are exact
   integers within `[0, 2^53-1]`. This candidate proposes one explicit exception:
   floor-derived field cell indices are signed safe integers within
   `[-(2^53-1), 2^53-1]`. The coordinator amendment is satisfied by reviewed
   decision `020d97fecae4a8d0d277b9b2695d9482620b4a76` and actual merge
   `8c649fee2e95e5ec6b5304a3351a0e16fca60533`. This owning plan's current
   review and native readiness remain required before implementation; the
   original positive-only selection stays historical provenance.
   Nonfinite scalars, missing coefficients, duplicate IDs, missing endpoints,
   unsafe integer arithmetic and mismatched revisions refuse unchanged state.
3. Host UTC observation identity is separate from monotonic elapsed integer
   microseconds. Negative, noninteger and nonfinite intervals refuse; exact zero
   changes nothing, including RNG. Explicit `catch-up` is a separate operation
   that admits no new elapsed time. Proposed integration quantum is 10,000µs,
   with exact residual carry and at most 100 substeps per call. Remaining time
   is explicit backlog, never clamped away or called current.
4. Boundary events bind an ordered kernel-time schedule. With the same schedule
   and full draining, splitting calls preserves quanta, residual and draws.
   Events whose declared time has not been reached remain pending; future events
   cannot affect an earlier substep. Elapsed decay is `exp(-lambda*t)`, layer
   `lambda=ln(2)/half-life`; friction is `exp(-gamma-kind*h)`.
5. One prior/next buffer pair gathers prior forces, updates velocity, applies
   elapsed friction, updates position and resolves ordered contacts; deposits
   and contact outputs affect the following buffer. Entities, cells, bonds,
   quadtree accumulation and contact pairs have canonical ID/tuple ordering.
6. `gamma-presence > gamma-nexus > gamma-daimoi >= 0` and matching static
   threshold ordering are enforced. Passive nexus/presences have no daimoi
   propulsion. Test zero thresholds. Recentring moves all spatial state
   together or only the visualization, never nexus alone.
7. One attributed intent-bond topology includes authored/reply/pin/inspiration/
   contradiction evidence. Structural and semantic representations cannot
   double its force. Dissimilar explicit pinning retains its purpose and
   flexible bond. Stable content embeddings never change to encode current mood.
   Each bond declares its actual evidence kinds from those five allowed kinds,
   and the shared force invariant counts one logical bond once across its
   structural and semantic representations. A bond need not invent evidence
   of all five kinds; declaring the invariant is not proof it has been enforced.
8. Eight sparse velocity layers use keys
   `[scope-revision, layer-index, floor(x/cell-size), floor(y/cell-size)]`.
   Indices `0..7` have versioned semantic bindings, not English keyword counters.
   Deposit is `gain-layer * weight-layer * velocity * h`: actual speed changes
   amplitude. Radial saturation and sparse pruning are explicit configured
   observations; retained event provenance permits reconstruction/revocation.
9. `xorshift32/1` has exact state `{:initial-seed s :word x :draw-counter n}`.
   Validate nonzero uint32 seed/word and an exact safe nonnegative counter.
   Sequentially compute `a=U32(x XOR U32(x<<13))`,
   `b=U32(a XOR floor(a/131072))`, `y=U32(b XOR U32(b<<5))`.
   U32 means unsigned modulo2^32 for validated internal integers; right shift
   is zero-fill, never arithmetic. Store and emit post-update `y`; unit output
   is exactly `y/4294967296`. Increment once per actual draw, including rejected
   selection draws; invalid external values or counter overflow refuse without
   reseeding/coercion, and a refused transition commits neither word nor counter.
   No read/checkpoint/zero-advance draws or unbounded seed-to-counter validation.
   ABI goldens give20 independently calculated successive words, including high-bit
   seeds, and first-draw binary64 unit bits. These are arithmetic references,
   not executed kernel tests or qualification of shuffle/noise draw placement.
   Candidate order remains canonical. Lazy 2D simplex uses a qualified seeded permutation and
   pinned gradient table/scales/octaves; the donor identity permutation is not
   adopted as proof of independent seeds. No clock or `Math.random` enters it.
10. Same-target continuous replay tolerance is
    `abs(a-b) <= 1e-9 + 1e-9*max(abs(a),abs(b))` in declared units. IDs, event
    order, residual time, seed counters, wallets, contacts, paths, granted scope,
    included memories, chosen actions and exact byte hashes must match exactly.
    A near-threshold scalar tolerance cannot excuse a different discrete choice.

## Explicit resolution proposed for partial exchange

The later design's partial-absorption wording is resolved here as **bounded
integer exchange with a surviving particle**. This is a reviewable selection,
not an assertion that donor code already implements it. Three operations stay
distinct:

| Operation | Wallet effect | Particle and provenance effect |
| --- | --- | --- |
| Full absorption | Transfer the particle's entire wallet vector atomically into a recipient able and authorized to accept every unit; insufficient capacity refuses absorption | Terminate the particle once; preserve emitter/recipient attribution, seed and mantle lineage |
| Deflection | No wallet transfer | Update trajectory using the configured contact geometry/restitution; preserve emitted owner, seed, grants and attributed mantle |
| Bounded exchange | Transfer whole counts of explicitly admitted intent kinds up to the configured per-kind cap and recipient capacity | Particle survives with residual wallet; emitted owner/seed/grants remain immutable and both sides gain attributed exchange evidence |

For a directed admitted exchange of kind `k`, propose
`q[k] = min(senderAvailable[k], recipientRemainingCapacity[k], exchangeCap[k])`.
All values are nonnegative safe integers. Intent kinds and contacts are processed
in canonical order using a recorded contact-pass ledger of remaining available
units and capacities. Incoming units cannot be spent again during that pass.
Debit and credit commit atomically; per-kind totals are exactly conserved.
`q=0` is an observed no-transfer contact, not success or new influence.
No implicit fallback between operations, fractional rounding, minting, borrowing
or owner handoff. Any overflow refuses the entire transition.

Deflection uses a finite normalized contact normal `n` pointing outward from
the recipient's contact surface toward the incident particle. Relative velocity
is `v = particleWorldVelocity - recipientWorldVelocity`, with restitution
`e∈[0,1]`. Reflection applies exactly when `(v·n) < 0`:
`v' = v-(1+e)*(v·n)*n`. Only that negative-dot reflection branch adds the
recipient's world velocity back after resolution. For `(v·n) >= 0`, separating
or tangent contact returns the original particle world components bit for bit;
it does not reconstruct them from the rounded relative subtraction. With
particle world x=1 and recipient world x=-2^53, the latter round trip would
incorrectly return 0. Preserve original signed-zero bits as well. Degenerate normal refuses
the operation. For a stationary recipient, `n=[1,0]` and `e=1`, approaching
`v=[-1,0]` must become `[1,0]`; separating `v=[1,0]` must stay `[1,0]`.
These are required future RED cases, not executed solver tests. Admitted
classification/geometry and coefficients are explicit configuration/input;
random exploration cannot decide ownership, authorization or resource transfer.
The reviewed RED matrix must cover multi-contact ordering, insufficient
capacity, zero units, exact conservation and replay at threshold boundaries.

## Physical recall, scope and character integration

The trusted adapter resolves the stored Knoxx actor and real grants before
sealing any seed, mass, field, bond, contact, trail or compacted history.
Private content cannot influence a visible result indirectly. Revocation
rebuilds retained contributions under a new permitted scope revision before
further choices; output-text filtering cannot repair hidden influence.

A recall request binds actor/scope/projection revisions, query and embedding
identity, kernel/config/artifact, seed, mood/lens revision and physical budget.
It emits an owned daimoi once. Real movement, sampled field, intent bonds and
contacts determine encountered nodes and included authorized memories. Trace
actual starting nodes, motion samples, bonds, contacts, inclusion reasons,
kernel horizon, draw counter and budget/refusal/completeness. A vector seed is
allowed; vector results alone or renamed graph path costs are insufficient.

Knoxx owns a separate model/state for mood and appraisal, with causal encounters,
elapsed relaxation, bounded updates and a versioned lens. Mood changes intent
weights and attention, never grants or emitted ownership. Slow traits and
relationships require accumulated encounter/outcome evidence. One stable actor
persists across facets and restarts. This describes a character model and makes
no claim of subjective feelings.

Intake includes outside feed/notifications and grounded interaction, with durable
cursors and self-output separated. The character may like, reply, follow,
unfollow or decline based on actual encounter/memory/mood/relationship evidence.
Account effects use the existing authorized adapters, immutable effect IDs and
observed outcomes. Retrieval or an attempted publication cannot stand in for a
useful association or delivered social interaction. Failed persistence/effects
remain explicit failure. Transient motion deposits describe actual movement;
semantic reinforcement requires a later actual choice/outcome and is idempotent.

## Calibration, build and licensing adoption

All forces, bounds, capacities, eight layer bindings, static thresholds, speed
caps, contact radius/restitution, half-lives, noise scales and pruning/saturation
limits belong to a complete revisioned calibration artifact. No donor constant
is a production default. Qualify the 10,000µs/100-step proposal at declared
entity/bond/particle/cell caps, including sparse high-density and quiet-time
catch-up loads. Record runtime, workload, time/memory limits, observed measures,
configuration/artifact hashes and explicit rejection boundaries. Until that
artifact exists, numeric selection is planning input, not admission.

The standalone build must remove dependence on an absent external `tsconfig`,
reproduce one compiled CLJS artifact from exact source and pinned dependency
inputs, and qualify the compatibility facade against declared old exports.
No build/test success is asserted by this documentation PR. Future source work
must establish its independently reviewed package/dependency/build contract.

Propose LGPL-3.0-or-later for new library code produced under the global contract,
and GPL-3.0-or-later for new process documents. The inspected historical source
has no tracked license grant/package field; the OpenPlanner copy's LGPL metadata
cannot retroactively supply one here. Before literal extraction or distribution,
the owning repository must record the source rights decision, applicable license
and retained author/notices for the actual selected bytes. This proposal does
not rewrite donor package metadata or declare a distribution already licensed.

## Execution slices and review/readiness

The existing 8-point solver story stays unchanged. Its breadth warrants a
source planning review of these slices; counts below are ordering/scope proposals,
not native card creation, admitted points or new board state:

1. Portable shapes/ABI, exact refusal/time/seed/order and standalone build seam.
2. One intent topology, deterministic forces and sparse elapsed field buffers.
3. Immutable emitted ownership, motion/contact operations and conserved exchange.
4. Scoped physical recall, idempotent trace/checkpoint and bounded replay/load.
5. OpenPlanner persistence and Knoxx mood/intake/choice/outcome composition, in
   their owning repositories, consuming the qualified artifact.

Before implementation laws/tests in RED, native Rheos must actually retain and
enforce the proposed predecessors: reject missing, unfinished and cyclic
dependencies; admit a completed predecessor; and perform lawful readiness/WIP
operations for the relevant card. Existing upstream Rheos work owns this gap.
Neither this file nor a local parser/validator/writer can substitute for it.
An approved source plan may remain unmerged while that independent gate is open.

Initial review setup had no repository App publisher secrets observed, and the
inherited active YAML requested eager squash auto-merge. This plan disables that
caller and adds the pinned canonical evidence-review caller. Later verified
existing App installation coverage and encrypted repository secret setup are
recorded in the workflow document and setup observation. First hosted review
`37667654730` failed before model execution on quoted Unicode paths in trusted
generated context; narrow root ignores preserve the strict source cleanliness
guard. A successful current-head hosted publication remains required. A missing
or failed route remains a setup failure, not a quota exception or approval.
`docs/agent-workflows.md` reports actual routes; canonical PR policy remains in
the external skill pack. Auto-merge stays off.

## Required verification and non-goals

The following are **future RED/GREEN obligations**, not tests run by this plan:

- Invalid/nonfinite/time/overflow admission preserves state; zero time does not
  move, decay, drain backlog or draw RNG.
- Split/drained event schedules and quiet-time decay preserve elapsed physics;
  excess backlog is visible, future events do not apply early.
- Sparse deposit retains velocity amplitude; passive nexus and unequal friction
  work; one explicit dissimilar bond avoids double force and lost intent.
- Same-seed/noise/permutation/restart replay and ordered collisions preserve
  exact contacts, wallets, owners, paths and choices within scalar tolerance.
- Checkpoint/restore preserves state and cursor without time, RNG or effect
  replay. Malformed snapshots, inconsistent cursors/time/seed counters, mismatched
  kernel/config/scope/projection revisions, revoked grants and unattributed
  causal contributions refuse unchanged prior state before causal use.
- Deflection approaching `(v·n)<0`, separating `(v·n)>0` and tangent `(v·n)=0`
  cases bind the outward normal, restitution and restoration of a moving
  recipient's world velocity. Only the approaching case reflects.
- Absorb/deflect/exchange capacity, zero/multiple contacts and exact conserved
  integer provenance falsify fractional, minted or respent units.
- A changed bond/deposit under fixed seed changes actual traced physical recall
  and inclusion, not merely a rendering.
- Hidden/foreign/revoked content cannot affect any seed, mass, pressure, trail,
  contact, compaction or feedback; projection revision prevents stale use.
- Polling/repeated requests do not emit/reinforce twice; failed storage returns
  failure; successful outcome feedback requires independently observed evidence.
- Feedback confirmation tests actual success/failure acknowledgements, duplicate
  success and retry after failure with the same effect ID; mismatched payload,
  outcome, scope or writer and conflicting acknowledgements refuse unchanged.
  Confirmation performs no storage/publication, time advance or RNG draw.
- Two outside encounters under fixed seed change field and independent mood/
  attention, then recall and meaningful choice; continuity survives restart.
- Full integration verifies actual scoped social effects and artifact quality,
  destination access, nonempty matching image alts, deduplication and frequency.

The existing reserved head, acknowledgement before delegated work, strict child
specs, maker reservation through terminal parent/delegates, truthful lifecycle,
one owner and cloud dependency guarantees remain prerequisites. Ten-minute
attempts, at most three, 1/5-minute backoffs within a 36-minute execution/backoff
budget remain bounded. Expiry is never proof of termination: unresolved ownership
stays quarantined until termination or fencing blocks both old artifact writes
and publication. Do not restart active makers to adopt a plan or maintain review.

Non-goals: copy the whole Fork Tales runtime, deploy a second gateway/scheduler,
duplicate TS/Python forces, equate keyword counters with mood, equate layout or
vector hits with physical recall, promote common-law ownership silently, alter
running services/credentials, or mark the full creative character goal complete.

## Acceptance and actual verification of this plan

Plan acceptance requires full current-source review of the acknowledged source
map, ABI/numeric/collision selection, licensing/build/calibration boundaries,
consumer authority, falsification matrix and estimate/decomposition. The plan
must retain all unresolved implementation requirements explicitly. Native review
identity, complete changed input, mandatory checks and settlements are assessed
through the current canonical skill, independently from Foresight approvals.

Actual preparation checks are recorded append-only in `.ημ/receipts.edn`:
source-manifest byte equality, EDN parse, YAML parse and diff hygiene. They check
the submitted planning artifacts and workflow syntax. They do not test physics,
compile the future kernel, validate board readiness or establish deployment.


## Canonical configuration and replacement identity precedence — 2026-10-15

Current Codex roots4289000341/4289000362 expose real missing configuration and
sampler representation. The single normative configuration grammar is
`cephalon-finite-field-coupling.edn#configuration-schema`, version
`finite-physical-configuration/1`: every map is closed, vectors ordered and
numeric types/ranges explicit. It locates all configuration-owned field/layer/
kind/force/noise/contact coefficients in one complete retained value, encoded with the existing
trace tagged-value algebra and hashed without a trace-record envelope. State
revision equals its revision; the digest is exactly64 lowercase hex characters.
Eight-vector index is the same layer throughout; daimoi weights remain in the
immutable request, while passive read/deposit vectors belong to configuration.
One admitted bond carries its own nonnegative strength/rest-length once;
bond coefficients and request weights retain their declared state/input carriers
and complete state/snapshot hash coverage.
Revision-bound contact geometry selects exactly one ID/revision parameter set;
its recipient kind/radii/restitution must match, with no independent override.
Automatic eligible-pair enumeration consumes the profile selection retained in
canonical admitted geometry or its original recorded boundary input. Complete
state/snapshot/history custody preserves it for replay; kind matching or the
first table entry cannot supply a missing selection.
The named force families/ranges, per-bond coefficient carriers, contact-profile
references and explicit256-entry permutation/gradient/scale/octave carriers are
**proposed representation choices in this correction**, not recovered qualified
defaults. Owning source review must accept them; forces/noise laws, table generation/
indexing and draw placement still require qualification. A revision string does
not adopt hidden donor formulas, clamps, constants, defaults or arbitrary code.

Restore/2 input cursor identifies the authenticated checkpoint; output cursor
identifies the reconciled current consumed state, with admitted cursor retained.
Empty-tail roundtrip remains exact. An older checkpoint is valid input without
promising historical output. Across every replacement, the physical target is
reconstructed, but applicable once-only recall/effect/outcome/confirmation facts
from the qualified provenance prefix survive in existing collections, with exact
payload/principal/scope matching applicable to each fact variant and current authority/
privacy; unestablished binding refuses/quarantines. Never erase them solely
because a target is old or invent an acknowledgement, journal or live effect.
Actual successful writer acknowledgement is required for confirmation only;
absent acknowledgement preserves pending status, and a failed writer preserves
its existing refusal/no-reinforcement disposition.
Recorded restore/2 uses its own original pre-operation horizon. An actually
qualified older restore without that input preserves its recorded target and
uses original owner-qualified predecessor evidence; no synthetic historical
argument or reinterpretation as restore/2. Existing clean-root requirements apply;
an authenticated historical digest alone cannot establish clean revocation state.


## Closed retained carriers and request refusal — 2026-10-15

Current Codex roots4289184904/4289184913/4289184922 identify missing canonical
contact/trail carriers and an unspecified request refusal. The ABI now owns
`finite-contact-profile-bindings/1` at the required root state key
`:contact-profile-bindings`: closed version/bindings container and exact
particle-ID/recipient-ID/profile-ID/profile-revision entries for every actual
particle/recipient entity pair admitted by the eligibility matrix, including
separated pairs, in canonical pair order. Admission receives
the complete explicit map from the qualified projection; emission receives an
explicit recipient/profile/revision vector and binds the actual qualified newly
emitted particle identity. Original admission/emission payloads retain those
values. Exact retries do not populate again. No kind-only, first-table-entry,
unrecorded geometry or external lookup can supply a missing selection. The
complete carrier is hashed and replayed under existing authority and all caps;
invalid data returns refused/invalid-contact-profile-binding/revision1 unchanged.

Mandatory `:trails` is a closed `finite-physical-trails/1` carrier. Each entry
identifies entity plus actual qualified origin and ordered samples; each sample
is exactly [executed-step, moved-position, final-velocity, causal-support-IDs,
actual-deposit-IDs]. Append once per surviving entity after an executed quantum's
ordered contact/final-cap/threshold stage, using actual values already used for
the existing deposits. Zero/read/checkpoint/queued events append nothing. Actual
origin/support references remain in existing qualified provenance, including
ended sources; no trail producer mints native event authority. Snapshot includes
every retained sample/reference. Current authority applies to transitive support,
and revoked influence requires reconstruction of affected motion, contacts,
fields and trails together, with permitted control. Historical replacement uses
the reconstructed physical branch; the once-only feedback rule never unions
abandoned trails back in. Charge all visits, values, validation and reconstruction
under existing state/checkpoint/input/history/work/time caps and stricter ordinary
limits. No ring eviction, truncation, new decay/force, summary or uncharged scan is
introduced. Complete unchanged workload targets still require future proof.
This motion/deposit trail interpretation, stage/frequency/layout/support and work
mapping are explicit proposed representation choices for owning review, not donor
pheromone adoption, a UI-only retag or an already qualified trail-force mechanism.

The same state-closure audit found the already required nexus-to-memory binding
had no named nested home. Every nexus in `:ordered-entities` now has a closed
`finite-nexus-memory-binding/1` value at `:memory-binding`, with explicit memory
or non-memory tag. The memory variant carries actual owner memory ID, content
revision and graph snapshot revision; non-memory has no invented memory fields.
Missing/nil is not the non-memory tag. Qualified projection/original boundary
inputs populate it with original principal/scope/provenance, snapshot/hash retains
it, and restore/rebuild recovers it before inclusion without another memory
lookup. Same-current authority and exact actual source revisions are required;
retagging denied memory to preserve its influence is forbidden. Explicit
non-memory contacts preserve existing physics and produce no memory inclusion.
This closes an existing inclusion requirement, without a new lookup/classifier,
operation, grant or packet. Actual owner revision types remain authoritative;
field storage or projection-rule labels cannot replace a graph snapshot revision.

Malformed or conflicting request admission now returns exactly
`:status :refused`, `:reason :invalid-recall-request`, `:reason-revision 1`, exact
unchanged prior state and no request result. Exact authorized immutable-input
retry remains idempotent with the current retained request result, including
original contact inputs, and no new particle/time/draw/binding/feedback/budget.
Authority and finite failures keep their own codes. Invalid trail or nexus
binding uses respectively invalid-trail-state or invalid-nexus-memory-binding,
refused/revision1; both the authoritative read reason/status table and reason
vector include all three new invalid-carrier codes with no recall payload.

Future controls cover complete nonempty carrier checkpoint/restore/continuation,
split/catch-up/unsplit equality, missing/extra/duplicate/foreign/mismatched data,
ended legitimate source, revocation and nested replacement, genuine explicit
non-memory nexus and exact/conflicting request retry, plus all existing exact/
one-over bounds. No domain/carrier/transaction/load fixture was executed by this
planning edit; same14 packets75/physical21 and no native readiness/estimate change.


## Current producing identity and pre-operation horizon — 2026-10-15

Actual native Codex review5541153717 identified missing explicit inputs, not an
implemented runtime failure. Every ABI operation now receives the same closed
`finite-qualified-producing-identity/1` argument: kernel revision, actual compiled
artifact SHA256, build qualification ID, launch-profile ID/SHA256 and numeric
profile ID. The existing qualified source/build/loaded-runtime adapter verifies
the actual identity before the call and retains its binding through exposure;
a copied label or `qualified=true` flag supplies no qualification. Pure code
consumes validated data and performs no host discovery. First empty-state
admission populates all six state fields from this input. Existing state and
checkpoint fields must exactly match it before use, including restore/rebuild.
Original argument bytes remain in qualified history and all existing wire/work/
continuation caps apply, including the unchanged512KiB remaining-argument bound.

Configuration `:mechanics-revision` must exactly equal that qualified kernel
revision and the admitted state's kernel revision. Its root `:revision` remains
the separate calibration/config revision. No range alias, copied config hash,
same-revision different binary or silent migration creates compatibility.
Missing/unqualified/changed producing identity returns revision1 refused
`producing-identity-unestablished`; established identity with different mechanics
returns revision1 refused `mechanics-revision-mismatch`. Both preserve the exact
prior state and expose no operation result; read returns its exact three-key
refusal without state or recall payload. Future actual positive/mismatch and
empty-admission fixtures are required, not executed here.

The top-level restore/rebuild reconstruction horizon is the qualified Clio tip
immediately BEFORE that current invocation. It includes every earlier admitted
operation and excludes only the actual current invocation, never an arbitrary
filtered tail. If Clio records the invocation first, qualified owner evidence
must bind that actual invocation, its immediate predecessor and the absence of
intervening unaccounted operations. Otherwise the owner reserves the exact
pre-operation boundary before recording the invocation. Qualified admission or
fencing protects that boundary through result exposure; missing capability or
concurrent unaccounted history refuses before any replacement is exposed.
The current invocation never recursively reconstructs itself. Historical nested
replacements still use their own recorded pre-operation horizons. Future
pre-recorded-with-attested-predecessor positive, inclusive-self, missing/foreign
predecessor and changed-boundary controls keep the existing history refusal and
all unchanged caps. No local Clio engine/fence, event rewrite, new time/draw,
external effect or physical implementation is introduced.


## Current finite observation and collision boundary — 2026-10-16

The preceding canonical-carrier proposal's dense unbounded motion-sample history
was an owning representation choice, not recovered donor physics. Native
Codex4289442134 correctly identified that indefinite appends would permanently
fill the continuation cap. The operative `finite-physical-trails/2` replaces
that choice with a **derived motion observation window**, separate from causal
field retention. The reviewed configuration must explicitly supply N, a positive
safe integer at most256; no production value/default is selected here. Across
ALL live and ended incarnations keep at most N samples total, not N per entity.
After each actual executed quantum, keep the newest min(N,total) by executed
step ID, exact unsigned-UTF8 entity ID, then origin-provenance ID; remove empty
projection entries. Identical original schedules produce identical windows
regardless of call partition, catch-up or restore. Missing/invalid configuration
refuses; independent profile-fit qualification precedes consumption.

Only this derived observation window may evict samples. It supplies no force,
deposit, memory-inclusion, authority or reconstruction input. Current causal
field/contribution state and qualified provenance, original immutable Clio
history/checkpoints, complete request motion/contact evidence, inclusion
witnesses and full recall trace accounting stay in their existing carriers.
Reconstruct the window from the qualified physical schedule; never turn it into
a substitute for missing source history or a lossy recall result. No field-force
retention or source-compaction rule is introduced. All bytes, visits, references
and reconstruction still count under the unchanged caps. A full valid N-window
must continue by replacing its oldest observation, with independent controls
for ended incarnations, ties, many quanta, split/restore and unchanged causal
results. This prevents trail-only gratuitous growth; it does not establish
indefinite capacity for every other retained state or a successful load profile.

The finite selected Scope already refuses unavailable absorption/exchange. The
ABI now states supported operations `[:deflect]` and separately reserves full
absorption/bounded exchange for the broader program. Attempting either reserved
operation returns revision1 refused `unsupported-contact-operation`, exact
unchanged state and no transfer, termination or binding removal. The original
wallet/capacity/conservation/termination obligations remain future obligations,
not enabled operations or hidden ambient inputs. No new wallet model enters
this finite milestone. Any separately qualified supported population removal
must atomically remove all incident contact bindings and replay the same removal;
complete projection replacement leaves exactly the resulting current pair set.
Unsupported absorption removes neither entity nor bindings.

For a structurally valid128-UTF8-byte request ID, the ordinary valid control
applies. A structurally valid129-byte ID returns revision1 refused
`finite-input-byte-limit`; structural-invalid-request controls stay within the
byte cap. Existing authority and finite-resource failures retain their own codes.
The complete parser check does not execute any of these future domain controls.

## Explicit conditional restore allocation — 2026-10-16

Native4289311646 is addressed by naming the integration work and its actual
completion boundary. The existing ABI8 codec/restore3 allocation owns closed
signatures/carriers, pure codec/private decoding, identity/mechanics guards,
public boundary wiring and independently executable interface/refusal
qualification. It does NOT claim full successful history reconciliation as an
ABI8 Done condition: that implementation depends on the later shared engine.
Contact8's existing shared-rebuild3 owns BOTH the shared reconstruction engine
and actual public restore/rebuild integration acceptance: authenticated nonempty
history, nested replacements, once-only recovery, exact/one-over bounds and
outer quarantine. A module's file location does not transfer that packet's work.
Atomic8 supplies the genuinely qualified transaction/checkpoint-evidence port;
causal8 retains the later complete contact-driven paired persistence/readback/
served proof. No acceptance cycle through a not-yet-implemented engine is allowed.

Fourteen packets75/physical21 is now expressly a **conditional estimate proposal**,
not an assertion that new integration work costs zero because of reuse. Before
Ready, independent owning planning review must price the complete boundary,
engine, integration and fixture matrix exactly once against those allocations.
If they do not fit, re-estimate an existing packet or propose a separately
estimated packet and obtain the required inclusion/owning review and lawful
Rheos changes before implementation. No current native point, dependency, status
or agreed primary body is changed by this source proposal. Existing Incoming
card text still requires owning Foresight mirror/review and native adoption;
links or this conditional allocation supply no Ready.


## Closed physical carriers and exact checkpoint overhead — 2026-10-16

Current CodeRabbit review5541484661 identifies the state/checkpoint boundary
mismatch and historical credential tense. The checkpoint's exact tagged wrapper
adds180bytes to its encoded state: state1,048,576, checkpoint1,048,756, encoded
tail1,048,576 and remaining arguments/framing524,288 compose to3,670,196bytes
within the unchanged4,194,304-byte input cap. This is a derivation of proposed
codec bytes, not an executed kernel fixture. The exact-state-cap positive,
checkpoint cap, one-over and largest-state lifecycle controls remain required.
The historical workflow section now consistently describes its then-active
credential mapping in past tense; current caller isolation is unchanged.

Current Codex review5541487995 adds four connected contract corrections.
`finite-physical-entity/1` now closes each presence/nexus/daimoi variant and its
nested physical values. Extra source graph metadata stays in its owner records;
adapters cannot silently retain different extra entity fields and still claim
the same snapshot. Source IDs, embedding revision/dimension and principal remain
qualified by their existing owners. This proposed field shape grants no memory
or authorization authority and enables no reserved wallet transfer operation.
The complete exact variant is hashed, restored and rebuilt under the qualified
kernel revision, with two-adapter snapshot equality as a future qualification.

`finite-request-field-weights/1` is a mandatory closed `field-weights` carrier
inside the original immutable admitted request: version, actual configuration
mapping revision, eight read weights and eight separate deposit weights. Retain
the complete value with the original admission inputs in `recall-requests` and
original events. The daimoi's request ID selects exactly one matching original
principal/scope record; retry, hashing, replay, restore and rebuild consume those
exact values. Missing/invalid/mismatched carriers use revision1
`invalid-recall-request`; authority and byte/work refusals keep their own codes.

The read-only closed refusal map and its reason vector both include revision1
`finite-trace-budget-exceeded` with status `refused`. Conflicting or untrusted
feedback acknowledgements have an explicit revision1
`invalid-feedback-acknowledgement` refusal with unchanged prior/pending/confirmed
state and no confirmation or reinforcement. Current causal-authority refusals
take precedence; a matching authorized failed writer observation retains its
separate `feedback-storage-failed` branch. All six corrections are proposed
owning contract/prose changes. Parser checks establish EDN shape only; no domain,
continuation, wallet, codec or live B1–B3 behavior is claimed implemented.
