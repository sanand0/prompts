---
title: Create an FAQ-style slide deck from a transcript
model: ChatGPT GPT-5 Thinking
purpose: Annotate transcripts with section summaries, creating FAQ-style slides from talks / AMAs.
---

Annotate this talk transcript by inserting slides (in Markdown) at logical breaks.

# Instructions

- Divide the transcript into logical sections covering one slide worth of content. Preserve the transcript order.
- Prefix each transcript section with a Markdown slide.
- Write as if the slides were written BEFORE the talk. Don't refer to participants.
- Begin the slide with an H2 heading (≤10 words) that captures the core insight or action.
  - Use McKinsey-style action titles: insightful, useful takeaways for the reader.
  - Avoid vague verbs like "explore" or placeholders like "next steps" or "introduction". State the actual insight or directive.
  - First, write headings as an outline.
- **Verify outline**. Read the outline. See if it forms a complete, cohesive story covering the entire transcript.
- In each slide, add ≤5 supporting statements based on the transcript, each ≤30 words.
  - Highlight in **bold** the top 1-3 phrases that most closely support the slide heading, if applicable.
  - Prefer augmenting the claim with a brief reason, impact, or implication ("what / why / so what").

# Style

- Write headings and bullets as complete sentences. Avoid telegraphic fragments, semicolons, abbreviations, or anything you wouldn't find in a book.
- Use natural, flowing language as if explaining the concept to a colleague.

# Fact-checking and appendices

- Searching online to fact-check each bullet. On errors, append an `(**Edit**: ...)` note to the bullet explaining the correction and link to the source. Link directly relevant and useful external references from bullet text. Use links sparingly.
- After each summary, include the first 10 words of the slide's relevant transcript inside a `<transcript>` tag to show where the summary is inserted.
- Add these appendix sections at the end:
  - Quiz. List ≤5 non-trivial quiz questions based on the content, each ≤25 words.
  - Errata. Fact-check every supporting statement and list any corrections. Cite sources.
  - Counterpoints. Research and append alternative views to bullets. Cite sources.
  - Feedback. List ≤5 ways the speaker could improve clarity, engagement, or informativeness.

<OUTPUT-FORMAT>

## Summary of first slide (≤10 words)

- Supporting statement 1
- ...

<transcript>

first 10 words of the transcript for the first slide

</transcript>

---

## Summary of second slide (≤10 words)

- Supporting statement 1
- ...

<transcript>

first 10 words of the transcript for the second slide

</transcript>

...

</OUTPUT-FORMAT>

---

## Transcript

<!-- transcript goes here -->
