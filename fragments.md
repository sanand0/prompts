---
title: Fragments
model: Any
purpose: Prompt fragments useful to add to other prompts
---

## Brainstorming

Generate 5+ diverse candidate ideas. Score each on impact, ease, novelty. Recommend the best 1-2.
For brainstorming, ideation, evaluation, etc.
Other styles: SCAMPER, TRIZ, lateral thinking, etc.

## Style detection

Think about whose style of writing would be the most engaging and informative to write the following content.
List options, mentioning their style, why they're suitable, and pick the best, with reason.
Then rewrite it in their style.

## Malcolm Gladwell Style

Explain it like a Malcolm Gladwell New Yorker article.
For research papers, HN/Reddit/WhatsApp/Discord threads, other hard-to-digest content.
Other styles: Feynman, Tim Harford, Randall Munroe, etc. See [developer-styles.md](developer-styles.md).

## Read between Lines

Read between the lines and explore implications and trends
For press releases, contracts, policies.

## Best practices and ancient wisdom

Research best practices from modern research and ancient wisdom.
For advice on self-help, psychology, or anything timeless.

## Confession / Post-mortem

Did you fully address both the letter AND spirit of my question?
List any shortcuts taken, corners cut, or ways you optimized for appearing correct rather than being correct.
What did I actually want vs what you provided?

## Handling ambiguity

<!-- Unproven. From GPT 5.2 Prompting Guide -->

- If the question is ambiguous or underspecified, explicitly call this out and:
  - Ask up to 1–3 precise clarifying questions, OR
  - Present 2–3 plausible interpretations with clearly labeled assumptions.
  - When external facts may have changed recently (prices, releases, policies) and no tools are available, answer in general terms and state that details may have changed.

## Double-checking

<!-- Unproven. From GPT 5.2 Prompting Guide -->

- Briefly re-scan your own answer for
  - Unstated assumptions,
  - Specific numbers or claims not grounded in context,
  - Overly strong language (“always,” “guaranteed,” etc.).
- If you find any, soften or qualify them and explicitly state assumptions.

## Tool use

<!-- Unproven. From GPT 5.2 Prompting Guide -->

- Send brief updates (1–2 sentences) only when:
  - You start a new major phase of work, or
  - You discover something that changes the plan.
- Avoid narrating routine tool calls (“reading file…”, “running tests…”).
- Each update must include at least one concrete outcome (“Found X”, “Confirmed Y”, “Updated Z”).
- Parallelize independent reads (read_file, fetch_record, search_docs) when possible to reduce latency.
