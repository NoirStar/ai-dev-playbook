# Stack Selection Policy

## 1) Policy Intent

This policy defines how AI agents should choose a stack for each project at decision time. Choices are dynamic and should evolve with ecosystem reality.

## 2) Evaluation Priorities (default order)

1. Product fit (user/job-to-be-done alignment)
2. Long-term maintainability
3. Delivery speed to first useful release
4. Deployment and operations simplicity
5. Performance and scalability headroom
6. Ecosystem maturity (libraries, docs, community)
7. AI-assisted development friendliness

> Adjust ordering only when project constraints require it (e.g., hard real-time requirements).

## 3) Product-Type Decision Rules

### Web App
- Favor stacks with mature UI tooling, robust data-fetch/state options, and predictable deployment.
- For internal/admin products, prioritize productivity and maintainability over visual experimentation.
- For consumer products, include UX performance and accessibility in first-tier criteria.

### Backend/API
- Prefer stacks that balance implementation speed with operability and reliability.
- Elevate performance concerns only when throughput/latency targets demand it.
- Penalize stacks that force excessive ops complexity for expected scale.

### Desktop App
- Compare web-tech-based desktop and native options every time.
- Default to web-tech desktop when code reuse and speed matter most and native constraints are moderate.
- Prefer native when deep OS integration, startup/runtime performance, or platform conventions are critical.

### Mobile App
- Compare cross-platform and native on each project.
- Prefer cross-platform when fast iteration and shared logic are primary.
- Prefer native when platform-specific UX, hardware integration, or performance constraints are central.

### Fullstack Product
- Evaluate frontend and backend independently first.
- Then score integration complexity, team context switching, and release workflow coherence.

## 4) Maturity vs Speed vs Performance

- **Favor maturity** when domain risk, team size, or maintenance horizon is high.
- **Favor speed** for discovery-stage products with reversible architecture decisions.
- **Favor performance** when measurable SLAs/SLOs require it.
- If performance is only hypothetical, avoid premature optimization and prefer simpler stacks.

## 5) Desktop Strategy: Web-Tech vs Native

Prefer web-tech desktop when:
- strong UI code reuse with web is valuable,
- team skills are web-heavy,
- deployment/update pipelines must be simple.

Prefer native desktop when:
- OS-level capabilities are first-class requirements,
- low-level performance is essential,
- platform-specific UX fidelity is non-negotiable.

## 6) Mobile Strategy: Cross-Platform vs Native

Prefer cross-platform when:
- rapid iteration and resource efficiency dominate,
- shared business logic/UI is high value,
- platform-specific UX differences are moderate.

Prefer native when:
- deep platform-specific behavior is core,
- critical rendering/performance constraints exist,
- long-term feature roadmap diverges between platforms.

## 7) AI-Friendliness Evaluation

Assess each candidate for:
- quality of official docs and examples,
- deterministic tooling and scaffold quality,
- quality of lints/tests/type systems for agent feedback loops,
- debugging visibility and error clarity,
- ecosystem support in contemporary AI coding workflows.

Avoid stacks where AI-generated code routinely produces fragile or opaque outcomes.

## 8) Handling Uncertainty and Ecosystem Change

When confidence is low:
1. Explicitly label confidence as Low.
2. Identify uncertainty drivers (tooling immaturity, unclear benchmarks, deployment unknowns).
3. Propose time-boxed validation (spike/prototype/benchmark).
4. Choose the most reversible architecture for initial delivery.

Revisit stack decisions at major milestones (MVP, scale-up, platform expansion).
