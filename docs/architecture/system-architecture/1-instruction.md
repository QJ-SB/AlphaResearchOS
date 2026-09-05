# System Architecture Directory Instruction

## Responsibility

`current-system-architecture.md` records only architecture supported by current code, tests, runtime observation, and other empirical evidence. It answers what components and interfaces are implemented now.

## Update Contract

- Replace the file as a concise rolling snapshot when implemented architecture changes.
- Cite code paths, tests, commits, or evidence for every substantive current component.
- Separate `Established Truth`, `Active Work`, and any non-current target reference.
- A target or Foundation north-star architecture may be linked only under a clearly labeled `Non-Current Target References` section.
- Use `TBD` or `Not yet established` when evidence is absent.
- Do not infer implementation from a plan, directory skeleton, coherent design, checkpoint, or chat.
- Architecture history and rationale belong in ADRs; milestones and blockers belong in Project State.

## Authority

For implementation truth, current code, tests, and empirical evidence outrank this summary. If they conflict, update this file after review; do not reinterpret the evidence to preserve the prose.
