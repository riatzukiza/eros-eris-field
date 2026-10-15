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

Every norm in aggregate wind saturation, both speed caps, both static
thresholds, cell saturation/pruning and contact normal/overlap geometry uses
this same scaled binary64 algorithm. Validate finite components
`x,y`; set `m=max(abs(x),abs(y))`. If `m=0`, return exact zero. Otherwise compute
`u=x/m`, `w=y/m`, then `u2=u*u`, `w2=w*w`, then `q=u2+w2`, then `r=sqrt(q)`,
then `n=m*r`, in that order, with the selected compiled Node binary64 square
root and no fused arithmetic. Check each intermediate for finiteness; a final
unrepresentable norm refuses unchanged state. Do not substitute naive squaring,
`Math.hypot`, approximation or replay tolerance. A representable large norm
therefore does not refuse merely because unscaled component squares overflow.
For every radial cap, first validate finite components and the operation-specific
cap domain. Aggregate wind and cell-saturation caps must be finite and strictly
positive; zero refuses unchanged state even for a zero vector. Kind speed caps
alone are finite nonnegative. Only that valid zero speed-cap case returns exact
[0,0] before evaluating any norm, even when the finite vector's norm would be
unrepresentable. No generic shortcut may precede operation-specific validation. Otherwise
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
   Before pair enumeration, validate every entity's revision-bound kind and
   contact role. This finite pass admits only the following complete matrix;
   kind names below are unordered, while the roles remain directed:

   | Entity kinds | Eligibility and roles |
   | --- | --- |
   | presence / presence | Excluded; no contact or contact observation. |
   | presence / nexus | Excluded; no contact or contact observation. |
   | nexus / nexus | Excluded; no contact or contact observation. |
   | daimoi / presence | Eligible; daimoi is particle, presence is recipient. |
   | daimoi / nexus | Eligible; daimoi is particle, nexus is recipient. |
   | daimoi / daimoi | Excluded; no contact or contact observation. |

   Presence and nexus have the recipient role; daimoi has the particle role.
   Missing/unknown kinds or missing/conflicting roles refuse the entire
   unchanged transition before the pass. Exclusion applies at both overlapping
   and separated positions; it is not an unsupported reflection or absorption.
   Enumerate every eligible unordered pair once, then test its overlap. An
   explicitly supplied contact pair outside this matrix refuses rather than
   bypassing eligibility; unknown absorption/exchange intents retain their
   existing refusal. Canonical ID sorting never selects or swaps roles. This
   finite case does not add passive/passive or particle/particle collision
   mechanics to the broader historical ABI.
   The finite deflection case supports declared spherical contact geometry with
   finite nonnegative particle/recipient radii and a positive recipient radius,
   plus revision-bound particle/recipient roles and restitution `0 <= e <= 1`.
   Other geometry requires its own reviewed normal construction; unsupported or
   ambiguous geometry/roles refuse rather than supplying an arbitrary normal.
   At the frozen moved positions, compute `w_x=p_particle_x-p_recipient_x`,
   then `w_y=p_particle_y-p_recipient_y`, then `q=norm(w)` using the declared
   scaled norm. Check every intermediate immediately. Overlap uses inclusive
   `q <= (radius_particle + radius_recipient)`, with that finite sum evaluated
   once. A valid overlapping pair requires `q > 0`; coincident centers refuse
   unchanged state. Compute `n_x=w_x/q`, then `n_y=w_y/q`, checking each finite
   result. These exact constructed components are the validated outward normal;
   no supplied alternative, fuzzy replacement or second normalization is used.
   Read world velocities from the private contact-pass working buffer, initially
   `v_move`. Compute relative x then y by particle minus recipient. Compute
   `d_x=v_relative_x*n_x`, then `d_y=v_relative_y*n_y`, then `d=d_x+d_y` in that
   order. When `d < 0`, compute `a=1+e`, then `b=a*d`, then `c_x=b*n_x` and
   `r_x=v_relative_x-c_x`, then `c_y=b*n_y` and `r_y=v_relative_y-c_y`.
   Otherwise retain the relative components without evaluating that reflection
   branch. Restore world x then y by adding the recipient working velocity to
   the resolved relative component, including the non-impulse branch; no
   bit-identical original-world-velocity shortcut replaces this declared
   round trip. Every product, sum, subtraction and division receives an immediate
   finite check; nonfinite arithmetic refuses the entire unchanged transition.
   Fused multiply-add, reassociation and alternate dot/norm primitives are
   forbidden. Record raw/normalized normal, dot terms/sign branch, resolved
   relative/world response and source geometry/configuration in the trace.
   Only the private contact velocity buffer evolves between canonical pairs;
   positions remain frozen and fields/forces/deposits cannot observe those
   updates before the pass completes. The final cap/threshold still runs once
   after the whole contact pass. Future RED covers non-axis normals, moving
   recipients, near-zero/cancellation-sensitive dots, tangent/separating round
   trips, coincident normals and unsafe intermediates under the reference profile.
   Exercise all six matrix rows with overlap and separation, each eligible row
   in both input orders, malformed kind/role inputs and excluded explicit pairs.
   A later refusal in a multi-pair pass must discard every earlier private
   velocity update and all candidate observations/deposits; prior state remains
   unchanged. Record the matrix revision and actual eligible ordered pairs in
   the replay trace, not just the supplied input-pair count.
   Compare the eligibility-matrix revision and full actual eligible ordered-pair
   sequence exactly during replay, including separated eligible pairs that emit
   no contact. Negative replay fixtures alter only that revision or omit/reorder
   an eligible separated pair while state and contact observations stay equal;
   exact trace comparison must fail before causal use or outward effects.
   Contact response is computed before this second cap and retained in the
   trace; do not interleave caps between contact pairs. Motion deposits use the
   final post-contact-cap-and-threshold velocity, with no second position advance.
   For this finite contact pass, positions remain exactly `p_move`: contact
   changes velocity only. Do not snap to a contact point, correct penetration,
   project onto a surface or advance position again. Deposit-cell selection
   uses that unchanged `p_move`, including at cell boundaries. Any later
   positional solver requires a separately versioned rule and requalification.
   Re-evaluate geometric overlap afresh at each substep from its moved positions.
   Each valid admitted overlapping unordered pair emits exactly one contact observation
   in canonical pair order for that substep, even when velocity is tangent,
   zero or separating and the response applies no impulse. There is no
   cross-substep suppression or extra observation within the same pair/substep.
   A separated pair emits none. Bind observation identity to step and exact pair;
   replay does not mint another effect or reinforce retrieval. Penetration
   fixtures continue through the next substep and assert its exact overlap,
   contact count/order and inclusion trace, including a pair that stays overlapped
   and one that separates. Existing work/trace caps still refuse overflow.
   Deposits and completed contact outputs enter the following world/field buffer;
   the ordered private contact velocity buffer is the sole within-pass exception.
   Class order and contribution
   order are revision-bound semantics, not collection insertion order.
6. Deposit `D_i = gain_i * deposit_weight_i * v_resolved * h` in the cell
   selected by the surviving entity's **unchanged `p_move` after contact**.
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
   it does not erase admission/effect receipts or ownership. Traverse the union
   of prior-cell and current-deposit keys in lexicographic complete-key order:
   scope revision by exact unsigned UTF8 bytes, then layer index, signed cell x
   and signed cell y by numeric integer comparison. Emit each prune observation
   in that traversal order after its cell decision; never persistent-map or
   serialized-number lexical order. A multi-cell pruning fixture inserts the
   same keys in reversed/map-layout orders and requires an identical exact
   ordered prune trace, including negative cell indices and numeric 2 versus 10.
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

