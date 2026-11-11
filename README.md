# Jobs-Inspired Product Aesthetics Skill

[![skills.sh](https://skills.sh/b/pipi-1997/jobs-aesthetic-product-design-scaler)](https://skills.sh/pipi-1997/jobs-aesthetic-product-design-scaler)

A portable product-design Skill that turns Apple design guidance, Steve Jobs’s public record, industrial-design history, and a rigorous review rubric into a workflow for software and hardware.

It focuses on product principles: clear purpose, focus, subtraction, hardware-software integration, craft, accessibility, long-term quality, and evidence-based tradeoffs. It does not copy Apple’s visual skin and is not an official Apple or Steve Jobs publication.

## Use it for

- Product direction, PRDs, feature tradeoffs, and roadmap reviews
- Web, mobile, desktop, wearable, and spatial-computing interfaces
- Industrial design, physical interaction, packaging, unboxing, and hardware-software systems
- Design systems, interaction flows, state design, copy, motion, sound, and accessibility
- Reviews where the goal is “minimal but not empty,” “premium without ornament,” or “complete like an art object”

## Install

Install from the [skills.sh ecosystem](https://www.skills.sh/) with:

```bash
npx skills add pipi-1997/jobs-aesthetic-product-design-scaler
```

The package entrypoint is `SKILL.md`. For explicit invocation, use:

```text
$jobs-aesthetic-product-design
```

For the manual global installations used by this workspace:

- Codex: `~/.codex/skills/jobs-aesthetic-product-design/`
- Cursor: `~/.cursor/skills/jobs-aesthetic-product-design/`

Restart the relevant agent after installation so it refreshes its skill index.

## Package contents

```text
jobs-aesthetic-product-design/
├── SKILL.md                              # Skill entrypoint and workflow
├── agents/openai.yaml                    # Codex UI metadata
├── references/
│   ├── apple-design-guidelines.md        # Official HIG and hardware translation
│   ├── jobs-public-principles.md         # Source-backed Jobs principles
│   └── extreme-aesthetic-review.md       # Rubric, tests, and output template
├── README.md
└── LICENSE
```

## Source boundary

Primary references include Apple’s Human Interface Guidelines, Apple Design Resources, SF Symbols, Steve Jobs Archive, Smithsonian Institution, and Stanford. Design-history and community sources provide context and debate; they do not replace primary evidence.

The Skill verifies quotations where possible, labels uncertain attributions, and separates design principles from Apple’s period-specific visual expressions. It does not redistribute Apple proprietary assets.

## License

The original Skill content is released under the MIT License. External sources, Apple resources, trademarks, and media remain subject to their own copyright, trademark, and usage terms.
