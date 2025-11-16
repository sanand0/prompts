---
title: Developer Styles
model: Coding agents
purpose: Have an AI coding agent write in the style of popular developers.
source:
  - JavaScript: https://chatgpt.com/c/68d65e38-9d54-8331-9c7b-ff5c375c445a
  - Python: https://chatgpt.com/c/68d7fcb8-3154-8332-b373-ed07513938de
  - Non-fiction: https://chatgpt.com/c/68db73d0-edbc-8322-b7da-5fbda6e1e120
  - Art: https://sanand0.github.io/llmartstyle/
---

## JavaScript

- Luke Edwards (lukeed): "micro-libs, no fluff". Single-purpose modules; native ESM; minimal deps; straight-line code.
- Sindre Sorhus (sindresorhus): "tiny, sharp utilities". Minimal surface area, strong defaults, predictable names (`execa`, `ky`, `p-queue`, `globby`).
- Mike Bostock (mbostock): low-level primitives and _explicit_ data>element bindings (d3); clean diffs; example-driven; notebook-native workflows.
- Rich Harris (rich-harris): "compiler-as-framework". Write components; the compiler outputs minimal runtime. Emphasis on DX + shipping less JS.
- Tanner Linsley (tannerlinsley): "headless, type-safe primitives". Framework-agnostic cores + typed adapters; declarative APIs (Query/Router/Table) with strong devtools.
- Kent C. Dodds (kentcdodds): "user-centric testing". Avoid implementation details; integration-first tests; pragmatic full-stack co-location patterns.
- Addy Osmani (addyosmani): "performance patterns as first-class code". Ship less JS; progressive bootstrapping; pattern catalogs (patterns.dev) usable across stacks.
- Evan Wallace (evanw): "tooling as leverage". Single binary; clear CLI/JS APIs; fast defaults over heavy config.
- David Khourshid (davidkpiano): "formal, visual state". Event-first, finite machines, visual tools; framework-agnostic.
- Anthony Fu (antfu): "unplugin-everything; DX-first". Convention over config, on-demand utilities, editor-centric workflows.
- Paul Irish (paulirish): "performance-first, tooling-led frontend". SOTA baseline, then _measure_, iterate; progressive enhancement, dev-friendly diagnostics
- Sebastian McKenzie (sebmck): "language-aware tooling". Compiler-grade transforms; cohesive DX across parse/lint/format.
- Jarred Sumner (jarred-sumner): "integrated runtime thinking". Batteries-included; prioritize startup/memory; pragmatic Node compat.
- Matteo Collina (mcollina): "measure first; zero-overhead Node". Schema-driven, plugin-centric, perf-budgeted code; tight JSON/HTTP control.
- Jason Miller (developit): "small framework thinking". 3kB-class frameworks, compile-free JSX (`htm`), pragmatic trade-offs.
- Ryan Carniato (ryansolid): "fine-grained reactivity". Minimal abstractions around signals; control over reactivity graph; JSX without VDOM.

## Python