In addition, require a lawful admitted-input comparison. From the same qualified
initial graph/field snapshot, construct two independently valid outside
encounters, each with its own canonical external revision, causal effect,
payload hash, cursor and expected revisions. The contact/inclusion packet
passes each arm through actual admission and candidate-projection validation,
then computes its pure kernel/contact/inclusion result and unchanged per-arm
kernel replay. Candidate state remains uncommitted; atomic commit, storage
readback and persisted-history replay are not contact completion requirements.
Hold initial scope, principal, query, seed, calibration, mood/lens/attention,
exact per-entity read weights and mapping revisions fixed. Also freeze the
exact eight deposit weights and deposit-mapping revision for every daimoi's
own immutable admitted request, and the exact configured per-kind deposit
weights/mapping revision for presence and nexus. Distinct request identities
do not permit different deposit-weight values or mapping revisions. Choose
encounter inputs whose resulting deposit/bond changes actual motion, contact,
recall path and included association. Preserve both complete admitted candidate
histories. An edited buffer carrying the other arm's hash/effect/cursor refuses.
The later atomic packet, after contact is complete, commits each arm's consistent
graph/field/effect state and independently reads it back, then replays its
unchanged persisted history. That later storage qualification supplies both
arms' persistence proof; it is not a prerequisite for the earlier contact
packet. The separate non-admitted pure ablation remains the mechanism control.
Neither arm can be a self-post relabeled as outside input or a duplicate
assigned a new effect identity. This is future RED/GREEN acceptance, not an
executed proof.

Run the two atomic arms in distinct owned fixture stores or isolated namespaces,
each initialized from and independently verified against the same qualified
graph/field baseline contents, hashes, revisions and stored authority. Store
routing is an outer fixture adapter input, never a kernel/recall parameter or
payload-selected grant. Each arm validates its own actual expected revisions,
commits only to its own store and independently reads that store back. The first
commit cannot advance the second arm's baseline. Reversing execution order on
fresh isolated baselines must reproduce each arm's result. No shared mutable
store reset, historical hash/cursor edit or invalid buffer substitution qualifies.
Bound fixture storage and snapshot work under the existing disk/concurrency
rules; this declares future tests, not a store clone performed now.

Each executed quantum has one schedule-local stable `:step-id`: the exact safe
integer `:kernel-time-us` at that quantum's end boundary (prior kernel time plus
10,000 microseconds). It is scoped to the same admitted immutable kernel history;
existing owner/scope/effect identity supplies the outward namespace. Calculate
and validate it before committing that substep and record it on every contact
observation. Overflow refuses the unchanged whole transition. Advancing the
same admitted schedule in one call, split calls or later `catch-up` yields the
same ordered step IDs and unordered-pair contact identities. Restore preserves
kernel time and the recorded schedule; zero-time/no-op, observations, read,
emission, API-call count, wall UTC and event-cursor allocation cannot mint or
advance step IDs. Include split/catch-up/restore/zero-time contact identity
fixtures and once-only outward effect replay. This is identity within one
history, not a global uniqueness claim across independent histories.

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
Require a finite revoke-after-deposit fixture: retain an initially authorized
contribution, revoke it, then rebuild the retained field/trails, any causally
affected world projection and every active inclusion fold under the new permitted
scope before the next causal sample or inclusion use. Reauthorize retained
first witnesses against the current stored principal, scope and graph authority;
reconstruct canonical first-witness order, exact dedup IDs, reasons and budget
counters from admissible history. If reconstruction cannot establish them,
invalidate the fold and refuse or quarantine before causal use. Never retag or
reuse an old fold result under new authority. The causal control revokes a memory
after its first witness, checkpoints/restores and finishes the same horizon;
neither that revoked witness nor its dedup/result influence may survive.
Use immutable contribution history and a compatible trusted checkpoint; record
the new scope/projection/field bindings without rewriting old history. Compare
with a clean permitted-history control: remaining authorized contributions must
survive and revoked pressure/trail influence must disappear from subsequent
motion, contact and inclusion. Successful bounded rebuild is required where
complete admissible history exists. Missing or ambiguous reconstruction inputs
make the pure transition return exactly its typed unchanged-prior-state refusal;
it does not mutate that state into a quarantined alternative. The outer adapter
must separately quarantine the retained snapshot reference or refuse to load it,
blocking every causal sample/contact/inclusion until a successful authorized
rebuild. Retained bytes remain inspectable provenance. Test pure byte-identical
refusal separately from adapter no-causal-use enforcement; filtering display,
retagging the old aggregate or zeroing all fields cannot pass. Keep this selected
revocation case in the finite proof; broader sustained revocation/restart remains
later work.

## Reference numerical execution profile

The ABI defines one proposed reference profile: Node22.20.0, V8
12.4.254.21-node.33, Linux x64, executable SHA256
`b1cbec894e45a5814b6ab756e1e14f8a76516273197e67e0412b57c1e10d0d9f`.
`LN2` is the binary64 constant with bits `3fe62e42fefa39ef`
(decimal `0.6931471805599453`), not a fresh logarithm calculation. Decay and
elapsed friction use the unmodified `Math.exp` builtin from that selected
Node/V8 revision; the norm uses its `Math.sqrt`. The selected Node source
identifies `MathExp`/`Float64Exp` and the V8 exponential implementation.

Compute `h = quantum_us / 1000000` once. Decay computes `lambda = LN2 /
half_life`, then `z = lambda * h`, `a = -z`, one shared `factor = Math.exp(a)`,
then prior x and prior y times that factor, in order. Friction computes
`z = gamma_kind * h`, `a = -z`, one shared factor with the same exponential,
then pre-friction x and y times that factor, in order. Preserve every immediate
finite check and unchanged-state refusal; a later finite underflow cannot hide
an overflowing intermediate. Reassociation and fused arithmetic remain forbidden.

Pure `.cljc` law/domain owns formulas, order, validation and discrete decisions.
The narrow numerical binding supplies this deterministic primitive; outer
adapters inspect and qualify runtime identity before causal use, without runtime
discovery inside a pure transition. Bind profile, compiled kernel/configuration
and executable hashes plus actual launch/build options in qualification and
checkpoint/restore evidence. Runtime/profile mismatch refuses. This declaration
is not an implemented numerical binding or qualified kernel artifact.

Future RED includes decay/prune equality and adjacent binary64 values, strict
static-threshold equality, contact-sensitive motion, zero friction, finite
underflow and unsafe intermediates. Continuous tolerance never excuses a
different prune/static-stop/contact/path/inclusion decision. At every aggregate
wind cap, either speed cap and cell saturation, replay must also match cap
applicability, the zero-ratio versus nonzero-ratio branch, inward-correction
count and ordered correction/refusal decisions exactly. Test equality and
adjacent binary64 norms, ratio underflow and zero/one/two correction passes;
continuous vector tolerance cannot conceal a changed discrete cap trace. Identical schedules
remain mandatory; repeated quantum decay need not bit-match one aggregated
exponential. Portability of `.cljc` is not JVM/browser/Python or arbitrary Node
build numerical parity; another runtime requires its own reviewed qualification.

