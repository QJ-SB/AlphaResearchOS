# Sidecar Bootstrap

This is the single reusable contract for bounded specialist work. The human authorizes launch and decides when the Sidecar mission is finished. After a human request or approval, Mainline compiles, versions, and issues the official Context Capsule and later adjudicates the typed Return. The Sidecar performs only the bounded mission. It does not inherit authority from a long conversation and cannot promote its own result.

## 1. Role Selection

| Role | Use when | Default boundary |
| --- | --- | --- |
| English Teacher | Prompt polishing or comprehension rescue | Read-only; preserve meaning |
| Concept Tutor | A concept needs explanation, questioning, or transfer practice | Read-only; no project decisions |
| Code Tutor | Code understanding, debugging guidance, or learning scaffold is needed | Read-only unless separately authorized |
| Reviewer | A proposed artifact, claim, or change needs adversarial review | Read-only; report findings |
| Examiner | Unaided capability must be tested | Read-only; no hints before attempt closes |
| External Coding Agent / Executor | A bounded implementation can be delegated | Writes only to the authorized copy, branch, or exact paths |

Use the smallest sufficient Sidecar. Do not send all project context by default.

## 2. Context Capsule Template

```markdown
# Context Capsule

- Capsule ID: CAP-YYYYMMDD-NN
- Created At: YYYY-MM-DDThh:mm:ssZ
- Mainline Session ID: SESSION-...
- Mainline Checkpoint ID: [ID or None]
- Base Commit or Input Archive SHA-256: [value or Not available]
- Project State Revision: [value or Not loaded]
- Research State Revision: [value or Not loaded]
- Learning State Revision: [value or Not loaded]
- Relevant ADR / Architecture Revisions: [values or None]
- Human Request / Approval: [request or approval evidence]
- Human Dispatch Mechanism: [manual paste/send or other explicit authorization]
- Sidecar Role: [role]
- Role Mode: [role-specific mode or N/A]
- Work Object Identity and Version: [exact name/path/range/attachment and version]
- Work Object Delivery Method: EMBEDDED | ACCESSIBLE PATH | ATTACHMENT FOLLOWS

## Objective and Precise Question
[one bounded objective and question]

## Necessary Facts and Definitions
- [fact with source]

## Protected Invariants
- [invariant]

## Allowed Files or Excerpts
- [exact path/range]

## Out of Scope / Forbidden
- [item]

## Required Return Type
[typed return plus role appendix]

## Acceptance Criteria
- [criterion]
```

The capsule is immutable after dispatch. Manual pasting or sending of the reviewed Capsule into the Sidecar is the human launch action. The Capsule itself may be the Sidecar opening prompt.

For `EMBEDDED`, include the exact work object in the Capsule. For `ACCESSIBLE PATH`, provide an exact accessible path or range and version. For `ATTACHMENT FOLLOWS`, name and version the exact object that will immediately follow; the Sidecar must wait for it and verify identity and version before starting. Any absence or mismatch is a blocker, not permission to infer or substitute.

One Capsule covers questions and iterations within its original role, mission, bound work object, scope, evidence, and acceptance criteria. A material change to any of those semantic dependencies requires a new Capsule ID; ordinary within-mission questions do not.

## 3. Common Typed Sidecar Return

```markdown
# Sidecar Return

- Return ID: RET-YYYYMMDD-NN
- Sidecar Role: [role]
- Source Capsule ID: CAP-...
- Base Commit / Archive Hash Used: [value]
- State and Architecture Revisions Used: [values]
- Freshness Declaration: FRESH | POSSIBLY STALE | STALE

## Direct Result
[bounded result, including `None`, blocked, negative, or no-change when applicable]

## Assumptions and Preserved Semantic Boundaries
- [item]

## Evidence and File References
- [reference]

## Uncertainties and Unresolved Questions
- [item or None]

## Proposed Mainline Action or Merge Target
[accept/review/apply target]

## Verification Performed
- [check]

## Deviations from Capsule
- [deviation or None]

## Canonical-State Impact
[None | Possible; specify affected authority]
```

Role-specific fields extend this schema; they never replace its provenance fields.

The human may request the final Return. The Sidecar may recommend closure when the acceptance criteria are met, but it must not invent a new mission. Every result brought back to Mainline uses this common typed Return. No Return means no merge; Mainline records the issued Capsule as cancelled, abandoned/incomplete, or reissued at closure.

## 4. Role-Specific Required Fields

### English Teacher

Declare `PROMPT MODE` or `COMPREHENSION MODE`.

`PROMPT MODE` must add: polished prompt; meaning-preservation statement; semantic change log; unresolved ambiguities/assumptions; concise Chinese back-check when material. It must not add hidden requirements or turn tentative language into a decision.

`COMPREHENSION MODE` must add: rescue level used; restored explanation; learner restatement request. Use the minimum rescue level: (1) simpler English; (2) English with concise Chinese anchors; (3) full Chinese semantic rescue followed by an English restatement.

### Concept Tutor

Add: target mental model; prerequisite check; learner prediction or explanation; counterexample; transfer question; observed evidence versus inference.

### Code Tutor

Add: code boundary; intended behavior; key invariant; learner prediction; hints given; debugging or test evidence; reconstruction/transfer check. Do not equate running code with learner mastery.

### Reviewer

Add: review scope; criteria; findings by severity; evidence; boundary/conflict check; required versus optional actions. Do not implement unless a separate authorized task exists.

### Examiner

Add: capability tested; conditions and assistance allowed; prompt/tasks; rubric; learner response evidence; result; remediation target. Withhold substantive help until the attempt ends.

### External Coding Agent / Executor

The capsule must include a task packet with:

- base commit or input archive hash;
- exact allowed paths and exact forbidden paths;
- requested changes and non-goals;
- acceptance criteria;
- required commands and tests;
- expected output form.

The return must include:

- base identifier actually used;
- changed-file list and diff summary;
- commands and tests run with results;
- deviations and unresolved items;
- risk notes;
- output commit, patch, or archive identifier.

An executor may modify only the supplied copy, task branch, or authorized files. It cannot merge, promote, or assert canonical status.

## 5. Freshness and Staleness

A return becomes stale if any relevant condition changes, including:

- a referenced state revision is no longer current;
- a relevant ADR, protected invariant, or architecture boundary changes;
- scope or acceptance criteria change;
- Mainline or another authorized executor changes the same artifact;
- a relied-upon assumption is falsified;
- the project enters a phase that invalidates the capsule.

Staleness is semantic and version-based, not merely age-based. `POSSIBLY STALE` must be treated as unmergeable until checked. Mainline either revalidates against current authority or issues a new capsule.

## 6. Merge and Escalation

Mainline records one Return disposition: `ACCEPT`, `PARTIAL ACCEPT`, `REJECT`, or `REISSUE`. For partial acceptance, identify exact accepted fragments and independently verify integration. Never import an entire Sidecar conversation as project truth. An issued Capsule without a Return is never mergeable and must be closed as cancelled, abandoned/incomplete, or reissued.

Escalate when the return conflicts with a protected invariant or accepted ADR, lacks required provenance, needs files outside the capsule, cannot meet acceptance criteria, or may affect capital-critical logic without strong independent verification.

Principle: **cheap execution, strong specification, independent verification**. Point-in-time correctness, leakage, statistics, risk, portfolio, and capital logic always require strong verification and deterministic tests.
