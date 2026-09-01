# 03 — States, Context & Feedback

## Always design states

For important screens consider:
- populated;
- first-use empty;
- search-no-results;
- loading;
- processing;
- error;
- offline where relevant;
- keyboard-open;
- long-content.

## First-use empty state

Focus on the main action. Use a concise explanation, optional illustration, primary CTA, and minimal guidance. Avoid filling the screen with dead placeholder cards.

## Search empty state

Acknowledge the failed search, reference the term when useful, suggest correction/filter changes, and give a clear next action.

## Processing states

Do not treat AI or network work as a blank waiting period. When real stages exist, communicate them at the user's mental-model level.

Example:
- Analyzing meal…
- Matching foods…
- Calculating nutrition…
- Result

Do not fake precise progress.

## Processing builds trust

Meaningful intermediate states can make AI workflows feel less opaque. Prefer user-facing process language over technical implementation details.

## Reduce uncertainty before commitment

When the resulting value matters, include it in or near the CTA when useful.

Examples:
- Subscribe · €4.99/month
- Start 30 min workout
- Add · €12.80

Do not overload every CTA with metadata.

## Proximity communicates meaning

Place conceptually linked information together:
- title + rating;
- calories + remaining amount;
- quantity + purchase action;
- meal input + log action.

Users should not mentally connect distant elements.

## Separate identity from mutable state

Do not embed user-changeable state inside a permanent object title if that can become misleading.

Prefer:
- Chicken breast
- 200 g selected

instead of treating both as one fixed identity.

## Remove redundant visible labels

If context already communicates meaning, avoid repetitive visible labels. Preserve semantic accessibility labels even when visual labels are removed.
