# Frontend Guidelines (Dynamic Selection)

Do not assume one frontend framework is always best. Select based on product shape and constraints.

## Evaluation Baseline

For each candidate frontend approach, evaluate:

- ecosystem maturity and upgrade stability,
- development speed and team familiarity,
- maintainability and architecture clarity,
- runtime performance and UX responsiveness,
- accessibility support,
- deployment model simplicity,
- AI-assisted coding reliability.

## When a React-Based Stack Often Makes Sense

React-oriented ecosystems are frequently strong when:

- building complex dashboards/admin tools,
- requiring large component ecosystem and tooling flexibility,
- needing broad hiring availability,
- targeting fullstack setups with strong community patterns.

Still validate alternatives for specific constraints (bundle size, simplicity, runtime needs).

## When Lighter or Alternative Frontend Approaches May Be Better

Consider lighter/alternative options when:

- app scope is modest and long-term complexity should remain low,
- fast startup and minimal bundle overhead are critical,
- team prefers convention-heavy systems with fewer decisions,
- content-heavy or mostly static experiences dominate.

## Product-Type Considerations

### Admin Tools and Dashboards
- Prioritize table/list workflows, state predictability, and maintainability.
- Favor mature component and data-grid ecosystems.
- Optimize for productivity and dense information display.

### Consumer Products
- Prioritize interaction smoothness, performance, and accessibility.
- Avoid over-engineering internal abstractions early.

### AI Products
- Prioritize streaming UX quality, robust async state handling, and observability.
- Ensure stack supports rapid iteration around prompt/tool interfaces.

### Content-Heavy Apps
- Prioritize rendering strategy, caching, SEO/discoverability needs, and editorial workflow fit.
- Consider whether server rendering or static strategies reduce operational burden.

## Decision Output Requirement

For each frontend decision provide:

- primary recommendation,
- 1-2 alternatives,
- explicit trade-offs,
- confidence level.
