---
title: Developer Styles
model: Coding agents
purpose: Have an AI coding agent write in the style of a popular developer
source:
  - JavaScript: https://chatgpt.com/c/68d65e38-9d54-8331-9c7b-ff5c375c445a
  - Python: https://chatgpt.com/c/68d7fcb8-3154-8332-b373-ed07513938de
  - Non-fiction: https://chatgpt.com/c/68db73d0-edbc-8322-b7da-5fbda6e1e120
---

## JavaScript

| GitHub        | Name               | Style                                                                                                                                      |
| ------------- | ------------------ | ------------------------------------------------------------------------------------------------------------------------------------------ |
| lukeed        | Luke Edwards       | "micro-libs, no fluff". Single-purpose modules; native ESM; minimal deps; straight-line code.                                              |
| sindresorhus  | Sindre Sorhus      | "tiny, sharp utilities". Minimal surface area, strong defaults, predictable names (`execa`, `ky`, `p-queue`, `globby`).                    |
| mbostock      | Mike Bostock       | low-level primitives and _explicit_ data>element bindings (d3); clean diffs; example-driven; notebook-native workflows.                    |
| rich-harris   | Rich Harris        | "compiler-as-framework". Write components; the compiler outputs minimal runtime. Emphasis on DX + shipping less JS.                        |
| tannerlinsley | Tanner Linsley     | "headless, type-safe primitives". Framework-agnostic cores + typed adapters; declarative APIs (Query/Router/Table) with strong devtools.   |
| kentcdodds    | Kent C. Dodds      | "user-centric testing". Avoid implementation details; integration-first tests; pragmatic full-stack co-location patterns.                  |
| addyosmani    | Addy Osmani        | "performance patterns as first-class code". Ship less JS; progressive bootstrapping; pattern catalogs (patterns.dev) usable across stacks. |
| evanw         | Evan Wallace       | "tooling as leverage". Single binary; clear CLI/JS APIs; fast defaults over heavy config.                                                  |
| davidkpiano   | David Khourshid    | "formal, visual state". Event-first, finite machines, visual tools; framework-agnostic.                                                    |
| antfu         | Anthony Fu         | "unplugin-everything; DX-first". Convention over config, on-demand utilities, editor-centric workflows.                                    |
| paulirish     | Paul Irish         | "performance-first, tooling-led frontend". SOTA baseline, then _measure_, iterate; progressive enhancement, dev-friendly diagnostics       |
| sebmck        | Sebastian McKenzie | "language-aware tooling". Compiler-grade transforms; cohesive DX across parse/lint/format.                                                 |
| jarred-sumner | Jarred Sumner      | "integrated runtime thinking". Batteries-included; prioritize startup/memory; pragmatic Node compat.                                       |
| mcollina      | Matteo Collina     | "measure first; zero-overhead Node". Schema-driven, plugin-centric, perf-budgeted code; tight JSON/HTTP control.                           |
| developit     | Jason Miller       | "small framework thinking". 3kB-class frameworks, compile-free JSX (`htm`), pragmatic trade-offs.                                          |
| ryansolid     | Ryan Carniato      | "fine-grained reactivity". Minimal abstractions around signals; control over reactivity graph; JSX without VDOM.                           |

## Python

| GitHub       | Name              | Style                                                                                                                              |
| ------------ | ----------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| simonw       | Simon Willison    | SQLite- and CLI-first data tooling: small composable utilities and plugins for reproducible data apps (`datasette`).               |
| wesm         | Wes McKinney      | Columnar & vectorized thinking: dataframes with performance pragmatism; Arrow/Ibis interoperability (`pandas`).                    |
| dabeaz       | David Beazley     | Generators/coroutines and "pure Python first": clarity, teaching-driven code & tooling.                                            |
| tiangolo     | Sebastian Ramirez | Type-hint-driven web apps: Pydantic models, async-first, auto-docs via OpenAPI-developer-ergonomics as a feature (`FastAPI`).      |
| mitsuhiko    | Armin Ronacher    | Pragmatic micro-frameworks: explicit APIs, tiny layers, superb DX across `Flask`/Jinja/Click-"simple first, escape hatches later." |
| willmcgugan  | Will McGugan      | Terminal UX as a platform: expressive, declarative widgets & tracebacks (`rich`, `textual`).                                       |
| samuelcolvin | Samuel Colvin     | Type-first data parsing/validation: dataclass-like models, speed, correctness at runtime (`pydantic`).                             |
| tomchristie  | Tom Christie      | Spec-first HTTP/ASGI: small, composable building blocks with clean, typed APIs (`Starlette`, `HTTPX`, DRF).                        |
| hynek        | Hynek Schlawack   | "Pragmatic robustness": explicit data classes, immutability, production-grade logging/retries (`attrs`, `structlog`, `stamina`).   |
| kennethreitz | Kenneth Reitz     | Human-friendly HTTP: readable API, sensible defaults-"for humans" ethos (`requests`).                                              |
| zzzeek       | Mike Bayer        | SQL power with control: Core+ORM symmetry, dialect depth, explicitness over magic (`SQLAlchemy`).                                  |
| amueller     | Andreas Muller    | Consistent estimator API and careful defaults; pipelines that encourage good practice (`scikit-learn`).                            |
| jaraco       | Jason R. Coombs   | Stdlib-aligned micro-libs and packaging hygiene; maintenance automation across many small projects.                                |
| brettcannon  | Brett Cannon      | Import system & packaging correctness; small, well-documented utilities and process guidance.                                      |
| asvetlov     | Andrew Svetlov    | asyncio-native HTTP: backpressure-aware servers/clients with explicit control (`aiohttp`).                                         |
| ericvsmith   | Eric V. Smith     | Dataclasses for declarative data models-generated methods, typing-friendly, minimal boilerplate.                                   |
| grantjenks   | Grant Jenks       | Pure-Python performance with clean APIs; sorted collections "fast as C-extensions" (`sortedcontainers`).                           |
| nicoddemus   | Bruno Oliveira    | Pytest ergonomics: fixtures/plugins that keep tests readable, fast, and scalable.                                                  |
| benoitc      | Benoit Chesneau   | UNIX-style simplicity for web serving: pre-fork model, predictable ops (`gunicorn`).                                               |
| andymccurdy  | Andy McCurdy      | Thin, Pythonic client over a fast backend: predictable API and pragmatism for Redis (`redis-py`).                                  |

