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
  identity and application authorities, plus an independently trusted current Clio provenance
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
  Clio/OpenPlanner and identity/application authority adapters must independently admit the committed atomic
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

The nine entries in `:state-transition-result :applies-to` use revision1 success
exactly `{:status S :result P}` and refusal exactly `{:status :refused :state PRIOR
:reason R :reason-revision 1}`. The actual entrypoint selects its exact closed
payload keys/types/status in the ABI's `:success :by-operation` table. There is no
flat alias, operation tag, extra key, reason on success or result/partial payload
on refusal. Operation-local result vectors are exact key-list mirrors of that
table. Refusal preserves the exact prior argument, including the same explicit
empty value for initial admission/restore, and every existing reason/precedence.
Local unchanged/absence notes constrain the result; they are not extra runtime
keys or nil placeholders. No shared failed branch is introduced.

Admit-state, emit-recall and feedback preparation/idempotent retrieval use
admitted. Advance/catch-up use complete iff the returned state has zero backlog,
otherwise incomplete, exactly matching payload completeness and mirrored state
counters. A nonzero subquantum residual alone is not incomplete. Valid zero
advance returns exact input state and empty observations, drains nothing and
reports the unchanged backlog; no-backlog catch-up is complete and unchanged.
Existing admission checks, 100-step ceiling and original schedule remain.

Emit's request-result is its exact current authorized retained recall success;
its own existing recall status remains independent of outer admitted. Exact
retry returns original state/result without another emission, binding, time,
draw, feedback or budget reset. Apply-outcome's admitted means preparation or its
existing idempotent retrieval, never storage/confirmation success. Confirm-feedback
is complete only after its existing matching actual authorized successful writer
acknowledgement or admitted matching confirmed retry; returned confirmation equals
the retained entry. Exact retry leaves state/confirmation unchanged. Failed
storage and invalid/conflicting acknowledgements keep their specific refusals.

Checkpoint, restore and rebuild use complete for their existing completed pure
operation. Checkpoint returns the existing canonical snapshot map and matching
consumed cursor without changing state or manufacturing a persistence receipt.
Restore returns complete current reconciled state/cursor only after existing
restore/2 history/authority/once-only/bounds checks. Rebuild returns exactly its
ten-field payload; snapshot, cursor map, scope/authority map, projection, folds,
pending queue and completed-result dispositions must all agree with its same
rebuilt state. Whole-invocation accounting covers actual main/nested/repeated
reconstruction under the unchanged limits. Its qualified replacement checkpoint
is the existing pure snapshot value, not a new authenticated storage record or
field revision. Complete reconciliation can retain admitted physical backlog;
no partial-history or post-return recovery success is introduced.

The separate read-recall success/refusal/public-failure unions, global status
vocabulary and all effect restrictions remain unchanged. Complete state,
configuration/identity, recall, source/authority, snapshot and bounded-accounting
references retain their owning meaning. This closes outer/payload-key structure
only where explicitly specified: still-open nested values do not become closed
through a reference or version label. Trace/inclusion/snapshot/input codecs and
existing work/byte/time/cutoff laws remain; there is no new result wire envelope,
operation, registry, admission/recovery rule, authority or budget.


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

Missing/extra/duplicate keys, wrong containers or nesting, invalid vector lengths,
coefficient-domain errors and failed configuration invariants use exactly
`:invalid-physical-configuration`, status `:refused`, reason revision `1`.
The shared transition returns exactly `:status`, the exact unchanged prior
`:state`, `:reason` and `:reason-revision`, without an operation result. Read
returns exactly the three status/reason/revision keys, without state or recall
payload. The normative mapping is the coupling EDN configuration schema's
`:invalid-configuration-result`; both read reason declarations and rebuild's
closed reason codes include it. Existing authority, producing-identity and
finite-byte/work checks retain their precedence and distinct reasons. A
structurally valid foreign mechanics revision keeps
`:mechanics-revision-mismatch`; unsupported contact operations and actual
arithmetic overflow keep their existing codes. Future schema-negative controls
isolate each defect with other gates valid, including admit/read/restore/rebuild.

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


### Canonical bond and memory-source custody — 2026-10-16

Current Codex review5541694130 on d6 identifies roots4289777747/7750/7753.
The proposed finite-physical-intent-bond/1 closes the complete bond collection
and record, exact endpoint order, contribution/provenance reference vectors,
intent/evidence kinds, invariant and finite coefficients. Original matching
source values remain in existing canonical provenance/countable history; IDs
alone grant no authority and pure transitions fetch no owner. Snapshot encoding
retains all and only those fields, with no extra adapter metadata or invented
coefficient aggregation. This is a proposed representation, not qualified code.

Memory variant finite-nexus-memory-binding/2 now retains a closed original
source-binding value: actual stored principal, memory owner, scope/resource,
Clio source event and original authority source revision. The complete binding
is populated from the qualified original projection/source envelope and retained
in entity/state/snapshot/history; advance receives the existing single explicit
current trusted authority projection, qualified from the identity and application
owners, to validate actual stored identities/resources before causal
use. Original provenance is not a current grant. Rebuild retains that original
binding and reconstructs against current authority; no ID inference, ambient
lookup, authority minting or denied retagging.

The shared result's declared reason set now includes operation-local
invalid-recall-request, missing-or-ambiguous-rebuild-history,
invalid-rebuild-binding and revocation-rebuild-budget-exceeded. New invalid
bond data has invalid-intent-bond/refused/revision1 consistently in shared,
read map/vector and rebuild declarations. All prior state-preservation, current
authority and finite bounds remain. Declared closed-shape/hash/source-binding
controls still require future owning RED/GREEN; parsing these maps executes no
bond, authorization, snapshot or physical behavior.


## Exact elementary state representations — 2026-10-16

The ABI's proposed `finite-state-elementary-carriers/1` fixes previously open
representations without adding a state field or physical law. Initial empty
prior state is exactly `nil` for admit/restore; it is not a retained state.
Consumed and admitted cursors each use `nil` for an owner-established empty
role or exactly the map `{:event-id ID :stream STREAM :seq SEQUENCE}`. All three
values must match the same complete original qualified Clio envelope. These
maps do not attest a covered history prefix, current horizon or freshness.

Sparse cells are one ordered vector of exact `[cell-key velocity]` entries.
Each key is `[scope-revision layer-index cell-x cell-y]`, with the existing
signed-safe cell indices and exact two-component finite binary64 velocity.
Order is scope UTF8, numeric layer, numeric x, numeric y; keys are unique.
The state retains only the committed prior buffer. Existing zero-absence,
sampling, saturation, pruning and signed-zero component laws remain unchanged.
RNG is exactly the existing initial-seed/word/draw-counter map, without an
optional per-record version field or a counter reset.

Successful feedback confirmations are an effect/outcome-ordered vector of
closed six-key maps: effect-id, outcome-id, payload-hash, scope-revision,
writer-principal and ack-observation-id. Existing full original acknowledgement
and payload/principal/scope evidence remains in qualified provenance/history;
the IDs and digest do not establish writer success. Confirmed outcome IDs are
exactly the distinct successful confirmation outcomes in strict unsigned UTF8
order. Existing once-only admission, exact retry and replacement precedence
remain required; failed acknowledgements do not become confirmation records.

