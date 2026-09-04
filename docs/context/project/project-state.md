# Project State

* **Last Updated:** 2026-09-04
* **State Revision:** 3
* **Based on Commit:** `f0b0911f45667db4a8ec7910aca17d36c50404f3`
* **Revision 2.1 Smoke-Test Baseline Commit:** `f0b0911f45667db4a8ec7910aca17d36c50404f3`
* **Protocol Integration Commit:** `83103010e1800ebe1d614607a46027677c84bf7b`
* **Validated Revision 2 Archive SHA-256:** `17b43c8b2f74ffb700038d85e39c37cef44f29b41f4fd701a350047ca40eb79a`
* **Validated Revision 2.1 Overlay SHA-256:** `38b7d62accd1652b19d5bed1251b803cb9393bd9579dd1311512d75afb9b989d`
* **Validated Human-Control Patch SHA-256:** `d99505691a2c6ade1abee82dc3048789b5355c9befca9de383b0830e515a5175`
* **Revision 3 Smoke-Test Checkpoint:** `../../session/session-checkpoints/SESSION-20260903-ST01-revision3-smoke-test.md`
* **Current Scope:** Revision 3 behaviorally validated collaboration control plane; substantive AlphaResearchOS code/research baseline inspection is the next project entry point

## Established Truth

* Foundation v0.3 Final Freeze remains the current frozen Foundation baseline.
* ADR-000 and ADR-001 remain Accepted and unchanged.
* Revision 2 established the independently validated documentation architecture, three-axis session model, selective context loading, rolling-state boundaries, Mainline/Sidecar contracts, semantic staleness checks, archive review, and selective canonical promotion.
* Revision 2.1 preserved that architecture and explicitly established human objective ownership, human-controlled Sidecar launch and termination, request-gated Capsule compilation, manual Capsule dispatch as launch authorization, bound work-object delivery, one-Capsule within-mission iteration, typed Return re-entry, complete issued-Capsule closure accounting, `NO RETURN -> NO MERGE`, and separately authorized canonical writes.
* Revision 3 behavioral smoke testing was executed against Revision 2.1 smoke-test baseline commit `f0b0911f45667db4a8ec7910aca17d36c50404f3`.
* The Revision 3 smoke-test checkpoint is `../../session/session-checkpoints/SESSION-20260903-ST01-revision3-smoke-test.md`.
* ST-01 passed: Mainline correctly initialized `RESEARCH / GUIDED / ENGLISH-FIRST` with Progressive Ownership Stage 1, used selective context, separated facts, assumptions, and open questions, and applied the Guided Decision Gate without inventing implementation, experiment, or research claims.
* ST-02 passed: human request preceded Context Capsule compilation; a read-only English Teacher operated in `PROMPT MODE`; the typed Return was fresh and accepted only for its bounded meaning-preserving language transformation.
* ST-03 passed: a material acceptance-criterion change was recorded before evaluation of the already-dispatched Return; the old Return was correctly treated as acceptance-incompatible and received `REISSUE / NO MERGE`; no stale work was merged; the replacement Capsule was subsequently human-cancelled before dispatch and recorded `NO RETURN / NO MERGE`.
* ST-04 passed with effective Return disposition `PARTIAL ACCEPT`: the Level 1 → explicit human escalation → Level 2 → explicit human escalation → Level 3 rescue sequence occurred under one unchanged Capsule; benchmark, risk adjustment, incrementality, out-of-sample validation, implementation/trading costs, and capacity remained preserved; Level 3 requested an English learner restatement; workflow completion was kept distinct from learner mastery.
* ST-04 retains two minor non-blocking deviations:

  1. an interim response attributed statements directly to Foundation / AlphaResearchOS authority outside the Sidecar Capsule's authorized evidence surface;
  2. the final Return contained blank `Evidence and File References` entries.
* Those ST-04 fragments are excluded from accepted evidence and must not be reused or promoted as Foundation-backed evidence.
* The original unqualified `ACCEPT` adjudication of `RET-20260904-03` remains historical provenance; the effective disposition for Revision 3 closure and promotion is `PARTIAL ACCEPT`.
* ST-05 passed: every issued Capsule was accounted for, stale and unreturned work was not merged, consequential evidence and deviations were surfaced for human review, one compressed checkpoint was produced, and promotion remained selective.
* The human approved ST-01 through ST-05 as `PASS`, approved the Human Review Surface, approved the compressed checkpoint, approved the Selective Promotion Matrix, and approved the proposed Revision 3 decision.
* Revision 3 smoke testing validates the collaboration control plane only.
* No AlphaResearchOS empirical research conclusion, Alpha evidence, reproducible experiment, implementation progress, runtime evidence, or learner mastery was established by the smoke suite.
* No learner English restatement was completed or evaluated in ST-04; therefore no learner-mastery evidence was established.
* Research State remains unchanged.
* Experiment Registry remains unchanged.
* Current System Architecture remains unchanged.
* Learning State remains unchanged.
* ADRs remain unchanged.
* Foundation v0.3 remains unchanged.
* Learning Maps remain unchanged.
* Collaboration protocol and Bootstrap files remain unchanged.
* Revision 3 becomes canonically effective only after this Revision 3 Project State and the approved smoke-test checkpoint are installed in the repository and committed to Git.

