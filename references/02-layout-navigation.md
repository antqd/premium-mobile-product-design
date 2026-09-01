# 02 — Layout, Navigation & Mobile Structure

## Bottom navigation

Prefer bottom navigation for roughly 3–5 primary destinations. Three or four is ideal; five is usually the upper practical limit.

If one action is overwhelmingly central, it may be visually separated, but do this only when it truly represents the product's dominant recurring action.

## Too many destinations

When important destinations exceed what a bottom bar can hold, consider a dedicated navigation/home menu instead of squeezing more icons into the bar.

A navigation hub may contain:
- destination rows;
- counts;
- recent items;
- contextual shortcuts;
- secondary actions.

## Contextual navigation

Persistent global navigation should disappear when it stops being useful. In focused workflows, replace global nav with task-specific actions.

Examples:
- editor → Back / formatting / Share;
- selection → Cancel / Confirm;
- camera/scanner → capture controls;
- checkout/confirmation → focused CTA.

## Bottom sheets

Use bottom sheets for temporary workflows where preserving context is valuable:
- filters;
- sorting;
- selecting templates/categories;
- small forms;
- contextual actions;
- confirmation flows.

Do not navigate to a full new page when the user should remain mentally anchored to the current screen.

## Sticky context

Long screens may collapse a large title into a compact sticky title. This preserves context while recovering space.

## Sticky bottom actions

Use a sticky bottom action when the primary action remains relevant throughout a long decision-oriented screen.

Examples: Continue, Save, Log Meal, Book, Confirm.

Do not stack a sticky CTA, global bottom nav, and system gesture area without a deliberate hierarchy. In focused flows, contextual actions may replace global nav.

## Keyboard-aware layout

Design input-heavy screens with the keyboard open.

Verify:
- focused input remains visible;
- composer/CTA remains reachable;
- scroll is predictable;
- bottom nav hides or adjusts where appropriate;
- content is not trapped behind the keyboard.

For chat-like experiences, keep the composer attached above the keyboard.

## Gestures

Useful gestures include:
- edge swipe back;
- swipe down to dismiss sheets;
- horizontal swipes through secondary cards;
- list-item swipe actions;
- long press for contextual actions.

Do not hide essential functionality behind an invisible gesture unless there is a visible alternative or the interaction is taught.

## Long press

Long press can function as mobile right-click for rename, duplicate, delete, share, save, move, preview, and more actions.

Use subtle scale/background treatment and haptics when appropriate.

## Information order follows user questions

Structure screens around the sequence of questions the user naturally asks:
- What is this?
- Is it relevant / trustworthy?
- What is its current state?
- What can I do?
- What happens next?

Do not expose database order as UI order.
