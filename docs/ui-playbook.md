# UI Playbook (Stable Direction)

This playbook defines consistent UX/UI rules across projects. Treat these as defaults unless explicitly overridden.

## Reference Foundation

- **GitHub Primer**: clarity, predictable navigation, collaboration-oriented workflows.
- **Apple HIG**: restrained visual language, content-first layout, careful hierarchy.
- **IBM Carbon**: structured systems, data-dense enterprise patterns, scalable components.

## Product UX Principles

1. Productivity-first: optimize for task completion speed.
2. Information-dense where appropriate: avoid wasted space in tool interfaces.
3. Content over decoration: visual style must support comprehension.
4. Clarity over novelty: predictable interaction patterns beat unusual effects.
5. Accessibility and legibility are baseline requirements.

## Layout and Information Architecture Rules

- Prefer clear, hierarchical layouts with strong section structure.
- Favor list/table/dashboard patterns for operational tools.
- Use cards only when grouping distinct content units; avoid oversized cards.
- Preserve visible context for users (filters, scope, status, selection state).
- Keep primary actions obvious and consistently located.

## Visual Style Rules

- Keep visual language clean and practical.
- Use restrained color accents; avoid heavy gradients by default.
- Minimize ornamental shadows/glows.
- Use typography hierarchy to communicate structure rather than decorative styling.
- Reserve high-emphasis color for status and critical actions.

## Interaction Rules

- Interactions should feel immediate and deterministic.
- Use animation only when it improves understanding (state change, continuity, feedback).
- Avoid meaningless motion and playful transitions in serious productivity tools.
- Keep forms concise; provide inline validation and actionable error messages.
- Ensure keyboard and power-user workflows are supported when relevant.

## Data-Dense UI Rules

- Tables should support sorting, filtering, and scanning efficiency.
- Prefer progressive disclosure over hiding critical controls.
- Make empty, loading, and error states informative and actionable.
- Surface system status and operation results clearly.

## Platform Tone Guidance

- Desktop/productivity contexts: prioritize structure, precision, and dense utility.
- Consumer/mobile contexts: maintain clarity and restraint while adapting touch ergonomics.
- Never force playful mobile aesthetics onto serious desktop enterprise workflows.
