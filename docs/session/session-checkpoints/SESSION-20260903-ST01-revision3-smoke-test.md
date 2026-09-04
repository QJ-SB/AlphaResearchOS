# Revision 3 Smoke-Test Checkpoint

* **Session ID:** `SESSION-20260903-ST01`
* **Date:** 2026-09-03 to 2026-09-04
* **Project Mode:** `RESEARCH`
* **Learning Mode:** `GUIDED`
* **Language Mode:** `ENGLISH-FIRST`
* **Progressive Ownership Stage:** `1`
* **Revision 2.1 Smoke-Test Baseline Commit:** `f0b0911f45667db4a8ec7910aca17d36c50404f3`
* **Project State Revision Used During Test:** `2.1`
* **Closure Result:** `PASS`
* **Human Review Surface:** `APPROVED`
* **Canonical Writes During the Dry Run:** `None`

## Objective

Behaviorally test the accepted Revision 2.1 AlphaResearchOS collaboration control plane before substantive project work.

The suite covered:

* Mainline Session Bootstrap;
* independent Project, Learning, and Language axes;
* Progressive Ownership Stage 1;
* selective context loading;
* Guided Decision Gate behavior;
* human-request-gated Sidecar Capsule compilation;
* human-controlled Sidecar launch and termination;
* English Teacher `PROMPT MODE`;
* typed Sidecar Returns;
* semantic staleness and reissue;
* cancellation and complete issued-Capsule accounting;
* English Teacher `COMPREHENSION MODE`;
* human-controlled comprehension rescue;
* one-Capsule within-mission iteration;
* closure review;
* selective canonical promotion.

The smoke suite did not implement AlphaResearchOS software and did not conduct empirical Alpha research.

## Acceptance Result

Revision 3 behavioral smoke testing completed successfully.

| Test  | Result | Evidence Summary                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| ----- | ------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ST-01 | `PASS` | Mainline declared `RESEARCH / GUIDED / ENGLISH-FIRST` and Stage 1 independently; separated system and human-learning objectives; selectively loaded context; separated facts, assumptions, and open questions; applied the Guided Decision Gate; made no implementation, experiment, empirical-research, or canonical-write claim.                                                                                                                                |
| ST-02 | `PASS` | Human request preceded Capsule compilation. `CAP-20260903-01` was manually dispatched to a read-only English Teacher in `PROMPT MODE`. `RET-20260904-01` was fresh and accepted for the bounded meaning-preserving language transformation only.                                                                                                                                                                                                                  |
| ST-03 | `PASS` | `CAP-20260904-01` was dispatched under the original acceptance criterion. The human then materially changed that criterion before Return evaluation. `RET-20260904-02` was therefore acceptance-incompatible with the current task and received `REISSUE / NO MERGE`. The original Capsule and Return remained immutable. Replacement `CAP-20260904-02` was issued but human-cancelled before dispatch and recorded `NO RETURN / NO MERGE`.                       |
| ST-04 | `PASS` | `CAP-20260904-03` executed `COMPREHENSION MODE` through Level 1 → explicit human escalation → Level 2 → explicit human escalation → Level 3 under one unchanged Capsule. Benchmark, risk adjustment, incrementality, OOS validation, costs, and capacity were preserved. Level 3 requested an English learner restatement. Effective disposition of `RET-20260904-03` is `PARTIAL ACCEPT` because of two minor provenance/presentation deviations recorded below. |
| ST-05 | `PASS` | Closure accounted for every issued Capsule, surfaced consequential evidence and deviations for human review, produced one compressed checkpoint, proposed selective promotion only, and performed no unauthorized canonical write. The Human Review Surface, checkpoint, Selective Promotion Matrix, and proposed Revision 3 decision were subsequently approved by the human.                                                                                    |

## Sidecar Lifecycle and Merge Accounting