- Simon Willison (simonw): SQLite- and CLI-first data tooling: small composable utilities and plugins for reproducible data apps (`datasette`).
- Wes McKinney (wesm): Columnar & vectorized thinking: dataframes with performance pragmatism; Arrow/Ibis interoperability (`pandas`).
- David Beazley (dabeaz): Generators/coroutines and "pure Python first": clarity, teaching-driven code & tooling.
- Sebastian Ramirez (tiangolo): Type-hint-driven web apps: Pydantic models, async-first, auto-docs via OpenAPI-developer-ergonomics as a feature (`FastAPI`).
- Armin Ronacher (mitsuhiko): Pragmatic micro-frameworks: explicit APIs, tiny layers, superb DX across `Flask`/Jinja/Click-"simple first, escape hatches later."
- Will McGugan (willmcgugan): Terminal UX as a platform: expressive, declarative widgets & tracebacks (`rich`, `textual`).
- Samuel Colvin (samuelcolvin): Type-first data parsing/validation: dataclass-like models, speed, correctness at runtime (`pydantic`).
- Tom Christie (tomchristie): Spec-first HTTP/ASGI: small, composable building blocks with clean, typed APIs (`Starlette`, `HTTPX`, DRF).
- Hynek Schlawack (hynek): "Pragmatic robustness": explicit data classes, immutability, production-grade logging/retries (`attrs`, `structlog`, `stamina`).
- Kenneth Reitz (kennethreitz): Human-friendly HTTP: readable API, sensible defaults-"for humans" ethos (`requests`).
- Mike Bayer (zzzeek): SQL power with control: Core+ORM symmetry, dialect depth, explicitness over magic (`SQLAlchemy`).
- Andreas Muller (amueller): Consistent estimator API and careful defaults; pipelines that encourage good practice (`scikit-learn`).
- Jason R. Coombs (jaraco): Stdlib-aligned micro-libs and packaging hygiene; maintenance automation across many small projects.
- Brett Cannon (brettcannon): Import system & packaging correctness; small, well-documented utilities and process guidance.
- Andrew Svetlov (asvetlov): asyncio-native HTTP: backpressure-aware servers/clients with explicit control (`aiohttp`).
- Eric V. Smith (ericvsmith): Dataclasses for declarative data models-generated methods, typing-friendly, minimal boilerplate.
- Grant Jenks (grantjenks): Pure-Python performance with clean APIs; sorted collections "fast as C-extensions" (`sortedcontainers`).
- Bruno Oliveira (nicoddemus): Pytest ergonomics: fixtures/plugins that keep tests readable, fast, and scalable.
- Benoit Chesneau (benoitc): UNIX-style simplicity for web serving: pre-fork model, predictable ops (`gunicorn`).
- Andy McCurdy (andymccurdy): Thin, Pythonic client over a fast backend: predictable API and pragmatism for Redis (`redis-py`).

## Non-fiction

Explain/Write/Summarize in the style of ...

