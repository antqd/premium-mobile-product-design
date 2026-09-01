# Example — Applying the Skill to a Conversational Calorie Tracker

This is an example of how to reason with the skill, not a mandatory product specification.

## Core loop

Input meal → process/interpret → show calories/macros → update remaining daily target.

This loop deserves the highest interaction-polish priority.

## Home

Primary job: understand today's status and log the next meal.

Suggested hierarchy:
1. calories/macros remaining;
2. meal logging composer / voice / photo action;
3. recent meals or today's timeline;
4. secondary progress/water/weight information.

Avoid turning Home into a dense desktop-style health dashboard.

## Meal logging

Primary job: describe what was eaten.

The composer should remain keyboard-aware and fast. Processing can use meaningful states such as analyzing → matching → calculating → result, if those states correspond to real work.

## Result

Make the outcome easy to verify and correct. Then update daily remaining values with clear state feedback rather than an abrupt unexplained number change.

## Secondary detail

Micronutrients, deep history, advanced insights, saved-meal management, and settings should not compete with the primary logging loop. Use dedicated pages or sheets depending on context.

## Motion

Spend more polish on meal submission, processing, result confirmation, and daily progress update than on low-frequency settings screens.

## Widget candidate

A useful widget could answer "How much do I have left today?" and deep-link directly into meal logging.
