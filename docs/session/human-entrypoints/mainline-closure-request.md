# Mainline Closure Request

> **Artifact class:** Human entry-point template (non-canonical operator aid)  
> **Governing contracts:** `docs/project-instruction.md`, `docs/ai-collaboration-and-learning-protocol-v1.md`, and `docs/session/session-archive-self-check.md`  
> **Conflict rule:** The governing contracts and current canonical state override this template.

Fill the bracketed fields and send this request to the current Mainline. This explicit request invokes closure; closing a browser or chat window does not. Closure review is not canonical-write authorization.

## Authoritative routing

Read and apply:

1. `docs/project-instruction.md`
2. `docs/ai-collaboration-and-learning-protocol-v1.md`
3. the instantiated Mainline Session Bootstrap and current working record;
4. `docs/session/session-archive-self-check.md`;
5. the ledger of every issued Capsule and received typed Return;
6. only the canonical authority/state files needed to assess proposed promotions.

## Human input

- **Reason for closing:** [OBJECTIVE COMPLETE / MEANINGFUL CHECKPOINT / BLOCKED / CONTEXT HANDOFF / OTHER]
- **Expected closure status:** [COMPLETE / PARTIAL / BLOCKED / LET MAINLINE ASSESS]
- **Known outstanding, cancelled, abandoned, or reissued Capsules:** [CAPSULE IDS / NONE / UNKNOWN]
- **Consequential items requiring human review:** [FILL IN OR LET MAINLINE IDENTIFY]
- **Closure packet mode:** [PROPOSE ONLY / INCLUDE AN AUTHORIZED CHECKPOINT SAVE]
- **Existing human dispositions, if any:** [FILL IN OR NONE]
- **Explicit canonical write authorization:** [NONE / EXACT TARGETS AND SUPPORTED CHANGES]

## Required Mainline behavior

Run `docs/session/session-archive-self-check.md` and produce:

1. session identity, modes, provenance, objective, outcome, acceptance result, and a decision supported by the actual test/work outcomes and unresolved defects;
2. one ledger row for every issued Capsule, accounting for it as returned and adjudicated, cancelled, abandoned/incomplete, or reissued; record every missing typed Return as `NO RETURN` with `NO MERGE`, and link superseded/replacement Capsule IDs;
3. where an earlier Return decision was later invalidated by a material change, preserve the chronology but state the effective current merge disposition—never silently rewrite provenance;
4. a concise Human Review Surface that exposes consequential evidence, negative results, failures, uncertainty, boundary violations, important diffs, unsupported learning claims, and the next irreversible or costly action, with a disposition slot for each consequential item;
5. one compressed Session Checkpoint draft for the whole session, using evidence pointers rather than raw dialogue archival;
6. a question-dependent authority/conflict assessment and a Selective Promotion Matrix naming each exact proposed target, supporting evidence, required human disposition, and whether an update is warranted;
7. files deliberately unchanged, unresolved items, the next-session entry point, and closure status.

Apply these promotion safeguards:

- Do not infer research evidence, implementation progress, or learner mastery merely because a workflow ran.
- Do not update every state automatically; unsupported or stale information is not promotable.
- Keep the closure report, checkpoint draft or saved checkpoint, promotion proposal, and actual canonical update distinct.
- Record human disposition and exact write authorization before any canonical write.

If the requested mode is `PROPOSE ONLY`, stop after presenting the closure packet. Do not save the checkpoint, write canonical files, create an ADR, update a rolling state, or claim a proposed revision as canonically confirmed.

