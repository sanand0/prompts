---
Source:
  - Preferences https://chatgpt.com/c/68c77466-eaa4-832f-aedc-b95f2b27922c
  - Prompt optimization https://chatgpt.com/c/68c62e60-3dd0-8328-a3df-2cdd2e90bb7c
---

Evaluate ________.

## Instructions

- Research and summarize what it does.
- List the closest alternatives.
- Evaluate it on the following criteria, depending on the type of technology:
  - CLI tool: popular, fast, lightweight, intuitive, easy setup, scriptable, good docs, preferably single-binary.
  - API/Service: popular, open-source, cost, liberal free tier, self-hostable, fast, lightweight, intuitive, easy auth, easy setup, good docs, extensible, REST API.
- Share the results as a table.

Be rigorous. **Verify and cite sources with dates.** Prefer primary docs, changelogs, and benchmarks. When unsure, state assumptions and offer 1-2 clarifying questions _up front_. If evidence is weak, **say so** and (if easy) propose ways to gather evidence.

GENERAL PREFERENCES (use if applicable)

- CLI > Web app > Native app
- OSS > Free > Cheap > Expensive
- File formats: Fast + Popular > Open standards > Proprietary
- Updated recently (date of latest release) + regularly (# releases last 12 months)
- Well documented with concise, practical examples
- Popular (# contributors / users)
- Speed of operation and low resource usage
- Minimalism
- Scriptable/automatable
- Data-driven configuration/declarative approaches > imperative code
- Modular > monolith
- Declarative outputs
- Browser-first JS + Python
- Cross-platform
- Single-binary, headless, portable
- Privacy: No telemetry, data export, offline capable, self-hostable
- Stable APIs with migration path
- Strong plugin ecosystem
- Easy install/uninstall with clean removal

ADDITIONAL CATEGORY-SPECIFIC CHECKS #TODO

- PLATFORM: data export; vendor lock-in risk; API stability; cost; clear pricing.
- SERVICES: uptime history; support quality; cost; clear pricing; terms of service.
- MODEL: cost; evals (name+date+link); context length; throughput; license; docs.
- LIBRARY/FRAMEWORK: learning curve; supported runtimes; semver; ABI/wheels; dependency tree; bundle size/tree-shaking; plugin system; community size; migration tools.
- DATASET: license; PII risk; size & splits; update cadence; schema stability; checksum.
- TECHNIQUE: reproducibility; sample prompts; ablations; compute cost deltas; failure modes & countermeasures.
