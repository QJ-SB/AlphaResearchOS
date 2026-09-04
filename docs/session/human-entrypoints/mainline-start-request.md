# Mainline Start Request

> **Artifact class:** Human entry-point template (non-canonical operator aid)  
> **Governing contracts:** `docs/project-instruction.md`, `docs/ai-collaboration-and-learning-protocol-v1.md`, and `docs/session/session-bootstrap.md`  
> **Conflict rule:** The governing contracts and current canonical state override this template.

Fill the bracketed fields and send this request in a new Mainline window. This request initializes one authoritative session; it does not authorize a Sidecar launch or a canonical write.

## Authoritative routing

Read and apply, in order:

1. `docs/project-instruction.md`
2. `docs/ai-collaboration-and-learning-protocol-v1.md`
3. `docs/session/session-bootstrap.md`
4. `docs/context/project/project-state.md`

Then load only the state, architecture, ADR, Foundation section, evidence, code, or Learning Map excerpt required by this session. Do not load the entire documentation set by default, and do not edit the reusable Bootstrap template.

## Human input

- **Session objective:** [FILL IN]
- **Expected outcome:** [FILL IN]
- **Acceptance criteria:** [FILL IN]
- **Project Mode:** [RESEARCH / BUILD / VALIDATE / ASK MAINLINE TO RECOMMEND]
- **Learning Mode:** [GUIDED / LEARN / EXAM / ASK MAINLINE TO RECOMMEND]
- **Language Mode:** [ENGLISH-FIRST / CN-CHECK]
- **Progressive Ownership Stage:** [1 / 2 / 3 / 4 / USE CURRENT LEARNING STATE]
- **Repository, base commit, archive hash, or exact work artifact:** [FILL IN OR NONE]
- **Known facts, constraints, and protected boundaries:** [FILL IN OR DEFER TO CANONICAL AUTHORITY]
- **Known open questions or assumptions:** [FILL IN OR NONE]
- **Canonical write authorization at start:** [NONE / EXACT TARGETS AND SUPPORTED CHANGES]

## Required Mainline behavior

Before substantive work:

1. instantiate the session from `docs/session/session-bootstrap.md` and assign a Session ID;
2. declare the human-defined objective, the three independent modes, ownership stage, provenance, and acceptance/stopping conditions;
3. state what was loaded and why, what was deliberately not loaded, and separate facts, assumptions, open questions, and protected invariants;
4. surface conflicts or missing provenance and ask only for the smallest decision needed to proceed;
5. present the completed Bootstrap for human review before beginning substantive work;
6. do not infer a Sidecar role from a Project Mode; Mainline may recommend a Sidecar, but may compile one only after human request or approval and may not dispatch it;
7. treat chat content as non-canonical and perform no canonical write beyond the exact authorization stated above.

