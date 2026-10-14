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

The original owner decision is Foresight
`6a4438982fdf1eca98f856748bb23b19ab017c0a`, path
`docs/notes/2026-10-07-cephalon-field-kernel-selection.md`.
Its positive-only integer statement did not admit negative floor-cell indices.
The matching signed-index amendment is now independently reviewed and merged
as decision `020d97fecae4a8d0d277b9b2695d9482620b4a76`, merge
`8c649fee2e95e5ec6b5304a3351a0e16fca60533` (personal Foresight PR36).
It retains the owner and changes only the field-index numeric exception.
This owning proposal/ABI still needs its own review and lawful native readiness
before implementation; original 6a and all prior provenance remain intact.

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

Every norm in aggregate wind saturation, both speed caps and both static
thresholds uses this same scaled binary64 algorithm. Validate finite components
`x,y`; set `m=max(abs(x),abs(y))`. If `m=0`, return exact zero. Otherwise compute
`u=x/m`, `w=y/m`, then `u2=u*u`, `w2=w*w`, then `q=u2+w2`, then `r=sqrt(q)`,
then `n=m*r`, in that order, with the selected compiled Node binary64 square
root and no fused arithmetic. Check each intermediate for finiteness; a final
unrepresentable norm refuses unchanged state. Do not substitute naive squaring,
`Math.hypot`, approximation or replay tolerance. A representable large norm
therefore does not refuse merely because unscaled component squares overflow.
For every radial cap, validate finite components and the finite nonnegative
cap first. If cap is zero, return exact [0,0] before evaluating any norm, even
when the original finite vector's norm would be unrepresentable. Otherwise
evaluate the scaled norm; exact zero norm returns exact [0,0]. Then
compare n to the cap first. If n is at or below the cap, retain the original
vector without division. Only when n exceeds the cap compute `ratio=cap/n`.
If ratio is nonzero, multiply x then y by ratio with finite checks. If a
positive cap yields exact zero ratio through binary64 underflow, instead
compute `unit_x=x/n`, then `result_x=unit_x*cap`, then `unit_y=y/n`, then
`result_y=unit_y*cap`, checking each operation. This underflow branch preserves
representable nonzero capped components such as [MAX_VALUE,0] capped at
MIN_VALUE. Pin the branch in the trace; no reassociation outside it is allowed.
Certify the resulting vector with the same declared scaled norm. If it exceeds
the cap through rounding, perform at most two inward correction passes: compute
`r=cap/result_norm`, then the immediately preceding nonnegative binary64 value
`r_down` (positive finite IEEE64 bit pattern minus one), then multiply result_x
and result_y by r_down in that order with finite checks and recertify. A zero
r_down or unrepresentable intermediate refuses unchanged state. After two
passes a still-over-cap norm also refuses as unsafe arithmetic; never return an
uncertified vector. Record every correction's factor, before/after vector and
certified norm. The bounded correction count is a versioned algorithm limit,
not production calibration or a claim of exact real-number direction.
Do not evaluate an overflowing inactive division for subnormal input. These rules remain unimplemented proposal data.