## Smoke-Test Capsule Accounting

| Capsule ID        | Lifecycle Outcome           | Return ID         | Effective Disposition | Merge Result                                                                                           |
| ----------------- | --------------------------- | ----------------- | --------------------- | ------------------------------------------------------------------------------------------------------ |
| `CAP-20260903-01` | `RETURN RECEIVED`           | `RET-20260904-01` | `ACCEPT`              | Bounded ST-02 PROMPT MODE result accepted                                                              |
| `CAP-20260904-01` | `RETURN RECEIVED`           | `RET-20260904-02` | `REISSUE`             | `NO MERGE` after material acceptance-criterion change                                                  |
| `CAP-20260904-02` | `CANCELLED BEFORE DISPATCH` | `None`            | `NO MERGE`            | No Return and no accepted scope                                                                        |
| `CAP-20260904-03` | `RETURN RECEIVED`           | `RET-20260904-03` | `PARTIAL ACCEPT`      | Only explicitly accepted ST-04 workflow and semantic-preservation scope merged into the closure record |

All issued Capsules are accounted for.

No stale Return was merged.

No unreturned Capsule contributed work to Mainline.

## Active Work

Begin the first substantive AlphaResearchOS entry-point assessment after Revision 3 canonical installation and commit are evidenced.

The next bounded task is to inspect:

* actual repository source code;
* actual tests;
* relevant research surfaces;
* relevant data surfaces;
* existing executable or reproducible behavior, if any.

Use that evidence to identify the smallest viable Research Kernel vertical slice before implementation.

Do not assume that Foundation target architecture or earlier educational project descriptions establish current implementation.

## Open Questions and Risks

* The actual AlphaResearchOS source-code and test baseline has not yet been inspected under the Revision 3 substantive workflow.
* The existence, completeness, and correctness of any Research Kernel implementation remain unestablished until code, tests, and runtime/reproducibility evidence are inspected.
* The first substantive research question, information set, benchmark, risk model, falsifier, local evidence, OOS design, costs, and capacity treatment remain `TBD`.
* No empirical Alpha claim is currently established.
* No experiment is currently established by Revision 3 smoke testing.
* ST-04's unsupported external-source attribution must not be reused as Foundation-backed evidence.
* ST-04's blank evidence-reference fields must not be treated as valid evidence.
* Successful collaboration workflow execution must not be mistaken for demonstrated learner capability.
* External Coding Agent / Executor work remains deferred until a real bounded `BUILD` slice has been identified and separately authorized.
* Target architecture must continue to be distinguished from implemented truth.

## Next Recommended Step

After repository installation and Git commit make Revision 3 canonically effective, open one bounded substantive Mainline session to:

1. inspect the actual repository code and tests;
2. inspect relevant research and data surfaces;
3. establish the evidence-backed current implementation baseline;
4. identify the smallest viable Research Kernel vertical slice;
5. specify its objective, inputs, outputs, time semantics, invariants, tests, and acceptance criteria;
6. stop before implementation unless a subsequent bounded `BUILD` action is explicitly authorized.

## Relevant Artifacts

* `../../foundation/AlphaResearchOS_Foundation_v0.3_Final_Freeze.md`
* `../../architecture/archive-decision-record/adr-000.md`
* `../../architecture/archive-decision-record/adr-001.md`
* `../../ai-collaboration-and-learning-protocol-v1.md`
* `../../session/session-bootstrap.md`
* `../../session/sidecar-bootstrap.md`
* `../../session/session-archive-self-check.md`
* `../../session/session-checkpoints/SESSION-20260903-ST01-revision3-smoke-test.md`
* `AlphaResearchOS_Revision3_Smoke_Test_Plan_Revision_2_1.md` (external smoke-test control artifact)

## Canonical Promotion Boundary

Revision 3 records successful behavioral validation of the collaboration control plane.

It does not promote:

* research conclusions;
* experiment events;
* implementation claims;
* architecture implementation claims;
* learner-mastery claims.

Any future promotion in those categories requires evidence under the appropriate authority and a separately authorized canonical update.
