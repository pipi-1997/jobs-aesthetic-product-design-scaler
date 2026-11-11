# Extreme Aesthetic Review Rubric

Use this rubric to turn “it feels like an art object” into a judgment that can be discussed, compared, and tested. It applies to software, hardware, and integrated product systems. The score is a diagnostic, not a beauty contest: use it to find the highest-leverage problem.

## Scoring

- **0 — Missing or contradictory.** The main task fails, or the design harms clarity, trust, safety, or accessibility.
- **1 — Usable but rough.** A solution exists, but its logic, edge cases, or evidence are weak.
- **2 — Complete and usable.** The main path works and most details are handled, but meaningful refinement remains.
- **3 — Intentional and validated.** The principle is clear, details are coherent, complexity is absorbed by the product, and real-context evidence supports it.

Release gates: **purpose, main path, feedback and recovery, accessibility/safety, and long-term quality** must each score at least 2. Any 0 means unfinished; do not hide it behind an average score.

## Core rubric

| Dimension | Software check | Hardware check | Evidence |
| --- | --- | --- | --- |
| Purpose | One sentence explains the task and outcome | Form, size, and parts serve the use | Product thesis, user task, tradeoff record |
| Focus | Main path is short; secondary capability has hierarchy | Ports, controls, parts, and accessories are deliberate | Task flow, removal list |
| Hierarchy | Order, spacing, contrast, and structure show what matters first | Primary action, grip, status indicators, and service access have priority | Static design, prototype, first-glance test |
| Discoverability | Important actions are findable without guessing | Touchpoints, opening, connection, charging, and service are understandable | New-user test, no-manual test |
| Predictability | The same action, state, and copy mean the same thing everywhere | Pressure, rotation, movement, sound, and screen feedback agree | State matrix, end-to-end recording |
| Feedback | Waiting, success, failure, offline, permission, and recovery are visible | Force, light, sound, vibration, screen, and network states agree | State test, accessibility test |
| Simplicity | Remove redundancy without hiding capability | Reduce parts and steps while preserving essential use and repair | Comparative prototype, error rate, completion time |
| Craft | Type, copy, icons, motion, sound, and defaults are precise | Proportion, radius, seam, edge, material, surface, and assembly are precise | Close-up inspection, render or prototype, manufacturing review |
| Integration | Account, data, notification, cross-device, and service belong together | Hardware, software, packaging, accessories, support, and recycling belong together | Journey map, service blueprint |
| Trust | Privacy, permission, error explanation, and data control are transparent | Safety, durability, heat, privacy, repair, and lifetime are explainable | Risk review, compliance test, repair test |
| Inclusion | Scaling, screen reader, keyboard, voice, touch, and localization work | One-hand use, different strength, sensory needs, environments, and cultures work | Accessibility matrix, real-user test |
| Emotion | Motion, copy, and sound create the right calm, delight, or control | Weight, touch, sound, unboxing, and long-term use create a relationship | Interviews, observation, longitudinal trial |
| Evidence | Not just screenshots; prototypes run in real contexts | Not just renders; samples, engineering, and manufacturing are tested | Test record, issue list, version comparison |

## Review sequence

### A. Purpose review

Write the product promise, core user, core task, and do-not-build list. Sort every design element into “directly serves,” “indirectly supports,” or “not needed yet.” If the team cannot agree, resolve product direction before polishing.

### B. First-glance review

Remove explanation, presenter narration, and marketing copy. Let a stranger see the first screen, first minute, or physical object. Record whether they can answer: What is it? What can I do? What comes next? Why should I trust it?

### C. Main-path review

Complete a real task from first contact. Record pauses, repetition, mis-taps, waiting, hesitation, and requests for help. Write each issue as **observation → task impact → design action → validation method**, not “it does not feel premium.”

### D. Boundary and recovery review

Introduce empty content, slow or absent networks, denied permissions, invalid input, low battery, glare, darkness, noise, orientation changes, large text, one-handed use, and damaged parts. The product must show a clear state, next step, and safe recovery path.

### E. Close-up review

Zoom in on the interface or inspect the physical sample at hand: spacing, alignment, type, icons, color, edges, seams, buttons, sound, cables, screws, material transitions, packaging, cleaning, and maintenance. Look for details that work only in a launch image.

### F. System review

Put software, hardware, content, packaging, sales, support, updates, repair, and recycling on one map. Check whether the same concept uses the same words, forms, actions, and feedback at every touchpoint.

### G. Inversion review

Ask:

1. What would the user lose if this element disappeared?
2. What happens in the worst realistic environment?
3. After one year of repeated use, what will fatigue, wear out, be misunderstood, or reduce trust?

## Common failure modes

- **Surface minimalism:** There are fewer elements, but the main path is harder to find and capability is hidden in gestures, long presses, or deep menus.
- **Material theater:** Glass, metal, light, animation, or texture adds glare, distraction, heat, or maintenance without improving understanding.
- **Launch-complete:** The render is beautiful, but loading, errors, permissions, offline use, repair, and recycling have no design.
- **Brand over task:** Every control emphasizes brand color or personality until hierarchy disappears.
- **False consistency:** Different platforms, sizes, or input methods are forced into one layout even when the context changes.
- **Jobs as evidence:** A historical quote ends the debate without prototypes, user observation, engineering validation, or accessibility evidence.
- **Unbounded perfectionism:** Low-value details receive infinite refinement while the core promise, reliability, delivery, or maintainability remains below bar.

## Review output template

```markdown
# Product Aesthetic Review

## Verdict
- Status: Pass / Conditional pass / Unfinished
- Highest-leverage issue:
- Next action:

## Product thesis
- Core user:
- Core task:
- One-sentence promise:
- Explicitly not pursuing:

## Scores and evidence
| Dimension | Score (0-3) | Observation | Impact | Recommendation | Test |
| --- | ---: | --- | --- | --- | --- |

## Key tradeoffs
- Removed, and why:
- Kept, and why:
- Complexity absorbed by the product:

## Risks
- Usability:
- Accessibility and inclusion:
- Privacy and safety:
- Engineering, manufacturing, repair, and lifecycle:

## Release gates
- [ ] Purpose is clear
- [ ] Main path requires no guessing
- [ ] States, feedback, and recovery are complete
- [ ] Visual and physical details passed close-up review
- [ ] Software and hardware share semantics
- [ ] Key contexts and assistive technologies were validated
```