This closes these elementary representations only. Complete pending-event,
provenance, request/result, inclusion-fold, pending-feedback and native authority
leaf shapes still need their exact owning definitions and selected actual
historical payload schemas. The complete state is not yet closed or Ready.
No generic canonical blob, label or wrapper supplies missing owner authority.
The existing ABI8 authoring/qualification boundary, all original caps, required
positive fixtures and native Incoming states remain. Future independent adapter,
malformed-container, cursor/source, signed-cell/zero, confirmation/retry and
full checkpoint/restore/rebuild controls qualify these proposed choices.


## Observed authority ports

Source inspection on 2026-10-16 separates three actual pieces of the current consumer path.
These exact commits were read as immutable local blobs and GitHub separately
confirmed each commit exists. This is source evidence, not a selected Field
supplier, reviewed artifact, default-branch assertion or live qualification.

| Observed source | Actual supplying behavior | Remaining Field qualification |
| --- | --- | --- |
| [Axxium 603ea4c](https://github.com/open-hax/axxium/blob/603ea4cd88f589c621234f73d3afd6e4e08788b8/src/cljs/axxium/auth/session.cljs#L70), with its [AuthContext](https://github.com/open-hax/axxium/blob/603ea4cd88f589c621234f73d3afd6e4e08788b8/src/cljs/axxium/schema.cljs#L76) | Resolves actor, entity, email, capabilities and roles from current session/credential storage. The registered context map is open. | An actual Field action/resource decision, native policy/grant-version binding and through-exposure custody are not supplied by those functions. |
| [Knoxx b6f4dfb authority resolver](https://github.com/riatzukiza/knoxx/blob/b6f4dfbb4a006934a191c8fb3f26f270579e7e62/backend/src/cljs/knoxx/backend/infra/character/authority.cljs#L9) and [graph snapshot](https://github.com/riatzukiza/knoxx/blob/b6f4dfbb4a006934a191c8fb3f26f270579e7e62/backend/src/cljs/knoxx/backend/infra/character/encounter_runtime.cljs#L332) | Reloads stored actor/org/membership policy through the canonical Knoxx resolver. Its graph `policy-revision` is an `encounter-policy:` digest of principal/source bindings. | That derived snapshot fingerprint does not establish an Axxium-native grant version, a protected commit or custody through Field result exposure. |
| [OpenPlanner 3ab5ffb trusted callback adapter](https://github.com/riatzukiza/openplanner/blob/3ab5ffbb6e34a2ee3607a74bf421785d47d5391d/packages/graph/graph-claim-core/src/openplanner/graph/recall/mongo.cljs#L21), with its [closed callback contract](https://github.com/riatzukiza/openplanner/blob/3ab5ffbb6e34a2ee3607a74bf421785d47d5391d/packages/graph/graph-claim-core/src/openplanner/graph/recall/mongo_contract.cljc#L12) | Accepts server-supplied scope/project/records, re-reads the binding after awaits and reports field status `not-loaded`. | No owner-native decision/version producer or atomic authority/exposure fence is established by these source functions. |

The older Axxium 2439 and Clio 788 routing observations remain historical source
references. Selecting a concrete supplier must reconcile actual owner source,
full closed value schema, principal/action/resource/version meanings and custody
with the existing Field contract. A wrapper, renamed digest, actor label or
injected callback alone cannot establish the missing owner facts. These reads
also do not demonstrate that a new upstream feature or additional packet is
necessary: an existing qualified owning interface may still supply them. No
owner reassignment, policy implementation, scope/point change or native Ready
transition is made by this source inventory.


## Retained recall success representation — 2026-10-16

The proposed ABI `finite-retained-recall-success/1` gives read success exactly
status, motion, bonds, contacts, included-memory-ids, inclusion-reasons,
kernel-horizon and budget-result. It retains the five declared statuses under
the explicit fixed-target lifecycle selection below. Actual caller, counter,
checkpoint production and positive controls still require qualification. An
empty inclusion vector or hit count cannot invent a status. Pure refusal
and qualified public failure remain their existing separate three-key results.

Motion contains the original emitted particle ID and every produced sample in
its retained horizon, using the existing five-value sample tuple. The separate
global derived-trail window cannot truncate this request result. Bond trace
entries retain step ID and the full actual logical bond evaluated for that
particle. Contact trace separates the complete per-step eligible-pair inventory
from actual overlaps, so a separated pair is evidence of eligibility without an
invented contact. Closed overlap records retain original geometry/profile,
frozen moved positions, actual dot intermediates and the actual response branch.
The nonnegative branch keeps original world velocity bit for bit and has no
inactive reflection fields. Negative reflection retains its actual intermediate
values. Per-contact raw response remains distinct from final post-pass speed
cap/threshold velocity; the existing operation trace and causal support remain.

Inclusion IDs and their ten-key reasons remain in exact first-witness order,
with the same two-field inclusion codec and byte counter. A request budget
result retains its original complete physical budget and the existing horizon,
fold-work, result-byte, trace-record and trace-byte counters. Reading validates
and charges its own work without mutating or resetting the retained request.
No counter is encoded into the payload it counts.

A checkpoint position has exactly kernel-time-us, event-cursor and
admitted-event-cursor under the same qualified request history and identity.
It identifies the physical cut; it does not authenticate persistence or mint a
native checkpoint/effect identity. The existing outer qualified checkpoint
record must match that cut and independently bind the actual snapshot. A
retained result cannot contain its enclosing snapshot or that snapshot's digest:
that would make the state/hash recursive. Original checkpoint/history custody
and all authentication requirements remain. Historical replacement preserves
the original result horizon or explicitly invalidates it under the existing
rules; the current root clock alone cannot judge a retained historical result.

Actual owner history/checkpoint/authority source leaves and production of the
selected target/lifecycle facts still require qualification. These representation
choices supply no complete-state closure or
Ready claim. The explicit target/lifecycle selection below changes the owned
request shape and predicates. Original force formulas, stage order, complete
trace coverage, required positives, global caps, recovery/replay, effects and
external-owner authority remain.


## Retained recall request and retry

Proposed on 2026-10-16 under the existing ABI8 authoring boundary.

`recall-requests` is a request-ID-ordered unique vector of the exact proposed
admission records. Each retains the entire five-value original emit input tuple,
complete original qualified custody and original actual emitted daimoi, plus a
current or safely invalidated result disposition. The scoped request retains its
original principal/scope, projection/graph bindings, full query, complete embedding
vector/source, kernel/configuration binding and exact read/deposit weights. The
existing weight/contact/entity/scalar contracts apply without normalization,
new producer or ID generation. Closed key layout does not close the explicitly
unqualified seed-source/owner/history/production leaves. The original query consumes the
observed owner contract below; candidate source observation does not qualify its
Field adapter.

Exact retry compares all original immutable input values and their original
principal/scope, not changing input state, fresh authority or evolved RNG/live
motion/population. Existing state/current-authority/producing-identity/configuration
and bounds checks still apply. It returns the unchanged CURRENT input state and
its current authorized retained result, never the original admission state or a
stale payload. Original contact entries are compared without new binding
population. No second emission, effect, time, draw or budget reset occurs.

A current disposition references main's single RecallSuccess contract, preserving
all five successful statuses. Safe qualified reconstruction may instead retain
an invalidated disposition with no success payload. Full original source values
remain immutable/private/current-authority controlled; stored authority proves no
future permission. Existing checkpoint/history reference carriers remain explicit
unresolved owner bindings. Neither original-input nor result-disposition wrappers
contain an enclosing state/snapshot or its self-referential hash. Public read
failure, denials and storage/provider failures are not retained request variants.
Every original source and duplicate value counts under existing budgets; no
recovery/admission/cutoff/eviction change or whole-state closure is claimed.


The validated seed's owned key layout is specified below; its complete original
presence source and physical birth mapping remain unselected. Naming xorshift
RNG state or an available query vector does not determine that seed. The original
physical budget's owned layout below is also distinct from global call/rebuild
limits. Those source
definitions and actual producer compatibility must be selected before native
readiness; the closed wrapper does not supply them by name.

## Original query owner — 2026-10-16

The proposed `original-query-carrier` consumes OpenPlanner's existing portable
`openplanner.graph.recall.contract/request` schema and its native validator. The
scoped Field request's `query` value is the **whole original native request map**:
version, recall ID, query text, k, fetch, max-nodes, max-cost and feedback. There
is no Field-owned duplicate schema or registry. Source is pinned to candidate
`riatzukiza/openplanner` commit
`3ab5ffbb6e34a2ee3607a74bf421785d47d5391d`, file
`packages/graph/graph-claim-core/src/openplanner/graph/recall/contract.cljc`,
SHA256 `350499515a80c71c6c9afc9ca463e9a4813e5d637da257049ec35eb8eb3f9d94`.

The actual observed Knoxx producer is `graph-hydration!` in
`backend/src/cljs/knoxx/backend/infra/agent/hydration.cljs` at candidate
`b6f4dfbb4a006934a191c8fb3f26f270579e7e62`, file SHA256
`a7632b6194e190c560e343c6148807bb9de3a0bfdf96fa96a48ccec83744769e`.
It passes that complete map to scoped graph recall with the original message as
query text. These source bytes matched their immutable Git blobs at inspection.
This selects a representation from actual owner source; it does not establish
protected review, compiled compatibility, deployment or a physical producer.

Retain all eight original values and their types for exact retries, including
the full query text with unchanged scalar UTF8 spelling. The nested native
recall ID must equal the enclosing request ID and the original emitted daimoi's
recall-request ID. This remains an owner request ID, not a Clio event UUID or a
new effect identity. No new ID, hash-only query, normalization or text truncation
is allowed. Knoxx's observed ID derives from conversation ID and message, without
the retrieval options or principal/scope. Reusing that ID with changed options or
original principal/scope therefore follows the existing conflicting-retry
refusal; this wrapper cannot repair it by silently minting a new identity.

Native retrieval options retain their original graph meaning. They do not become
physical inclusion cutoffs, the separate physical budget, or grants. Owner
feedback remains `:none`, without changing Field's separate outcome/confirmation
operations. A valid query supplies no source/principal permission;
existing current-authority checks still govern every causal use and exposure.

Both the owner schema and the existing Field profile apply. In particular, the
owner's query length limit does not widen Field's 512-UTF8-byte other-string cap
or 128-byte request-ID cap. An owner-valid query exceeding a Field byte bound
returns the existing `finite-input-byte-limit` unchanged-state refusal, without
truncation, normalization or a changed profile. All original bytes, copies and
validation count under the existing input/state/checkpoint/work limits. Before
Rheos Ready, select exact owner/source/interface and adapter/ID mappings plus the
complete fixture plan, preserving existing required upstream/native prerequisites.
Implement the owning consumer after lawful Ready; qualify actual compiled owner
consumption, adapter mappings and executed fixture fit before consumption and
Done. Query-embedding and presence-seed source, physical birth
mapping, original custody, history and lifecycle production remain unqualified.

## Originating-presence seed — 2026-10-16

The selected Fork Tales correction at
`f4c43d7b9c832a54bc5d224cb4d5d2497c04423b`,
`docs/notes/system_design/2026-02-20-design-hole-responses-field-and-collisions.md`,
SHA256 `c4ef760eb2b1cd050a95391a0b36675c2971e351d17d3559dd97e962373185fc`,
distinguishes the seed embedding from the originating presence (lines98–100),
the nearby-particle mantle, and the weighted intent embedding. It describes the
presence seed/lens in terms of that presence's meaning and purpose (lines122–128).
The checked local note matched its immutable selected Git blob. This recovers
the intended semantic roles; it does not adopt donor runtime defaults or prove
a current Knoxx producer.

The proposed `validated-recall-seed-carrier` owns exactly five keys:
`origin-presence-id`, `emitted-owner`, `embedding`, `embedding-revision`, `source`.
Retain the complete finite binary64 vector with its original qualified source
dimension and revision. The origin is an actual qualified presence ID; do not
assume it equals a stored principal ID. The original qualified source must bind
that presence to the original principal/scope. The emitted owner equals the
request's original stored principal and the original emitted entity's owner.
The vector/revision exactly match the original presence source and the emitted
daimoi's seed fields. The entity contract now names that source explicitly.

This snapshot is immutable for the emitted particle. Exact retries compare the
whole original seed record, without requiring the origin presence to remain
live or substituting its current lens. The scoped request's separate embedding
is the original query vector. A query vector, ranked graph entry node, mantle,
weighted intent, mood/lens revision or xorshift word is not a fallback for the
originating-presence seed. Even numerically equal vectors do not prove identical
roles, source or permission. Global RNG initialization/draw rules are unchanged.

OpenPlanner's inspected `query-embedding!` and `rank-nodes` at candidate
`3ab5ffbb6e34a2ee3607a74bf421785d47d5391d` produce a query vector and a ranked
semantic graph entry. The route returns field not loaded. Neither supplies the
presence-seed producer or the initial physical particle mapping. Position,
velocity, mass, wallet, mantle lineage and emission identity keep their existing
qualified original source obligations; the seed vector cannot invent them.

The physical presence entity's closed shape stays unchanged and has no seed/lens
field. Consume the complete original qualified presence source through existing
admission projection/source/history custody; do not infer it from an entity ID
or add a hidden field. `FullOriginalQualifiedPresenceSeedSource` remains a named
unselected source schema and producer. A generic map, model alias, digest or
invented prompt embedding does not close it. Full original values and copies
count under the existing caps. Before Rheos Ready, select exact source/binding,
physical birth mapping and fixture obligations, satisfying existing required
upstream/native prerequisites. Owning implementation follows lawful Ready;
actual source production, compiled consumption and executed fixture fit still
require qualification before consumption and Done. This source
correction resolves an ambiguous planned embedding origin; it demonstrates no
running seed defect, new authority, complete-state closure or physical behavior.

## Original per-request physical budget — 2026-10-16

The proposed `request-physical-budget-carrier` owns exactly five required original
caller values. Each is an exact safe nonnegative integer. Zero means zero;
there is no omitted-key default or unlimited sentinel.

| Budget key | Inclusive ceiling | Existing retained counter |
| --- | ---: | --- |
| `max-horizon-quanta` | 100 | `executed-horizon-quanta` |
| `max-semantic-fold-work` | 67,108,864 | `accumulated-semantic-fold-work` |
| `max-inclusion-result-utf8-bytes` | 8,388,608 | `canonical-result-byte-count` |
| `max-trace-records` | 131,072 | `trace-record-count` |
| `max-trace-utf8-bytes` | 8,388,608 | `accumulated-trace-utf8-byte-count` |

These are proposed per-request limits under existing source ceilings, not a
claim that the per-call profile was already a stored request budget. The original
map is retained in admission and budget-result custody. Exact retry compares
the entire original map; the remaining balance cannot replace it. All five
counters retain the same original qualified start and explicit target across
split calls, catch-up, checkpoints, restore and reconstruction, without reset.
The observed prefix endpoint advances only through qualified execution; the
completed target has the same final cut, trace and counters across equivalent
split/unsplit schedules.

In particular, 67,108,864 fold-work units and 131,072 trace records across an
entire request horizon are newly explicit owning selections using the existing
per-call numeric ceilings. They are not recovered frozen per-horizon policy.
A lower selected request limit can refuse a transition earlier; it cannot
shorten the selected horizon or alter the force law.

The inclusion-byte count measures the complete two-field
`finite-contact-inclusion-result/1` envelope at that result, not summed repeated
reads or the whole read-success map.
The trace uses the complete existing `finite-field-trace/1` envelope. Empty
envelopes still have encoded overhead; a structurally valid zero budget may not
fit an actual operation. No trace, required record or serialization work may be
omitted to make it pass. Every actual retained counter must stay within its
original limit; equality alone guarantees no broader admission.

Existing global call and rebuild guards still charge all actual work. A request
budget accounts for its semantic fold; it does not grant separate physical-world
work, a multiplied allowance per request, or a reset after transport/restore.
State/input/checkpoint/history/continuation limits and every original budget-copy
byte remain charged. The 100-step call limit and an otherwise admissible
101-quantum world input's 100-executed/one-backlog behavior remain unchanged.
Active-horizon and other resource obligations still apply; elapsed time above
100 quanta is not itself a new refusal. The 64-total-reconstruction limit remains
independent, even if an original request permits 100 quanta.

Inclusion-result or trace overflow keeps `finite-trace-budget-exceeded`; semantic
fold work overflow keeps `finite-work-budget-exceeded`. Refuse the whole
unchanged operation, without a shortened horizon, partial result or truncation.
Malformed budget shape/value keeps the existing request-refusal contract and
byte/authority/request precedence. Target/progress inconsistencies use the
operation-specific refusal selection below. Counter equality alone cannot
manufacture success: the selected `exhausted` predicate additionally requires
the entire explicit target to be complete and a positive original limit consumed
exactly. Qualify the actual caller/counter/cut source, lifecycle, zero/exact/one-over,
split/restored replay and unchanged required positives before consumption.
This is an owned representation proposal, not executed budget behavior, complete
state closure, native Ready or a larger resource allowance.

## Fixed recall target and lifecycle — 2026-10-16

This is an explicit owning ABI8 interface and semantic selection. Git history
shows that `6d8b610b390839178a8c3e100a8b3c3a4ce1e4bd` added the five-success
enum to its parent `4a286aedfdc01bb25c7fc457ad7ddff7fce7dc68`; it did not
define exclusive lifecycle predicates. The inspected six current `src/` files
do not supply that mapping. The labels are planning vocabulary, not evidence of
an existing native lifecycle that an adapter can import.

The Field-owned scoped immutable request now requires one additional owned key,
`target-horizon-quanta`: an explicit original caller Count from zero through100,
at most the original physical budget's `max-horizon-quanta`. Do not infer the
target from that maximum, query options or a future checkpoint. This changes the
proposed Field request shape; the original five `emit-recall` input values and
function arity are unchanged. The nested native OpenPlanner request remains its
unchanged owner shape. Actual target plumbing remains unimplemented.

Retain the target in original inputs, retries, folds, history and result horizon.
Let `n` be the actual executed request quanta from qualified history. Require
`0 <= n <= target <= original horizon budget <= 100`, with all existing resource,
state, authority, trace and source checks. The start is the actual qualified
post-emission admission cut. The result's selected end is its actual committed
observed prefix cut. A target is an execution objective, never a fabricated
future authenticated checkpoint. Safe clock/history arithmetic must bind both
real positions and `n`. The result horizon has six keys, adding the immutable
target to its existing actual positions/count/history/fold revision.

After every validity and current-authority guard passes, evaluate these
exclusive predicates in order:

The producer commits the matching status with the whole result. Read/retry
validate that agreement and return the stored result; they cannot repair a
mismatched status through read-time retagging or a hidden state write.

| Predicate | Read status |
| --- | --- |
| `n = 0 < target` | `admitted` |
| `0 < n < target` | `incomplete` |
| `n = target`, with at least one positive original budget limit exactly equal to its matching retained counter | `exhausted` |
| `n = target`, no preceding exhausted predicate, and no actual qualified overlap observations | `no-contact` |
| Remaining `n = target` case, with actual qualified overlap observations | `complete` |

Use `contacts.observations`, not eligible separated pairs or the count of
included memories. A fully completed presence-only or non-memory-nexus contact
may therefore be `complete` with empty inclusion vectors. A zero target is
terminal at the actual start cut, not `admitted`. At zero target, positive byte
limits exactly consumed by mandatory envelope overhead can select `exhausted`;
equality to a zero-valued limit cannot. This is the selected successful meaning
of exhausted: all original requested work is complete at a positive budget
boundary. It never means an unaffordable next step or a failed/truncated horizon.

All eight read fields remain mandatory for every status. A nonterminal success
contains the complete, untruncated actual committed prefix and its explicit
unfinished target. It cannot claim target completion. Failure in an attempted
later operation preserves the previous committed state/result, not a partially
updated candidate or an early exhausted closure. This distinguishes truthful
progress from partial output of a failed operation; it does not relax trace,
inclusion, privacy or checkpoint authentication.

If target3 finishes inside a world100 call, materialize and independently qualify
the actual target3 cut. The world100 snapshot cannot be relabelled as that cut.
The qualified cut/source must fit all existing state, history, input and work
limits. Freeze the completed request endpoint, trace and counters, retaining the
full result in `recall-requests` as the completed active fold closes atomically.
The particle and original request record/weight binding remain available for
later lawful world motion; closing recall does not terminate a particle, delete
its immutable request or extend the closed recall horizon. Current-authority
reconstruction and safe invalidation retain their existing obligations.

Malformed/conflicting target/progress data uses `invalid-recall-request`,
revision1, for emit/read where that reason is admitted, preserving original
byte/authority/request precedence and the existing result shapes. Restore and
rebuild retain their applicable existing binding/history/state reasons; do not
introduce a universal invalid-request remapping into their different unions.
Real authority/source/history/byte/work failures retain their specific codes.
No new refusal/status vocabulary, event identity, clock, force or resource cap
is selected. The otherwise-admissible100/101 world control and64-total rebuild
limit remain.

Before Rheos Ready, select exact caller/source/interface bindings and the full
fixture plan, preserving existing required upstream/native prerequisites. This
does not claim implemented Field plumbing or executed domain controls. After
lawful Ready, implement and qualify actual caller target input, zero and
in-progress cuts, mid-call cut
materialization, counter/history production and all five executed positives,
including the lawful exhausted case and budget failure before target. Equivalent
split/restored schedules must retain the same original target and final cut,
trace and counters; a changed-target retry refuses. All original required
privacy, reconstruction, codec and cap controls remain. Independent executed
qualification is required before consumption and Done. These are source-law and
future executed-control obligations, not implemented lifecycle, compiled owner
consumption, native Ready, whole-state closure or live B1–B3 proof.

## Active inclusion-fold record — 2026-10-16

The existing17 fold fields now have an exact owned closed-map/type layout in
`inclusion-fold-state/entry-fields`. The vector under `entry` is the complete
key set, not a runtime list or permission to accept additional keys. Retain one
strictly request-ID-ordered entry per qualified current unfinished request with
`n < target`; completed, zero-target and invalidated requests have no active
entry. The original request/result/source records remain separately retained.

| Field | Selected carrier or agreement |
| --- | --- |
| `fold-revision` | Exactly `finite-contact-inclusion/1` |
| `request-id`, `daimoi-id` | Existing IDs matching the unique parent request and original emitted entity |
| `stored-principal-binding` | Exact original parent principal/scope pair; provenance, not a grant |
| `scope-authority-and-graph-versions` | Closed current-context map with scope, projection and graph revisions plus the parent's complete qualified authority binding/projection |
| `field-history` | Same complete qualified current fold/result history binding |
| `start-checkpoint`, `selected-end-checkpoint` | Existing real checkpoint-position carrier, with full independent matching source |
| `target-horizon-quanta`, `executed-horizon-quanta` | Exact original target and actual `n`, matching the parent current result |
| `processed-contact-cursor` | Nil or exactly step-id/pair for the last actual qualified overlap |
| `accumulated-semantic-fold-work` | Existing retained semantic-fold work Count |
| `first-witnesses-in-canonical-contact-order` | Vector of the existing ten-key inclusion reasons in first-witness order |
| `dedup-memory-ids` | Unique vector equal to the ordered witness-memory-ID projection and retained inclusion IDs |
| `canonical-result-byte-count`, `trace-record-count`, `accumulated-trace-utf8-byte-count` | Exact existing parent budget-result Counts |

The original principal/scope pair and current authority context have different
roles. Current scalar versions come from actual qualified current source, not
original request versions or an arbitrary witness. Full parent original/current
owner records and history remain mandatory. The existing unresolved qualified
authority/history leaf schemas are referenced, not closed by a copied revision,
digest or local authorization decision. This closes the owned key/type layout
without claiming transitive or whole-state closure.

The cursor is nil exactly when the actual per-request overlap vector is empty.
Otherwise it identifies its last canonical step/pair, including duplicate-memory,
presence and non-memory overlaps. Separated eligible pairs do not advance it.
Step ID is the existing absolute kernel substep-end microsecond time, not relative
`n` or a new event identity. Later no-contact steps can advance `n` while leaving
the cursor at an earlier step. No accepted record represents only part of its
committed prefix. First witnesses equal retained inclusion reasons; dedup IDs
are neither a set nor a separately ID-sorted copy.

All five counters exactly match the retained result's counters. Its complete
original budget equals the admission budget, and counters stay at or below
their corresponding limits. Their existing
semantic/result/complete-trace measures do not become witness or overlap counts.
Empty encoded envelopes retain their actual overhead; initial records cannot be
filled with guessed zeros. Retaining another data copy adds its actual storage
and validation costs under existing bounds, not a new logical physical record.
Complete owner/source values and duplicates remain counted.

At the target, one successful whole transition retains the complete matching
terminal result/status in the parent and removes only that active fold. Request,
source history and field-weight bindings remain for later lawful world motion,
read and retry. If the private target cut is reached but a later step in that
world operation refuses, neither terminal result/cut nor fold removal commits.
Qualified reconstruction and safe invalidation retain their existing complete
closure rules; clock rewind alone cannot reset `n`, cursor, target or counters.
An invalidated result cannot leave an exposable/processable active fold.

The full source/interface/binding and fixture plan, with existing required
upstream/native prerequisites, precede Rheos Ready. Own implementation and
domain RED/GREEN follow lawful Ready; actual producer/cut/replay/counter and
atomic-handoff controls require independent executed proof before consumption
and Done. No fold algorithm, producer, actual checkpoint, profile fit, native
readiness or B proof was executed by this representation edit.

## Original query-embedding source — 2026-10-16

The ABI now selects the existing query embedding's `source` as a closed
`finite-original-query-embedding-source/1` capture record. Its seven keys are
`version`, `owner-query`, `model-selection`, `formatter-inputs`,
`formatted-query-text`, `generate-output`, and `producer-source`. This is a
proposed Field adapter record; the observed OpenPlanner factory currently
returns only graph selection with `field-status: not-loaded` and does not export
or persist this record. No current embedding-capture implementation is claimed.

The observed boundary at OpenPlanner
`3ab5ffbb6e34a2ee3607a74bf421785d47d5391d` selects its actual hot model using
source `graph-event`, kind `graph.node` and the authoritative project. Retain
that exact scope/result and the selected runtime's optional declared dimension.
A missing dimension declaration is nil, not a guessed dimension; a declared
dimension must match the full returned vector. The native embedding validator
and all existing Field bounds apply together. No fixed model or vector size is
selected, and the model label establishes no hidden weight revision.

Preserve the complete raw owner query separately from the actual formatted text.
The selected SDK formatter can trim the query and apply a template or prefix,
including escaped newlines. Retain the actual template-read value. A successful
nonempty expanded/trimmed template returns before the owner reads the prefix:
record that prefix as exactly `{:read? false}`, without a `value` key or an added
environment read. When the owner reaches its prefix read, record exactly
`{:read? true :value <original-value>}`. Nil then means read-and-unset; empty
string remains distinct. Every read value is original, unexpanded and untrimmed.
A later or earlier environment snapshot is not the actual capture. Consume the
owning formatter; Field does not acquire a
second text-formatting implementation. Retain the complete one-vector normalized
public `generate` return, with exact binary64 bits equal to the parent embedding.
Cache, batching and overflow/chunk normalization can precede that public return;
this source asserts neither a raw HTTP response nor a cache/network origin.

The record's exact source selection pins eight observed immutable blobs, including
the request/vector contracts, Mongo boundary and SDK model/formatter/runtime/
generator/cache sources. Those pins establish source selection only. The actual
loaded artifact and trusted original capture still need independent qualification.
Empty/incomplete-index branches that did not generate a vector cannot invent one.
No provider credential, private endpoint, runtime object or error text belongs in
this source record. Existing source authority and scoped storage remain required.

The parent query `embedding-revision` is now explicitly selected as the owned
content revision `query-embedding-source/1:` followed by lowercase SHA256 of the
complete source map under the existing exact trace-1 tagged-value algebra. This
is a new owning interface selection, not a recovered native model-version scheme.
It omits no source field and hashes no enclosing state, trace-record envelope or
host-printer representation. The source contains no own revision/hash, so there
is no self-reference. The digest is an integrity binding, not original-source or
permission evidence. Original query, formatted text, model/dimension, vector bits
and source manifests participate. Replay/retry/restore/rebuild retain and validate
that complete record without calling the formatter, cache or provider again.

All copies, strings, source pins, encoding and hashing count under existing
input/state/checkpoint/work/continuation limits, including the unchanged512-byte
other-string cap. Oversize data refuses unchanged; no query truncation or cap
increase is selected. This does not close the original principal/authority/
history/admission evidence, presence-seed source or physical birth mapping.
Before Ready, select the exact interface/capture mapping and complete fixture
plan while preserving all existing native/upstream prerequisites. Own recorder/
consumer implementation and actual loaded-source/capture/content-revision
controls follow lawful Ready and require independent executed proof before
consumption/Done. No domain, producer, persistence or live B proof ran here.

## Presence meaning source and observed substitutions — 2026-10-16

The selected Fork Tales note gives the presence seed a meaning/purpose role.
The actual donor constructor is different evidence: `_spawn_particle` combines
its presence prompt with variant, changing directive, target and queue ratio
before embedding. `_embedding_from_text` can slice/pad/normalize a model result
and can silently use a deterministic token/SHA1 vector after an absent/error
semantic result. These are observed code paths, not a live failure or a claim
about an agent's motivation. Copying them would not establish this plan's
separate original presence/query/mantle/intent/mood inputs or qualified semantics.

Knoxx has a real owner data port: `CharacterContext` in
`knoxx.backend.shape.character.tool-modes`, validated by the owning
`character-refusal`. Its root is closed with identity, persona, snapshot, evidence
IDs and optional revision, but its nested snapshot is explicitly open. Consume
the actual owner schema; do not restate it as a competing Field registry or
claim it closes all original source/authority/history leaves. The candidate
meaning source is the actual trusted explicitly authored original persona and
identity, selected by `resolved-agent-map` from agent-level or root-level
`character-context`. Retain the complete original owner value, including snapshot,
evidence and optional-revision presence, under existing bounds. Snapshot, mood,
query and outside text do not become original meaning or trusted instructions.

The native preparation fallback is conditional: only with tool modes enabled
and no explicit character context does `character-spec` copy actor/contract ID
and the already-rendered system prompt, with empty snapshot/evidence. Rendering
happens before that fallback. It supplies neither original stable purpose nor a
proof that the actor/contract label is a presence identity. This source selection
does not promote that fallback into the physical seed producer.

The observed creative agent resource declares `role/open-hax` but no explicit
character context at either supported location. The actual Open-Hax role carries
creative personality material; its system text is380UTF8bytes and description
96bytes. These measurements are neither complete source fit nor proof that an
explicit original context or vector was produced. Do not automatically copy that
role into a new presence, infer an identity/permission, or change the resource.
This is candidate source evidence, not a served configuration observation.

ABI `presence-character-source-port` pins eleven actual source blobs across
Knoxx b6f4dfb and Fork Tales f4c43d7, records the candidate explicit context
port, and excludes those automatic substitutions. The full original presence
source, actual principal/scope binding, meaning-to-vector/revision producer and
physical birth mapping remain unselected. The original five-key seed, all emit
arguments, entity shapes, RNG, forces, caps and existing fixtures stay unchanged.
Complete source/interface/birth mapping and fixture selection with existing
upstream/native prerequisites precede Ready; own adapter/compiled implementation
and independently executed controls follow lawful Ready before consumption/Done.
No context, seed vector, embedding call, physical birth or live proof ran here.

## Stored principal namespace and native binding path — 2026-10-16

The actual Knoxx policy path distinguishes a membership's stored actor binding
from a role-derived display/default actor label. `ctx-actor-binding` returns the
stored assignment; `ctx-actor-id` can return the display convenience. The native
membership resolver verifies actor against an explicit membership, and without
that exact narrowing refuses multiple actor candidates within one organization
or across organizations. Current actor resolution reloads the membership, user,
organization, roles and policies and validates active statuses. The character
resolver requires a server-bound actor or the actual unforgeable in-process event
token, then checks selected actor/current stored binding and requested scope.

The existing encounter `authorization-evidence` names membership ID as
`principal-id`. Its graph snapshot separately retains all five native scope
values: actor, organization, membership, user and derived policy revision. The
Field proposal now explicitly selects that **membership-ID namespace** for
original `stored-principal`, preserving the existing emitted-owner equality.
This is a new owning input-mapping choice aligned with the observed native port;
no existing Field producer or identity migration is claimed. Consume the native
OpenPlanner scope/authority schemas and preserve the full original scope. Do not
replace it with an actor label, a credential ID or a tuple hash. The explicit
character presence ID remains distinct and still needs its actual original
association to that scope and selected contract.

`selected-spec!` re-resolves the canonical contract using actor and contract IDs
and checks enabled status and exact identity. That selection, its actual explicit
CharacterContext and the actual stored scope must have qualified original source
custody together before emission. Contract actor allowlists or role resolution
alone establish neither a stored grant nor a presence association. A JSON map
cannot recreate the event-authority object token, and serialization of its keys
is not original admission evidence. No second identity registry is selected.

This resolves the proposed original principal's ID namespace, not the complete
original source or current authority. The physical `scope-revision` source
mapping remains unselected. Native `encounter-policy:` is a derived fingerprint;
checked times and await-boundary rechecks establish no reservation or fence
through commit/result exposure. The inspected Axxium session/schema surfaces
supply identity/capability context without proving that required resource fence.
The explicit owner-routing amendment below corrects the earlier attribution of
application decisions to Axxium. All current decision/policy/grant/admission-or-fence
requirements remain, assigned to their qualified existing owners. These observations authorize no local policy evaluator or
new upstream prerequisite/point, and supply no waiver for a missing port.

ABI `stored-principal-source-port` pins fifteen actual source blobs and links the
original seed's principal source selection. Full original principal/presence
source, physical scope revision and current qualified authority/history remain
open. All original runtime fields, mechanics, caps and fixtures are unchanged.
Select complete source/association/interfaces/fixture obligations with existing
upstream/native prerequisites before Ready; own adapter/compiled implementation
and independent executed controls follow lawful Ready before consumption/Done.
No live membership, policy decision, token, field emission or B proof ran here.


## Existing authority-owner routing correction — 2026-10-16

The earlier wording attributed application policy/grant decisions and their
whole-call/commit/exposure protection specifically to Axxium. That source
attribution is corrected here. The inspected Knoxx Axxium facade explicitly
binds authenticated issuer/subject identity while leaving roles under local
control. Axxium retains canonical identity/authentication and applicable
capability authority through that facade. Knoxx owns application membership,
roles, source/resource policy and current-grant resolution through its existing
stored-policy and character-authority boundaries. This is routing for the
pinned integration, not promotion to common Foresight law or a transfer of
canonical authority.

Field consumes independently qualified outputs from those existing owners;
it implements no second evaluator, local authority version or local fence.
Retain the full original identity/principal/presence/ownership/scope/source
association. Current decisions and qualified policy/grant-version bindings
must cover every retained causal influence. Qualified admission/fencing must
hold through the whole call, atomic commit where applicable, and result
exposure. Missing, denied, stale, changed or unsupported authority/protection
keeps the existing refusal, unchanged state, no effect and no partial payload.
Both required Axxium identity/capability denial and current owning-application
denial must remain effective; cached application allowance overrides neither.

ABI authority-owner-routing-port pins thirteen actual facade/owner source
blobs at Knoxx b6f4dfbb4a006934a191c8fb3f26f270579e7e62 and Axxium
603ea4cd88f589c621234f73d3afd6e4e08788b8. The native server-event route
retains its actual owner-qualified process authority; no Axxium login/subject
is fabricated for it. Successful authentication, local roles or a scope map
do not establish the full original association, physical scope revision,
current qualified decision/version output, current identity validity where
required, or whole-call/commit/exposure custody. Native policy fingerprints
and await-boundary checks remain observations, not fences. The inspected
Axxium interfaces do not establish those application outputs or protection;
this bounded observation is no claim about all possible repository behavior.

Those producer shapes, versions and custody interfaces remain unqualified.
Select complete source/interface/fixture obligations with existing upstream
prerequisites before Ready; implement the owning adapters and execute
independent controls after lawful Ready before consumption/Done. The two
denial controls and the missing/stale/changed/unsupported protection controls
are planned, not executed. This amendment changes no runtime shape/arity,
mechanics, cap, source provenance, native event identity or replay requirement,
and authorizes no new upstream feature, point, scope, credential, grant
migration or board transition. Prior immutable history remains intact.


## Original explicit character/principal association component — 2026-10-16

ABI original-character-principal-association-carrier selects a proposed closed
six-key provenance component: version, scope, actor-id, contract-id,
character-context and source-pins. Consume the entire actual native Scope
through the existing OpenPlanner owner schema, and the entire explicit original
Knoxx CharacterContext through its owner schema/validator. Retain its open
snapshot, evidence IDs and optional-revision presence. The selected actor must
equal the scope actor; membership remains the original stored principal.
Character identity remains the separate original presence ID. No identity
equality or grant is inferred from labels.

The planned owning-adapter capture starts at canonical actor/contract selection
before prompt rendering and character-spec fallback, then reconciles that
original explicit context with the actual final scope after asynchronous source/
account/policy checks. Require exact selected actor, contract and complete
explicit context agreement at the relevant canonical re-resolutions before
finalizing original custody and entering the Field-consuming query/emission
path. Current graph-authority exports only scope/project/records: unchanged
scope or policy fingerprint cannot prove unchanged CharacterContext. The adapter
must have the corresponding canonical selection and actual final snapshot.
That access/capture integration is planned and unimplemented.

Carry only these named owner values through the existing protected source/
authority inputs and original history. No new graph-authority key or Field ABI
argument is selected; raw auth-context, credentials, process token, assembled
prompt and whole resolved-agent maps are excluded. Source-pins bind thirteen
inspected immutable files; they do not attest to authored-contract origin,
loaded capture code, original admission or current permission/custody.

The current pinned creative contract has no explicit context in either supported
location. This planned Field association/seed admission must refuse that case;
it neither auto-populates the contract nor adds a blanket context requirement
to generic native graph recall. A malformed truthy agent-level context cannot
be replaced by a root context or rendered fallback. Existing original-source
association, current authority/version/denial and whole-call/commit/exposure
protection remain required.

Only this component's outer value layout is selected. Complete qualified
principal-scope and presence-seed sources, authored origin/admission history,
physical scope revision, actual capture producer and semantic seed/birth
production remain open. Retain and compare the whole original component during
retry/checkpoint/restore/rebuild without refetching or retagging the original
source. Independent current authority inputs remain required.
Every copied value remains charged to the existing finite limits; no owner-open
snapshot field is dropped to fit. Existing source/interface/fixture/upstream
prerequisites precede Ready; own implementation follows lawful Ready and
independent executed qualification precedes consumption/Done. These are source
declarations, not executed association, field or live B evidence.


## Original presence-purpose seed source interface — 2026-10-16

ABI presence-seed-source-carrier selects seven source keys: version, association,
model-selection, formatter-inputs, formatted-purpose-text, generate-output and
producer-source. The complete original association is retained. Raw purpose is
exactly its CharacterContext persona, including original untrimmed bytes; no
second purpose field, rendered prompt, query, snapshot or mood value replaces it.

The planned owning adapter reuses the actual original graph query's complete
model-selection tuple and qualified loaded SDK runtime. It does not route a new
model or invent an observation where the native query never produced its source.
It invokes the existing passage formatter and separately calls that runtime's
getEmbeddingFunctionForModel(model).generate with the one formatted purpose.
Graph ingestion already uses this passage formatter; this presence integration
is selected source work, not existing or qualified native seed production.
Capture the qualified original association before the query; retain the actual
original query source before this separate presence generation; validate the
source and seed before Field emission. No query/seed source cycle is introduced.

Capture only the formatter reads actually reached: template and, conditionally,
the unread/read prefix variant preserving nil, empty and nonempty values. Empty
or whitespace persona returns before both environment reads, so it cannot
produce a successful nonblank seed source. A nonblank template can omit the
persona entirely. Nonblank output alone therefore proves neither meaning nor
qualification: the actual purpose-preserving formatter/model/configuration and
paired controls must qualify before consumption. Field adds no second formatter
or placeholder evaluator.

Retain the complete one-vector public generate result with exact binary64 bits.
It must equal the parent seed and original emitted entity's seed vector, satisfy
the native vector/dimension contract and the independently qualified participating
model/configuration bindings. Same label and dimensions alone do not establish
compatible query, Nexus and presence semantics. The SDK may return cache/batched
or split-and-averaged output; it performs no general L2 normalization. Coincident
query/passage inputs may reuse one cached vector. Distinct invocation/source
roles remain required, but no fresh HTTP call, hidden weight revision, numerical
difference or independent network origin is claimed. No query-vector assignment,
donor hash fallback, slicing, padding or adapter normalization is selected.

The parent seed/emitted embedding revision is presence-seed-source/1: followed by
the lowercase SHA256 of the complete seven-key presence-seed-source component,
excluding the outer emission wrapper, under the existing exact trace tagged-value
algebra without a trace envelope, host printer or self-hash.
That content revision grants no authority. Replay retains the original source,
vector and revision without reformatting/routing/provider/cache/network work;
independent current owner authorization is still required.

Thirteen pinned source files establish interface provenance only. Original
source/admission/history, current authority/custody, loaded capture code,
purpose-preserving configuration, semantic compatibility and physical birth
remain unqualified. The current creative contract's missing explicit context is
not repaired by this declaration. All source copies/validation/hashing remain
under existing finite bounds, with no truncation/cap change. Existing before-Ready
source/interface/fixture/upstream prerequisites remain; own implementation follows
lawful Ready and independent executed source/fit controls precede consumption/Done.
No vector, provider call, physical seed or live B behavior was executed here.


## Explicit original physical birth source and entity projection — 2026-10-16

The existing seed source slot now selects an explicit three-key original emission
wrapper: version, presence-seed-source and physical-birth-source. The parent
seed still has five keys and emit-recall still has eight arguments. Its existing
seven-key semantic source remains a complete separate component. The semantic
embedding revision hashes only that component, using its unchanged prefix and
tagged-value content recipe. Exact original-input comparison and state/checkpoint/
history custody include the whole wrapper, so changed birth data cannot masquerade
as an exact retry even when semantic vector/revision are unchanged.

Birth has nine keys including its version: entity-id, position, velocity, mass,
scope-revision, mantle-lineage, intent-wallet and emission-id are its eight
payload fields. Reuse the existing entity ID, Vector2, positive finite mass,
lineage and safe-integer wallet requirements. Its scope revision must exactly
equal the original request's physical scope revision and existing state binding;
it cannot introduce another scope or alias the native policy fingerprint.

Field's selected value projection fills exactly the existing **13** daimoi
fields: those eight birth values, fixed kind daimoi, original request principal,
parent semantic vector/revision and original request ID. Projected principal
also equals parent emitted-owner and original association membership. There is
no additional entity field and no resulting-entity/source-wrapper self-cycle.
The retained admission-output entity cannot bootstrap its own first-emission
input. After motion, retry/replay retains original birth values rather than
copying the current live pose or recreating the original presence.

This selects the value layout and projection, not the population policy or
actual producer of geometry, mass, wallet, lineage or identities. Each value
must match complete actual qualified original source/admission/history evidence.
Retain nonempty original wallet entries and lineage, and accept emptiness only
when that actual original source was empty. Select no default geometry, inferred
presence wallet, donor screen-orbit/hash/time rule, float-resource conversion,
extra RNG draw, clock read or identity minter. Birth is not hidden in character
snapshot, current authority, role or prompt data. Map validity does not prove origin.

The donor source and legacy Field Particle/stepField do not establish that
qualified producer. The local Clio submodule is uninitialized; bounded native
commit/tree/blob reads recovered the pinned Clio event interface without cloning
or executing it. Native make-event stamps event/id, type, schema identity and
time; native UUID/stream/sequence/causal and historical schema validation retain
their authority. This supplies no physical birth API or equality between a
domain entity ID, emission ID, request ID and Clio event ID. Actual producer and
domain-history/source bindings remain unqualified.

All source values/copies remain under existing bounds and exact immutable-retry
rules. Bare semantic source is not silently wrapped with missing birth defaults.
Existing source/interface/fixture/upstream prerequisites precede Ready; own
implementation follows lawful Ready and independent executed source/projection/
fit controls precede consumption/Done. No native birth, particle, history write
or runtime behavior was executed by this source-only amendment.


## Native Clio boundary for original emission inputs — 2026-10-16

The proposed Field consumer event `:field/recall-emission-inputs` records original
inputs, not successful physical emission. Its two-key event data contains a
literal domain version and the complete existing five-key original-inputs value,
encoded with the Field's existing trace tagged-value algebra. The tagged tree is
plain EDN data inside the native Clio envelope. It is not JSON text, a trace
record envelope, or a replacement Clio codec. No physical number remains raw:
its existing sixteen-digit binary64 string preserves signed zero and every
admitted finite bit pattern. Native Clio canonicalization intentionally identifies
both zeros and refuses unsafe integer-valued doubles; raw number custody would
therefore fail the existing Field requirement.

Clio retains native complete-envelope schema materialization, historical root and
leaf validation, UUID/time creation, append admission and ledger serialization.
Retain and recover the same complete native envelope for a retry. Calling the
native runtime append convenience function again makes a fresh UUID and time;
that is not an exact-envelope retry. Native append handles identity and stream
slot conflicts, while complete union canonicalization separately checks parent
availability, contiguous stream history, predecessor causes and cycles. A valid
schema, actor string or append result supplies no current authorization or
physical state success.

This input record contains no enclosing event/cursor, output entity, state or
snapshot self-reference. The complete six-key original custody remains mandatory
in separately qualified, counted owner source/history, immutably bound to the
actual complete native envelope and payload. A later mutable lookup or digest
alone cannot substitute. Its shape and actual
population, the request/event association, birth producer, native stream/actor/
subject/cause selection, durable envelope retention, current authority and
cross-store commit/exposure custody remain open. Existing private source access,
whole-call guards and byte/work caps apply to all encoded inputs and native
overhead. Native EDN transport does not redefine Field canonical admission
lengths or bypass tagged expansion accounting. No truncation, extra budget,
public ledger or identity alias is added.

This is a prospective domain payload and native interface selection. The actual
expanded schema, loaded encoder/decoder and producer still need source and
fixture qualification under the existing Ready and implementation order. The
seven newly recovered native blobs are bound to commit
`788cdd3434615a7932b924e68520dbf7f88408c2` and its resolved tree; native responses,
Git object hashes and decoded source bytes were retained. Inspection executed no
Clio schema, codec, append, canonicalization, Field operation or runtime proof.


## Explicit original custody at the emit call — 2026-10-16

The previous eight-argument proposal required complete original custody but had
no selected path for supplying the first emission's native input event. Its five
original inputs are inside that event; putting the enclosing event into one of
them creates self-reference. State cursors provide only identifiers, and neither
current authority nor producing identity is a historical-source container.
Unclosed provenance/state leaves cannot silently supply an implemented bridge.

Append an explicit final `original-admission-custody` argument to emit-recall.
The preceding eight argument positions and the five immutable input values stay
unchanged. This is ordinary interface repair in the existing eight-point ABI
card; that card's estimate is not an eight-argument requirement. Prior notes
preserving eight arguments describe their historical source selections. There
is no implemented API migration, extra point or upstream feature in this change.

The new argument supplies the already-required complete six-field original
custody map. Its history binding has two keys: version and input-event, holding
the complete actual native Clio original-input envelope. Native schema/source and
complete-history admission remain Clio-owned. The envelope's exact tagged
payload must match all five supplied original input values; its schema reference
cannot authenticate itself. The input event contains no custody, enclosing event,
result or post-state, so custody can reference it without a cycle.
Other checkpoint, fold and rebuild reference carriers remain explicitly
unresolved; this history wrapper binds only the original input event.

The outer source producer must prepare and qualify the inputs, native input
record and complete original custody before the pure Field call. Validate them
before causal work and retain exactly the supplied custody only on successful
admission. Exact retry compares the original five inputs and, separately, all
six supplied original custody values against the retained originals. Missing or
different custody refuses; the caller cannot silently reuse a stored copy.
Fresh current authorization, producing identity and result-exposure guards remain
independent. Original authority stays historical and is never retagged as current.

All nine arguments, including repeated complete envelope, payload, schema and
source evidence, count under existing input/state/checkpoint/history/work limits.
No default custody, ambient cache, eight-argument bypass, truncation or extra
allowance is selected. Existing refusal precedence and whole unchanged-state
behavior remain. Replay retains original source roles without refetching facts.

Pinned Knoxx has canonical Clio history and a fixed accepted-operation store,
but its provider result precedes construction of that operation's envelope. The
encounter adapter uses existing OpenPlanner event rows. Neither inspected path
already produces this Field input event or complete first-admission custody.
Actual producer/source leaves, native envelope selection/retention, current
admission, cross-store commit/exposure protection and executed fit remain open.
This amendment selects the explicit data route and history layout; it executes
no producer, native store, Field transition or runtime behavior. Existing lawful
Ready and implementation/independent qualification ordering remains required.


## Original principal and scope data reuse — 2026-10-16

Original custody's principal-scope-source now selects the entire existing
six-key original-character-principal association: version, complete native
scope, selected actor, selected contract, full explicit CharacterContext and
source pins. It must exactly equal the association already retained inside the
original semantic seed source, including its open snapshot and optional revision
presence. No new runtime wrapper, custody key or call argument is added.

The native scope retains actor, org, membership, user and policy revision. Its
membership is the Field stored principal and emitted owner; selected actor must
match scope actor, while explicit CharacterContext identity remains the distinct
origin-presence identity. The existing thirteen-entry association source manifest
and its runtime value layout are unchanged.

This selects principal/scope data, not the authenticated origin of that data.
Complete original membership/grant records, authored-context origin, native
admission/source evidence and history remain mandatory in their existing separate
custody fields. The qualified mapping to request/birth/state physical scope is
still required; native policy-revision is not that physical revision or a current
grant. Current owner decisions and commit/exposure protection remain independent.

The native final source snapshot keeps its selected spec internally, but graph
authority exports scope/project/records. Planned complete-context capture and
reconciliation at that boundary therefore remain unimplemented and unqualified.
No raw auth context, process-only token, credentials, whole resolved agent map or
assembled prompt is selected for this leaf. Replay retains original data rather
than refetching current context. Full owner values and copies remain subject to
existing finite bounds, without dropping snapshot fields or changing limits.
