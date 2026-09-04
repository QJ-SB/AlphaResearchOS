# Sidecar Capsule Request

> **Artifact class:** Human entry-point template (non-canonical operator aid)  
> **Governing contracts:** `docs/project-instruction.md`, `docs/ai-collaboration-and-learning-protocol-v1.md`, and `docs/session/sidecar-bootstrap.md`  
> **Conflict rule:** The governing contracts and current canonical state override this template.

Fill the bracketed fields and send this request to the current Mainline. It authorizes Mainline to compile a Capsule for review; it does not run the Sidecar. Manually sending the reviewed Capsule to a Sidecar is the launch authorization.

## Authoritative routing

Read and apply:

1. `docs/project-instruction.md`
2. `docs/ai-collaboration-and-learning-protocol-v1.md`
3. `docs/session/sidecar-bootstrap.md`
4. the current Mainline Session Bootstrap and only the canonical revisions relevant to this task.

## Human request

- **Requested Sidecar role:** [ENGLISH TEACHER / CONCEPT TUTOR / CODE TUTOR / REVIEWER / EXAMINER / EXTERNAL CODING AGENT]
- **Role mode, if applicable:** [PROMPT MODE / COMPREHENSION MODE / N/A / FILL IN]
- **Bounded mission and precise question:** [FILL IN]
- **Exact work-object identity:** [EXACT EXCERPT / CANONICAL PATH AND RANGE / ATTACHMENT NAME]
- **Work-object version:** [COMMIT / HASH / REVISION / NOT AVAILABLE]
- **Delivery method:** [EMBEDDED / ACCESSIBLE PATH / ATTACHMENT FOLLOWS]
- **Allowed evidence and source surface:** [EXACT FILES, EXCERPTS, OR CAPSULE-ONLY]
- **Explicit exclusions / forbidden sources or actions:** [FILL IN]
- **Permitted within-mission iteration:** [FILL IN]
- **Required typed-Return emphasis:** [FILL IN]
- **Acceptance criteria:** [FILL IN]
- **Mission completion condition:** [FILL IN]

## Required Mainline behavior

Compile one immutable, versioned Context Capsule using `docs/session/sidecar-bootstrap.md`. If any identity, version, evidence boundary, or acceptance condition needed for safe execution is missing, ask for the minimum clarification instead of guessing.

The Capsule must:

1. bind the human request/approval, role and mode, mission, exact work object and version, delivery method, allowed evidence, exclusions, required Return, and acceptance criteria;
2. include only the minimum sufficient context and record the relevant session/checkpoint, commit or archive hash, state revisions, and architecture/ADR revisions;
3. embed the object, point to an exact accessible path/range, or name the exact attachment that will follow; for `ATTACHMENT FOLLOWS`, require the Sidecar to wait and verify identity/version before working;
4. require explicit disclosure of any unsupported or out-of-scope source use and prohibit invented evidence or references;
5. keep ordinary questions and iteration inside the unchanged mission under this Capsule, but require a fresh Capsule ID for a material change to role, work object, mission, scope, required evidence, or acceptance criteria;
6. record manual paste/send as the dispatch mechanism and state that the Capsule remains undispatched until the human performs that action;
7. return the Capsule for human review without performing the Sidecar task in Mainline.

