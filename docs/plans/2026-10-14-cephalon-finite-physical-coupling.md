# Finite physical coupling for the cephalon character

License: GPL-3.0-or-later.

## Context and authority

This is an owning-repository planning proposal within Foresight physical task
`ff3e628b-cd5c-4a89-a397-42cc88dbde70` and its existing selected B1/B2/B3
milestone. It adds no implementation inventory, board, status, UUID, estimate,
runtime or deployment authority. Foresight remains the native board owner.

The independently merged [kernel plan](2026-10-07-cephalon-physical-kernel.md)
and [ABI](cephalon-physical-kernel-abi.edn) at personal MERGE
`a2c64bee9878fef3abd2b38481b972e6aa29cd37` remain the historical broader source
contract. This candidate makes one explicit prospective numeric amendment:
signed safe cell indices; counts, wallets and elapsed time remain nonnegative.
The amended source plan/ABI and matching coordinator selection must be reviewed
before that exception is admitted. Original Git blobs and ledger history remain.
This proposal makes the finite causal proof and the previously unspecified
field-sampling/force boundary concrete. It requires its own current planning
review; existing approvals do not transfer. The corresponding coordinator
decomposition remains proposed until reviewed native adoption.

The selected owner decision remains Foresight
`6a4438982fdf1eca98f856748bb23b19ab017c0a`, path
`docs/notes/2026-10-07-cephalon-field-kernel-selection.md`.
Its positive-only integer statement does not admit negative floor-cell indices.
The signed cell-index amendment is therefore a pending coordinator decision
change, not a claim of compatibility with the old selection. Review and record
the new decision revision before implementation; do not overwrite provenance.

## Outcome

An admitted outside encounter changes persistent graph and physical field
state. A daimoi samples that retained field, physically moves and contacts an
authorized memory; the resulting attributed inclusion reaches actual character
recall. The independently persisted field also supplies the separate mood
transition. Different admitted input can change this causal result.

The finite proof does not complete the larger physical task or character epic.
The actual source still implements neither this kernel nor its persistence and
consumer integration. A changed state counter, layout, graph cost fill or
matching revision labels cannot satisfy the outcome.

## Scope and retained mechanics

- Keep compiled CLJS on Node, finite binary64, 2D world units and exact safe
  integers. Pure portable shape/law/domain namespaces own semantics; outer
  adapters own conversion, storage and product composition.
- Retain one attributed intent-bond topology, counted once across structural
  and semantic representations. Explicit dissimilar pinning survives. Nexus
  and presences stay passive; their friction/static thresholds differ from
  daimoi as declared in the selected plan.
- Keep eight sparse vector layers with revisioned semantic bindings and keys
  `[scope-revision, layer-index, floor(x/cell-size), floor(y/cell-size)]`.
  Preserve velocity amplitude in deposits and actual elapsed exponential decay.
  The layers are not keyword-driven mood counters.
- Preserve emitted owner, seed embedding, scope and mantle provenance. A
  correctly resolved finite deflection may supply the contact case. Unavailable
  absorption/exchange operations refuse explicitly; they are not emulated or
  called complete.
- Preserve prior/next buffers, fixed 10,000 microsecond quanta, maximum 100
  substeps per call, exact residual/backlog and separate catch-up. Zero advance
  remains an exact no-op, including RNG. The finite case retains split-call,
  quiet-time decay and differing-friction laws.
- Retain nonzero uint32 xorshift32 with shifts 13/17/5, explicit draw count and
  canonical ordering. Any enabled simplex exploration requires the selected
  qualified permutation, gradients and configuration; no clock or Math.random
  may enter the pure transition.
- Continuous replay tolerance remains
  `abs(a-b) <= 1e-9 + 1e-9 * max(abs(a),abs(b))`. Discrete identities, event
  order, residuals, draws, contacts, scope, included memories and byte hashes
  stay exact. Tolerance cannot excuse different inclusion.

## Proposed sampling and force rule

These rules are proposed semantics, not implemented functions or production
calibration. All coefficients, bounds, layer bindings and vectors are required
revision-bound inputs. Missing/nonfinite/mismatched inputs refuse unchanged
state; no donor constant becomes a default.

1. For each admitted entity position `p=(x,y)`, compute the declared cell key
   using mathematical floor and positive world-unit `cell-size`. Read only
   the exact authorized scope revision and indices 0 through 7 from the prior
   buffer. An absent cell contributes the zero vector. There is no coordinate
   normalization, border clamping, cross-scope fallback or interpolation in
   this selected finite rule. Each logical/storage cell index is an exact signed
   safe integer in `[-(2^53-1), 2^53-1]`; an out-of-range quotient/floor refuses
   unchanged state. This is the proposed field-index exception, not permission
   for negative counts, wallets, elapsed time, residuals or RNG counters.
