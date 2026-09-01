# Premium Mobile Product Design Skill

A modular Agent Skill for designing, auditing, redesigning, and polishing premium mobile app experiences.

The skill focuses on the areas that most often separate a merely functional mobile UI from a polished product:

- mobile-first information architecture;
- navigation and bottom sheets;
- typography, spacing, hierarchy, and alignment;
- empty/loading/error/keyboard states;
- motion and micro-interactions;
- haptic feedback;
- iconography and illustrations;
- widgets and platform surfaces;
- final UI/UX audit workflows.

## Why it is modular

The root `SKILL.md` acts as a router. Instead of forcing the agent to read a very large playbook on every task, it tells the agent which reference files to open based on the task.

```text
premium-mobile-product-design/
├── SKILL.md
├── README.md
├── references/
│   ├── 01-foundations.md
│   ├── 02-layout-navigation.md
│   ├── 03-states-context.md
│   ├── 04-visual-audit.md
│   ├── 05-interaction-polish.md
│   ├── 06-brand-iconography-widgets.md
│   └── 07-final-checklists.md
└── examples/
    └── fitcontext.md
```

## Example prompts

- "Use premium-mobile-product-design to redesign this mobile home screen."
- "Audit this React Native screen and rank the top UX/UI issues before changing code."
- "Polish this app so it feels less static: focus on motion, haptics, loading states, and tab transitions."
- "Convert this desktop dashboard into a mobile information architecture."
- "Review this screen for typography, spacing, icon consistency, and hierarchy."
- "Design the empty/loading/error states for this AI-powered flow."

## Recommended workflow with Codex

Give Codex the existing screen/code plus the outcome you want. Ask it to use the skill in two passes:

1. **Audit / reasoning pass** — identify structural UX problems before editing.
2. **Implementation / polish pass** — make changes, then re-run the final checklist.

For UI work, explicitly ask Codex to test or inspect the result on a real mobile viewport/device simulator where available. Static code review alone does not reveal keyboard, safe-area, animation, or touch problems.

## Philosophy

First make the application effortless. Then make it feel responsive. Then make it recognizable.
