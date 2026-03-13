# ai-dev-playbook

A long-term operating manual for AI coding agents that must choose the **best current stack per project**, not a fixed default stack.

## Purpose

This repository is designed to be reused across many future projects where requirements, ecosystem maturity, and constraints will change over time.

It defines a repeatable process so agents can:

1. Identify product type first.
2. Evaluate current candidate stacks and trade-offs.
3. Recommend one primary option + alternatives.
4. Explain confidence and uncertainty clearly.
5. Preserve consistent UX/UI direction.

## Core Principles

- Dynamic stack selection, never frozen by habit.
- Product fit over trend-chasing.
- Reasoning and comparison over hype.
- Minimal complexity for long-term maintainability.
- Stable UX/UI principles across projects unless explicitly changed.

## Required Workflow (all projects)

1. **Classify product type**: web app, mobile app, desktop app, backend/API, or fullstack product.
2. **Gather constraints**: users, team skill profile, timeline, budget, compliance, integration needs, performance targets.
3. **Build candidate set**: include mature and newer options when justified.
4. **Evaluate using matrix** in `docs/platform-decision-matrix.md`.
5. **Apply product-specific rules** from platform docs.
6. **Recommend**:
   - one primary stack,
   - one or two alternatives,
   - explicit trade-offs,
   - confidence level.
7. **If confidence is low**: state uncertainty and list validation experiments.

## Document Map

- `AGENTS.md`: main protocol for AI agents.
- `.github/copilot-instructions.md`: compact guidance for Copilot-style assistants.
- `docs/stack-selection-policy.md`: decision policy and rules.
- `docs/platform-decision-matrix.md`: practical comparison matrix.
- `docs/evaluation-template.md`: reusable project evaluation template.
- `docs/ui-playbook.md`: stable UX/UI operating rules.
- `docs/frontend-guidelines.md`: frontend stack selection logic.
- `docs/backend-guidelines.md`: backend/API stack selection logic.
- `docs/desktop-guidelines.md`: desktop strategy (web-tech vs native).
- `docs/mobile-guidelines.md`: mobile strategy (cross-platform vs native).

## UX/UI Direction (stable defaults)

Design and interaction rules are anchored in:

- GitHub Primer (clarity and collaboration-oriented interfaces)
- Apple Human Interface Guidelines (restrained, content-first UX)
- IBM Carbon (structured, enterprise-friendly, data-dense systems)

Practical emphasis:

- productivity-focused,
- information-dense,
- clean and practical,
- minimal decoration,
- strong list/table/dashboard/tool workflows,
- avoid visual gimmicks.

## Change Policy

- Stack recommendations must evolve as ecosystem reality changes.
- UX/UI rules remain stable by default and only change via explicit decision.
