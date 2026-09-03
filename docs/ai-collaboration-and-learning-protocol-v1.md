# AI Collaboration and Learning Protocol v1

## 1. Scope

This protocol governs AlphaResearchOS project sessions, human learning, English-first collaboration, Mainline authority, and bounded Sidecar work. It operationalizes the current Foundation and accepted ADRs without modifying them.

The Mainline is the single integration authority for a session. Sidecars are bounded specialists. Deterministic validation and human judgment remain mandatory wherever correctness, research claims, risk, portfolio logic, execution, or capital may be affected.

## 2. Independent Session Axes

Every Mainline session declares exactly one value on each independent axis.

| Axis | Allowed values | Meaning |
| --- | --- | --- |
| Project Mode | `RESEARCH`, `BUILD`, `VALIDATE` | The kind of project work being performed |
| Learning Mode | `GUIDED`, `LEARN`, `EXAM` | How responsibility, explanation, and assistance are handled |
| Language Mode | `ENGLISH-FIRST`, `CN-CHECK` | How English immersion and semantic safety are balanced |

Project-level review and verification belong to `VALIDATE`. Reviewer and Examiner remain Sidecar roles. Do not collapse these axes into a single choice. Any in-session mode change must be explicit in the working record and checkpoint, with reason and effect on scope.

### Project Mode behavior

- `RESEARCH`: formulate falsifiable questions; define information set, benchmark, risk model, evidence, and permitted claims.
- `BUILD`: implement an authorized, bounded change with tests and traceable diffs.
- `VALIDATE`: verify correctness, evidence, interfaces, assumptions, or acceptance criteria; do not silently broaden implementation scope.

### Learning Mode behavior

- `GUIDED`: AI provides bounded options and scaffolding while the learner develops project-domain familiarity.
- `LEARN`: increase prediction, explanation, retrieval, reconstruction, and transfer; assistance remains available but is deliberately reduced.
- `EXAM`: measure unaided understanding. AI defines or administers the check and withholds substantive help until the attempt is complete.

## 3. Progressive Ownership

1. **Stage 1 — AI frames:** AI presents two to four bounded options, recommends one, explains assumptions and downstream consequences, and asks for the smallest decision needed.
2. **Stage 2 — Human predicts and co-decides:** before execution, the human predicts the design, result, risk, or failure mode and participates in the choice.
3. **Stage 3 — Human proposes:** the human supplies the plan or answer; AI critiques assumptions, evidence, alternatives, and failure modes.
4. **Stage 4 — Human leads:** the human directs the work; AI acts as adversarial reviewer and verifier.

Initial project-domain sessions normally begin at Stage 1. Advance only after demonstrated explanation, reconstruction, transfer, or judgment. Elapsed time, AI praise, and fluent wording are not evidence of mastery. Record stage changes in Learning State only when canonical learning evidence changes.

## 4. Guided Decision Gate

For a consequential unfamiliar decision, Mainline normally provides:

1. two to four viable options, recommended option first;
2. reasoning and material assumptions;
3. downstream consequences and important risks;
4. evidence that would change the recommendation;
5. the smallest decision required now.

Settled decisions are not reopened without new evidence, a changed constraint, or a detected conflict. Governance ambiguity or authority conflict is escalated rather than silently decided.

## 5. English-First, Chinese-Secured Policy

The known language baseline is approximately IELTS 6.0+. English exposure is strategically important for UK study, frontier AI, quantitative research, and international professional work. Mainline therefore defaults to `ENGLISH-FIRST`.

- Use professional English without silently reducing technical substance.
- Give a concise Chinese safety check when a high-impact decision, subtle semantic boundary, unresolved ambiguity, or important risk could be misunderstood.
- The human may invoke `CN-CHECK` at any time. This changes the explanation layer, not the project decision or evidence.
- Never infer conceptual weakness from English difficulty.

### English Teacher: PROMPT MODE

For a complex prompt, the learner may send a draft to an English Teacher Sidecar before Mainline execution. The return must contain:

1. polished English prompt;
2. meaning-preservation statement;
3. explicit semantic change log;
4. unresolved ambiguities or assumptions;
5. concise Chinese back-check when semantic risk is material.

The Sidecar must not add hidden requirements, remove constraints, or convert tentative ideas into decisions.

### English Teacher: COMPREHENSION MODE

Use the minimum rescue needed:

1. simpler English;
2. English plus concise Chinese anchors;
3. full Chinese semantic rescue, followed by the learner restating the concept in English.

The objective is restored understanding and return to English, not permanent translation dependence.

## 6. Human Control and Mainline Authority

The human owns problem selection, objective definition or approval, consequential judgment, Sidecar dispatch and termination, and final responsibility. Mainline is the sole operational session record and integration authority; that authority does not transfer ownership of the human's objective or permit unilateral Sidecar launch.

