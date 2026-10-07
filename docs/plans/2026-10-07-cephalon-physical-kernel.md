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

- `admit-state` takes a trusted, sealed visible projection and complete
  revisioned physical configuration. It returns either an admitted kernel state
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
  snapshot, budget and Knoxx mood/lens revision. It emits once or returns the
  existing request result; identical polling never emits or reinforces.
- `read-recall` projects committed motion/contact/bond traces for that request
  and includes actual authorized memory IDs with reasons. It has no write,
  emission, RNG advance or time advance. Denied, no-contact, stale, incomplete,
  exhausted and failed outcomes are distinct.
- `apply-outcome` takes an immutable observed choice/outcome identity and the
  admitted prior recall reference. It proposes attributed semantic feedback
  once. The outer writer returns success only after actual storage success;
  refusal/failure never becomes a success receipt. Pending feedback and confirmed
  feedback are distinct. Retrying a failed outer write uses the same effect ID;
  only an actual writer acknowledgement admits the completed outcome and its
  persistent reinforcement. A prepared proposal is not success or permission to
  emit a second effect.
- `checkpoint` encodes a canonical snapshot and transition/event cursor. Restore
  validates kernel/config/projection revisions, grants, seed counters and causal
  contributions before use. Canonical encoding and hash format are adopted from
  the existing contract/event authorities where available, not invented locally.

JS strings/arrays/objects convert at the adapter boundary to Clojure data. Native
provider and storage output is untrusted input. Both sides of replaceable seams
are validated. ABI refusal reason names remain explicit and revisioned.

## Numeric, temporal and replay commitments

1. The authoritative initial target is compiled CLJS on Node with finite
   binary64 scalars in 2D world units. No f32 packing or JVM/browser/Python
   numerical parity claim. Velocities are wu/s, accelerations wu/s², mass
   positive dimensionless inertia; friction and decay are s⁻¹. Embeddings stay
   immutable and model/dimension-revision-bound, not spatial coordinates.
2. Integer inputs and arithmetic results are exact within `[0, 2^53-1]`.
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
8. Eight sparse velocity layers use keys
   `[scope-revision, layer-index, floor(x/cell-size), floor(y/cell-size)]`.
   Indices `0..7` have versioned semantic bindings, not English keyword counters.
   Deposit is `gain-layer * weight-layer * velocity * h`: actual speed changes
   amplitude. Radial saturation and sparse pruning are explicit configured
   observations; retained event provenance permits reconstruction/revocation.
9. Record nonzero uint32 seed and draw counter. Proposed discrete xorshift32
   shifts are `13,17,5`, with unsigned output divided by `2^32` and canonically
   ordered candidates. Lazy 2D simplex uses a qualified seeded permutation and
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
`v' = v-(1+e)*(v·n)*n`. For `(v·n) >= 0`, separating or tangent contact keeps
the relative velocity unchanged. The adapter-independent domain adds the
recipient's world velocity back after resolution. Degenerate normal refuses
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
