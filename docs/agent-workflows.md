# Agent workflows and observed setup

License: GPL-3.0-or-later (new process documentation).

Read `~/.agents/skills/pr-flow/SKILL.md` for every PR phase. The current canonical
pack owns review, availability, findings, convergence and merge policy. Native
evidence and actual repository routes control each qualification; historical
workflow descriptions or a model's summary cannot substitute for them.

## Source work

Development head and base are `riatzukiza/eros-eris-field`. Organizational
publication requires separate release qualification. Plans link Foresight's
existing workspace cards and explicit UUIDs, rather than maintaining another
board. Rheos alone supplies board state, dependency admission and readiness.

The [owning physical-kernel plan](plans/2026-10-07-cephalon-physical-kernel.md)
records the current source map, proposed ABI, numeric/collision decisions and
remaining build/licensing/calibration/integration gates. Planning review does
not supply an implementation test or deployment guarantee.

## Review routes

| Surface | Actual scope and limitation |
| --- | --- |
| Native CodeRabbit and Codex mentions | Request on a ready PR through canonical `pr.cljs`. Verify actual response identity, completed input, exact head, findings and native quota/pending state. An invitation is not evidence that an App is installed or has finished. |
| `.github/workflows/eta-mu-review.yml` | Proposed pinned canonical evidence-first MiMo caller. It grants read scopes, supplies exact PR head and forwards only the two App publisher secrets. Its diff/EDN gates check planning input; they do not compile or verify physical behavior. |
| `.github/workflows/opencode-code-review.yml.disabled` | Historical Kimi caller is disabled. Do not describe it as an installed available reviewer, guessed identity, quota exception or current approval. |
| `.github/workflows/review-resolution-gate.yml` | Retained strict shared conversation check. It does not replace the canonical full merge gate. Its actual same-head run and result remain required evidence. |

On 2026-10-07, the initial authenticated repository secret list was empty and its native
workflow inventory was empty. The user-token installation inventory request
returned HTTP 403; that observation does not establish App installation scope.
The reusable MiMo workflow explicitly refuses missing `ETA_MU_APP_ID` /
`ETA_MU_APP_PRIVATE_KEY`. Its actual publisher requires the existing App to have
access to this repository. A configured YAML file without those credentials and
native execution is a missing route. Preserve an actual failure and complete
the setup before qualification; do not invent reviewer identity or a quota exit.
Never print private keys, tokens or webhook URLs.

Later native App-authenticated reads verified existing `eta-mu-ai` App `3152464`,
personal installation `118318185`, `repository_selection: all`, and actual
coverage of this new fork. Its two existing publisher values were encrypted into
this repository at `2026-10-07T18:35:42Z`; metadata readback verifies their names
and update times, not decrypted contents. No App or installation was created.
The [setup observation](../.ημ/plan-evidence/reviewer-route-preparation-20261007.json)
is not a completed review or publication proof.

The first native run `37667654730` failed before model execution at bounded
context installation: Git's default quoted Unicode filenames inside the trusted
`.review-context` failed the pinned reusable workflow's prefix filter. It did not
reach credential validation or produce a review. The root `.gitignore` excludes
only the two declared generated context/evidence directories. A real isolated
Git fixture must verify that Unicode files there are ignored while an unrelated
untracked source file and a tracked source modification still fail cleanliness.
The strict guard itself is retained. A later successful exact-head hosted run
must verify the repaired route.

The caller pins the shared workflow, Muse compiler, canonical agent-pack revision
and OpenCode runner. Full hosted artifacts and native review publication need
their own exact-head verification. Keep paid/on-demand credits disabled.

## Merge and operational automation

`.github/workflows/auto-merge.yml.disabled` preserves the historical eager
`SQUASH` caller as inactive evidence. It cannot be the merge authority. New PRs
stay ready with native auto-merge off; eventual authorized merge uses the
canonical current-head gate and its merge-commit guard.

GitHub visibility workflows remain inherited. Their external Discord writes
depend on the existing private webhook configuration. This plan neither
configures a webhook nor proves message delivery.

The inherited Kanban sync workflow targets `kanban/` and schedules issue writes.
There is no source board authored here, and issues were observed disabled on
the new fork. Do not run this workflow to manufacture cards or enable repository
settings as a shortcut. Workspace board work uses native Rheos in Foresight.

Running creative work is independent from review setup. Keep one event/gateway
owner and the existing native creative clock. Do not restart active makers,
replay social publication, change unrelated PM2 services or enable cloud event
runtime to maintain this source plan.

## Evidence

Record owned work append-only under `.ημ/receipts.edn` and retain explicit source,
configuration, artifact and native record hashes. Preserve observed, derived,
provisional and accepted claims separately. Reflections go in
`.ημ/session-mycology/ledger.md`; a reflection is not a review or a policy waiver.