## Non-fiction

| Author              | Task                                         | Style                                                                                                          |
| ------------------- | -------------------------------------------- | -------------------------------------------------------------------------------------------------------------- |
| Richard Feynman     | Teaching first-principles thinking           | Conversational, curious, strip problems to basics, use analogies and thought experiments to demystify.         |
| Randall Munroe      | Executive one-pagers & FAQs                  | Dead-simple diagrams, stick-figure humor, and "explain like I'm five" text that makes hard ideas feel obvious. |
| Bill Bryson         | Inspiring curiosity & wonder                 | Amiable, witty "curious layman" voice; sprinkle trivia, humor, and awe to make science welcoming.              |
| David Macaulay      | Diagram-first technical onboarding           | Visual storytelling with annotated cut-aways, showing how hidden systems work step by step.                    |
| Steven Strogatz     | Bridging high-school math -> real world      | Friendly and rigorous; walk readers through math with stories, metaphors, and gentle scaffolding.              |
| Martin Gardner      | Teaching intuition via puzzles               | Playful puzzles that reveal deeper math; warm, witty, Socratic style that nudges readers to discover.          |
| Oliver Sacks        | Empathy-first medical/science comms          | Case stories blending patient humanity with neuroscience; lyrical, humane, and anecdote-driven.                |
| Neil deGrasse Tyson | Public talks & space explainers              | Conversational, pop-culture analogies, rhythmic phrasing, inviting readers to share cosmic awe.                |
| James Gleick        | Context-rich tech/history explainers         | Elegant prose tracing the history of ideas; connects abstract science to culture and narrative arcs.           |
| Steven Pinker       | Evidence-based persuasion                    | Clear, data-heavy arguments; use charts, controlled vocabulary, and careful logic to build trust.              |
| Stephen Jay Gould   | Nuanced debates & perspective-taking         | Essayist voice mixing science, history, and metaphor; relish complexity while staying readable.                |
| Tim Harford         | Policy/ops choices under constraints         | Everyday stories unpacking incentives; engaging, conversational economics with sharp metaphors.                |
| Michael Lewis       | Executive storytelling for complex markets   | Narrative nonfiction built around characters; reveal systems (finance, sports, gov't) through story arcs.      |
| Mary Roach          | Making "dry" topics irresistibly readable    | Irreverent, curious, conversational; dive into taboo/overlooked corners with quirky questions.                 |
| Hannah Fry          | Applied data/AI to everyday life             | Crisp, modern math/data explanations; balances rigor with storytelling and humor.                              |
| Ed Yong             | Crisis comms & public-health explainers      | Clear, empathetic journalism; explain systems with human stakes and metaphorical clarity.                      |
| Vaclav Smil         | Policy/strategy grounded in physical reality | Dense, data-rich analysis; blunt, contrarian style focused on energy, food, and material limits.               |
| Jared Diamond       | Framing civilization-scale questions         | Sweeping synthesis of geography, biology, and history; grand-theory storytelling with cautionary tone.         |
| Matt Ridley         | Big-picture synthesis                        | Cross-domain evolutionary/economic analogies; optimistic narratives about progress and innovation.             |
| Brian Greene        | Explaining abstract math/physics             | Careful metaphors and storytelling; bridge advanced physics to intuition without oversimplifying.              |
| Don Norman          | UX principles for engineers & PMs            | Plain, practical design psychology; clear rules on affordances, feedback, and usability.                       |
| Isaac Asimov        | Building broad scientific literacy fast      | Encyclopedic, lucid, and straightforward; explain any topic clearly, step by step, with zero jargon.           |
| Malcolm Gladwell    | Shifting lay mental models quickly           | Narrative-driven, counterintuitive hooks; blend social science with parables and anecdotes.                    |
