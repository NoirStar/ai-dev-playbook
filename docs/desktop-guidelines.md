# Desktop Guidelines (Dynamic over Time)

The best desktop stack may change over time. Re-evaluate for each project.

## Mandatory Comparison

Always compare:
1. web-tech-based desktop stacks,
2. native desktop stacks.

Do not default automatically to either category.

## Evaluation Axes

- UX requirements (density, workflows, interaction fidelity)
- Native integration needs (filesystem, OS APIs, background services, hardware)
- Performance (startup, memory, heavy computation, rendering)
- Packaging/distribution (signing, installer complexity, auto-updates)
- Maintenance burden (upgrade path, tooling complexity, team expertise)
- Code reuse potential with web/mobile products

## When Web-Tech Desktop Is Usually Favorable

- Product shares significant UI/business logic with web.
- Team is primarily web-focused and needs high iteration speed.
- Native OS integration needs are moderate.
- Operational simplicity for cross-platform delivery is high priority.

## When Native Desktop Is Usually Favorable

- Deep OS integration or low-level system access is core.
- Startup/runtime performance constraints are strict.
- Platform conventions and behavior need near-native fidelity.
- Long-term roadmap depends on platform-specific capabilities.

## Risk Management

- Validate risky assumptions with a small prototype.
- Prefer architecture that isolates platform-specific modules.
- Document migration cost if future move between web-tech and native becomes necessary.

## Decision Output Requirement

Provide:
- primary recommendation,
- 1-2 alternatives,
- trade-offs,
- confidence level with uncertainty notes.
