# Staffman — Portfolio Case Notes

## Case type

Historical HR / enterprise product presentation artifact focused on landing-page motion and Lottie / Bodymovin handoff.

## What this repository proves

- motion design for a product landing experience;
- Lottie / Bodymovin export workflow;
- interaction / animation thinking for web delivery;
- ability to prepare design assets for implementation and stakeholder review.

## What it does not prove

This repository is not the Staffman application source. It contains a generated animation demo, not the product frontend, backend, database, authentication or business logic.

## Suggested current portfolio framing

**Context** — Staffman was an HR / enterprise product context in which motion and presentation were part of the design work.

**Role** — Product / UI design and motion-design contribution. Keep engineering claims limited to what the repository actually contains.

**Artifact** — A self-contained Bodymovin / Lottie web export used to preview or hand off landing-page animation.

**Value** — Demonstrates that interaction and motion were treated as part of the product presentation rather than as decorative afterthoughts.

## 10 improvement tasks for this repository

1. Keep the existing generated demo intact as archival evidence.
2. Add explicit portfolio / authorship boundaries.
3. Document how to run the demo locally.
4. Clarify that `demo.html` is generated output, not maintainable application source.
5. Add a modern case-study summary for recruiters and reviewers.
6. Capture desktop and mobile screenshots from the animation for durable portfolio evidence.
7. Extract the animation payload into a standalone JSON asset if the project is modernized.
8. Replace the embedded runtime with a pinned external dependency in any modern recreation.
9. Add accessibility guidance for reduced-motion users in a future implementation.
10. Verify client, image, font and animation rights before public redistribution.

## Recommended modernization

If the animation is rebuilt, use a minimal static or React wrapper with:

- `prefers-reduced-motion` support;
- explicit play / pause behavior if the animation carries information;
- responsive sizing;
- a separately versioned animation asset;
- a lightweight pinned Lottie dependency;
- no claim that this archive is the complete Staffman application.
