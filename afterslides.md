---
title: Create an FAQ-style slide deck from a transcript
model: ChatGPT GPT-5 Thinking
purpose: Annotate transcripts with section summaries, creating FAQ-style slides from talks / AMAs.
---

Annotate this talk transcript by inserting slides (in Markdown) at logical breaks.

Instructions

- Divide the transcript into logical sections covering one slide worth of content. Preserve the transcript order.
- Prefix each transcript section with a Markdown slide.
- Write as if the slides were written BEFORE the talk. Don't refer to participants.
- Use simple language as if explaining the concept to a student.
- Begin the slide with an H2 heading (≤10 words) that makes a declarative assertion.
  - Write as a complete sentence stating a finding, insight, or claim.
  - Use the Pyramid Principle: each title should answer "So what?" with a clear point of view (preferably with reason)
  - Use plain, conversational language: "makes it easy" not "reduces friction", "lets you" not "enables".
  - You may use "we" or "you" sparingly if it makes the title more direct and natural.
  - Don't condense into telegraphic fragments, punctuation, abbreviations, etc.
  - Example: Not "Choose right tool; improve setup" but "Improve set up by choosing the right tool".
  - Prefer concrete subjects and active verbs over abstract nouns and linking verbs.
  - Example: Not "Edge cases justify synthetic data" but "Synthetic data lets you test rare edge cases".
- Write headings as an outline. **Verify**. See if it forms a complete, cohesive story covering the entire transcript.
- Begin the slide with an H2 heading (≤10 words) that captures the core insight or action.
- Write each slide, add 3-5 supporting statements based on the transcript, each ≤30 words.
  - Highlight in **bold** the top 1-3 phrases that most closely support the slide heading, if applicable.
  - Prefer augmenting the claim with a brief reason, impact, or implication ("what / why / so what").
  - Incorporate content references / links if provided below.
  - Add a `<transcript>` tag with the first 10 words of transcript for this slide to mark the position.

Append these slides:

- Quiz. List ≤5 non-trivial quiz questions based on the content, each ≤25 words.
- Errata. Fact-check every supporting statement and list all corrections (≤5 per slide, ≤30 words each). Cite sources.
- Counterpoints. Research and append alternative views to the content (≤5 per slide, ≤30 words each). Cite sources.
- Feedback. List ≤5 ways the speaker could improve clarity, engagement, or informativeness.

<OUTPUT-FORMAT>

## Outline

- (Summary of first slide)
- (Summary of second slide)
- ...

## (Summary of first slide)

- (Supporting statement)
- ...

<transcript>

(first 10 words of the transcript for the first slide)

</transcript>

---

## (Summary of second slide)

- (Supporting statement)
- ...

<transcript>

(first 10 words of the transcript for the second slide)

</transcript>

...

</OUTPUT-FORMAT>

---

<CONTENT-REFERENCES>

<!-- PLACEHOLDER: include content references if any -->

</CONTENT-REFERENCES>

---

## Transcript

<!-- PLACEHOLDER: include transcript here -->
