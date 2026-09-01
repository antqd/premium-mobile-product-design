# 01 — Mobile Foundations

## One screen, one primary job

Most mobile screens should have one obvious purpose. Settings should be settings. Search should be search. An editor should primarily edit. Avoid adding unrelated recent content, recommendations, analytics, or promotional modules merely because there is room.

The Home screen is the main exception, but even Home needs a clear hierarchy rather than becoming a miniature desktop dashboard.

## Do not shrink desktop

Do not solve mobile constraints by making everything smaller. Mobile type and touch targets often need to remain as large as, or larger than, desktop equivalents.

Use removal and prioritization before compression.

## Reduce information density

Desktop can reasonably support multiple columns and simultaneous modules. Mobile usually cannot. Choose the most valuable content and progressively reveal the rest.

A useful order is:
1. current state;
2. primary action;
3. most important next information;
4. secondary information;
5. deeper detail screens.

## One primary direction per section

Mobile sections should generally progress in one direction:
- vertical stack for primary/full-width information;
- horizontal carousel for secondary preview/discovery content.

Avoid recreating 2D desktop grids on narrow screens.

## Core building blocks

Most mobile UI can be built from:
- text and links;
- inputs;
- images/illustrations;
- lists;
- cards/surfaces;
- navigation;
- sheets/overlays.

Cards are useful for grouping, not as a default wrapper around everything.

## Avoid nested cards

Nested containers create padding-on-padding and reduce usable width. Prefer grouping with typography, whitespace, separators, and alignment.

## Progressive disclosure

Show what the user needs for the current decision and defer deeper details.

Example: show calories, protein, carbs, and fat first; move micronutrients and historical analysis deeper unless they are central to the screen's purpose.

## Touch

Keep interactive hit areas comfortable even when the visible icon is small. Approx. 44pt/px-equivalent targets are a useful baseline.

## Typography

Avoid tiny body text. Use a small number of coherent type roles and create hierarchy using size, weight, color, and line height.

Titles should stand out without shouting. Body text should support comfortable understanding.

## Spacing

Use a small spacing scale consistently, e.g. 4 / 8 / 12 / 16 / 20 / 24 / 32.

Spacing is relational: related elements should be closer together; unrelated sections should have greater separation.

## Safe areas

Respect system status areas, notches, Dynamic Island, home indicator, and gesture regions. Floating/sticky controls must include safe-area padding.

## Product-system robustness

Test UI with:
- short and long titles;
- missing and unexpected images;
- large/zero values;
- long translations;
- empty data;
- many items and one item.

Design for production variation, not one ideal screenshot.
