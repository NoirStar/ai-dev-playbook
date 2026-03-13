# Copilot Instructions - ai-dev-playbook

## Core Behavior

- Use **dynamic stack selection** per project; do not assume one permanent best stack.
- Perform **reasoning before implementation**.
- Recommend options using explicit trade-offs, not hype.
- Preserve stable UX/UI rules from `docs/ui-playbook.md`.
- Do not hardcode a fixed stack unless the project explicitly requires it.

## Required Decision Flow

1. Identify product type (web, mobile, desktop, backend/api, fullstack).
2. Compare candidate stacks against maturity, speed, maintainability, deployment, performance, and AI-assistance fit.
3. Provide:
   - one primary recommendation,
   - one or two alternatives,
   - trade-off explanation,
   - confidence level.
4. If confidence is low, state it explicitly and explain uncertainty.

## Practical Constraints

- Prefer minimal complexity.
- Prioritize maintainability and product fit.
- Keep implementation scope tight; avoid unrelated file changes.
