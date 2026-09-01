---
name: premium-mobile-product-design
description: Design, audit, redesign, and polish premium mobile product interfaces. Use for mobile UI/UX architecture, desktop-to-mobile adaptation, visual hierarchy, typography, spacing, touch targets, bottom sheets, empty/loading/error states, motion, haptics, iconography, illustrations, widgets, and final product-quality audits.
---

# Premium Mobile Product Design

Use this skill whenever the task is primarily about designing, redesigning, auditing, or polishing a mobile app experience.

## Core rule

Mobile is not desktop made smaller. Prioritize the user's current task, preserve readable type and touch comfort, reduce simultaneous information density, and progressively reveal secondary content.

## How to use this skill

Do not load every reference automatically. First identify the task, then read only the relevant modules below.

### New mobile UI / redesign
Read:
- `references/01-foundations.md`
- `references/02-layout-navigation.md`
- `references/03-states-context.md`
- `references/07-final-checklists.md`

### Audit / critique / polish an existing screen
Read:
- `references/04-visual-audit.md`
- `references/05-interaction-polish.md`
- `references/07-final-checklists.md`

### Motion / micro-interactions / premium feel
Read:
- `references/05-interaction-polish.md`
- `references/06-brand-iconography-widgets.md`

### Empty states / loading / AI processing / errors
Read:
- `references/03-states-context.md`
- `references/05-interaction-polish.md`

### Navigation / bottom bar / sheets / keyboard / gestures
Read:
- `references/02-layout-navigation.md`
- `references/03-states-context.md`

### Iconography / illustrations / mascot / widgets
Read:
- `references/06-brand-iconography-widgets.md`

### Desktop → mobile conversion
Read:
- `references/01-foundations.md`
- `references/02-layout-navigation.md`
- `references/07-final-checklists.md`

## Required workflow

1. **Define the screen job.** State in one sentence what the user is trying to accomplish.
2. **Identify the primary action.** There should usually be one obvious dominant action.
3. **Rank information.** Separate critical, frequent, contextual, secondary, and rare content.
4. **Choose the mobile structure.** Decide what stays on-screen, what moves to another page, what becomes a sheet, and what becomes contextual.
5. **Design interaction states.** Include populated, empty, loading, error, keyboard-open, and long-content states where relevant.
6. **Apply the visual system.** Verify typography, spacing, alignment, color, iconography, and component consistency.
7. **Add motion only after UX is correct.** Motion should communicate state and relationships, not decorate randomly.
8. **Perform the final audit.** Use `references/07-final-checklists.md` before declaring the work complete.

## Output expectations

When proposing a design or redesign:
- explain the hierarchy and why major decisions exist;
- avoid random card-heavy layouts;
- describe state changes and navigation behavior, not just static appearance;
- prefer native/mobile conventions unless there is a strong product reason not to;
- note important accessibility, safe-area, keyboard, and reduced-motion considerations;
- keep implementation suggestions consistent with the existing product stack/design system when one is provided.

When auditing:
- prioritize UX problems before decoration;
- distinguish structural issues from polish issues;
- rank findings by impact;
- give specific fixes, not vague comments such as “make it cleaner.”

## Priority order

Use this order when tradeoffs appear:

1. Correct functionality
2. Clear UX
3. Accessibility
4. Information hierarchy
5. Consistency
6. Performance
7. Motion and interaction polish
8. Brand personality
9. Delight

Never sacrifice an earlier layer just to make the UI more visually distinctive.

## Final principle

When space becomes a problem:

**remove → prioritize → split into another screen → progressively disclose → use a sheet → only then reduce size**

When a design feels generic:

**improve the core interaction → improve feedback → improve states → improve motion → improve personality**

Do not start by adding gradients, shadows, cards, or decorative effects.
