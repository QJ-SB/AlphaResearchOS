# Mainline Session Bootstrap

Use this template to initialize the sole authoritative Mainline for one bounded session. Load only the context needed for the declared objective. Do not automatically load the Foundation, all state files, architecture, ADRs, and every learning map.

## 1. Identity and Modes

- **Session ID:** `SESSION-YYYYMMDD-NN`
- **Date:** `YYYY-MM-DD`
- **Project Mode:** `RESEARCH | BUILD | VALIDATE`
- **Learning Mode:** `GUIDED | LEARN | EXAM`
- **Language Mode:** `ENGLISH-FIRST | CN-CHECK`
- **Progressive Ownership Stage:** `1 | 2 | 3 | 4`

Record any later mode change with timestamp, reason, and scope effect. Reviewer and Examiner are Sidecar roles, not Project Modes.

## 2. Objectives

- **System Objective:** [single bounded project outcome]
- **Human Learning Objective:** [specific capability or understanding to develop or test]
- **Smallest decision required now:** [decision or `None`]

## 3. Provenance

- **Base Commit:** [full commit, `TBD`, or `Not available`]
- **Project State Revision:** [revision or `Not loaded`]
- **Research State Revision:** [revision or `Not loaded`]
- **Learning State Revision:** [revision or `Not loaded`]
- **Architecture Revision / Last Updated:** [value or `Not loaded`]
- **Relevant ADRs:** [paths/status or `None identified`]

## 4. Selective Context Plan

### Load

| Artifact or excerpt | Why it is required | Authority for this question |
| --- | --- | --- |
| [path/range] | [reason] | [authority] |

### Explicitly Do Not Load

- [artifact/group and reason]

Load the current frozen Foundation only when mission, principles, capital governance, or a possible conflict requires it. Load only relevant ADRs and map sections. Treat old checkpoints and chats as provenance, not current truth.

## 5. Working Model

### Known Facts

- [fact plus source]

### Assumptions

- [assumption and how it will be tested]

### Open Questions

- [question]

### Protected Invariants

- AI handles exploration and ambiguity; deterministic systems preserve validation and capital boundaries; the human retains judgment and responsibility.
- `Benchmark != Risk Model`.
- `Active Return != Alpha`.
- `Residual != Alpha`.
- `Research Neutralization != Portfolio Neutrality`.
- [task-specific invariant]

## 6. Planned Sidecars

Status vocabulary: `NONE | PROPOSED | REQUESTED | CAPSULE ISSUED | DISPATCHED | CLOSED | CANCELLED`.

| Status | Role | Purpose | Work object and version | Human authorization / dispatch evidence | Capsule ID | Read/write boundary | Required Return |
| --- | --- | --- | --- | --- | --- | --- | --- |
| `NONE` | [role or `None`] | [bounded purpose] | [exact object/version or `None`] | [request, approval, manual dispatch, or `None`] | [ID or `None`] | [boundary] | [typed Return or `None`] |

Mainline may propose a Sidecar during Bootstrap and explain why, but it must not dispatch one. It compiles and issues an official Capsule only after a human request or approval. The human's manual dispatch of the reviewed Capsule authorizes launch. Do not generate a Capsule every turn: one immutable Capsule covers bounded iteration until a semantic dependency such as role, work object, mission, scope, evidence, or acceptance criteria changes.

Issue each authorized Sidecar through [Sidecar Bootstrap](sidecar-bootstrap.md). Normal Sidecars are read-only. Every formal result intended for Mainline requires the specified typed Return. Mainline decides whether a fresh Return is accepted, rejected, partially merged, or reissued.

## 7. Delivery Contract

### Expected Outputs

- [output]

### Acceptance Criteria

- [observable criterion]
- [test or evidence]

### Stopping or Escalation Conditions

- protected invariant or accepted ADR conflict;
- unavailable authority needed to resolve a consequential ambiguity;
- evidence is insufficient for the requested claim;
- requested scope or write boundary would be exceeded;
- [task-specific condition].

## 8. End-of-Session Trigger

The human may trigger closure with a concise request. When the outcome is meaningful or the session must stop, Mainline should propose closure. Closing a browser or chat window is not an executable trigger.

After the human closure request or accepted Mainline proposal, draft a compressed checkpoint and run [Session Archive Self-Check](session-archive-self-check.md). Account for every issued Capsule and review Return freshness and merge decisions before proposing canonical promotion. Closure output does not authorize canonical writes.