- Richard Feynman: Teaching first-principles thinking. Conversational, curious, strip problems to basics, use analogies and thought experiments to demystify.
- Malcolm Gladwell: Shifting lay mental models quickly. Narrative-driven, counterintuitive hooks; blend social science with parables and anecdotes.
- Isaac Asimov: Building broad scientific literacy fast. Encyclopedic, lucid, and straightforward; explain any topic clearly, step by step, with zero jargon.
- Randall Munroe: Executive one-pagers & FAQs. Dead-simple diagrams, stick-figure humor, and "explain like I'm five" text that makes hard ideas feel obvious.
- Bill Bryson: Inspiring curiosity & wonder. Amiable, witty "curious layman" voice; sprinkle trivia, humor, and awe to make science welcoming.
- David Macaulay: Diagram-first technical onboarding. Visual storytelling with annotated cut-aways, showing how hidden systems work step by step.
- Steven Strogatz: Bridging high-school math -> real world. Friendly and rigorous; walk readers through math with stories, metaphors, and gentle scaffolding.
- Martin Gardner: Teaching intuition via puzzles. Playful puzzles that reveal deeper math; warm, witty, Socratic style that nudges readers to discover.
- Oliver Sacks: Empathy-first medical/science comms. Case stories blending patient humanity with neuroscience; lyrical, humane, and anecdote-driven.
- Neil deGrasse Tyson: Public talks & space explainers. Conversational, pop-culture analogies, rhythmic phrasing, inviting readers to share cosmic awe.
- James Gleick: Context-rich tech/history explainers. Elegant prose tracing the history of ideas; connects abstract science to culture and narrative arcs.
- Steven Pinker: Evidence-based persuasion. Clear, data-heavy arguments; use charts, controlled vocabulary, and careful logic to build trust.
- Stephen Jay Gould: Nuanced debates & perspective-taking. Essayist voice mixing science, history, and metaphor; relish complexity while staying readable.
- Tim Harford: Policy/ops choices under constraints. Everyday stories unpacking incentives; engaging, conversational economics with sharp metaphors.
- Michael Lewis: Executive storytelling for complex markets. Narrative nonfiction built around characters; reveal systems (finance, sports, gov't) through story arcs.
- Mary Roach: Making "dry" topics irresistibly readable. Irreverent, curious, conversational; dive into taboo/overlooked corners with quirky questions.
- Hannah Fry: Applied data/AI to everyday life. Crisp, modern math/data explanations; balances rigor with storytelling and humor.
- Ed Yong: Crisis comms & public-health explainers. Clear, empathetic journalism; explain systems with human stakes and metaphorical clarity.
- Vaclav Smil: Policy/strategy grounded in physical reality. Dense, data-rich analysis; blunt, contrarian style focused on energy, food, and material limits.
- Jared Diamond: Framing civilization-scale questions. Sweeping synthesis of geography, biology, and history; grand-theory storytelling with cautionary tone.
- Matt Ridley: Big-picture synthesis. Cross-domain evolutionary/economic analogies; optimistic narratives about progress and innovation.
- Brian Greene: Explaining abstract math/physics. Careful metaphors and storytelling; bridge advanced physics to intuition without oversimplifying.
- Don Norman: UX principles for engineers & PMs. Plain, practical design psychology; clear rules on affordances, feedback, and usability.

## Art

- Frottage Technique: Draw in frottage technique style, with textured paper-rubbing effects, organic surface patterns, charcoal-like textures, layered rubbing marks.
- Decalcomania: Draw using decalcomania, with mirrored paint-transfer blotches, unpredictable organic textures, and accidental symmetry.
- Scumbling: Draw with translucent scumbled layers, soft cloudy transitions, visible underpainting, and an ethereal haze.
- Grattage: Draw with grattage scraping, revealing bright underlying colors, rough surface scratches, and layered paint excavation.
- Sgraffito: Draw in sgraffito style, scratching linear motifs through the surface to expose contrasting layers beneath.
- Soufflage (Blown Paint): Draw with blown-paint soufflage effects, wind-driven drips and splatters, airy dispersion, and organic branching forms.
- Paper-Cut Shadow Layering: Draw as layered paper-cut shadow art, crisp stacked silhouettes, precise cast shadows, and architectural depth.
- Stippling Mixed Media: Draw with dense stippling and mixed textures, micro-dots forming gradients, interleaved with paper, ink, or pastel accents.
- Digital Encaustic: Draw in a digital encaustic look, waxy flows, semi-translucent color pools, and molten, tactile surfaces.
- Textured Gesso Relief: Draw over textured gesso, sculptural low-relief ridges, impasto-like grooves, and tactile, light-catching surfaces.
- Mecanorma / Vintage French Collage: Draw as a Mecanorma collage, cut-and-paste printed textures and patterns with slight misregistration on grainy paper.
- Stained-Glass (Medieval / Folk): Draw as crude stained glass, thick black lead cames, segmented uneven color panes, and backlit luminosity.
- Xerox / Photocopy Aesthetic: Draw in Xerox copy-art style, high-contrast black-and-white, degraded midtones, gritty halftone noise, zine energy.
- Adinkra-Inspired Symbolism (Pseudo-Sankofa): Draw with West African Adinkra-style symbols, bold symmetry, dense patterned negatives, and red-black-gold palette.
- Frutiger Aero: Draw in a mid-2000s Frutiger Aero vibe, glossy skeuomorphism, glowing bubbles, clean skies and grass, nature-tech harmony.
- Psychedelic Op Art: Draw as psychedelic Op Art, precise geometric interference, moire vibrations, high-contrast illusions of motion and warp.
- Soviet Brutalist Poster: Draw a Soviet-brutalist poster, monumental geometry, limited red-black-cream palette, bold block typography, concrete grain.
- Trouvelot Astronomical Pastels: Draw like a 19th-century astronomical pastel, scientifically accurate celestial forms with soft luminous glows on textured paper.
- Dazzle Camouflage: Draw using WWI dazzle patterns, disruptive black-white geometry that fractures silhouette and confuses direction.
- Toba-e Caricature (Edo): Draw playful anthropomorphic animals in flowing brush lines, sparse color, and witty Edo-period caricature energy.
- Anamorphic Hidden Image: Draw an anamorphic illusion that resolves into a hidden portrait or symbol from a specific viewing angle.
- 'Bad Painting' Irreverent Figuration: Draw intentionally naive figures with flat planes, decorative patterns, and cheeky anti-polish attitude.
- Etched Gothic-Surreal Linework: Draw dense gothic-surreal line etchings, spired architectures and grotesques in obsessive cross-hatching.
- Doodle-Constructivist Architecture: Draw fantastical doodle-architecture, biomorphic buildings fused with everyday objects in exuberant schematic chaos.
- Nychos Street Mural (Anatomical Cross-Section): Draw a bold street-art mural showing skeletal anatomy beneath the surface, x-ray layers and high-contrast spray.
- Neo-Surreal Polished Macabre: Draw crisp neo-surreal scenes with uncanny body fragments, glossy finish, and quietly humorous dark undertones.
- Psychedelic Retro Poster ('60s): Draw a 1960s-style psychedelic poster, swirling saturated gradients, bold lettering forms, and subtle film-grain texture.
- Quantum Flux Patterns: Draw in a quantum-inspired style, with probabilistic wave-like forms, shimmering particle trails, and dynamic interference patterns that shift with perspective.
- Bioplastic Morphic Layers: Draw with translucent, organic bioplastic layers, fluid cellular structures, and soft bioluminescent gradients that mimic living tissue.
- Glitchtopian Relics: Draw as fragmented digital artifacts, with pixelated decay, corrupted data shards, and neon glitches forming futuristic relics.
- Aerochromatic Flux: Draw with iridescent, prismatic color shifts, fluid metallic sheens, and aerodynamic contours that evoke weightless energy flows.
- Neural Tapestry Weave: Draw as a neural network-inspired tapestry, with interconnected nodal threads, synaptic pulses, and evolving fractal patterns in muted tones.
- The Bengal School of Art: Draw in the Bengal School of Art style, with delicate Japanese wash watercolor layers, soft dreamlike atmospheres, sombre muted palettes, refined linear figures, and flattened miniature-inspired perspectives depicting mystical or symbolic scenes.
- Africobra: Draw in Africobra style, with vibrant coolade colors, rhythmic interlocking patterns, bold text and imagery, and powerful depictions of Black identity, community, and pride infused with positive energy.
- Stridentism (Estridentismo): Draw in Stridentism style, with dynamic fragmented lines, urban-industrial motifs like skyscrapers, machines, airplanes, and telegraph cables, woodcut-like bold contrasts, and irreverent, energetic compositions celebrating modernity and revolution.
- Gutai Group: Draw in Gutai Group style, emphasizing raw energy, explosive splatters, smeared textures, gouges, drips, and unconventional materials, capturing the physical force and bodily movement of performance-based creation.
- Ebru (Turkish Paper Marbling): Draw in Ebru marbling style, with floating pigments on liquid, combed into swirling veins, concentric organic forms, bleeding edges, and fluid unpredictable patterns resembling marble, smoke, or water.
- Pysanka Symbology: Draw in Pysanka style, with geometric wax-resist motifs, suns, stars, trees of life, birds, and eternity bands, structured into symmetrical sections, using symbolic colors like red, black, yellow, and green for dense talismanic patterns.
- Lowbrow (Pop Surrealism): Draw in Lowbrow Pop Surrealism style, with polished classical painting techniques applied to playful or grotesque cartoon-like characters, surreal juxtapositions, kitsch pop-culture icons, and satirical, humorous undertones.
- Algorithmic Beauty (Fractal Art): Draw in fractal art style, with infinitely recursive geometric spirals, self-similar branching forms, organic mathematical patterns, and intricate details resembling galaxies, coastlines, snowflakes, or tree growth.
- Vaporwave Aesthetics: Draw in Vaporwave style, with pastel pink and blue gradients, retro computer graphics, VHS glitch textures, Greco-Roman statues, obsolete 90s UI elements, palm trees, Japanese text, and a melancholic nostalgic mood.
- Risograph Texture: Draw in Risograph style, with limited vibrant spot colors, overprinted layers creating unexpected blends, halftone grainy textures, and charming imperfections like misaligned color registration and uneven ink coverage.
