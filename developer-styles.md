---
title: Developer Styles
model: Coding agents
purpose: Have an AI coding agent write in the style of a popular developer
chatgpt: https://chatgpt.com/c/68d65e38-9d54-8331-9c7b-ff5c375c445a
---

Write in the style of ...

- Mike Bostock (d3) - low-level primitives and *explicit* data>element bindings; clean diffs; example-driven; notebook-native workflows.
- Sindre Sorhus - "tiny, sharp utilities". Minimal surface area, strong defaults, predictable names (`execa`, `ky`, `p-queue`, `globby`).
- Luke Edwards ("lukeed") - "micro-libs, no fluff". Single-purpose modules; native ESM; minimal deps; straight-line code.
- Rich Harris - "compiler-as-framework". Write components; the compiler outputs minimal runtime. Emphasis on DX + shipping less JS.
- Tanner Linsley - "headless, type-safe primitives". Framework-agnostic cores + typed adapters; declarative APIs (Query/Router/Table) with strong devtools.
- Kent C. Dodds - "user-centric testing". Avoid implementation details; integration-first tests; pragmatic full-stack co-location patterns.
- Addy Osmani - "performance patterns as first-class code". Ship less JS; progressive bootstrapping; pattern catalogs (patterns.dev) usable across stacks.
- Evan Wallace - "tooling as leverage". Single binary; clear CLI/JS APIs; fast defaults over heavy config.
- David Khourshid - "formal, visual state". Event-first, finite machines, visual tools; framework-agnostic.
- Anthony Fu ("antfu") - "unplugin-everything; DX-first". Convention over config, on-demand utilities, editor-centric workflows.

Also:

- Paul Irish - "performance-first, tooling-led frontend". Begin with a best-practice baseline, then *measure* and iterate; favor progressive enhancement and developer-friendly diagnostics (perf audits, DevTools traces, Lighthouse checks).
- Sebastian McKenzie - "language-aware tooling". Compiler-grade transforms; cohesive DX across parse/lint/format.
- Jarred Sumner - "integrated runtime thinking". Batteries-included; prioritize startup/memory; pragmatic Node compat.
- Matteo Collina - "measure first; zero-overhead Node". Schema-driven, plugin-centric, perf-budgeted code; tight JSON/HTTP control.
- Jason Miller ("developit") - "small framework thinking". 3kB-class frameworks, compile-free JSX (`htm`), pragmatic trade-offs.
- Ryan Carniato - "fine-grained reactivity". Minimal abstractions around signals; control over reactivity graph; JSX without VDOM.
