# Platform Decision Matrix

Use this matrix to compare candidate stacks for the identified product type.

Scoring scale: 1 (poor) to 5 (excellent). Add notes for constraints.

## Web App Matrix

| Axis | What to Measure | Candidate A | Candidate B | Candidate C |
|---|---|---:|---:|---:|
| Ecosystem maturity | Framework stability, release quality, proven usage |  |  |  |
| Development speed | Time to deliver core flows with quality |  |  |  |
| Maintainability | Architecture clarity, testability, onboarding ease |  |  |  |
| Deployment simplicity | CI/CD simplicity, hosting flexibility, rollback ease |  |  |  |
| Performance | Runtime responsiveness, bundle/load efficiency |  |  |  |
| Hiring/community/docs | Availability of talent and reliable docs |  |  |  |
| AI-assisted dev friendliness | Tooling determinism, codegen reliability, debug loop quality |  |  |  |

## Mobile App Matrix

| Axis | What to Measure | Candidate A | Candidate B | Candidate C |
|---|---|---:|---:|---:|
| Ecosystem maturity | SDK stability, plugin health, release cadence |  |  |  |
| Development speed | Iteration speed, shared code potential, tooling quality |  |  |  |
| Maintainability | Long-term project structure and upgrade burden |  |  |  |
| Deployment simplicity | Build/sign/release complexity across platforms |  |  |  |
| Performance | Startup, rendering smoothness, device-level constraints |  |  |  |
| Hiring/community/docs | Talent availability and support quality |  |  |  |
| AI-assisted dev friendliness | Build feedback speed, lint/type guardrails, debug ergonomics |  |  |  |

## Desktop App Matrix

| Axis | What to Measure | Candidate A | Candidate B | Candidate C |
|---|---|---:|---:|---:|
| Ecosystem maturity | Packaging/update ecosystem and framework stability |  |  |  |
| Development speed | Velocity for complex tool-style interfaces |  |  |  |
| Maintainability | Upgrade path, architecture complexity, testability |  |  |  |
| Deployment simplicity | Installer/update/signing/distribution workflow |  |  |  |
| Performance | Startup/memory/runtime behavior |  |  |  |
| Hiring/community/docs | Team availability and support resources |  |  |  |
| AI-assisted dev friendliness | Build/reload loop, diagnostics, deterministic scaffolding |  |  |  |

## Backend/API Matrix

| Axis | What to Measure | Candidate A | Candidate B | Candidate C |
|---|---|---:|---:|---:|
| Ecosystem maturity | Framework/library durability and production usage |  |  |  |
| Development speed | API delivery speed with tests and observability |  |  |  |
| Maintainability | Modularity, typing/contracts, operational clarity |  |  |  |
| Deployment simplicity | Runtime packaging, infra requirements, scaling path |  |  |  |
| Performance | Throughput, latency, concurrency characteristics |  |  |  |
| Hiring/community/docs | Talent pool and support ecosystem |  |  |  |
| AI-assisted dev friendliness | Tooling quality, error readability, test feedback cycle |  |  |  |

## Interpretation Rules

- Do not select by score alone; use notes and hard constraints.
- Weight axes per project context (e.g., performance-heavy product weights performance higher).
- Require explicit trade-off notes before final recommendation.
- Include confidence level and uncertainty rationale in final output.
