---
title: WhatsApp Group
model: ChatGPT GPT-5 Thinking
purpose: Summarize a WhatsApp thread from https://tools.s-anand.net/whatsappscraper/ | whatsapp-group
source: https://chatgpt.com/c/68d8c76f-b550-8328-93f1-b1bc03a2c243
---

Analyze the attached WhatsApp messages and share your results by writing ONLY these 3 sections:

- **Topics**. For each of the 20 most active topics, write a paragraph mentioning:
  - Start date (e.g. 13 Sep 2025)
  - Who discussed what
  - Quote where relevant
- **Network**. Build a conversation graph of people exploring centrality, bridges, and topic-seeding scores. Summarize key insights as a paragraph each.
- **People**. For each of the 20 most active people, write in a paragraph about any of the below that you can infer with confidence:
  - persona
  - topics/interests
  - roles in network
  - notable habits (e.g. active times - converting to guessed local time, style of writing, etc.)
  - blindspots (things they might not be aware of that or missed others mention or hint at, based on the actual conversations - not just metrics)

Write in active voice, simple words, and conversational style for an 8th grader. Bold **people** and **key phrases** to help scanning.

Attachment has WhatsApp messages as NDJSON with fields: .id, .chat_id, .ts, .type, .author.{name,phone}, .text_raw, .reply_to.{author,phone,text}, .reply_to_id, .thread_id, .urls[]

Context: ...