| Capsule ID        | Lifecycle Outcome           | Return ID         | Freshness / Compatibility                                                    | Effective Return Disposition | Accepted Scope                                                                                                                                                                                                                                                                                                                                                                                                     | Excluded / Rejected Scope                                                   |
| ----------------- | --------------------------- | ----------------- | ---------------------------------------------------------------------------- | ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------- |
| `CAP-20260903-01` | `RETURN RECEIVED`           | `RET-20260904-01` | `FRESH`                                                                      | `ACCEPT`                     | Bounded ST-02 English `PROMPT MODE` language transformation and its provenance-bearing Return                                                                                                                                                                                                                                                                                                                      | None material                                                               |
| `CAP-20260904-01` | `RETURN RECEIVED`           | `RET-20260904-02` | `STALE / acceptance-incompatible with materially changed Mainline criterion` | `REISSUE / NO MERGE`         | None for the revised ST-03 task                                                                                                                                                                                                                                                                                                                                                                                    | Entire old work product for the materially changed acceptance criterion     |
| `CAP-20260904-02` | `CANCELLED BEFORE DISPATCH` | `None`            | `N/A`                                                                        | `NO MERGE`                   | None                                                                                                                                                                                                                                                                                                                                                                                                               | Entire cancelled task; no Return exists                                     |
| `CAP-20260904-03` | `RETURN RECEIVED`           | `RET-20260904-03` | `FRESH`                                                                      | `PARTIAL ACCEPT`             | Capsule provenance header; Level 1 → explicit human escalation → Level 2 → explicit human escalation → Level 3 sequence; one unchanged Capsule; preservation of benchmark, risk adjustment, incrementality, OOS validation, costs, and capacity; Level 3 English restatement request; workflow-completion versus learner-mastery distinction; absence of research, experiment, canonical-write, and mastery claims | Unsupported external-source attribution and blank evidence-reference claims |

Every issued Capsule is accounted for.

No stale Return was merged.

No Capsule without a typed Return contributed work to Mainline.

`CAP-20260904-02` has `NO RETURN` and therefore `NO MERGE`.

## ST-03 Staleness Evidence

The original acceptance criterion in `CAP-20260904-01` required the polished prompt to recommend one option and explain why.

Before `RET-20260904-02` was evaluated, the human materially changed the acceptance criterion: the prompt must compare the alternatives but must not recommend, select, endorse, or prefer one.

Because the already-dispatched Capsule was immutable and the new criterion directly contradicted its original acceptance criterion:

* `RET-20260904-02` was not accepted as fresh work for the revised task;
* its self-declared `FRESH` status did not override Mainline semantic freshness adjudication;
* disposition was `REISSUE / NO MERGE`;
* `CAP-20260904-01` and `RET-20260904-02` were preserved unchanged as historical provenance;
* replacement `CAP-20260904-02` was generated under the new criterion;
* the human then cancelled `CAP-20260904-02` before dispatch;
* no Return was generated from the cancelled Capsule;
* nothing from the cancelled Capsule was merged.

## ST-04 Effective Adjudication

The original Mainline adjudication of `RET-20260904-03` as unqualified `ACCEPT` is preserved as historical provenance.

Before closure, the human corrected the effective disposition to:

`PARTIAL ACCEPT`

### Accepted ST-04 Scope

The following are accepted:

* the `CAP-20260904-03` provenance header;
* the Level 1 → explicit human escalation → Level 2 → explicit human escalation → Level 3 sequence;
* use of one unchanged Capsule across the rescue ladder;
* preservation of benchmark;
* preservation of risk adjustment;
* preservation of incrementality;
* preservation of out-of-sample validation;
* preservation of implementation and trading costs;
* preservation of capacity;
* the Level 3 English learner-restatement request;
* the distinction between workflow completion and learner mastery;
* the absence of research conclusions;
* the absence of experiment claims;
* the absence of canonical-write claims;
* the absence of learner-mastery claims.

### ST-04 Minor Deviations

#### 1. Unsupported External-Source Attribution

An interim Level 3 response attributed statements directly to the Foundation / AlphaResearchOS authority even though `CAP-20260904-03` permitted the Sidecar to use only:

* the embedded target concept; and
* the semantic boundaries contained inside the Capsule.

The semantic content may be correct, but the direct external-source attribution exceeded the authorized evidence boundary.

Classification:

`MINOR PROVENANCE DEVIATION`

The attribution is excluded from accepted merge scope and must not be reused or promoted as evidence that the Foundation itself was consulted or directly supported the Sidecar wording.

#### 2. Blank Evidence References