1. For each admitted entity position `p=(x,y)`, compute the declared cell key
   using exact floor of the binary64 inputs' rational ratio and positive
   world-unit `cell-size`. Decode each finite binary64 operand into sign,
   integer significand M and power-of-two exponent E: subnormal/zero use
   M=fraction_bits, E=-1074; normals use M=2^52+fraction_bits,
   E=exponent_bits-1023-52. Form the exact signed coordinate/cell-size ratio
   with integer shifts and apply integer quotient/remainder; a negative
   nonintegral quotient rounds toward negative infinity, never toward zero.
   Use exact integer scratch arithmetic, then enforce the declared signed
   safe-index range before conversion to the stored numeric index. Zero and
   negative zero both map to canonical cell 0; a tiny negative coordinate maps
   to -1 even when floating division would underflow. No rounded floating
   quotient, clamping or shifted origin defines identity. Read only
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
   Start each component accumulator at exact zero. For each layer i, compute
   `product_x=weight_i*cell_x`, then `sum_x=prior_sum_x+product_x`, then
   `product_y=weight_i*cell_y`, then `sum_y=prior_sum_y+product_y`. Check each
   product and each sum for finiteness before continuing; no fused multiply-add,
   reassociation, tree reduction or tolerance-based arithmetic is admitted.
   A nonfinite intermediate refuses the entire unchanged transition.
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
   unsigned UTF-8 ID bytes. Every entity/target/source/contribution/deposit ID
   must be a nonempty well-formed Unicode-scalar string: reject lone UTF16
   surrogate halves before encoding. Preserve exact scalar spelling and bytes,
   with no normalization or replacement encoding. Require unique exact UTF8
   bytes within each declared ID namespace; different IDs cannot share a sort
   key. Duplicate contribution identities refuse. The same admission applies
   to deposit ordering and every other canonical ID/tuple order. A semantic
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
   For each layer compute `a=gain_i*deposit_weight_i`, then `b_x=a*v_x`,
   then `D_x=b_x*h`; use the same a followed by `b_y=a*v_y`, then `D_y=b_y*h`.
   This is left-associated binary64 multiplication, without reordered or fused
   arithmetic. Check a, each b and each D for finiteness immediately and refuse
   the whole unchanged transition on overflow. Zero layer weight or an exact
   zero velocity vector skips that layer's deposit before these products.
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
   `prune_i(saturate_cell_i(fold_deposits(decayed_prior_i, ordered_D_i)))`,
   with `lambda_i=ln(2)/half_life_i` and required positive half-lives. The
   substep's deposit is recorded at the end boundary and is not decayed for
   time before its creation. Empty prior cells start at zero. Cell saturation
   and pruning have required separate revisioned calibration; their declared
   order is decay old field, add ordered new deposits, saturate, then prune.
   Compute lambda as ln(2) divided by positive half-life, multiply lambda by h,
   negate, then exponentiate. Multiply each prior component by that decay
   factor to initialize the accumulator (absent cell: exact [0,0]). Left-fold
   each canonically sorted deposit directly into this accumulator: x addition
   then y addition, checking each result immediately. Do not sum deposits from
   zero first or reassociate additions. All decay intermediates/products must
   be finite. Per-contribution creation times/provenance replay this schedule.
   Cell saturation is the same explicit radial cap algorithm, using a required
   positive finite velocity cap `cell_cap_i` per layer; it is not componentwise
   clipping. Then compute the same scaled norm of the saturated cell and prune
   (omit that cell from the next sparse buffer) exactly when the norm is at or
   below required finite `epsilon_i`, with `0 <= epsilon_i < cell_cap_i`.
   Equality prunes; epsilon zero prunes only exact zero. Calibration is
   revision-bound input with no default. Any invalid calibration or unsafe
   intermediate refuses the entire unchanged transition. Pruning retains
   immutable contribution/event provenance and an explicit prune observation;
   it does not erase admission/effect receipts or ownership.
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
The signed field-index coordinator amendment is satisfied by reviewed decision
`020d97fecae4a8d0d277b9b2695d9482620b4a76` and actual merge
`8c649fee2e95e5ec6b5304a3351a0e16fca60533`. Current owning-plan review and
native readiness remain outstanding. The old positive-only decision stays
provenance and supplies no admission for the exception by itself.

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
the standard EDN reader in Babashka, supplied by the existing pinned shared
workflow toolchain (Babashka 1.13.219). The gate consumes the entire file and requires
exactly one EDN map for each declaration; comments and whitespace after the map
are allowed, while a second form or malformed trailing bytes refuse the gate.
The standard `clojure.edn/read` API reads one map and then requires actual EOF
using an identity-distinct sentinel and a closed PushbackReader. NBB’s EDN
facade accepted unsupported `#!` reader comments, so this check uses Babashka’s
standard reader; strings and semicolon comments containing literal `#!` remain
valid. The shared toolchain setup is enabled for this dependency; the caller’s
explicit evidence script still supplies the gates, without a package install.
Apostrophe-prefixed symbols and ordinary lists remain valid EDN data, not
executed quote expressions. Its existing parse messages remain, and parsing
executes no domain law.
No new solver or mirrored implementation test is
claimed. Later RED/GREEN follows lawful native readiness in the owning packages.
Retain the frozen input, actual source/configuration hashes, commands, prior/new
state, independent readbacks, observed refusals and consumed causal trace.

