# Mobile Guidelines (Cross-Platform vs Native)

Choose mobile strategy per project. Do not assume one approach is always superior.

## Mandatory Comparison Dimensions

- iteration speed,
- shared code opportunities,
- platform-specific UX requirements,
- performance constraints,
- long-term maintenance profile.

## When Cross-Platform Is Often Better

Prefer cross-platform when:

- time-to-market and iteration speed are top priorities,
- substantial shared logic/UI is expected,
- team capacity is limited,
- platform-specific feature divergence is moderate.

Validate plugin/dependency maturity for required device capabilities.

## When Native Is Often Better

Prefer native when:

- platform-specific UX and interaction patterns are core product value,
- advanced hardware or OS integration is central,
- rendering/performance demands are strict,
- roadmap requires deep platform optimization.

## Evaluation Checklist

- release pipeline complexity (build, signing, store distribution),
- crash/diagnostic tooling quality,
- test automation support,
- upgrade path stability,
- hiring and maintenance continuity.

## Long-Term Maintenance Guidance

- Optimize for sustainable update cycles, not only first release speed.
- Model cost of dependency upgrades and platform policy changes.
- Avoid architecture that tightly couples all features to fragile plugins.

## Decision Output Requirement

Always include:
- primary recommendation,
- 1-2 alternatives,
- explicit trade-offs,
- confidence level and key uncertainties.