Primary references: [ECMAScript exponential](https://tc39.es/ecma262/multipage/numbers-and-dates.html#sec-math.exp),
[Node22.20 MathExp source](https://github.com/nodejs/node/blob/v22.20.0/deps/v8/src/builtins/math.tq),
[V8 exponential implementation](https://github.com/nodejs/node/blob/v22.20.0/deps/v8/src/base/ieee754.cc).

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
   unchanged `p_move` deposit position at penetration and cell-boundary fixtures,
   post-contact deposit velocity, decay-before-new-deposit,
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
6. The mood-state predecessor completes at its deterministic transition,
   atomic persistence and independent changed-state/revision readback, without
   waiting for appraisal or the blocked runtime consumer. The separate
   mood-consumer owns validated bounded appraisal and actual recall/prompt
   consumption. Actual Knoxx consumption in the served-proof successor then
   demonstrates field-to-contact-to-inclusion causality, separate persisted and
   consumed mood, and the same actual principal/revisions in the submitted
   maker prompt. Source fixtures alone do not complete B1/B2/B3.

## Dependencies, estimates and later obligations

Implementation still requires reviewed native decomposition/readiness, admitted
encounter data, a qualified scoped graph interface and completed owner/numeric
handoff. The graph-only interface may explicitly report `not-loaded`; actual
finite loop completion may not. Existing whole-story edges remain until reviewed
replacement interfaces are applied through Rheos; no larger task is marked Done
from this subset. The selected kernel needs standalone build/license adoption,
complete calibration and current source/consumer qualification before deployment.
These are packet acceptance obligations: ABI `d68344c4-f18b-4b96-8585-bd8f7ac7c6a2`
owns the standalone compiled build/facade/dependency contract after separately estimated source-rights task `5ce9c975-1d30-4679-b607-e2dcd76f8192` qualifies the exact selected-byte permission/license/notices artifact. That task is an explicit native ABI predecessor before extraction/distribution;
new library LGPL-3.0-or-later does not relicense ungranted historical bytes. Contact
`ba078119-482c-49dc-bd18-c2dfcaad9024` completes kernel/inclusion/replay source fixtures with valid fixture inputs. Separate re-estimated8-point calibration `4f4c7cf6-9be8-47b9-b03a-be235c4dd519` consumes that completed kernel and reviewed force inputs, then completes
one revisioned artifact with all force/contact/bounds/layer/threshold/radius/
restitution/half-life/noise/prune/saturation values and finite configured load/
time/memory/rejection evidence, without requiring storage or live deployment.
Deployment `885a4b34-74fb-4e4e-a42a-6dbb54d54829` independently verifies those
completed artifacts, exact currently qualified Eros/Eris/OpenPlanner/Knoxx and
Foresight source/consumer merges, compiled hashes/configuration and applicable
promotion/rollback gates before any served change. Missing calibration or
unqualified source refuses deployment; prose or an earlier packet's fixture
constants cannot supply adoption.
The signed field-index coordinator amendment is satisfied by reviewed decision
`020d97fecae4a8d0d277b9b2695d9482620b4a76` and actual merge
`8c649fee2e95e5ec6b5304a3351a0e16fca60533`. Current owning-plan review and
native readiness remain outstanding. The old positive-only decision stays
provenance and supplies no admission for the exception by itself.

The current Foresight native roster contains eighteen Incoming records: fourteen selected execution packets, retained field/mood/automatic aggregate parents, and the separate three-point selection predecessor `b5f2ba9e-8d67-4c73-9919-e275983aca87`. Selection is outside the fourteen-packet execution total; it is included in the native roster count and retains its existing relationships. Earlier fourteen-card creation remains history; calibration `4f4c7cf6-9be8-47b9-b03a-be235c4dd519` and source-rights `5ce9c975-1d30-4679-b607-e2dcd76f8192` are first-class initial Markdown with native readback/comment, not an invented creation event. Physical source execution now allocates16 plus separately estimated existing source-rights qualification2 and calibration8, atomic8, encounter3, scoped graph5, feedback5, mood transition/persistence3 and appraisal/consumer3, deployment5, served proof5 and closeout2: proposed total65 plus separate selection3; prior48 remains history. Earlier45/44/36 totals remain estimate history. Native Rheos classifies original field `ff3e628b-cd5c-4a89-a397-42cc88dbde70` through native category=aggregate-history and an explicit non-additive comment, preserving8/type/relationships and broader obligations. Conditional type=epic correctly refused without mutation because current children bind the character epic; no graph/type/aggregate-points adoption is claimed. Field8/mood5/automatic5 are containing history and excluded; do not add any containing-story/epic estimate to exact selected execution IDs.
The mood split refines existing work and independently proposed estimates,
not an adopted increase or new behavior/prerequisite. Independent fair estimate/
reuse/type/aggregation review through Rheos precedes Ready. No subtraction from
the original8-point field story or Incoming creation grants implementation.

The table records exact native `uuid`-namespace values, including feedback's
actual native default slug identity. `dependency` is the canonical Foresight
predecessor field; these are its complete selected values rather than a new
`blocked_by` parser or admission rule. Preserve native identity; never infer it
from a title or replace it locally. Parent/epic/dependency reads and writes
remain Rheos operations. Source qualification and full lawful graph readiness
remain mandatory before RED.

| Packet | Canonical task identity (`uuid`) | Proposed points | Exact parent | Exact epic | Exact dependency identities |
| --- | --- | --- | --- | --- | --- |
| admission | `a0176ec0-0616-4d7f-86e1-e6cf9a160a7a` | 3 | `6eb77110-8cf4-44d5-a242-f495d25d6aaf` | `63a0e4ff-353f-4c90-ab8a-7241d958d54c` | None |
| graph | `1eb3aa1f-53d2-4a6a-828c-57ffe990e23b` | 5 | `a1e9d6af-0233-4dcb-9677-5c76fa9a2701` | `63a0e4ff-353f-4c90-ab8a-7241d958d54c` | None |
| field-history | `ff3e628b-cd5c-4a89-a397-42cc88dbde70` | 8 (native aggregate-history category; excluded) | `63a0e4ff-353f-4c90-ab8a-7241d958d54c` | `63a0e4ff-353f-4c90-ab8a-7241d958d54c` | `a1e9d6af-0233-4dcb-9677-5c76fa9a2701`, `6eb77110-8cf4-44d5-a242-f495d25d6aaf`, `b5f2ba9e-8d67-4c73-9919-e275983aca87` (broader history; excluded) |
| source-rights | `5ce9c975-1d30-4679-b607-e2dcd76f8192` | 2 | `ff3e628b-cd5c-4a89-a397-42cc88dbde70` | `63a0e4ff-353f-4c90-ab8a-7241d958d54c` | `b5f2ba9e-8d67-4c73-9919-e275983aca87` |
| abi | `d68344c4-f18b-4b96-8585-bd8f7ac7c6a2` | 3 | `ff3e628b-cd5c-4a89-a397-42cc88dbde70` | `63a0e4ff-353f-4c90-ab8a-7241d958d54c` | `a0176ec0-0616-4d7f-86e1-e6cf9a160a7a`, `1eb3aa1f-53d2-4a6a-828c-57ffe990e23b`, `b5f2ba9e-8d67-4c73-9919-e275983aca87`, `5ce9c975-1d30-4679-b607-e2dcd76f8192` |
| forces | `2eebbcf3-875d-4b7e-aad8-50a1c46472d2` | 5 | `ff3e628b-cd5c-4a89-a397-42cc88dbde70` | `63a0e4ff-353f-4c90-ab8a-7241d958d54c` | `d68344c4-f18b-4b96-8585-bd8f7ac7c6a2` |
| contact | `ba078119-482c-49dc-bd18-c2dfcaad9024` | 8 | `ff3e628b-cd5c-4a89-a397-42cc88dbde70` | `63a0e4ff-353f-4c90-ab8a-7241d958d54c` | `2eebbcf3-875d-4b7e-aad8-50a1c46472d2` |
| calibration | `4f4c7cf6-9be8-47b9-b03a-be235c4dd519` | 8 | `ff3e628b-cd5c-4a89-a397-42cc88dbde70` | `63a0e4ff-353f-4c90-ab8a-7241d958d54c` | `ba078119-482c-49dc-bd18-c2dfcaad9024` |
| atomic | `2f4421ee-2e48-405e-96d2-fee1a5597ff2` | 8 | `ff3e628b-cd5c-4a89-a397-42cc88dbde70` | `63a0e4ff-353f-4c90-ab8a-7241d958d54c` | `a0176ec0-0616-4d7f-86e1-e6cf9a160a7a`, `1eb3aa1f-53d2-4a6a-828c-57ffe990e23b`, `ba078119-482c-49dc-bd18-c2dfcaad9024` |
| mood-state | `7f7b6b5b-2df1-4e52-a167-8e631ca598e4` | 3 | `8bcaa0f3-37ec-44e2-8f20-4798dfc4b795` | `63a0e4ff-353f-4c90-ab8a-7241d958d54c` | `2f4421ee-2e48-405e-96d2-fee1a5597ff2` |
| mood-consumer | `5450c07d-1e90-4640-90e9-995f1e32d28a` | 3 | `8bcaa0f3-37ec-44e2-8f20-4798dfc4b795` | `63a0e4ff-353f-4c90-ab8a-7241d958d54c` | `7f7b6b5b-2df1-4e52-a167-8e631ca598e4`, `1eb3aa1f-53d2-4a6a-828c-57ffe990e23b` |
| mood | `8bcaa0f3-37ec-44e2-8f20-4798dfc4b795` | 5 (aggregate history; excluded) | `4cac8ac8-1a9f-441d-ac87-aa09f874eb57` | `63a0e4ff-353f-4c90-ab8a-7241d958d54c` | `7f7b6b5b-2df1-4e52-a167-8e631ca598e4`, `5450c07d-1e90-4640-90e9-995f1e32d28a` |
| automatic | `2df3d26b-394a-436d-9e02-fe18a55132dd` | 5 (aggregate history; excluded) | `5ea872c3-1db4-47c5-a63d-d49f99f79497` | `63a0e4ff-353f-4c90-ab8a-7241d958d54c` | `2f4421ee-2e48-405e-96d2-fee1a5597ff2`, `8bcaa0f3-37ec-44e2-8f20-4798dfc4b795`, `1eb3aa1f-53d2-4a6a-828c-57ffe990e23b`, `deliver-outcome-attributed-once-only-graph-feedback`, `7bdedd43-30a2-41b6-8f5c-e5c3aa5e9f71` |
| feedback | `deliver-outcome-attributed-once-only-graph-feedback` | 5 | `a1e9d6af-0233-4dcb-9677-5c76fa9a2701` | `63a0e4ff-353f-4c90-ab8a-7241d958d54c` | `1eb3aa1f-53d2-4a6a-828c-57ffe990e23b` |
| deployment | `885a4b34-74fb-4e4e-a42a-6dbb54d54829` | 5 | `2df3d26b-394a-436d-9e02-fe18a55132dd` | `63a0e4ff-353f-4c90-ab8a-7241d958d54c` | `1eb3aa1f-53d2-4a6a-828c-57ffe990e23b`, `2f4421ee-2e48-405e-96d2-fee1a5597ff2`, `8bcaa0f3-37ec-44e2-8f20-4798dfc4b795`, `deliver-outcome-attributed-once-only-graph-feedback`, `4f4c7cf6-9be8-47b9-b03a-be235c4dd519` |
| causal | `f503ae5a-e414-4da8-a8d4-328a7218bcf3` | 5 | `2df3d26b-394a-436d-9e02-fe18a55132dd` | `63a0e4ff-353f-4c90-ab8a-7241d958d54c` | `885a4b34-74fb-4e4e-a42a-6dbb54d54829` |
| closeout | `7bdedd43-30a2-41b6-8f5c-e5c3aa5e9f71` | 2 | `2df3d26b-394a-436d-9e02-fe18a55132dd` | `63a0e4ff-353f-4c90-ab8a-7241d958d54c` | `f503ae5a-e414-4da8-a8d4-328a7218bcf3` |

Graph read completion supplies ABI and atomic inputs without waiting for its
separate feedback successor. Deployment depends on graph, atomic, mood and
feedback; causal proof depends on deployment; terminal closeout depends on
causal proof. Atomic persistence feeds the independently completable mood
transition/persistence interface; the separate bounded appraisal/actual-consumer
child consumes it and the scoped graph interface. The mood parent integrates
both; the automatic parent's additional terminal-closeout dependency prevents
its completion before deployment/proof/closeout. Children have parent links,
not dependencies on the automatic parent, so this introduces no dependency
cycle. These
edges are observed initial planning state, not installed readiness/admission.
The owning Foresight plan and this source plan retain independent gates.


Later work retains full absorption/bounded exchange and multi-contact
conservation, the complete bond/association matrix, sustained quiet/load/restart
and broader revocation behavior beyond the required finite revoke-after-deposit
case, long-running outcome-reinforcement studies, long-running mood and
traits, concurrent continuity, social/artistic outcomes and reserved-head/recovery
guarantees. The finite selected persistence/privacy/replay proofs stay mandatory.

## Verification and risks

Review this document and its matching declared-rule data; parse the data with
the standard EDN reader in Babashka, supplied by the isolated
`proposed_abi_parse` job (Babashka 1.13.219). The gate consumes the entire file and requires
exactly one EDN map for each declaration; comments and whitespace after the map
are allowed, while a second form or malformed trailing bytes refuse the gate.
The standard `clojure.edn/read` API reads one map and then requires actual EOF
using an identity-distinct sentinel and a closed PushbackReader. NBB’s EDN
facade accepted unsupported `#!` reader comments, so this check uses Babashka’s
standard reader; strings and semicolon comments containing literal `#!` remain
valid. This job has only contents:read, no App secrets/private mirror, and parses
with `bb --config /dev/null` after exact clean-head checks, repeated afterward.
The reusable reviewer depends on parser success and receives explicit
`setup_eta_mu_toolchain: false`; the pinned producer's credential detector,
dependency-token and private-mirror chain must stay skipped. Its explicit
evidence script checks the successful parser-job result plus diff gates,
without reinstalling the parser or running candidate `bb.edn` initialization.
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


## Bound atomic authority and same-encounter proof — 2026-10-15

Immediately before entering the atomic transaction, independently reload the actual stored principal, grants/sharing/visibility, admission policy and scope revision from their authoritative owner. Require equality with the admitted/current computation binding and authorization for every relationship/embedding/field/effect write. Bind the transaction's commit condition to those authority/policy versions as well as expected graph/field revisions; a revocation or version conflict during the transaction aborts before any component is committed. No payload authority or earlier snapshot can substitute. Fixtures revoke/change private/shared access after admission, during computation and between the final authority read and commit, requiring no graph/field/effect write or partial success.

Before physical candidate projection, bind one new-encounter content embedding identity to the exact admitted content revision/hash: exact embedding bytes/hash, shape/dimensions and embedding model/configuration revision. Use those same bytes/revisions in semantic projection, atomic commit and independent after-state readback. Reuse the existing bounded embedding route without changing model routing or credentials. Preserve unchanged existing-memory embeddings separately; test E1 candidate versus E2/missing persisted embedding and content/model/config drift as refusals.

The selected projection has one exact outcome for each unavailable embedding:

| Input condition | Status | Code |
| --- | --- | --- |
| Missing embedding | refused | embedding-missing |
| Indexing pending | refused | embedding-pending |
| Embedding production failed | failed | embedding-failed, with the bounded typed audience-safe cause defined below |
| Content/hash/shape/dimensions/model/configuration binding mismatch | refused | embedding-binding-mismatch |

Every row preserves the complete prior graph, field and effect-receipt state,
the existing admitted envelope and cursor. This projection writes no retained
incomplete-admission or retry/cursor state and reports no complete physical
effect. It does not roll back an envelope already admitted by the separate
intake authority. No automatic retry occurs here. A later separately authorized
bounded attempt consumes the same admitted content/effect identity with fresh
current authority and newly validated embedding; it cannot mint another effect.
A changed content revision requires its own admitted predecessor binding.
Future RED asserts each exact status/code and unchanged state, plus a the atomic packet's bounded availability/resubmission fixture and once-only atomic
commit. This does not implement an additional ingestion/recovery state machine.

The natural B1 encounter/content revision and its immutable root effect remain common provenance, never a mutable effect with two values. Use comparison manifest `selected-encounter-comparison/1`: freeze the actual stored principal/scope and authority, selected encounter/content hash, root-effect reference, attributed domain deposit/bond identity, the independently verified pre-selected-effect graph/field checkpoint, query/corpus/embeddings, seed, time schedule, mood/lens/attention and every other causal input. Declare exactly one selected deposit/bond property, its units/domain and the control/comparison values; both values must be independently admissible and nonzero. The control value equals the naturally observed selected value. An unrelated encounter or unadmitted ablation fails proof.

Each arm starts from that same authorized baseline in a distinct isolated diagnostic store/stream. Through the qualified canonical Clio interface admit a distinct comparison event/effect citing the same selected root and exact manifest/arm/value; apply that comparison effect once instead of reapplying the original production effect. Clio owns those genuine event/effect identities, parent links and idempotency. Do not invent local IDs, overwrite the natural event, reuse one immutable effect identity for different bytes, or apply both effects to the production state. Unsupported canonical comparison admission refuses proof. Replay each arm with its existing admitted IDs rather than reminting.

Permitted differences are the declared physical value and necessary comparison identity/manifest provenance. Independently prove comparison metadata introduces no additional physical/recall input: canonical domain IDs, input ordering, random seed and all nonintervened numerical/read inputs remain equal. Derived event-history, graph/field revisions, motion/contact/path and included-memory outputs are expected to differ and must be traced/read back per arm; they are not frozen equal. Invoke the same qualified served physical and recall/prompt-assembly path under the actual principal for each admitted diagnostic arm, and require at least one different eligible contact and one different actually included authorized memory beyond the seed. The unchanged natural turn alone supplies live B1/B3; diagnostic comparisons cannot supply another natural turn, production feedback or publication. Never replay publication to manufacture this contrast.

Classify artifact and destination evidence audiences separately from the maker's access. Private/restricted artifact bytes, paths/media identity, destination account/record IDs/URLs and their association may be inspected only through an authorized protected seam outside Git/public logs. Retain full restricted matching proof only in protected private storage or inspect transiently. Committed/reviewer/public evidence may retain only an explicitly audience-authorized digest/redacted binding to that protected proof; identifiers or hashes are not presumed safe merely because the maker may read them. No credentials, raw private artifact/message content or unapproved identifiers enter receipts/events/resources/logs. Positive private-destination/artifact fixtures must prove actual protected matching and no forbidden retained disclosure; public outcomes retain their authorized independent readback. If protected verification or safe evidence is unavailable, refuse outcome proof and reinforcement. No publication replay.


## Canonical event/authorization and producing-artifact custody — 2026-10-15

Atomic authorization consumes an Axxium-owned current decision and its policy/grant version through the qualified Axxium interface, bound to actual stored principal, action, resource and permitted scope. Validate that Axxium decision/version through commit under its qualified admission/fencing seam, not just an OpenPlanner cached grants/policy snapshot or a locally minted version. Reload actual owner inputs and refuse revocation/mismatch/unsupported commit protection before any graph/field/effect component commits. Use the actual qualified Axxium shape/field names at the adapter; this declaration invents no competing authorization implementation. A fixture with stale local grants but current Axxium denial must write nothing.

The tuple of end-boundary step ID and canonical unordered pair is a deterministic contact/domain key within the admitted kernel history, not native event identity. Pure kernel observations are data. The outward adapter maps that key, immutable source/history and ownership to the qualified canonical Clio event envelope; Clio owns emitted event identity, causal stream and idempotency admission. Retain the actual admitted Clio event reference beside the domain key so replay recovers the same event/effect without reminting. Never deduplicate or authorize a downstream effect solely with the tuple or implement a local event-identity scheme; unsupported Clio admission refuses outward effects. Split/catch-up/restore fixtures verify the same domain observations and canonical admitted event/effect references.

Checkpoint state includes the actual producing compiled-artifact SHA256, build-qualification identity and exact launch-profile identity/digest, alongside kernel/config/numeric revisions. Bind these to independently verified qualified producing source/build/runtime evidence and include them in the canonical checkpoint hash. Restore independently verifies the actual currently loaded artifact/build/launch qualification and requires equality with that producing identity before causal use; same revision labels alone cannot pass. Missing producer fields or a byte-different artifact/build/launch identity refuses unchanged state. No silent migration, copied producer label or new snapshot hash can qualify a different producing executable; a separate reviewed migration would be required outside this finite same-artifact replay proof.

Require independently bound reviewed friction coefficients for presence, nexus and daimoi; none may inherit a shared/default coefficient. Positive isolated fixtures use three distinct reviewed gamma values, fixed elapsed schedule and initial velocity with other forces/contact/caps/threshold effects neutralized, checking each kind against its own elapsed exponential and mechanics/calibration revision. Include the moving daimoi case explicitly, a valid zero-friction case, repeated/quiet/split schedules and wrong/default/shared coefficient negatives. Enforce the existing mechanics inequality `gamma-presence > gamma-nexus > gamma-daimoi >= 0` before any transition; it is independent of static-threshold ordering. Equal adjacent, distinct reversed and negative-daimoi values refuse the whole unchanged transition. Zero is valid only for daimoi with both strict predecessor inequalities satisfied; no shared/default coefficient or newly inferred ordering is admitted. All operation-specific cap domains are validated before generic radial shortcuts: wind and cell caps are strictly positive; only kind speed caps permit zero. Zero invalid wind/cell calibration refuses unchanged state even for zero vectors; valid zero speed returns zero before norm arithmetic.

The actual submitted model-visible authorized node/edge path and traversal trace explicitly carries BOTH matching graph/projection revision and physical-field revision, bound to the selected encounter/effect lineage and independently read states from served-proof packet `f503ae5a-e414-4da8-a8d4-328a7218bcf3` acceptance criterion1. A singular traversal/graph revision plus a field revision only in protected diagnostic metadata cannot satisfy B3. Add stale/mixed/omitted model-visible field-revision negatives while preserving protected full-prompt inspection and audience-safe retained evidence.

## Canonical contact-pair traversal — 2026-10-15

Reuse exact well-formed scalar entity IDs and unsigned UTF8 byte comparison. Normalize each unordered distinct-entity pair into `(lower-ID, higher-ID)` without Unicode normalization, locale, case folding or replacement. Compare normalized pairs lexicographically by first-ID bytes, then second-ID bytes; a proper byte prefix sorts before its extension. Enumerate each eligible unordered pair exactly once in that strict substep order. Normalization defines identity/traversal only; it cannot swap validated particle/recipient roles or reflection orientation. Duplicate/malformed IDs, self pairs or duplicate supplied pairs refuse the unchanged transition rather than acquire insertion-order ties.

With at least3 eligible overlapping entities/several contacts, reverse entity/pair/map input order, including non-ASCII IDs/common prefixes. Require identical ordered pair/domain-key observations, private contact-velocity updates, final deposits/state and admission references under the same numeric profile/seed. Map order cannot define physical outcomes.


## Measurable finite qualification and safe failure ownership

The proposed finite qualification profile `finite-character-load/2` retains the selected ABI maximum100 substeps per call. State caps remain32 entities (8 presence,8 nexus,16 daimoi),64 bonds and256 complete scoped layer-cell keys. Proposed per-call caps are131072 trace records,8388608 encoded trace UTF8 bytes and67108864 work units. Exact limits accept otherwise valid input; each one-over refuses unchanged. No omitted trace, clipping or silent load reduction meets a cap.

Bound variable width before expensive decoding/comparison: complete incoming wire at most4194304UTF8 bytes, each exact entity/contribution/deposit/source/target/request ID at most128UTF8 bytes, and every other variable-width string at most512UTF8 bytes (stricter existing shape limits still apply). Use the qualified ABI/owner codec and a bounded outer reader before full allocation/decoding; decode/validate scalar strings before sorting, with bounded scans that stop once the relevant cap is exceeded. Reject, never truncate, normalize, hash-replace or relabel an otherwise canonical identity. Charge one work unit before each entity-update/layer-cell visit/eligible-pair evaluation/contribution application AND before every input code unit or UTF8 byte processed by scalar validation, encoding, comparison (each operand byte), hashing or serialization; each trace append also costs one. Canonical ordering uses `finite-order-work/1` below, so an adaptive host sort cannot change acceptance through a different comparison count. Account across the entire call, including preflight and attempted visits, without resetting counters by phase. Preflight/lazy bounded trace encoding enforces byte/record caps before append or whole-result exposure. Input/ID/string overflow returns refused/finite-input-byte-limit; trace overflow refused/finite-trace-budget-exceeded; work exhaustion refused/finite-work-budget-exceeded, all with exact prior state and no partial credit. Test exact/one-over IDs with multibyte Unicode, complete wire bytes, trace bytes/records and work, holding other bounds valid; bytes must not be inferred from character counts or fixed short-ID fixtures.

Before timing, freeze reviewed fixture bytes/layouts/seed42, calibration and source/build/runtime/host identities. High-density (all state caps), quiet and four-step catch-up workloads each execute64 quanta per baseline/selected-contribution arm in exactly16 calls of4 substeps. Separately execute a maximum-call workload at the same state/byte envelope:100 quanta in exactlyONE call per arm, plus an otherwise valid101-quantum elapsed input that executes100, returns successful incomplete with exactlyone quantum of explicit backlog, then drains that one through catch-up without new elapsed time. This tests the retained100-step ceiling directly; sixteen small calls cannot substitute. Disclose five bounded warm-up calls. Proposed acceptance budgets remain1000ms wall time per measured call (including the100-step call),512MiB process peak RSS and120000ms entire job including warm-up/controls. Record every measurement/baseline delta; equality passes and exhaustion/failure does not qualify. Wall/RSS are outer observations, never pure clock/process reads. These are unadopted finite engineering targets, not observed performance/defaults. A failed target requires a reviewed changed artifact, not silent tuning or a larger host limit.

A dedicated fixed causal fixture must produce at least one different eligible contact and at least one different actually included authorized memory beyond the vector seed between permitted field-intervention arms, with every other declared input fixed. A finite nonzero vector alone or saturation hiding every downstream change fails calibration. Retain complete force/contact/bounds/layer/threshold/radius/restitution/half-life/noise/prune/saturation values, domains, source/review and revisions. Missing values fail; no library default or source pin adopts calibration.

The versioned finite revocation profile `finite-revocation-rebuild/2` admits at most128 immutable contribution events after the trusted checkpoint,1048576 canonical Clio envelope UTF8 bytes for that tail,64 replayed quanta and67108864 total rebuild work units. It respects finite-character-load/2 state, variable-width input/ID/string and trace byte/record caps; selected codecs stay owned by ABI/Clio. Charge all visits and actual scalar/UTF8 validation, encoding, comparison, hashing and serialization before each operation across the ENTIRE private rebuild, including preflight. Preflight tail count/bytes with bounded readers before replay; no component commits until complete authorization and every budget pass. Test each exact/one-over bound independently, including multibyte/long-ID and trace-byte exhaustion. Pure rebuild count/byte/step/work exhaustion returns refused/revocation-rebuild-budget-exceeded with byte-identical prior state. The outer adapter separately quarantines/refuses the retained reference and permits no causal use until successful authorized rebuild. The outer rebuild call has2000ms wall budget; timeout yields no accepted replacement and the same quarantine, never a pure clock read/partial commit. Missing/ambiguous history retains its distinct refusal. No automatic budget increase, new scheduler or broad recovery program is included.

Embedding production failure returns failed/embedding-failed with a bounded typed category from timeout,unavailable,rate-limited,invalid-output,internal-error,unclassified. The existing qualified embedding-provider seam consumed by atomic8 owns versioned mapping `embedding-failure-category/1`; consumers retain that category/mapping revision verbatim rather than reinterpret errors. At that protected seam, shape validated actual HTTP status and explicit transport-timeout/unavailable, invalid-output and internal-failure indicators from the actual provider outcome. Do not parse or retain exception prose. If the bound indicator attestation is unavailable or malformed, return unclassified before evaluating rules1–5. Otherwise apply FIRST matching rule: (1) HTTP429 => rate-limited; (2) explicit timeout OR HTTP408/504 => timeout; (3) explicit transport-unavailable OR other HTTP500–599 => unavailable; (4) explicit validated invalid-output => invalid-output; (5) explicit validated internal-failure => internal-error; (6) no match, unavailable/malformed attestation or unknown => unclassified. A contradictory lower-priority flag cannot override the first match. Tests require timed-out429=>rate-limited,503+invalid-output=>unavailable,timeout+invalid-output=>timeout,invalid-output+internal=>invalid-output, and missing/unknown=>unclassified, with exact stable replay/category/revision and no raw-string heuristics. Atomic8 owns delivery/qualification at the actual existing provider seam as part of its failure handling, not a second classifier in Eros/Eris or another unowned prerequisite.

State/receipts/review artifacts contain no raw provider exception/body/header, credential, private path or private source ID. An optional at-most128UTF8-byte opaque diagnostic reference is retained only after independent audience authorization; otherwise omit it. Actual raw provider evidence remains solely in its authorized protected diagnostic store. RED injects a synthetic secret/header/private-ID marker and proves absence from every public/retained output while preserving deterministic typed failure.

Atomic packet `2f4421ee-2e48-405e-96d2-fee1a5597ff2` owns the finite availability/resubmission source fixture and idempotent entry point. Its bounded caller fixture makes exactly one initial projection call with unavailable embedding and at most one explicitly authorized resubmission (two calls total,10000ms whole-fixture wall cap); it supplies availability through the existing embedding port, fresh actual owner authorization and the same admitted content/effect identity. The caller issues the second call only after controlled valid embedding availability; a permanently unavailable input ends without success. A third invocation is outside this finite driver budget and cannot be executed or counted as proof. Each call remains independently checked; only one graph/field/effect transaction may commit. Changed content needs its own admitted predecessor. The packet implements/tests no automatic retry trigger, sleep, queue, daemon, persistent attempt counter or new recovery state machine; production retry orchestration is not an exit of this finite source fixture. Fresh authorization, unavailable/permanent failure, conflicting revision, duplicate after success and one-commit readback controls belong to the same8-point atomic packet, not an unowned successor.


## Matched proof and Incoming re-estimation — 2026-10-15

Reinforcement also requires an independently established contribution witness `recalled-item-contribution/1`, bound to the exact recalled item/content/graph revision, actual turn and action/effect, actual saved artifact bytes/hash and independently observed destination outcome. Its source must be an authorized supervisor/qualified transformation observation, not a model-authored claim or a copied item ID. Accept either (a) independently captured actual consumed-input/choice-to-artifact provenance through a qualified transformation whose effective artifact/action parameter is derived from that item, with independently matched actual execution and artifact readback, or (b) a matched bounded causal intervention showing that changing only the permitted recalled contribution changes the relevant action or artifact output. Mere presence in a prompt, unused recipe metadata, a destination label, producer acknowledgment or successful unrelated artifact supplies no contribution witness.

The pre-deployment writer qualifies the witness shape, source/identity/authority and matching logic with isolated positive and negative fixtures; actual natural contribution/outcome observation remains the served proof. In the intervention channel use at most two isolated, publication-disabled transformation executions within10000ms, frozen remaining inputs and a qualified declared input/output mapping. Never replay destination writes or infer model understanding from a changed hash. A nondeterministic/unavailable/unqualified transformation or uncertain witness refuses reinforcement rather than substituting a narrative. Tests include recalled M plus unrelated successful A, a forged M label, an input field ignored by the transformation, mismatched content/turn/effect/artifact, denied witness authority, and a valid contribution with failed destination readback: all write no reinforcement. A qualified positive requires both actual contribution and complete independent artifact/destination matching before one atomic once-only feedback commit.

Require an independently verified owner/epoch fence that prevents BOTH old-artifact persistence and publication throughout revision change and rollback. The fence must be effective before serving the replacement, bound to every old parent/delegate/effect writer and the new owner, and independently read back at both effect boundaries; one fenced endpoint is insufficient. Preserve held maker identities and wait for verified terminal makers/parents/delegates before any service stop or replacement. Do not interrupt a maker to create eligibility. An idle poll, lease expiry, elapsed timeout, reachability or a maker status label is not a fence. If the qualified owner/admission interface cannot establish and retain both protections, refuse deployment and leave the current runtime unchanged; no unsupported idle alternative or local fencing implementation is admitted. The same protections and fresh qualified bindings apply during rollback.

The owning native Incoming estimates are now calibration8 (enforcement3/workload3/complete calibration2), atomic8 (classifier2/finite caller1/transaction5), composition-deployment5 (qualification2/fenced rollout3) and feedback5 (contribution witness2/writer3). Separate artifacts/refusal exits remain explicit inside each packet; all must pass for completion. This uses the review's re-estimate option, exposes existing work and changes no behavior or dependency identity. The same 14 selected execution packets then totaled 62 provisionally (superseded by the 65-point handoff below); previous 50/48 and containing field8/mood5/automatic5 stay non-additive history, selection3 separate. No aggregate-points adoption, native Ready, source implementation or deployment is claimed.


### Current revocation and estimate handoff — 2026-10-15

The same native fourteen execution packets now provisionally total 65. Contact ba078119-482c-49dc-bd18-c2dfcaad9024 is re-estimated through qualified Rheos from 5 to 8: ordinary contact/inclusion/replay source qualification 5 and the already required bounded revocation-tail rebuild 3. The latter separately owns typed-envelope decoding, four independent replay limits, whole-rebuild work/exact-one-over accounting and outer timeout/quarantine/no-causal-use evidence; both allocations are required for Done. This exposes existing work and changes no behavior or dependency. Calibration remains 8, with a matching 8sp label and operative handoff. Earlier total 62, contact 5 and other allocations remain history; containing field/mood/automatic estimates are excluded and selection 3 is separate. Contact step identity consumes the exact quantum from the revision-bound ABI selection. Pure portable .cljc contracts and causal tests precede adapters. Old native comments are retained and superseded by explicit readable corrections. No native Ready, aggregate adoption, implemented kernel, deployment or live B proof is claimed.


## Existing-order work accounting — finite-order-work/1

The field pure law/domain owns one bounded most-significant-component trie ordering operation over the ABI's already qualified key shapes. IDs use exact unsigned UTF8, with terminator before byte 0 through 255; tuples descend component by component, and signed numeric components retain the ABI's exact signed-integer key order. This does not create another identity codec, normalize IDs or change canonical pair/force/cell order. Scan each complete validated input key once for insertion, charge every code unit/key byte and edge visit before use, and create each distinct prefix node once. Traverse each distinct node with terminator first and a fixed 256-branch probe schedule, charging each probe/edge/emitted key; never use insertion-dependent comparison counts or host adaptive-sort comparisons as the semantic budget. The same valid logical multiset therefore has the same scanned bytes, distinct prefixes, probes, total charge and canonical result for sorted, reversed and shuffled arrival orders. Duplicate/invalid keys retain whole-transition refusal.

All allocation/traversal uses the existing bounded input, ID, state, trace and whole-call/rebuild work limits; insertion or traversal exhaustion exposes no partial state, inclusion or trace. Do not reset or discount the counter between preflight and execution. Qualify sorted/reversed/shuffled long-prefix Unicode and tuple fixtures at the exact required whole-call work bound and one unit below: all orders either accept the identical full result or refuse with the same budget code and byte-identical prior state. Retain this algorithm/revision and its charged work in replay/calibration custody. This repairs the existing deterministic-order/resource contract; it adds no host service or implementation here.

## Contact-to-memory inclusion — finite-contact-inclusion/1

Contact task `ba078119-482c-49dc-bd18-c2dfcaad9024` owns the portable pure fold after its qualified contact observations; OpenPlanner/Knoxx consume that result rather than implementing a second physical inclusion rule. Bind one actual admitted request/daimoi, stored principal/scope/authority, graph revision, field history, explicit request-emission start checkpoint and selected end checkpoint, plus this fold revision. The horizon is validated against those immutable inputs and the ABI's maximum substeps (currently 100) across the ENTIRE horizon. Split calls/catch-up/restored replay retain the same start/end and the complete qualified `inclusion-fold-state` in the canonical checkpoint ABI; an unqualified private cache cannot supply continuity. Restore validates the fold revision, actual request/authority/history, cursor, accumulated horizon quanta/semantic fold work, ordered first witnesses, exact dedup IDs and byte/record counters before use. All fields enter the state/snapshot hash. Missing/stale/forged/reset fields refuse unchanged state; fresh whole-call decode/validation/serialization work is charged separately rather than erasing accumulated fold work. Missing, reversed or oversized horizons refuse unchanged state. This is source qualification on candidate snapshots, with no dependency on later atomic storage or served proof.

Fold actual eligible overlapping contacts in exact `(step-end-time-us, canonical unordered pair)` order. Only contacts for the bound request's daimoi with an authorized memory-nexus recipient can add an item, using the actual qualified nexus-to-canonical-memory/content-revision binding. Presence contacts remain physical trace only, separated pairs add nothing, and another request's daimoi supplies no inclusion. Missing, conflicting or denied recipient/memory authority refuses the whole result. Deduplicate exact canonical memory IDs across repeated substeps and multiple nexuses, retaining the first contact in that order as the inclusion witness; output unique items in first-witness order. Every reason carries the exact memory/content revision, nexus/daimoi, step/pair, eligibility revision, graph/field history and fold revision. All contacts remain in the bounded physical trace; duplicate inclusion suppression never deletes observed contact provenance.

The owning state/work/trace byte/record caps apply before exposure; exhaustion refuses the whole unchanged transition with its existing typed code. No partial ranked or truncated physical inclusion is accepted. A later bounded prompt may explicitly subselect eligible items under its own disclosed consumer contract while retaining the full physical-fold custody; that is not a changed contact result. Required fixtures cover two distinct memory contacts, repeated contact across substeps, multiple nexuses mapping to one memory, reversed input, split/catch-up/restored schedules, presence-only and other-daimoi contacts, missing/denied/conflicting bindings and independent exact/one-over horizon/work/trace limits. Equal contact traces with the same bound horizon must yield identical ordered IDs/reasons. The earlier gamma and native-roster corrections above preserve their owning contracts; no Ready, measured solver, deployed inclusion or live proof is asserted.


## Canonical trace bytes and restorable fold custody

`finite-field-trace/1` in the declaration is the sole byte-counting trace codec. Encode the complete JSON array `["finite-field-trace/1", encoded-records]` as UTF8 with no BOM, whitespace or trailing newline. Every value is tagged: nil `["nil"]`, boolean `["bool",true-or-false]`, number `["f64","hhhhhhhhhhhhhhhh"]` using exactly16 lowercase hexadecimal digits for its big-endian IEEE754 binary64 bits, string `["str",s]`, keyword `["kw",namespace-or-empty,name]`, vector `["vec",encoded-values]`, map `["map",[[encoded-key,encoded-value],...]]`. Map pairs sort by the exact canonical encoded-key unsignedUTF8 bytes using the owning fixed ordering law. Escape quote and backslash with their two-byte JSON escapes; U+0000..U+001F always use lowercase `\u00xx`; emit all other well-formed scalar characters in exact UTF8 with no normalization or optional ASCII escaping. Positive/negative zero retain distinct bits. Nonfinite numbers, sets, lists, native objects and unsupported values refuse rather than acquire host printer semantics.

The8388608-byte trace bound includes the entire envelope, tags, separators, brackets and escaping, including its fixed empty-envelope overhead. Count/charge before byte/record exposure with the same whole-call work guard. EDN, host JSON number formatting or compacted output cannot determine this semantic admission. ABI defines the shape/bit representation and portable codec contract before implementation; contact/calibration consume it. Future RED/GREEN includes golden Unicode/control/map-order/binary64/zero vectors and independent complete-envelope exact/one-over limits. No codec implementation is asserted by this planning declaration.

The canonical ABI now requires `inclusion-folds` (empty with no active request horizon) and complete revisioned entries with actual request/daimoi/authority/graph/field/start/end bindings, contact cursor, accumulated horizon quanta and semantic fold work, ordered first witnesses, exact derived dedup IDs, canonical result bytes, trace-record count and the explicit accumulated finite-field-trace/1 UTF8 byte count for the whole horizon. Every entry is hashed into the checkpoint. Each contact update charges new fold work before use; a new transport call cannot reset the same horizon. The whole-call/rebuild budget additionally charges every actual decode/validate/hash/serialization operation, including restore work. Restore verifies the complete qualified checkpoint state and current authority before further inclusion; missing fields, mismatched history, reordered witnesses, forged/reset counters or a bare scratch cache refuse. Source fixtures checkpoint after a contact, restore, then repeat that memory and compare with the unsplit horizon: identical unique IDs/reasons/order/counters and no reset. Atomic storage remains a later owning packet; this defines and tests the pure checkpoint interface first.

The maximum100 substeps is an execution cap, not admission rejection for otherwise valid longer elapsed time. The finite101-quantum elapsed control must execute100, preserve one quantum as explicit backlog with incomplete status, and drain that same backlog through catch-up without inventing elapsed time. Other unsafe/resource-limit inputs retain their distinct unchanged refusals. The earlier unchanged101 refusal requirement was incorrect and is explicitly superseded; historical native receipts/comments remain immutable.


### Restored inclusion authority and complete trace accounting

A split or checkpoint restore retains the accumulated canonical trace UTF8 byte
count, including the complete finite-field-trace/1 envelope overhead and every
emitted tag, escaped scalar and separator. It cannot restart the same horizon's
8,388,608-byte counter, discard earlier bytes or count only records. Restore
validates that counter against the retained qualified trace/history under the
same existing work budget. The unsplit and split/restore fixtures at the exact
complete-envelope byte cap must agree, and one additional canonical byte must
refuse identically without accepted partial inclusion or changed prior state.
A missing, forged or reset trace-byte count refuses. These are required future
source fixtures, not executed implementation tests or a larger horizon budget.

Revocation rebuilding includes active/restored inclusion folds as well as fields,
trails and affected world projection. A retained first witness or dedup entry is
causal state: reauthorize/reconstruct it before the next inclusion or recall use,
or invalidate and refuse/quarantine it when reconstruction is unestablished.
The existing bounded whole-rebuild limits cover all fold work; no independent
counter reset, new persistence authority or unbounded replay is permitted.

## Exact ordering, inclusion result bytes, rebuild ABI and request identity

The four native Codex findings in review5533052161 refine existing finite
contracts. These remain unimplemented planning declarations and required future
RED/GREEN fixtures, with no readiness or measured behavior implied.

`finite-integer-trie-key/1` defines an eight-byte, unsigned-lexicographic key
for admitted safe integers. For a nonnegative integer, emit byte128 then its
seven-byte unsigned big-endian magnitude. For a negative integer, emit byte127
then the bytewise complement (255 minus each byte) of the seven-byte unsigned
big-endian representation of `abs(n)-1`. Derive the seven base256 digits using
bounded safe-integer operations; never form an unsafe wide bias. Thus -1 maps
to `7fffffffffffffff`, zero to `8000000000000000`, one to
`8000000000000001`, and the signed safe limits to `7fe0000000000001` and
`801fffffffffffff`. Positive and negative zero are the same integer key;
float trace values still retain their distinct binary64 bits. Each qualified
key position has a fixed component type. Tuple components use distinct
component-root tries; their non-byte terminator edge enters the next component
root, or emits the final key. Every visited node incurs exactly257 ordered
branch probes: terminator first, then bytes0 through255, including every absent
branch and the terminator. Charge followed byte/terminator edges and each
once-created distinct component-prefix/root node as well as actual encoding
operations and all eight numeric bytes before use. This fixes the prefix and
work count independently of input insertion order. Future fixtures cover the
signed golden keys, tuple boundaries, empty components where allowed, and the
terminator/absent-branch charges at exact and one-short work budgets.

`finite-contact-inclusion-result/1` defines the exact persisted result-byte
counter. Its complete UTF8 JSON envelope is
`["finite-contact-inclusion-result/1", encoded-result-map]`, using precisely
the existing finite-field-trace/1 tagged value algebra, canonical map-key
ordering and scalar escaping. The closed payload contains only
`:included-memory-ids` and `:inclusion-reasons`: unique canonical memory IDs
in first-witness order, paired one-for-one with the closed reason maps declared
in the contact fold. All ten reason keys and their actual qualified values
are included; no extra payload or reason key is accepted. Count the entire
version envelope, tags, map keys, values, separators and escapes. The count
itself stays outside the payload, avoiding self-reference. Motion, status,
bonds, contacts and fold custody retain their complete trace/state/work
accounting; they are not silently treated as these two inclusion fields.
The complete inclusion envelope is independently bounded by the existing
8,388,608-byte engineering limit, as the complete trace envelope is; neither
counter is reset on a split or restore. Restore recomputes the exact same
ordered inclusion bytes/count from qualified first witnesses. All encoding,
hashing, validation and restoration work is charged to the existing whole
call/rebuild budget. Future golden and exact/one-over controls distinguish
empty inclusion, Unicode/control escaping, map insertion order, duplicate
memory witnesses and split/restored equality. Host EDN/JSON printer choices
cannot determine the count.

The ABI now exposes `rebuild-revocation`, version finite-revocation-rebuild/2.
Its exact inputs are prior state, compatible trusted checkpoint, complete
ordered immutable contribution-event tail, current trusted authority projection,
and physical configuration. Consume qualified Axxium decisions/versions and
Clio envelopes/history; the kernel does no authorization lookup or history I/O.
Validate the existing restore artifact/configuration/cursor obligations and
reconstruct all retained fields, trails, affected world projection and active/
restored inclusion folds. Success returns the complete rebuilt state,
replacement checkpoint/cursor, new scope/authority/projection/field bindings,
complete folds and budget accounting as one operation result. A budget, binding,
authority or missing/ambiguous-history refusal returns the exact unchanged prior
state with its declared reason. Tail128events/1,048,576canonicalClio bytes,
64quanta/67,108,864work units and the existing state/input/trace/result limits
apply across the whole private rebuild. No partial replacement, retagging,
new elapsed time, new random draws, outcome or publication replay is allowed.
The outer adapter owns the2,000ms observation and quarantine/refusal before
causal use; a timeout supplies no accepted replacement or pure clock read.
`admit-state` remains its existing operation and is not an implicit history
replay interface.

Recall-request IDs now explicitly use the same nonempty well-formed scalar
string, exact unsigned UTF8 spelling,128-byte bound and namespace uniqueness
contract as the other declared IDs. Request IDs are unique across all admitted
requests in one kernel state, independently of principal and scope. Validate
before recall state, fold creation, ordering or hashing, and require every
restored/reference ID to match exactly one admitted request with its unchanged
original principal/scope binding. Reject lone surrogates,
replacement-encoding collisions and conflicting duplicate admissions. An exact
idempotent retry refers to its original admitted request and is not a second
admission. Future controls include malformed/multibyte/exact-and-over-byte IDs,
conflicting duplicates and valid retry/readback. The provisional packet estimates
and existing board dependencies are unchanged by these contract corrections.

### State-unique recall identity

Native Codex5534454109/root4284004806 identified that the earlier per-principal
request namespace allowed ambiguous same-ID folds in one state, while the
existing fold order and read API use the request ID directly. Request IDs are
therefore unique across all admitted requests in the state, across principals
and scopes. A different principal or scope cannot admit a second request with
that ID. A retry can only reference the single original request with identical
input and original ownership/scope bindings. Fold ordering and lookup retain
their existing request-ID key without a new compound-key interpretation. Future
fixtures admit the same proposed ID from two principals in one scope, and from
two scopes in one state: the conflicting second admission refuses unchanged,
while the original exact retry remains idempotent and cannot select another
principal's fold. This is a correction to the existing proposed identity
contract, with no new implementation or claimed authorization proof. Historical
native findings and the earlier receipt remain unchanged.