Risks include discontinuity at nearest-cell boundaries, poorly calibrated force
or saturation hiding the deposit, numeric threshold divergence, mis-scoped
retained influence, unclear persistent atomicity and a decorative coupling
fixture. The reviewed finite calibration and sensitive physical ablation must
resolve these risks; the plan alone does not establish performance or behavior.

## Current4b planning corrections

Codex review 5523734461 on4b08fdd identified three missing deterministic rules:
4275496845 (force integration), 4275496853 (entity deposit binding), and
4275496863 (static-threshold placement). The proposal now specifies component
divide/multiply/add ordering before friction, the same immutable request or
passive-kind configuration as deposit-weight authority, and strict-below
thresholds after both speed caps. Matching EDN records the same boundaries.
These are reviewed proposal corrections, not executed physical behavior.

The separate coordinator selection amendment is actually MERGED as personal
Foresight PR36 at `8c649fee2e95e5ec6b5304a3351a0e16fca60533` on
2026-10-14T20:18:50Z, after current020d approvals/checks and canonical gate PASS.
The owning proposal binds its exact selected decision commit
`020d97fecae4a8d0d277b9b2695d9482620b4a76`; original 6a selection remains
historical provenance. This does not qualify this separate PR or establish
native readiness, an implemented kernel or any live B1/B2/B3 proof.


## Later native consistency and arithmetic corrections

Codex review 5524217029 roots4275894355/4363/4368 and MiMo
review 5524305119 root 4275970732 identified a stale ABI compatibility marker,
an unspecified norm algorithm, and unspecified deposit association. The ABI
now distinguishes original 6a from qualified020d/merge 8c and exposes the same
reviewed amendment state as the finite declaration. All wind/cap/threshold
norms use the explicit scaled component algorithm; deposits use declared
left-associated products with immediate intermediate checks. Future RED must
cover representable large norms, unrepresentable results and product overflow
versus reordering, alongside zero/equality cases. Proposed EDN parse is the
current verification; no solver, numerical behavior or native readiness is
claimed. MiMo's actual finding-bearing review does not approve the source.


## Explicit field-fold and calibration algorithms

Later Codex review 5524401966 repeats the introductory selection status concern
already corrected in c79 and identifies four further unspecified operations:
weighted sampling arithmetic, next-cell accumulation, cell saturation/pruning
and inactive-cap division. Their exact ordered binary64 operations and zero/
equality/refusal cases are now declared above and in the EDN. No per-component
cell clamping, reassociation or ignored intermediate overflow is admitted.
Future RED includes cancellation-sensitive folds, subnormal inactive caps,
prune equality/zero and unsafe products. Current verification is declaration
parse/hygiene; implementation and causal behavioral proof remain outstanding.


## Active-cap underflow and strict ID encoding

Codex 5524555284 roots4276175354/5366/5369 add three confirmed boundaries:
active cap ratio underflow, cell-operation norm applicability, and noninjective
replacement UTF8 encoding of lone surrogates. The cap now has an explicit
underflow fallback, the norm declaration includes cell saturation/pruning, and
IDs require well-formed Unicode scalars and unique exact bytes. Future RED
includes MAX_VALUE capped to MIN_VALUE, unequal tiny components, malformed
surrogates and preserved distinct composed/decomposed valid ID spellings.
No numerical behavior or solver execution is claimed by this plan correction.


## Zero-cap, coordinate-floor and final-cap certification

Codex 5524722331 roots4276317791/7801/7807 confirm three further numerical
ambiguities. Zero speed caps now precede norm evaluation after finite-input
validation. Cell identity uses exact integer floor of the decoded binary64
rational ratio, covering negative underflow and near-integer boundaries while
retaining safe stored indices. Active caps recertify the rounded result with
at most two ordered inward corrections; an uncertifiable result refuses the
whole transition. Future RED includes huge finite zero-cap vectors, tiny
negative cell ratios, quotient boundaries and 5*MIN_VALUE caps of diagonal
large vectors. These are algorithm declarations, not executed solver proof.
