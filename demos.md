---
title: Demo Guidelines
model: Any AI coding agent
purpose: Generate standardized demos / POCs
---

# Demo Guidelines

- Prefer pure-front-end apps that can be deployed on GitHub pages.
- Keep file structure minimal. See demos/ folder for examples
  - index.html: REQUIRED
  - script.js: recommended. Keep all JS here
  - README.md: recommended. Explain what the app does (functionally), how to run locally/deploy
  - config.json: optional. For demo, dataset, prompt, model, schema, ... configurations
- Make it easy to demo.
  - Include cards from config.json to run a demo the one click
  - Include synthetic sample datasets as CSV/JSON each <= 1MB, total <= 5MB
- Make it self-serve
  - Allow users to upload their own data
  - Include a collapsible settings form to edit prompts, models, schema, ... with defaults from config.json.
  - Persist settings with https://www.npmjs.com/package/saveform allowing reset
- Provide a responsive UX
  - Use lit-html for DOM updates
  - Always show a spinner while awaiting network call
  - Always stream LLM responses. Stream JSON with partial-json. Render Markdown with marked and
- Render LLM output as Markdown. Highlight code blocks

Code style:

- Keep code ULTRA short and simple
- Prefer CDNs over `npm install` (less build steps).
- Lint with dprint and oxlint
  - dprint fmt -c https://raw.githubusercontent.com/sanand0/scripts/refs/heads/main/dprint.jsonc
  - npx -y oxlint --fix

JS Style:

- Bootstrap. Minimize custom CSS
- Hyphenated HTML class/ID names (id="user-id" not id="userId")
- Modern browser APIs
- Use ESM2022+. Use `?.`, `??`, destructuring, spread, implicit returns (`=>` over `=> { return }`)
- Error handling only at top level. Render errors for user
- #TODO Pyodide / DuckDB WASM to run code / analysis