2. Every sampled entity has one explicit weight source. A daimoi resolves its
   immutable `recall-request-id` to exactly one admitted same-scope request,
   which carries eight finite nonnegative weights and their semantic mapping
   revision. A passive presence or nexus instead uses the complete physical
   configuration's eight wind-read weights for its kind and their mapping
   revision, independent of recall request creation/order. Missing, ambiguous,
   stale or foreign-scope request bindings and invalid passive configuration
   refuse before force computation; there is no latest-request/average fallback.
   Compute
   `V(p) = sum_i(weight_i * cell_velocity_i(p))` in ascending layer order.
   The mapping is explicit validated input from the owning projection; this
   plan invents neither English keyword categories nor mood dimensions.
3. Apply one declared radial saturation to the aggregate:
   `S(V) = V * min(1, wind-cap / norm(V))`, with `S(0)=0` and positive finite
   `wind-cap`. Preserve direction and unsaturated speed amplitude. Refuse
   overflow before committing state. Cell deposit saturation/pruning retain
   their separately declared calibration and observations.
4. External wind acceleration is `a_wind = coupling_rate(kind) * S(V)`.
   `coupling_rate` is finite nonnegative and has units s^-1; `V` is wu/s,
   so acceleration is wu/s^2 and force is `mass * a_wind`. No normalization
   to unit direction hides speed. Passive entities may respond to this external
   force; they receive no daimoi self-propulsion.
5. For each entity, left-fold binary64 vector addition from exact `[0,0]` in
   this force-class order: non-bond semantic attraction, unified intent-bond,
   repulsion, boundary, wind, seeded exploration. Within each class, sort
   contributions by `(target-id, source-id, contribution-id)` using ascending
   unsigned UTF-8 ID bytes; duplicate contribution identities refuse. A semantic
   pair represented by an intent bond belongs only to the unified bond class;
   structural/semantic evidence cannot add its force twice. Every contribution
   is a force in wu/s^2 times positive dimensionless inertia. For each component,
   after the ordered sum `F_total`, compute `a = F_total / mass`, then
   `delta_v = a * h`, then `v_pre_friction = v_prior + delta_v`, in that
   binary64 operation order, with `h = quantum_us / 1,000,000` seconds. There
   is no fused arithmetic, omitted mass division or timestep substitution.
   Refuse nonfinite intermediate results before state commit. Multiply each
   component by `exp(-gamma_kind*h)`, apply the kind's radial speed cap,
   apply the static-threshold rule below, then move once using
   `p_move = p_prior + v_move * h` (multiply, then add per component).
   Resolve the canonically ordered contact pass using those velocities; only
   after the whole pass apply the same kind cap, then static threshold, to each
   resolved velocity.
   Contact response is computed before this second cap and retained in the
   trace; do not interleave caps between contact pairs. Motion deposits use the
   final post-contact-cap-and-threshold velocity, with no second position advance.
   Deposits/contact outputs enter the following buffer, not other entities
   midway through the same prior-buffer pass. Class order and contribution
   order are revision-bound semantics, not collection insertion order.
6. Deposit `D_i = gain_i * deposit_weight_i * v_resolved * h` in the cell
   selected by the surviving entity's **post-contact resolved position**.
   Use its final post-contact-cap-and-threshold velocity too; do not use the old position or
   pre-contact velocity. An absorbed entity has no motion deposit. For
   velocity-valued cells, `gain_i` is finite nonnegative with units s^-1.
   Read/deposit weights are distinct revisioned inputs. A daimoi takes exactly
   eight deposit weights and their mapping revision from the same unique
   immutable admitted same-scope request bound by its `recall-request-id`. A
   presence or nexus instead takes its kind's eight deposit weights and mapping
   revision from the complete physical configuration, independent of any
   recall request order. No global, latest-request, average, read-weight reuse
   or other-entity fallback is admitted. Missing, ambiguous, stale or foreign
   bindings refuse unchanged state before either sampling or depositing. Negative,
   missing, wrong-length or nonfinite deposit weights refuse unchanged state.
   A supported zero-weight
   or zero-velocity case deposits nothing. Sort deposits by entity ID and
   deposit/contribution ID using the same UTF-8 ordering.
7. A substep samples `F_i(t)` from the prior buffer. Its next cell value is
   `prune_i(saturate_cell_i(exp(-lambda_i*h) * F_i(t) + sum_ordered(D_i)))`,
   with `lambda_i=ln(2)/half_life_i` and required positive half-lives. The
   substep's deposit is recorded at the end boundary and is not decayed for
   time before its creation. Empty prior cells start at zero. Cell saturation
   and pruning have required separate revisioned calibration; their declared
   order is decay old field, add ordered new deposits, saturate, then prune.
   Per-contribution creation times/provenance must replay this schedule.
