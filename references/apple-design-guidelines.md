# Apple Design Guidelines and Transferable Principles

Apple’s HIG, design resources, and platform guidance change with system releases. Use this file as a stable decision framework and open the linked official pages for current details.

## 1. Official entry points

### Principles and foundations

- [Apple Design](https://developer.apple.com/design/): HIG, design resources, SF Symbols, icon tools, and design videos.
- [Human Interface Guidelines: Design principles](https://developer.apple.com/design/human-interface-guidelines/design-principles/): Purpose, Agency, Responsibility, Familiarity, Flexibility, Simplicity, Craft, and Delight.
- [Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines/): Current platform and topic guidance.
- [Principles of great design — WWDC26](https://developer.apple.com/videos/play/wwdc2026/250/): A practical explanation of clarity, simplicity, hierarchy, and why every element should earn its place.

### Software experience and visual systems

- [Accessibility](https://developer.apple.com/design/human-interface-guidelines/accessibility): Visual, auditory, speech, touch, cognitive, and assistive-technology considerations.
- [Inclusion](https://developer.apple.com/design/human-interface-guidelines/inclusion): Design for different abilities, identities, cultures, and contexts.
- [Writing](https://developer.apple.com/design/human-interface-guidelines/writing): Clear, direct, concise, localizable product language and useful error messages.
- [Layout](https://developer.apple.com/design/human-interface-guidelines/layout): Hierarchy, alignment, spacing, adaptation, and different display sizes.
- [Typography](https://developer.apple.com/design/human-interface-guidelines/typography): Type hierarchy, legibility, Dynamic Type, and system fonts.
- [Color](https://developer.apple.com/design/human-interface-guidelines/color): Color for communication, status, continuity, and brand expression; never rely on color alone for essential information.
- [Materials](https://developer.apple.com/design/human-interface-guidelines/materials): Materials for foreground, background, hierarchy, translucency, and spatial relationships; do not add glass effects merely for fashion.
- [Motion](https://developer.apple.com/design/human-interface-guidelines/motion): Motion for feedback, direction, status, and continuity; provide reduced-motion alternatives.
- [HIG patterns and components](https://developer.apple.com/design/human-interface-guidelines/?locale=en_us): Current guidance for navigation, tab bars, sidebars, toolbars, controls, inputs, and patterns.
- [Feedback](https://developer.apple.com/design/human-interface-guidelines/feedback): Timely and understandable feedback for waiting, failure, and recovery.
- [Design principles: Responsibility](https://developer.apple.com/design/human-interface-guidelines/design-principles/): Privacy, safety, transparency, and trust in the product experience.
- [Protecting the User’s Privacy](https://developer.apple.com/documentation/uikit/protecting-the-user-s-privacy): Informed consent, data minimization, transparency, and user control.

### Design resources

- [Apple Design Resources](https://developer.apple.com/design/resources/): Figma and Sketch files, templates, color guides, device bezels, and icon tools.
- [SF Symbols](https://developer.apple.com/sf-symbols/): A system symbol library aligned with San Francisco; follow its license, semantic, weight, scale, and accessibility guidance.
- [Fonts — Apple Developer](https://developer.apple.com/fonts/): San Francisco, New York, and related font resources and licenses.
- [Icon Composer](https://developer.apple.com/icon-composer/): Layered icon tooling for Apple platforms; it is not a generic icon standard for non-Apple products.

## 2. Convert the principles into decisions

| Principle | Design action | Review question |
| --- | --- | --- |
| Purpose | Write one core promise and prioritize around it | Does this element directly serve the product’s purpose? |
| Agency | Provide discoverable actions, clear states, and reversible operations | Can people tell what happened, what they can do, and how to undo it? |
| Responsibility | Put privacy, safety, misuse, and consent into the default path | Do people understand the risk, scope, and consequence? |
| Familiarity | Use understood patterns and preserve a transferable mental model when innovating | Can a person form a correct expectation without a manual? |
| Flexibility | Support different inputs, sizes, abilities, environments, and rhythms | Does it work one-handed, with a keyboard, a screen reader, large text, or no network? |
| Simplicity | Remove redundancy and establish hierarchy without hiding capability | Is each element necessary and at the right level? |
| Craft | Refine defaults, boundaries, copy, motion, sound, and physical details | Does it remain precise up close, over time, and after failure? |
| Delight | Use restrained feedback, rhythm, and detail to create the right feeling | Does delight support understanding, trust, or relationship? |

## 3. Minimum software checklist

### Information and structure

- Each screen or stage has one clear primary task; important information appears first.
- Hierarchy comes from order, spacing, contrast, and scale rather than highlighting everything.
- Navigation position, return paths, selection states, and cross-device relationships remain stable.
- Empty, loading, offline, denied-permission, success, failure, and update states include a clear next step.

### Visuals and language

- Use semantic and dynamic colors across light, dark, increased-contrast, and cultural contexts.
- Do not spread transparency, blur, shadow, or dynamic materials across every layer; use them to clarify context and hierarchy.
- Use short, action-oriented copy; explain both the problem and the remedy in errors.
- Prefer system fonts, symbols, and controls for platform coherence; introduce custom branding only with a clear reason.

### Interaction and accessibility

- Give immediate, appropriate feedback and support reduced motion.
- Core tasks work with touch, keyboard, pointer, voice, screen reader, and switch access where relevant.
- Do not use color as the only state; controls expose readable names, roles, states, and focus.
- Text can grow without clipping after scaling, rotation, localization, or layout changes.

## 4. Transfer the principles to hardware

Apple’s public HIG primarily describes software platforms and digital interaction. It is not a universal industrial-design manual. Map the principles to physical experience instead:

- **Hierarchy** → visual and tactile priority for primary actions, secondary actions, hidden structure, and service access.
- **Feedback** → a shared meaning across key travel, damping, light, sound, vibration, screen states, and network states.
- **Simplicity** → fewer parts, ports, steps, cables, and maintenance costs while preserving essential capability and repair.
- **Materials** → weight, temperature, texture, and durability honestly express purpose; decoration does not disguise poor quality.
- **Spatial relationships** → grip, sightline, reach, storage, charging, cooling, and the surrounding environment.
- **Responsibility** → safety, privacy, repair, upgrades, recycling, accessibility, and total ownership cost.

## 5. Hardware and design-history sources

- [Steve Jobs Archive: Objects of Our Life](https://stevejobsarchive.com/stories/objects-of-our-life): Background on the 1983 Aspen design talk and the idea that industrial design, software design, and human interaction deserve equal attention.
- [Steve Jobs Archive: Design Inspiration](https://stevejobsarchive.com/artifact/design-influences): Historical influences including small footprints, clean lines, and restrained color. Treat it as history, not a ready-made style template.
- [Dieter Rams: Design by Vitsœ](https://www.vitsoe.com/files/assets/1000/17/VITSOE_Dieter_Rams_speech.pdf): Product configuration, purpose, function, proportion, materials, and system relationships.
- [Dieter Rams — Design Museum](https://designmuseum.org/designers/dieter-rams): Background on the ten principles of good design.
- [The nature of simplicity in Apple design](https://doi.org/10.1080/14606925.2015.1059609): Academic discussion of simplicity, integrity, essence, deference, style, and honesty in Apple design.

### Community and design-history reading

These sources are context, not specifications:

- [How Steve Jobs’s Love of Simplicity Fueled a Design Revolution — Smithsonian Magazine](https://www.smithsonianmag.com/arts-culture/how-steve-jobs-love-of-simplicity-fueled-a-design-revolution-23868877/): Historical context around Hartmut Esslinger, Jony Ive, and Apple’s design shift.
- [Back to core values — Design Week](https://www.designweek.co.uk/issues/30-may-2002/back-to-core-values/): A 2002 interview about design, innovation, and company values.
- [An Oral History of Apple Design: 1992 — Fast Company](https://www.fastcompany.com/3016318/an-oral-history-of-apple-design-1992): Apple industrial design, Robert Brunner, and Jony Ive’s early context.
- [An Oral History of Apple Design: 2004 — Fast Company](https://www.fastcompany.com/3016337/an-oral-history-of-apple-design-2004): Organization, engineering, product integration, and design collaboration.
- [Jonathan Ive and the Future of Apple — The New Yorker](https://www.newyorker.com/magazine/2015/02/23/shape-things-come): Industrial design, prototypes, details, and organizational tension.
- [The Guts of a New Machine — Design Observer](https://designobserver.com/the-guts-of-a-new-machine/): The iPod, how design works, and simplicity as an outcome.
- [Dieter Rams — Rams Foundation](https://rams-foundation.org/foundation/design-comprehension/): Original context for the ten principles of good design.

When reading community sources, extract what happened, why it happened, and what it cost. Do not treat a publication’s adjectives as design rules. Apple’s expression changed across the early Mac, iPod, iOS 7, Apple Watch, visionOS, and current systems; separate principles from period, platform, and brand expression.

## 6. Source discipline

Prefer sources in this order: current Apple documentation and resources → Steve Jobs Archive, Smithsonian, Stanford, and other primary records → attributed design history, research, and long-form interviews → community articles, forums, and secondary quotes.

Community material can reveal cases and disputes, but it cannot replace primary evidence. Verify “Jobs said” claims against the original talk, interview, or archive. If verification is unavailable, label the claim as common attribution or unverified and do not make it a hard rule. Preserve source links and license boundaries; do not present this file or the Skill as Apple material.
