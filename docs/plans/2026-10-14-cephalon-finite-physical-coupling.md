# Finite physical coupling for the cephalon character

License: GPL-3.0-or-later.

## Context and authority

This is an owning-repository planning proposal within Foresight physical task
`ff3e628b-cd5c-4a89-a397-42cc88dbde70` and its existing selected B1/B2/B3
milestone. It adds no implementation inventory, board, status, UUID, estimate,
runtime or deployment authority. Foresight remains the native board owner.

The independently merged [kernel plan](2026-10-07-cephalon-physical-kernel.md)
and [ABI](cephalon-physical-kernel-abi.edn) at personal MERGE
`a2c64bee9878fef3abd2b38481b972e6aa29cd37` remain the broader source contract.
This proposal makes the finite causal proof and the previously unspecified
field-sampling/force boundary concrete. It requires its own current planning
review; existing approvals do not transfer. The corresponding coordinator
decomposition remains proposed until reviewed native adoption.

The selected owner decision remains Foresight
`6a4438982fdf1eca98f856748bb23b19ab017c0a`, path
`docs/notes/2026-10-07-cephalon-field-kernel-selection.md`.
If this proposal conflicts with that decision, retain the conflict and review
the owning decision before implementation; do not overwrite its provenance.

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
   this selected finite rule.
2. An admitted immutable request carries exactly eight finite nonnegative
   layer weights and the revision of their semantic mapping. Compute
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
5. Other admitted forces compose in the existing declared canonical order;
   this rule does not replace or duplicate semantic/bond forces. Update velocity,
   apply `exp(-gamma_kind*h)`, move and resolve canonically ordered contacts.
   Deposits and contact output affect the following buffer, not other entities
   midway through the same prior-buffer pass.
6. Deposit remains `gain_i * deposit_weight_i * velocity * h` at the declared
   cell. For velocity-valued cells, `gain_i` has units s^-1. Read weights and
   deposit weights are distinct revisioned inputs. Apply elapsed decay using
   `lambda_i=ln(2)/half_life_i`. Require declared positive half-lives; any
   supported zero-weight/zero-velocity case is a deterministic no-deposit.

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
actual scoped storage port. Replay from that readback. In the paired case, keep
graph/query/principal/embeddings/config/seed/event timing fixed and remove only
the attributed deposit: physical contact/inclusion must change. The trace must
reach the automatic maker's actual bounded recall input and provider prompt.
The separate mood model binds the same independently loaded field revision.

OpenPlanner owns persistence and identity-safe projection; Knoxx owns its stored
principal, mood and prompt composition. A selected write count, in-memory map,
API200 or writer-returned snapshot is not independent persisted readback.
Idempotent replay recovers the admitted effect rather than depositing again.
Partial/failed writes, duplicate/conflicting identities and stale revisions stay
explicit. Hidden field contributors must not affect allowed motion or inclusion.

## Acceptance criteria and RED obligations

1. Independent planning review assesses the proposed sampling/force rule,
   dimensional consistency, source mapping, proof sensitivity, finite scope and
   decomposition. Keep the original complete solver obligations attributable.
2. Before GREEN, owning portable laws fail for the actual predecessor's clamp,
   per-call damping, missing field coupling and unseeded graph exploration.
   Proposed modules are `eros-eris-field.shape`, `.law`, `.domain`, with matching
   test namespaces; their declaration here is not test execution.
3. Sampling tests cover all eight layers, negative cell coordinates, cell edges,
   absent/zero cells, exact scope refusal, weight/revision mismatch, saturation,
   finite-value/overflow refusal and declared canonical accumulation. Units tests
   bind gain, wind coupling, velocity, acceleration and timestep calibration.
4. The selected finite case covers elapsed decay/friction, zero-time no-op,
   split/catch-up, immutable ownership, single-counted bonds and actual contact
   deflection. Unavailable operations refuse unchanged state.
5. Real owning storage tests establish once-only admitted persistence, independent
   readback, conflicts/failures and frozen replay. A hidden contributor variation
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