8. The kind speed cap is finite nonnegative, in wu/s. Its rule is
   `C(v)=v*min(1, max-speed_kind/norm(v))`, with `C(0)=0`; a zero cap returns
   zero velocity. Overflow refuses unchanged state. Record both cap stages'
   before/after velocities and whether a limit applied. A cap is an explicit
   dissipative constraint; do not relabel capped velocity as the raw exact
   contact response or claim kinetic-energy conservation. Wallet conservation
   and immutable ownership remain independent unchanged laws.
9. Each kind's static threshold `s_kind` is finite nonnegative in wu/s, with
   `s_presence > s_nexus > s_daimoi >= 0` as the owning contract requires.
   Define `T(v)=[0,0]` exactly when `norm(v) < s_kind`; otherwise retain `v`.
   Equality retains the velocity, and a zero threshold never stops a nonzero
   velocity. Apply `T` immediately after the pre-movement cap and after the
   final post-contact cap, with no threshold/cap interleaving between contact
   pairs and no second movement. Trace the velocity before/after each threshold
   and whether it stopped. Contact response remains separately inspectable.
   All norm/intermediate overflow refuses the unchanged transition; threshold
   comparison never uses the continuous replay tolerance.

The historical Fork Tales `nooi.py` at
`f4c43d7b9c832a54bc5d224cb4d5d2497c04423b` samples one dense normalized cell
and sums its layers, but normalizes deposit direction and uses per-layer donor
decay constants. Its runtime also normalizes the returned flow direction.
Those are source observations, not the selected amplitude/time/units law.
This sparse world-unit proposal explicitly retains the later correction and
does not copy donor clamping, normalization or calibration.

## Causal fixture and persistence boundary

Freeze the actual principal and authorized graph, two memory nexuses, one
evidenced bond, an emitted daimoi, request/encounter/effect identity, immutable
embeddings, complete finite calibration, event placement, time schedule and seed.
The supplied calibration must make this test sensitive to the recorded deposit;
arbitrary perturbation without an admitted encounter is insufficient.

Persist the encounter's graph change and attributed motion deposit. Advance to
a subsequent sample and elapsed decay, retaining:

`encounter -> deposit -> sampled vector -> force/velocity -> trajectory/contact -> included memory`.

Independently read the committed graph and field revision through OpenPlanner's
actual scoped storage port. Replay the **unchanged admitted snapshot and causal
history** from that readback. The trace must reach the automatic maker's actual
bounded recall input and provider prompt. The separate mood model binds this
same independently loaded field revision. A snapshot with its deposit removed
while retaining the original effect/hash/cursor is invalid and must refuse.

The physical causal control is a separate **lower-level pure kernel
intervention**, not another admitted persisted state or restore proof. It varies
only a field-vector contribution passed to the sampling/force/motion/contact
calculation. Fix graph/query/principal/embeddings/calibration/seed/event schedule,
the exact mood/lens revision, attention inputs, each daimoi's request/read weights
and mapping revision, and both passive-kind configuration/read weights and
mapping revisions in both arms. The resulting contact and inclusion must differ.
Do not pass the altered buffer to production admission, storage or restore,
forge its source hashes, or report it as valid encounter history. The fixture
tests the physical causal mechanism; the separate positive persistence/replay
and actual consumer case supplies the lawful end-to-end proof. B2 tests mood
influence separately while holding physical inputs fixed; it cannot confound
the physical intervention.

OpenPlanner owns persistence and identity-safe projection; Knoxx owns its stored
principal, mood and prompt composition. A selected write count, in-memory map,
API200 or writer-returned snapshot is not independent persisted readback.
For this finite effect, the owning OpenPlanner port must atomically commit its
graph projection update, field checkpoint and immutable effect receipt in one
transaction, with a unique owner-scoped effect identity and expected graph/field
revision checks. Unsupported transactions refuse before either update. This is
a required future adapter capability, not observed SDK behavior.

After an uncertain commit result, read the matching effect receipt and both
referenced component revisions independently. A complete matching transaction
recovers its prior result without depositing again. Absence permits retry of
the same transaction/identity only under the same expected revisions. Hash,
scope or revision conflict refuses. A receipt with a missing/mismatched graph
or field component is quarantined as inconsistent; do not replay both sides or
declare success. Transaction fault tests must establish neither-half persistence
before commit and complete matching recovery after an acknowledged or uncertain
commit. Hidden field contributors must not affect allowed motion or inclusion.

## Acceptance criteria and RED obligations

1. Independent planning review assesses the proposed sampling/force rule,
   dimensional consistency, source mapping, proof sensitivity, finite scope and
   decomposition. Keep the original complete solver obligations attributable.
