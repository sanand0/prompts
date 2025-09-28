---
title: Developer Styles
model: Coding agents
purpose: Have an AI coding agent write in the style of a popular developer
source:
  - JavaScript: https://chatgpt.com/c/68d65e38-9d54-8331-9c7b-ff5c375c445a
  - Python: https://chatgpt.com/c/68d7fcb8-3154-8332-b373-ed07513938de
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
