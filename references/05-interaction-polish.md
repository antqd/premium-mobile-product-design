# 05 — Motion, Haptics & Interaction Polish

## Make the app feel alive

Once usability and accessibility are correct, use subtle motion, micro-interactions, haptics, and responsive state changes to make the app feel intentional rather than static.

## Motion is a system

Define consistent behavior for:
- page transitions;
- sheets;
- tabs;
- buttons;
- cards;
- selections;
- loading;
- completion;
- insertion/deletion;
- errors.

## Animate relationships

Motion should answer:
- where did this come from?
- what changed?
- what is selected?
- is work happening?
- did it succeed?

Avoid random animation on unrelated properties.

## Prefer subtle motion

Good micro-interactions may be almost invisible consciously. Use small scale response, short transitions, restrained spring, and consistent easing.

If routine animations constantly call attention to themselves, reduce them.

## Page direction

Navigation transitions should preserve spatial orientation. Forward and back should feel related and reversible.

## State transitions

Where it improves comprehension, animate:
- numeric updates;
- progress;
- selected tabs;
- insertion/removal;
- expansion/collapse;
- success state.

## Haptics

Use haptics for meaningful events such as selection, snapping, completion, long press, thresholds, and confirmations.

Do not vibrate on every tap.

Match strength to importance. Visual feedback must remain sufficient because haptics may be unavailable or disabled.

## Reduced motion

Respect reduced-motion preferences. Replace large spatial transitions with simpler fades/state changes when appropriate. Never make functionality depend on animation.

## Performance

Smooth simple motion beats complex janky motion. Avoid expensive continuous blur/layout work and do not block user input while decorative animation finishes.

## Evaluate the feel

Do not judge only screenshots. Tap, swipe, scroll, type, wait, complete, undo, dismiss, and navigate back.

If an interaction feels unusually good/bad and the cause is unclear, record it and replay slowly to inspect position, scale, opacity, timing, easing, and state changes.
