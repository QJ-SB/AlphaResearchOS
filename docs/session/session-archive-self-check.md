# Session Archive and Promotion Self-Check

Extend the existing session workflow with this single closure and promotion review. Do not create a parallel archival process.

Invoke this protocol through a human closure request, or when Mainline proposes it at a meaningful stopping point and the human accepts. It is not a background watcher and is not automatically executed by closing a browser or chat window. Generating a closure packet does not itself authorize canonical writes.

```text
Raw session work
  -> Sidecar merge/freshness check
  -> Human review surface
  -> Session checkpoint
  -> Scope and authority assessment
  -> Selective canonical promotion
```

## 1. Session Identity and Provenance

- Session ID:
- Date:
- Project / Learning / Language Modes:
- Ownership Stage:
- Base Commit:
- State revisions used:
- Issued Capsule IDs and associated Return IDs:

## 2. Sidecar Lifecycle, Merge, and Freshness Review

Account for every issued Capsule, whether or not a Return was received:

| Capsule ID | Lifecycle outcome | Return ID | Freshness evidence | Return disposition | Accepted scope | Independent verification | Human disposition |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | `RETURN RECEIVED / NO RETURN / CANCELLED / ABANDONED-INCOMPLETE / REISSUED` | [ID or `None`] | [evidence or `N/A`] | `ACCEPT / PARTIAL ACCEPT / REJECT / REISSUE / NO MERGE` | [scope or `None`] | [check or `N/A`] | `APPROVE / REJECT / DEFER / NEEDS EVIDENCE` |

`NO RETURN -> NO MERGE`. A cancelled or abandoned/incomplete Capsule contributes nothing to Mainline. For a reissued Capsule, record the replacement Capsule ID and do not merge the superseded work without a valid typed Return and fresh adjudication.

- Did any relevant state, ADR, architecture boundary, artifact, assumption, scope, or acceptance criterion change? `YES / NO`
- If yes, was the return revalidated or reissued before merge? [evidence]
- Did any Sidecar exceed its read/write boundary? `YES / NO`; if yes, stop and record the violation.

## 3. Human Review Surface

Present concise, evidence-linked items in this order:

1. decisions or changes of direction;
2. evidence, negative results, and falsification status;
3. uncertainties and unresolved questions;
4. risks, boundary violations, or governance conflicts;
5. changed invariants or interfaces;
6. important diffs;
7. learning claims that require demonstration;
8. next irreversible or costly action.

Record human disposition for each consequential item: `APPROVE / REJECT / DEFER / NEEDS EVIDENCE`.

## 4. Session Checkpoint

Create one compressed checkpoint under `session/session-checkpoints/` containing:

- session provenance and declared modes;
- objective, outcome, and acceptance result;
- decisions and their authority status;
- evidence and verification references;
- Sidecar dispositions;
- unresolved risks/questions;
- meaningful negative results or failed approaches;
- proposed promotions and next entry point.

A checkpoint is a provenance node, not canonical truth by itself. Do not copy raw dialogue or repeated explanations.

## 5. Scope and Authority Assessment

For each proposed promotion, identify the question, highest authority, supporting evidence, conflict check, and recorded human disposition. Newer content does not automatically override a Foundation, accepted ADR, code/test evidence, or current state.

## 6. Selective Promotion Matrix

| Information type | Canonical target | Update? | Evidence / reason |
| --- | --- | --- | --- |
| Important durable decision | New ADR | `YES / NO` | |
| Current implemented architecture | `architecture/system-architecture/current-system-architecture.md` | `YES / NO` | |
| Milestone, blocker, or next step | `context/project/project-state.md` | `YES / NO` | |
| Active hypothesis or research conclusion | `context/research/research-state.md` | `YES / NO` | |
| Reproducible experiment event | `research-log/experiment-registry.md` | `YES / NO` | |
| Demonstrated capability or misconception | `context/learning/learning-state.md` | `YES / NO` | |
| Stable domain relationship | Appropriate Learning Map, after deliberate protected-surface review | `YES / NO` | |
| Session provenance and outcome | Session Checkpoint | `YES / NO` | |

Not every session changes every state file. Do not promote unsupported confidence, raw discussion, stale returns, or unverified narratives. Preserve important failures and negative evidence in the correct durable record.

Before any canonical file update, record both the human disposition and explicit write authorization for the exact target and supported change. Keep these outputs distinct:

1. closure report;
2. checkpoint draft or saved checkpoint;
3. promotion proposal;
4. actual canonical update.

Producing items 1–3 does not authorize item 4.

## 7. Closure

- Canonical files actually updated:
- Files deliberately not updated:
- Unresolved items:
- Next session entry point:
- Next irreversible/costly action and required authorization:
- Human disposition recorded for each proposed promotion: `YES / NO`
- Explicit canonical write authorization: [authorized targets and scope, or `NONE`]
- Closure status: `COMPLETE / PARTIAL / BLOCKED`
