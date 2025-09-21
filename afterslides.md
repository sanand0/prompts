---
title: Create an FAQ-style slide deck from a transcript
model: ChatGPT GPT-5 Thinking
purpose: Annotate transcripts with section summaries, creating FAQ-style slides from talks / AMAs.
---

Annotate this talk transcript by inserting FAQ-style section summaries at logical breaks.

# Instructions

- Divide the transcript into logical sections, each covering one topic.
- Before each transcript section, insert a Markdown summary.
- Begin the summary with an H2 heading (≤7 words). If the section answers a question, summarize the question as the heading.
- Then add ≤5 bullet points, each ≤25 words, that directly answer the question using content from the transcript.
- Write bullets as complete sentences.
- Mimic the transcript style in the bullets, e.g. first person, casual tone.
- Highlight in **bold** the top 1-3 phrases that address the section heading directly, if applicable.
- Searching online to fact-check each bullet. On errors, append an `(**Edit**: ...)` note to the bullet explaining the correction and link to the source. Link directly relevant and useful external references from bullet text. Use links sparingly.
- After each summary, include the first 10 words of that section's transcript inside a `<transcript>` tag to show where the summary is inserted.
- Add these sections at the end:
  - Quiz. List ≤5 non-trivial quiz questions based on the content, each ≤25 words.
  - Errata. Fact-check every bullet points and list any corrections. Cite sources.
  - Counterpoints. Research and append alternative views to bullets. Cite sources.
  - Feedback. List ≤5 ways the speaker could improve clarity, engagement, or informativeness.
- Preserve the order of the transcript. Write sections in the same order as in the transcript.

<OUTPUT-FORMAT>

## Summary of first section (≤7 words)

- bullet point 1
- ...

<transcript>

first 10 words of the transcript for the first section

</transcript>

---

## Summary of second section (≤7 words)

- bullet point 1
- ...

<transcript>

first 10 words of the transcript for the second section

</transcript>

...

</OUTPUT-FORMAT>

---
