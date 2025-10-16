---
title: Create an FAQ-style slide deck from a transcript
model: ChatGPT GPT-5 Thinking
purpose: Annotate transcripts with section summaries, creating FAQ-style slides from talks / AMAs.
---

Annotate this talk transcript by inserting slides (in Markdown) at logical breaks.

# Instructions

- Divide the transcript into logical sections covering one slide worth of content.
- Prefix each transcript section with a Markdown slide.
- Begin the slide with an H2 heading (≤10 words).
  - Use McKinsey-style action titles / newspaper-style headlines. They're insightful, useful takeaways for the reader.
  - Headings summarize the entire slide.
  - Headings, read together, string a cohesive story.
  - Write headings as an outline first. THEN fill in the slide bullets.
  - Preserve transcript order. Write slides in the same order as in the transcript.
- In each slide, add ≤5 bullet points, each ≤25 words, that support the H2 heading with content from the transcript.
  - Write simple, flowing, conversational prose as complete sentences.
  - Highlight in **bold** the top 1-3 phrases that address the slide heading directly, if applicable.
- Write as if the slides were written BEFORE the talk. Don't refer to participants.

Fact-checking and appendices:

- Searching online to fact-check each bullet. On errors, append an `(**Edit**: ...)` note to the bullet explaining the correction and link to the source. Link directly relevant and useful external references from bullet text. Use links sparingly.
- After each summary, include the first 10 words of the slide's relevent transcript inside a `<transcript>` tag to show where the summary is inserted.
- Add these appendix sections at the end:
  - Quiz. List ≤5 non-trivial quiz questions based on the content, each ≤25 words.
  - Errata. Fact-check every bullet points and list any corrections. Cite sources.
  - Counterpoints. Research and append alternative views to bullets. Cite sources.
  - Feedback. List ≤5 ways the speaker could improve clarity, engagement, or informativeness.

<OUTPUT-FORMAT>

## Summary of first slide (≤7 words)

- bullet point 1
- ...

<transcript>

first 10 words of the transcript for the first slide

</transcript>

---

## Summary of second slide (≤7 words)

- bullet point 1
- ...

<transcript>

first 10 words of the transcript for the second slide

</transcript>

...

</OUTPUT-FORMAT>

---

<!-- transcript goes here -->
