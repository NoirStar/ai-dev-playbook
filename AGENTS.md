# AGENTS.md - Operating Protocol for AI Coding Agents

This repository is a decision system for selecting project stacks dynamically while keeping UX/UI direction stable.

## Mission

For each new project, choose the most appropriate stack based on current ecosystem and project constraints, not habit.

## Non-Negotiable Sequence

1. **Analyze first**: classify product type and constraints.
2. **Recommend second**: compare options and explain trade-offs.
3. **Implement third**: execute only after recommendation is clear.

## Product Type First

Always begin by identifying one primary product type:

- web app
- mobile app
- desktop app
- backend/api
- fullstack product

For fullstack, evaluate frontend and backend separately, then assess integration complexity.

## Stack Selection Rules

- Do not freeze to one default framework without evaluation.
- Use up-to-date information when ecosystem maturity or tooling quality may affect outcomes.
- Prefer minimal complexity consistent with requirements.
- Prioritize long-term maintainability over short-term novelty.
- Prioritize product fit over trendiness.
- Prefer mature, well-documented ecosystems unless project constraints justify risk.

## Recommendation Output Standard

Every recommendation must include:

1. **Primary recommendation** (one stack).
2. **Alternatives** (one or two).
3. **Trade-offs** (speed, maintainability, performance, ops burden, hiring/docs, AI tooling support).
4. **Confidence level** (High / Medium / Low + short rationale).

If confidence is low, explicitly say so and list what would reduce uncertainty.

## UX/UI Consistency Rule

Apply `docs/ui-playbook.md` consistently across projects unless the user explicitly overrides it.

## Implementation Discipline

- Keep changes scoped to the requested task.
- Avoid modifying unrelated files.
- Avoid unnecessary dependency or architecture expansion.
- When uncertain, prefer reversible choices and clear migration paths.

## Required References

Before recommending stacks, consult:

- `docs/stack-selection-policy.md`
- `docs/platform-decision-matrix.md`
- relevant platform guideline docs in `docs/`
- `docs/evaluation-template.md` for final output shape
