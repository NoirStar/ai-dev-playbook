# Backend/API Guidelines (Dynamic Selection)

Backend stack selection must balance delivery speed, reliability, operability, and performance needs.

## Core Evaluation Factors

1. Development speed
2. AI ecosystem compatibility
3. Runtime/performance profile
4. Domain complexity fit
5. Long-term maintainability
6. Deployment and operations burden

## 1) Development Speed

Evaluate:
- API framework productivity,
- test setup and feedback loop speed,
- migration/data tooling maturity,
- observability and debugging ergonomics.

Favor high-velocity stacks for discovery-stage projects if decisions remain reversible.

## 2) AI Ecosystem Compatibility

Evaluate:
- quality of SDKs for LLM/providers/vector systems as required,
- typing and contract quality for agent-generated code safety,
- clarity of errors and logs for debugging,
- ecosystem stability and maintenance health.

## 3) Runtime and Performance Needs

- Use measured requirements, not assumptions.
- Elevate performance-centric runtimes only when throughput/latency constraints demand it.
- If performance targets are moderate, prefer simpler operational models.

## 4) Domain Complexity

- High-complexity domains benefit from strong typing, clear module boundaries, and explicit contracts.
- Event-heavy or integration-heavy systems should prioritize observability and resilience patterns.
- Avoid introducing distributed complexity before scale justifies it.

## 5) Maintainability

Assess:
- codebase structure clarity,
- testability and CI reliability,
- upgrade path stability,
- team onboarding cost.

Prefer boring, understandable architecture over clever but brittle patterns.

## 6) Deployment and Ops Burden

Evaluate:
- packaging/runtime simplicity,
- infrastructure requirements,
- scaling path and rollback safety,
- on-call and incident response complexity.

Penalize stacks that require disproportionate ops overhead for expected business value.

## Decision Output Requirement

Always provide:
- primary recommendation,
- 1-2 alternatives,
- trade-off analysis,
- confidence level and uncertainty notes.
