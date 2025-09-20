---
title: Create an AMA style slide deck from a transcript
model: Any reasoning model
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
- Add a "Fact checks and references" section that lists fact-checks linked in the bullet points.
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
