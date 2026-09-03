# AlphaResearchOS Project Instruction

## Purpose

AlphaResearchOS is governed as one AI-native research operating system that develops both the system and the human researcher. This file is the concise operating entry point. The frozen mission and principles live in the current Foundation; accepted durable decisions live in ADRs; current truth lives in evidence, code, architecture, and rolling state according to the question being asked.

Read [AI Collaboration and Learning Protocol](ai-collaboration-and-learning-protocol-v1.md) for the complete Mainline, Sidecar, learning, and language rules.

## Binding Principles

- AI expands exploration and handles ambiguity.
- Deterministic systems preserve validation, reproducibility, risk, and capital boundaries.
- The human defines objectives, exercises judgment, authorizes consequential actions, and retains final responsibility.
- Prefer minimal, testable vertical slices over speculative infrastructure.
- Research validation precedes system expansion; survival precedes optimization.
- Learn and reproduce mature methods before localization; validate local conclusions with local evidence.
- Never silently change a protected invariant, accepted decision, scope, or research assumption.
- Never present a target architecture as current implementation.

Preserve these semantic boundaries:

```text
Benchmark != Risk Model
Active Return != Alpha
Residual != Alpha
Research Neutralization != Portfolio Neutrality
```

Any Alpha claim must be benchmark-relative, risk-adjusted, incremental, out-of-sample, cost-aware, and capacity-aware.

## Question-Dependent Authority

| Question | Highest authority | Secondary authority | Non-authoritative input |
| --- | --- | --- | --- |
| Mission, frozen principles, capital governance | Current frozen Foundation | Accepted ADR that does not contradict it | Chat or session notes |
| Why an important decision was made | Most recent relevant Accepted ADR | Earlier ADRs and Foundation | Rolling state |
| What is implemented now | Current code, tests, and empirical evidence | Current system architecture and project state | Target-design prose |
| Current project status and next milestone | Project State | Latest checkpoint and current architecture | Old checkpoints |
| Current research status | Reproducible evidence and Experiment Registry | Research State | Coherent narrative |
| Current human capability | Demonstrated performance and Learning State | Human Skills Map | AI praise or untested confidence |
| Session-local working state | Current Mainline session and valid capsules | Fresh Sidecar Returns | Stale Sidecar conversations |

Newer does not automatically mean more authoritative. Chat is never canonical by itself. Surface conflicts; do not silently resolve them.

## Session Operating Rule

The human defines or approves the objective and decides whether to dispatch and terminate each Sidecar. One Mainline is the sole operational session record and integration authority. At bootstrap it must declare three independent axes:

- Project Mode: `RESEARCH`, `BUILD`, or `VALIDATE`;
- Learning Mode: `GUIDED`, `LEARN`, or `EXAM`;
- Language Mode: `ENGLISH-FIRST` or `CN-CHECK`.

It must also declare the progressive ownership stage, human-defined or human-approved objectives, selectively loaded artifacts, acceptance criteria, and escalation conditions. Use [Session Bootstrap](session/session-bootstrap.md). Reviewer and Examiner are Sidecar roles, not Project Modes.

Mainline may recommend a Sidecar and explain why, but it cannot silently launch one. Only after a human request or approval does Mainline compile and issue an official, versioned Context Capsule. A generated Capsule is not dispatched until the human manually sends it or otherwise explicitly authorizes launch. Sidecars receive bounded Capsules and return typed, provenance-bearing results; no result may re-enter Mainline without a typed Return. They cannot silently update canonical state. Use [Sidecar Bootstrap](session/sidecar-bootstrap.md).

## Completion Rule

The human may trigger closure with a concise request. Mainline should propose closure when the result is meaningful or the session must stop. Closing a browser or chat window is not an executable trigger.

At meaningful session end:

1. review Sidecar freshness and merge decisions;
2. expose consequential decisions, evidence, uncertainty, risks, changed invariants, and important diffs for human review;
3. create a compressed checkpoint under `session/session-checkpoints/`;
4. run [Session Archive Self-Check](session/session-archive-self-check.md);
5. promote only supported information to the appropriate canonical target after recorded human review and explicit write authorization.

Generating a closure packet, checkpoint draft, or promotion proposal does not itself authorize a canonical write. Not every session changes every state file. Unsupported confidence, raw discussion, and repeated explanations are not promotable evidence.