The final `RET-20260904-03` contained `Evidence and File References` entries whose text after the colons was unpopulated.

Classification:

`MINOR PRESENTATION / PROVENANCE DEVIATION`

Those blank entries are not valid evidence references and must not be treated as evidence.

### ST-04 Consequence

The two deviations do not invalidate the independently visible rescue sequence or preservation of the six required semantic boundaries.

No reissue or rerun is required.

ST-04 remains:

`PASS`

with effective Return disposition:

`PARTIAL ACCEPT`

## Human Learning Boundary

The ST-04 workflow reached Rescue Level 3 and issued an English learner-restatement request.

However:

* no learner English restatement was completed;
* no learner response was evaluated;
* no reconstruction, transfer, prediction, debugging, or other independent capability demonstration was completed.

Therefore:

`Workflow completion != demonstrated learner mastery`

No learner mastery is established by this smoke suite.

No Learning State promotion is supported.

## Research and Implementation Boundaries

The Revision 3 smoke suite validates behavior of the collaboration control plane only.

It does not establish:

* an AlphaResearchOS research result;
* empirical Alpha evidence;
* a reproducible experiment;
* a registered experiment;
* an implemented AlphaResearchOS component;
* source-code progress;
* runtime correctness;
* a validated Research Kernel;
* learner mastery.

The following remain unchanged by this smoke suite:

* Research State;
* Experiment Registry;
* Current System Architecture;
* Learning State;
* ADRs;
* Foundation v0.3;
* Learning Maps.

## Human Review and Promotion Disposition

The human explicitly approved:

* ST-01 as `PASS`;
* ST-02 as `PASS`;
* ST-03 as `PASS`;
* ST-04 as `PASS` with effective `PARTIAL ACCEPT`;
* ST-05 as `PASS`;
* the Human Review Surface;
* this compressed checkpoint for saving;
* the Selective Promotion Matrix;
* the proposed Revision 3 decision.

The human explicitly authorized exactly two canonical documentation writes:

1. create this checkpoint;
2. update `docs/context/project/project-state.md` from Revision 2.1 to Revision 3.

No other canonical target is authorized.

## Selective Promotion Result

| Canonical Target                                                                 | Promotion    |
| -------------------------------------------------------------------------------- | ------------ |
| `docs/session/session-checkpoints/SESSION-20260903-ST01-revision3-smoke-test.md` | `AUTHORIZED` |
| `docs/context/project/project-state.md`                                          | `AUTHORIZED` |
| Research State                                                                   | `NO CHANGE`  |
| Experiment Registry                                                              | `NO CHANGE`  |
| Current System Architecture                                                      | `NO CHANGE`  |
| Learning State                                                                   | `NO CHANGE`  |
| ADRs                                                                             | `NO CHANGE`  |
| Foundation v0.3                                                                  | `NO CHANGE`  |
| Learning Maps                                                                    | `NO CHANGE`  |
| Collaboration protocol / Bootstrap files                                         | `NO CHANGE`  |

## Revision 3 Decision

Revision 3 behavioral smoke testing:

`PASS`

The two recorded ST-04 deviations are minor and non-blocking.

The smoke suite behaviorally validates the Revision 2.1 collaboration control plane across Mainline bootstrap, Sidecar lifecycle control, semantic staleness, comprehension rescue, closure, and selective promotion.

Revision 3 becomes canonically effective only after both authorized files are installed in the repository and committed to Git.

Until repository installation and commit are independently evidenced, this checkpoint content and the corresponding Revision 3 Project State content must not by themselves be represented as already installed, committed, or canonically effective.

## Next Substantive Entry Point

After Revision 3 becomes canonically effective, begin one bounded substantive Mainline session that:

1. inspects the actual repository code;
2. inspects the actual tests;
3. inspects relevant research and data surfaces;
4. establishes what is actually implemented rather than inferring from target architecture;
5. identifies the smallest evidence-backed Research Kernel vertical slice;
6. specifies that slice before implementation.

No implementation is authorized merely by this checkpoint.

## Canonical-Write Boundary

This checkpoint records approved session provenance and outcome.

It does not create empirical research evidence, implementation evidence, experiment evidence, or learner-mastery evidence.

Any subsequent substantive project activity requires its own appropriate session scope and authorization.
