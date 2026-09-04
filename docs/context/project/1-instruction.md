# Project State Directory Instruction

## Responsibility

`project-state.md` is the concise rolling truth for current phase, milestones, blockers, active work, and next project action.

## Update Contract

- Preserve the standard header fields: Last Updated, State Revision, Based on Commit, Current Scope, Established Truth, Active Work, Open Questions and Risks, Next Recommended Step, Relevant Artifacts.
- Increment `State Revision` only when canonical project state changes.
- Distinguish verified current facts from targets, proposals, and assumptions.
- Replace obsolete status rather than accumulating a diary.
- Use `TBD`, `Not yet established`, or `No active item` instead of guessing.
- Historical reasoning belongs in checkpoints or ADRs; detailed experiments belong in the Experiment Registry; research interpretation belongs in Research State.

## Authority

For current project status, this file is primary. Current code/test evidence remains primary for implementation claims. The latest checkpoint may propose updates but does not become canonical until reviewed and promoted.