2. Before GREEN, owning portable laws fail for the actual predecessor's clamp,
   per-call damping, missing field coupling and unseeded graph exploration.
   Proposed modules are `eros-eris-field.shape`, `.law`, `.domain`, with matching
   test namespaces; their declaration here is not test execution.
3. Sampling tests cover all eight layers, signed safe cell coordinates and their
   positive/negative bounds, cell edges,
   absent/zero cells, exact scope refusal, entity/request/weight/revision mismatch,
   multiple request ordering with fixed bindings, passive weight invariance,
   saturation,
   finite-value/overflow refusal and declared canonical accumulation. Units tests
   bind gain, wind coupling, velocity, acceleration and timestep calibration.
4. The selected finite case covers force-class/contribution ordering,
   post-contact deposit position/velocity, decay-before-new-deposit,
   elapsed decay/friction, both over-cap stages (including zero cap),
   raw-contact-versus-final-cap trace, zero-time no-op,
   split/catch-up, immutable ownership, single-counted bonds and actual contact
   deflection. Unavailable operations refuse unchanged state.
5. Real owning transaction tests establish once-only graph/field/effect persistence,
   independent component readback, uncertain-commit recovery, quarantine of an
   inconsistent pair, conflicts/failures and unchanged admitted-snapshot replay.
   Altered contribution/hash/cursor restore refuses. The separate kernel
   intervention freezes mood/lens/attention and exact eight read weights; a
   hidden contributor variation
   changes no authorized result. Production calibration remains separately
   qualified before live use; fixture values are never implicit defaults.
6. Actual Knoxx consumption demonstrates field-to-contact-to-inclusion causality,
   separate persisted/consumed mood and the same actual principal/revisions in
   the maker prompt. Source fixtures alone do not complete B1/B2/B3.

## Dependencies, estimates and later obligations

Implementation still requires reviewed native decomposition/readiness, admitted
encounter data, a qualified scoped graph interface and completed owner/numeric
handoff. The graph-only interface may explicitly report `not-loaded`; actual
finite loop completion may not. Existing whole-story edges remain until reviewed
replacement interfaces are applied through Rheos; no larger task is marked Done
from this subset. The selected kernel needs standalone build/license adoption,
complete calibration and current source/consumer qualification before deployment.
The signed field-index exception also requires an independently reviewed
coordinator selection amendment; the old positive-only decision is retained as
provenance and supplies no admission for that exception.

Independent local audit sizes this as several substantial kernel packets—
ABI/time/order/build; forces/bonds/winds/seed; contact/trace/replay—plus storage
and consumer integration. It assigns no native points and does not obtain a
remainder by subtracting from the original eight-point story. Native estimates
and any aggregation change need reviewed planning and the canonical writer.

Later work retains full absorption/bounded exchange and multi-contact
conservation, the complete bond/association matrix, sustained quiet/load/restart
and revocation behavior, outcome-confirmed reinforcement, long-running mood and
traits, concurrent continuity, social/artistic outcomes and reserved-head/recovery
guarantees. The finite selected persistence/privacy/replay proofs stay mandatory.

## Verification and risks

Review this document and its matching declared-rule data; parse the data with
the existing EDN surface. No new solver or mirrored implementation test is
claimed. Later RED/GREEN follows lawful native readiness in the owning packages.
Retain the frozen input, actual source/configuration hashes, commands, prior/new
state, independent readbacks, observed refusals and consumed causal trace.

Risks include discontinuity at nearest-cell boundaries, poorly calibrated force
or saturation hiding the deposit, numeric threshold divergence, mis-scoped
retained influence, unclear persistent atomicity and a decorative coupling
fixture. The reviewed finite calibration and sensitive physical ablation must
resolve these risks; the plan alone does not establish performance or behavior.

## Current4b planning corrections

Codex review5523734461 on4b08fdd identified three missing deterministic rules:
4275496845 (force integration), 4275496853 (entity deposit binding), and
4275496863 (static-threshold placement). The proposal now specifies component
divide/multiply/add ordering before friction, the same immutable request or
passive-kind configuration as deposit-weight authority, and strict-below
thresholds after both speed caps. Matching EDN records the same boundaries.
These are reviewed proposal corrections, not executed physical behavior.

The separate coordinator selection amendment is actually MERGED as personal
ForesightPR36 at `8c649fee2e95e5ec6b5304a3351a0e16fca60533` on
2026-10-14T20:18:50Z, after current020d approvals/checks and canonical gate PASS.
The owning proposal binds its exact selected decision commit
`020d97fecae4a8d0d277b9b2695d9482620b4a76`; original6a selection remains
historical provenance. This does not qualify this separate PR or establish
native readiness, an implemented kernel or any live B1/B2/B3 proof.