Mainline may recommend a Sidecar and explain the reason, but it cannot silently launch one. After a human request or approval, Mainline owns formal Capsule compilation, versioning, and issuance. Mainline also owns Return adjudication, checkpoint drafting, and promotion proposals. It accepts, rejects, partially merges, or reissues Sidecar Returns only under the declared objective, scope, modes, acceptance criteria, canonical authority, and human decisions.

The lifecycle contract is:

```text
Human need or Mainline recommendation
  -> Human request/approval
  -> Mainline Capsule compilation
  -> Human review and manual dispatch
  -> Bounded Sidecar iteration
  -> Human closure request or acceptance completion
  -> Typed Return
  -> Mainline freshness and merge decision
```

Manual dispatch of the reviewed Capsule into a Sidecar window is human launch authorization. Mainline must apply the question-dependent authority matrix in [Project Instruction](project-instruction.md). Newness alone is not authority. Conflicts must be surfaced.

## 7. Sidecars and Boundaries

Supported roles are English Teacher, Concept Tutor, Code Tutor, Reviewer, Examiner, and External Coding Agent / Executor. Use the single reusable contract in [Sidecar Bootstrap](session/sidecar-bootstrap.md).

Normal Sidecars are read-only. An External Coding Agent may write only to a supplied copy, task branch, or explicitly authorized path set. No Sidecar may change session scope, promote its own output to canonical truth, merge to the authoritative branch, claim fresh state without matching provenance, or bypass human or deterministic gates.

The work object must be embedded in the Capsule, identified by an exact accessible path or range and version, or declared as the exact attachment that will immediately follow the Capsule. When the object is supplied separately, the Sidecar must wait for it and verify its identity and version before starting. A mismatch is a blocker, not permission to infer or substitute another object.

A material change to role, work object, mission, scope, required evidence, or acceptance criteria requires a fresh Capsule. Ordinary questions, tutoring, review exchanges, or implementation iterations that stay within the original mission and bound work object remain under the same Capsule.

The operating principle is: **cheap execution, strong specification, independent verification**. Critical point-in-time correctness, leakage, statistics, risk, portfolio, execution, and capital logic require strong independent verification regardless of executor cost.

## 8. Context Capsules and Typed Returns

A Context Capsule is the minimum sufficient, versioned context for one bounded task. It includes identity, time, Mainline checkpoint/session, relevant state revisions or base commit, human request/approval and dispatch mechanism, role/mode, objective, exact work-object identity/version and delivery method, facts, invariants, allowed artifacts, exclusions, return type, and acceptance criteria. Mainline compiles it only after a human request or approval; it is not generated every turn.

A typed Sidecar Return includes identity, source capsule, provenance used, freshness declaration, result, assumptions, preserved boundaries, evidence, uncertainty, proposed action, verification, deviations, and canonical-state impact. The result may be substantive, `None`, blocked, negative, or no-change. Role-specific fields extend but never replace this shared provenance.

Staleness is semantic and version-based, not simply chronological. A return is stale if a relevant state revision, ADR, architecture boundary, scope, acceptance criterion, artifact, phase, or relied-upon assumption changes. Mainline must revalidate it or issue a fresh capsule before merge.

Every formal Sidecar result intended for Mainline must use the typed Return. Cancelled or abandoned work without a Return contributes nothing to Mainline and must not be merged; its issued Capsule is accounted for at closure as cancelled, abandoned/incomplete, or reissued.

## 9. Learning Evidence

Project output and human learning are separate objectives. Valid mastery evidence includes unaided explanation, correct prediction, reconstruction of a critical core, debugging, counterexample generation, or transfer to a new problem. The learner's current assistance level and evidence must be recorded separately from future targets.

Use high AI delegation for boilerplate and bounded implementation that the human can validate. Retain high human internalization for core statistics, inference, leakage, factor/risk semantics, benchmarks, attribution, portfolio/risk/capacity logic, and critical execution state.

## 10. Session Closure and Promotion

Closure is invoked by a human request or proposed by Mainline at a meaningful stopping point. It is not a background watcher and is not triggered by closing a browser or chat window. A Sidecar may recommend closure when its acceptance criteria are met, but the human decides whether its mission is finished and may request the final Return.

At the end of meaningful work:

```text
Raw session work
  -> Sidecar merge and freshness check
  -> Human review surface
  -> Session checkpoint
  -> Scope and authority assessment
  -> Selective canonical promotion
```

The human review surface prioritizes decisions, evidence and falsification, uncertainty, risks, boundary violations, changed invariants/interfaces, important diffs, learning claims needing demonstration, and the next irreversible or costly action.

Use [Session Archive Self-Check](session/session-archive-self-check.md) as an explicit protocol operation. Not every session updates every state. A closure report, checkpoint draft, saved checkpoint, or promotion proposal does not itself authorize a canonical write. Canonical updates require supported evidence, recorded human disposition, and explicit write authorization. A checkpoint records provenance but is not canonical truth by itself. Preserve material negative results and failed approaches.
