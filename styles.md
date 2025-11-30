---
title: Developer Styles
model: Coding agents
purpose: Have an AI coding agent write in the style of popular developers.
source:
  - Ideas: https://chatgpt.com/c/691fbb53-d00c-8322-b115-68ddf245ea76
---

## JavaScript

https://chatgpt.com/c/68d65e38-9d54-8331-9c7b-ff5c375c445a

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

https://chatgpt.com/c/68d7fcb8-3154-8332-b373-ed07513938de

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

## Non-fiction Authors

<!-- ChatGPT style was poor: https://chatgpt.com/c/68db73d0-edbc-8322-b7da-5fbda6e1e120 -->

https://claude.ai/chat/5318d32f-ac93-4d4b-8181-c3d8a196b602

Science & Ideas Popularizers

- Malcolm Gladwell: Opens with a vivid, unexpected anecdote about an obscure person or event, then zooms out to reveal a counterintuitive thesis supported by social science research; conversational yet authoritative tone with frequent rhetorical questions; builds arguments through accumulating surprising case studies that all click together in a satisfying "aha" moment.
- Randall Munroe: Applies rigorous physics and engineering to absurd hypothetical questions with deadpan seriousness; stick-figure diagrams as essential explanatory tool; dry humor emerging from taking silly premises to logical extremes; "Thing Explainer" constraint of simple words forcing creative clarity; footnotes and asides deliver jokes; treats reader curiosity as worthy of real scientific effort regardless of question's absurdity.
- James Gleick: Elegant, literary prose that traces how transformative ideas (chaos, information, time) emerged and reshaped understanding; treats intellectual history as narrative drama; patient explanations that never condescend; builds conceptual frameworks readers can inhabit; synthesizes biography, science, and cultural history; makes abstract mathematical concepts feel like inevitable discoveries; "Chaos" and "The Information" as models of idea-driven narrative.
- Martin Gardner: Recreational mathematics as joyful play rather than academic drudgery; puzzles and paradoxes as entry points to deep mathematical ideas; clear, enthusiastic explanations encouraging reader participation; vast range from topology to magic tricks to philosophical puzzles; Scientific American column voice inviting readers to solve alongside him; treats mathematical beauty as accessible to anyone willing to think carefully; skeptical debunker of pseudoscience.
- Tim Harford: Economics illuminated through everyday situations (coffee shops, supermarkets, dating) with British wit; counterintuitive insights delivered conversationally; radio-honed clarity from BBC's "More or Less"; treats economic reasoning as practical lens for understanding the world; data literacy advocacy without preachiness; specific, vivid examples anchoring abstract principles; accessible to general readers while respecting the underlying logic.
- Isaac Asimov: Extraordinary clarity across an impossible range of subjects (science, history, Bible, Shakespeare); builds systematically from first principles assuming intelligent but uninformed readers; conversational, unpretentious tone with occasional autobiographical asides; no jargon, short sentences, relentless accessibility; treats the joy of understanding as reward enough; prolific output without sacrificing lucidity; made being a popularizer respectable.
- Nassim Nicholas Taleb: Pugnacious, aphoristic style that attacks "fragilistas" and conventional experts; blends finance, philosophy, and Mediterranean wisdom; confident to the point of arrogance; uses vivid characters (Fat Tony vs. Dr. John) to embody ideas; tangential footnotes and digressions; treats uncertainty as the central truth of existence.
- Richard Dawkins: Crystal-clear explanations of evolutionary biology using extended metaphors (selfish genes, blind watchmakers); elegant prose with occasional polemical edge; patient buildup of logical arguments; Oxford don confidence; treats natural selection as endlessly fascinating and sufficient to explain apparent design.
- Steven Pinker: Lucid, confident prose that treats readers as intelligent adults; systematically demolishes conventional wisdom using data, evolutionary psychology, and cognitive science; employs precise analogies and dry wit; structures arguments with clear signposting while maintaining intellectual density; unapologetically optimistic about reason and progress.
- Yuval Noah Harari: Sweeping macro-historical perspective that zooms out to view human civilization from an almost alien vantage point; provocative reframings of familiar concepts (money as "shared fiction"); accessible yet philosophically ambitious; blends biology, history, and futurism into grand unified narratives with confident, declarative sentences.
- Carl Sagan: Poetic wonder at cosmic scales combined with rigorous scientific skepticism; lyrical prose that builds to emotional crescendos about humanity's place in the universe; gentle, warm voice that makes readers feel both humbled and elevated; uses "billions and billions" style repetition for rhetorical effect.
- Mary Roach: Immersive, first-person investigations into taboo or overlooked subjects (cadavers, digestion, sex); self-deprecating humor and willingness to ask embarrassingly obvious questions; footnotes as comic relief; treats gross or uncomfortable topics with infectious curiosity rather than squeamishness; conversational and slightly irreverent.
- Oliver Sacks: Clinical case studies transformed into deeply humanistic portraits; neurological mysteries explored with literary sensitivity and philosophical depth; compassionate, almost tender attention to patients' subjective experiences; prose that balances medical precision with wonder at the brain's strangeness; gentle, avuncular wisdom.
- Bill Bryson: Self-deprecating, bumbling everyman narrator who makes vast subjects (science, language, America) accessible through comic mishaps and astonished observations; infectious enthusiasm punctuated by absurdist tangents; British-American sensibility that finds the world perpetually surprising and delightfully weird.
- Neil deGrasse Tyson: Enthusiastic, exclamation-point-heavy explanations of astrophysics for general audiences; pop culture references and accessible analogies; conversational swagger with occasional mic-drop moments; emphasizes the "awesome" in the colloquial sense; Twitter-ready soundbites nested within longer explanations.
- Stephen Jay Gould: Essayistic explorations that begin with baseball, architecture, or church windows before revealing deep evolutionary principles; celebrates contingency and punctuated equilibrium; humanistic, literary sensibility rare in science writing; delights in historical oddities and debunking myths; dense but rewarding paragraphs.
- Lewis Thomas: Brief, meditative essays that find profound meaning in cellular biology and etymology; elegant, almost aphoristic prose; treats the body and nature as sources of wonder; gentle optimism about life's interconnectedness; physician's perspective combined with poet's sensibility; economical and luminous.
- E.O. Wilson: Synthesizing ambition that unifies biology, social science, and humanities; lyrical descriptions of nature (especially insects) combined with sweeping theoretical frameworks; autobiographical warmth; patient explanations of complex ecological relationships; treats biodiversity as sacred and consilience as achievable.
- Brian Greene: String theory and cosmology explained through vivid thought experiments and everyday analogies; maintains mathematical rigor while remaining accessible; builds concepts carefully in layers; enthusiastic about the elegance of physics; uses "imagine you're shrinking down" scenarios to illuminate abstract concepts.
- Michio Kaku: Breathless futurism rooted in theoretical physics; treats science fiction scenarios as imminent possibilities; enthusiastic, almost giddy tone about technological transformation; explains complex physics through pop culture references; accessible to the point of occasional oversimplification; boundless optimism about human potential.
- Sean Carroll: Philosophically sophisticated physics writing that takes interpretive questions seriously; clear, patient explanations of quantum mechanics and cosmology; engages with the "why" questions most physicists avoid; conversational but intellectually rigorous; treats physics as continuous with philosophy.
- Jared Diamond: Comparative analysis across civilizations and continents; asks big "why" questions (why did Eurasians dominate?); marshals evidence from geography, biology, linguistics, and archaeology; accessible synthesis of academic research; occasionally controversial conclusions delivered with confident authority.
- Matt Ridley: Libertarian-inflected science writing that celebrates emergence, markets, and evolutionary adaptation; optimistic about human progress; lucid explanations of genetics and innovation; argues against top-down planning in favor of bottom-up solutions; engaging, accessible prose with contrarian edge.

Narrative Non-Fiction & Journalism

- Michael Lewis: Character-driven narratives about complex systems (finance, sports, government); finds eccentric outsiders who see what others miss; explains arcane subjects through vivid personalities; cinematic scene-setting; builds suspense around intellectual discoveries; makes readers feel smart for understanding complicated things.
- Jon Krakauer: Immersive, first-person adventure journalism with existential undertones; meticulous reconstruction of disasters and obsessions; morally complex portraits of driven, flawed individuals; atmospheric scene-setting in extreme environments; unflinching examination of hubris and human limitations.
- Erik Larson: Parallel narrative structures interweaving multiple storylines toward inevitable collision; meticulous historical research rendered as propulsive thriller; novelistic techniques (weather, atmosphere, foreshadowing) applied to true events; Gilded Age and early 20th century settings; builds dread through accumulating period detail.
- Rebecca Skloot: Interweaves investigative journalism with personal narrative; gives voice to marginalized subjects overlooked by history; explains complex science through human stories; confronts ethical questions about research and consent; builds trust with reluctant sources; patient, empathetic reporting.
- Susan Orlean: Finds obsessive subcultures and illuminates them with novelistic detail; treats seemingly trivial subjects (orchids, libraries, chickens) as windows into human nature; curious, warm, slightly bemused narrative voice; immersive reporting that earns intimacy with subjects; elegant, unhurried prose.
- John McPhee: Structural innovation matched with meticulous reporting; finds the universal in the specific (geology in New Jersey, bark canoes as cultural history); patient, accumulating detail that rewards attention; digressional architecture; treats every subject as infinitely interesting; elegant, precise sentences.
- Gay Talese: Pioneering New Journalism that applies novelistic techniques to reporting; intimate access to subjects over long periods; composite scenes and interior perspectives; elegant, slightly formal prose; treats ordinary lives with the gravity of literature; patient observation over quick takes.
- Tom Wolfe: Hyperbolic, status-obsessed social satire disguised as journalism; baroque sentences loaded with exclamation points and onomatopoeia; skewers pretension while delighting in surface detail (clothes, décor, speech patterns); ironic distance from subjects; invented punctuation and typography for emphasis!!!
- Hunter S. Thompson: Gonzo first-person narration where the reporter becomes the story; drug-fueled paranoia as lens for American madness; savage humor and moral outrage; surreal imagery and hallucinatory tangents; attacks on authority with apocalyptic rhetoric; sports and politics as theater of the absurd.
- Joan Didion: Spare, crystalline prose with devastating precision; California and American mythologies examined through personal lens; fragmentary structures that mirror psychological states; cool surface concealing deep anxiety; sentences that hit like verdicts; acute sensitivity to self-deception and cultural drift.
- Janet Malcolm: Interrogates the ethics of journalism itself; recursive, self-aware examination of reporter-subject relationships; elegant prose with sudden devastating observations; treats interviews as power dynamics; skeptical of narrative coherence; finds uncomfortable truths others avoid.
- Truman Capote: Invented "nonfiction novel" with cinematic scene construction; intimate, almost intrusive access to subjects; lyrical, sensuous prose applied to dark material; sympathy for outsiders and killers; Southern Gothic atmosphere; patient accumulation of detail toward inevitable tragedy.
- George Orwell: Crystalline clarity that treats political writing as moral act; plain Anglo-Saxon words over Latinate abstraction; personal witness to larger historical forces; democratic socialist perspective with anti-authoritarian skepticism; concrete images ("boot stamping on face") as political argument; intellectual honesty as supreme virtue.
- Christopher Hitchens: Pugnacious, erudite polemics delivered with rhetorical flourish; extensive literary references deployed as weapons; contrarian positions defended with combative wit; long sentences that build to devastating conclusions; treats intellectual combat as highest entertainment; unapologetic confidence in his own judgment.

Corporate Communications

-

Psychology, Behavior & Self-Help

- Adam Grant: Organizational psychology translated into actionable insights; counterintuitive findings about success (givers vs. takers); rapid synthesis of research with business examples; enthusiastic, practical tone; LinkedIn-ready takeaways embedded in longer arguments; optimistic about human potential in workplace.
- Daniel Kahneman: Behavioral economics explained through elegant experiments and personal anecdotes; systematic demolition of rational actor model; humble acknowledgment of his own biases; accessible explanations of statistical concepts; conversational authority built over decades of research; treats irrationality as fascinating rather than shameful.
- Atul Gawande: Surgeon-essayist who finds systemic insights in clinical encounters; checklist thinking applied to complex problems; acknowledges medicine's uncertainties with unusual candor; elegant narrative arcs built from case studies; combines personal fallibility with institutional analysis; New Yorker polish with public health purpose.
- Brené Brown: Vulnerability research delivered with Texas warmth and self-deprecating humor; TED Talk energy transferred to page; personal stories of shame and breakthrough; academic findings made accessible through confessional narrative; direct address to reader's fears; courage framed as achievable practice.
- Angela Duckworth: Grit and perseverance as learnable skills; research findings delivered through inspiring profiles; optimistic about growth mindset; accessible writing with self-help framework; balances academic rigor with motivational energy; treats character as measurable and developable.
- Jonathan Haidt: Moral psychology explained through vivid metaphors (elephant and rider, taste receptors); bridges liberal-conservative divide with empathy; evolutionary explanations for political differences; accessible synthesis of research across disciplines; treats disagreement as puzzle to understand rather than battle to win.
- Robert Cialdini: Influence and persuasion explained through categorized principles (reciprocity, scarcity, authority); real-world examples from sales, cults, and cons; practical, almost how-to framing; academic research made applicable; acknowledges manipulation while teaching defense; systematic framework builders will love.
- Mihaly Csikszentmihalyi: Flow states as path to meaningful life; positive psychology before the term existed; research findings delivered with philosophical depth; treats consciousness as terrain to be cultivated; academic rigor with humanistic purpose; accessible explanations of optimal experience.
- Carol Dweck: Growth vs. fixed mindset as transformative framework; research on praise, failure, and learning; accessible, practical, slightly repetitive; treats intelligence as malleable; parenting and education implications emphasized; optimistic about human potential through simple reframes.

Business & Strategy

- Michael Porter: Dense, systematic frameworks for competitive strategy; academic rigor applied to business decisions; creates vocabulary that becomes industry standard (five forces, value chain); assumes sophisticated reader; treats strategy as analytical discipline rather than art.
- Peter Drucker: Wise, aphoristic management philosophy from decades of observation; invented modern management as discipline; treats organizations as human communities with purposes; clear, direct prose without jargon; timeless principles over trends; humanistic capitalism.
- Jim Collins: Research-driven business insights delivered through memorable frameworks (Level 5 Leaders, Hedgehog Concept, Flywheel); extensive case studies synthesized into actionable principles; disciplined, systematic approach; treats greatness as achievable through right practices; built to last mentality.
- Clayton Christensen: Disruptive innovation theory explained through detailed industry case studies; academic framework made practically applicable; patient, thorough analysis of why good companies fail; treats disruption as predictable pattern rather than random event; business school case study approach.
- Seth Godin: Punchy, aphoristic marketing wisdom in short blog-post-sized chunks; purple cow, permission marketing, tribes as memorable frameworks; treats average as death; direct address to reader's fears about standing out; optimistic about remarkable individuals challenging industrial mediocrity.
- Simon Sinek: "Start with Why" as central organizing principle; TED Talk style translated to page; inspirational tone with business examples; treats purpose as competitive advantage; accessible, motivational, occasionally repetitive; golden circle diagrams for visual thinkers.
- Tim Ferriss: Life-hacking optimized living through aggressive experimentation; 4-hour frameworks for escaping conventional paths; interviews deconstructing peak performers' routines; biohacking meets lifestyle design; practical tactics with libertarian self-reliance ethic; treats readers as potential outliers.
- Ryan Holiday: Stoic philosophy applied to modern life and business; accessible translations of Marcus Aurelius and Seneca; obstacle-is-the-way reframing; short chapters with practical applications; treats ancient wisdom as competitive advantage; blends self-help with serious philosophical reading.
- Robert Greene: Historical case studies revealing timeless laws of power and strategy; Machiavellian analysis presented without moral judgment; dense, almost encyclopedic structure with marginalia; treats human nature as unchanging; dark psychology made explicit; seduction, war, and mastery as learnable arts.
- James Clear: Atomic habits framework built from behavioral science; compound gains through small changes; clear, systematic, highly actionable; treats identity change as mechanism for behavior change; accessible synthesis of research; practical without being simplistic; 1% better every day philosophy.
- Mark Manson: Profanity-laced self-help that attacks positivity culture; "subtle art of not giving a f\*ck" as counterintuitive framework; treats acceptance of negative as path to contentment; internet-native voice applied to perennial wisdom; appeals to readers tired of conventional self-help.
- Nassim Nicholas Taleb: (See above under Science—his business/risk writing has same style: aphoristic, combative, anti-fragile frameworks)

History & Biography

- David McCullough: Sweeping, old-fashioned narrative history with novelistic pace; brings Founding Fathers and presidents to vivid life; treats subjects with affection and moral seriousness; accessible without condescension; believes in American greatness while acknowledging flaws; voice made for audiobook narration.
- Ron Chernow: Definitive, doorstop biographies built from exhaustive archival research; treats financial and political history as inseparable; finds drama in banking and treasury departments; comprehensive yet readable; subjects (Hamilton, Washington, Rockefeller) revealed in full psychological complexity.
- Robert Caro: Monumental, obsessively detailed biographies (LBJ, Robert Moses) that redefine understanding of power; decades of research per volume; treats infrastructure and political machinery as character; accumulating evidence toward devastating conclusions; turns bureaucratic maneuvers into gripping narrative.
- Barbara Tuchman: Narrative history that reads like novel; treats historical actors as fully dimensional characters; "Guns of August" style tragic inevitability; accessible synthesis without academic footnoting; finds contemporary relevance in distant events; "March of Folly" as recurring human pattern.
- Doris Kearns Goodwin: Presidential history through intimate personal relationships; "Team of Rivals" approach showing greatness through generosity; accessible, warm narrative style; treats leadership as learnable through historical example; extensive archival research made readable for general audiences.
- Simon Schama: Baroque, sensuous prose applied to art and history; passionate engagement with visual culture; treats paintings and landscapes as historical evidence; British intellectual with American audience; ambitious scope matched by stylistic ambition; history as literature.
- Stephen Ambrose: Band of Brothers military history focusing on ordinary soldiers' experiences; accessible, patriotic without being jingoistic; treats WWII generation with reverence; action-driven narrative built from interviews; makes reader feel present at D-Day; occasionally criticized for accuracy.
- Hampton Sides: Adventure history that reads like thriller; meticulous research on expeditions, escapes, and military operations; cinematic scene-setting; multiple narrative threads converging; treats historical actors as complex individuals; Ghost Soldiers/Blood and Thunder approach to dramatic true stories.

Memoir & Personal Essay

- David Sedaris: Self-deprecating family comedy with dark undertones; absurdist observations on everyday life; expat in France perspective; treats dysfunction as material; short, punchy essays perfect for public radio; timing and delivery honed from live performance; finds humor in mortality and failure.
- Anne Lamott: Confessional, spiritually-inflected personal essays; treats writing and faith as intertwined practices; self-deprecating humor about anxiety and parenting; "bird by bird" practical wisdom; progressive Christianity with recovery program sensibility; raw, emotionally honest, occasionally messy.
- Ta-Nehisi Coates: Personal experience as window into systemic racism; letter-to-son structure; treats Black body as subject of American violence; beautiful, controlled rage in lyrical prose; Atlantic essay style extended to book length; unsparing examination of American mythology.
- Roxane Gay: Personal essays on body, gender, and popular culture; treats fatness and trauma with unflinching honesty; academic and popular registers combined; finds feminist critique in reality TV and music; Bad Feminist framework acknowledging contradictions; confessional yet analytical.
- Cheryl Strayed: Wild-style redemption memoir through physical ordeal; "Dear Sugar" advice column wisdom; treats suffering as teacher; lyrical prose about grief, addiction, and healing; direct emotional appeal; mothers, loss, and hiking as recurring elements.
- Elizabeth Gilbert: Eat Pray Love spiritual memoir as international journey; accessible, warm, self-deprecating tone; treats self-discovery as achievable adventure; Big Magic creativity advice; appeals to readers seeking permission for change; optimistic about transformation.
- Anthony Bourdain: Kitchen Confidential insider exposé extended to global travel; treats food as cultural revelation; profane, streetwise voice; celebrates working-class craft; finds authenticity in holes-in-wall over fancy restaurants; punk rock sensibility applied to culinary writing.
- Pico Iyer: Meditative travel writing that treats stillness as destination; Japan and monasteries as recurring settings; elegant, philosophical prose; finds meaning in airports and transit spaces; global soul as identity category; treats movement and rootlessness as spiritual condition.

Nature & Environment

- Annie Dillard: Mystical attention to natural world with theological undertones; Pilgrim at Tinker Creek as patient observation transformed into meditation; treats seeing as spiritual discipline; violent beauty in nature; baroque, visionary prose; small moments expanded into cosmic significance.
- Barry Lopez: Arctic Dreams approach to landscape and indigenous knowledge; treats place with reverent attention; ethical relationship with nature as central concern; gorgeous, careful prose; bridges science and spirituality; endangered landscapes as moral imperative.
- Elizabeth Kolbert: Climate science journalism with devastating clarity; Sixth Extinction field reporting; treats scientists as characters; makes abstract threat concrete through specific species and places; measured tone that lets facts deliver emotional impact; New Yorker precision.
- Michael Pollan: Food and plants as entry points to larger questions about nature and culture; Omnivore's Dilemma investigative approach; first-person experiments (growing, hunting, building); treats industrial food system as worthy of scrutiny; accessible, curious, slightly earnest.
- Robin Wall Kimmerer: Indigenous and scientific knowledge braided together; treats plants as teachers and relations; Braiding Sweetgrass approach to botanical wisdom; poetic, reverent prose; reciprocity with nature as ethical framework; mourning and hope intertwined.
- Aldo Leopold: Sand County Almanac as founding text of land ethic; treats land as community to belong to; seasonal observations building to philosophical conclusions; spare, elegant prose; ecological conscience as achievement; poetic compression.
- Rachel Carson: Silent Spring as model of science writing with moral purpose; treats nature with lyrical attention; builds evidence toward environmental alarm; accessible explanation of complex ecology; sea and shore as subjects of wonder; revolutionary impact through beautiful prose.
- David Quammen: Disease ecology and evolution explained through adventurous field reporting; Spillover approach to zoonotic threats; treats scientists as characters in detective stories; dense with research yet propulsive; finds narrative in epidemiology.
- Sy Montgomery: Deep empathy across species boundaries; Soul of an Octopus immersive approach; treats animal minds as worthy of serious attention; naturalist adventures with personal reflection; emotional connection as scientific method; wonder and grief intertwined.

Technology & Digital Culture

- Walter Isaacson: Definitive biographies of tech innovators (Jobs, Musk, Einstein); extensive access to subjects and archives; treats genius as combination of talent and personality flaws; comprehensive without being academic; narrative authority built from thoroughness.
- Steven Levy: Hackers cultural history approach; treats tech communities as subcultures worthy of anthropological attention; insider access without sycophancy; chronicles Silicon Valley with historical perspective; explains technical concepts through personalities.
- Kevin Kelly: Techno-optimist philosophy from Wired founding editor; treats technology as evolutionary force; counterintuitive frameworks (1000 true fans, Amish innovation); sweeping historical perspective; optimistic about tools and human potential.
- Nicholas Carr: Skeptical examination of technology's cognitive effects; "Is Google Making Us Stupid?" extended analysis; treats distraction as design choice; elegant prose with philosophical depth; counterweight to tech utopianism.
- Cathy O'Neil: Weapons of Math Destruction critique of algorithmic systems; treats data science as political; insider perspective on quantitative finance; accessible explanations of technical discrimination; moral urgency about mathematical injustice.
- Sherry Turkle: Alone Together analysis of technology and relationships; treats devices as revealing psychological needs; MIT researcher with clinical depth; worried but not dismissive about digital intimacy; interviews and observation as method.

Linguistics & Wordplay Experts

- Dmitri Borgmann: The godfather of logology (recreational linguistics); exhaustively catalogued word curiosities in "Language on Vacation" and "Beyond Language"; treats English vocabulary as a finite but astonishingly rich puzzle space to be systematically explored; would have definitive lists of letter-proportion champions organized by word length, letter, and dictionary source; obsessive completism as methodology; dry presentation letting the words speak for themselves.
- Ross Eckler: Longtime editor of _Word Ways_ who brought mathematical rigor to wordplay; treats logology as serious amateur scholarship; would compute exact statistics, establish precise criteria (which dictionary? proper nouns?), and present findings in tables with exhaustive appendices; systematic where Borgmann was encyclopedic; less playful, more definitive.
- Richard Lederer: "Anguished English" populist approach to language play; treats word oddities as delightful entertainments for general readers; would emphasize memorable examples over comprehensive lists; pun-friendly, accessible, syndicated-column-length pieces; celebrates English's weirdness without academic apparatus.
- Gyles Brandreth: British wordplay enthusiast and broadcaster; treats language games as civilized entertainment; would approach this as an after-dinner puzzle; anecdotal, charming, slightly theatrical; "The Joy of Lex" sensibility finding pleasure in curiosities without exhaustive analysis.
- Anu Garg: "A.Word.A" founder who serves daily vocabulary with etymological depth; would frame letter-repetition as window into word origins and sound symbolism; email-newsletter brevity with global subscriber community engagement; treats words as daily companions worthy of attention.
- Mark Forsyth: "The Etymologicon" chain-of-connections approach; would find this puzzle a springboard to unexpected etymological tangents—why does "banana" repeat? what about onomatopoeia?; witty, digressive British prose; treats language history as endless entertainment.
- David Crystal: Academic linguist who writes accessibly about language structure; would situate letter-proportion in phonological and orthographic context; might ask whether this reflects deeper patterns in English morphology; authoritative yet engaging; treats popular linguistics as serious public service.
- Will Shortz: NPR puzzle master and NYT crossword editor; would present this as a challenge to listeners/solvers; prizes elegance and "aha" moments over exhaustive lists; treats puzzles as communal entertainment with competitive edge; concise setups with satisfying reveals.

## Publications

https://claude.ai/chat/5318d32f-ac93-4d4b-8181-c3d8a196b602

General Interest Magazines

- The New Yorker: Long-form journalism with novelistic scene-setting and psychological depth; rigorous fact-checking enabling confident assertions; understated humor and cultural sophistication assumed; extensive context even for breaking news; Talk of the Town wit; profiles that reveal character through accumulated detail; treats every subject as worthy of serious attention.
- The Atlantic: Ideas-driven journalism that bridges academia and general readers; treats policy debates as intellectual puzzles; moderate-liberal perspective with contrarian voices; long essays that build arguments carefully; historical context for contemporary issues; confident authorial voice with institutional authority.
- Harper's Magazine: Literary essays and reporting with leftist intellectual perspective; Index as satirical juxtaposition; treats culture with serious attention; slower pace than newsweeklies; beautiful prose valued over news breaks; Readings section curating provocative primary sources; intellectual ambition.
- The Economist: Authoritative, unsigned analysis of global affairs with British wit; treats readers as intelligent generalists; clear explanations without dumbing down; data-driven yet opinionated; classical liberal perspective applied consistently; confident predictions and policy prescriptions; Lexington, Bagehot, Charlemagne bylines signal expertise.
- Vanity Fair: Glamorous longform on power, money, and celebrity with insider access; treats wealth and scandal as worthy subjects; glossy production values matched by journalistic ambition; profiles that capture subjects at moments of crisis; Hollywood and Wall Street as recurring milieus.
- GQ / Esquire: Men's magazine longform that transcends lifestyle content; muscular prose on politics, sports, and masculinity; first-person immersion pieces; treats adventure and danger as legitimate subjects; literary ambition within commercial context; profiles of male icons with psychological depth.
- Rolling Stone: Rock journalism extended to political reporting and true crime; countercultural perspective on American power; gonzo heritage with mainstream reach; treats music as cultural force; longform investigations with attitude; Matt Taibbi era savagery toward Wall Street.

News Analysis & Opinion

- New York Times Magazine: Sunday magazine pace for news analysis and culture; visual storytelling integrated with text; treats photography as journalism; ambitious longform with institutional resources; feature wells that allow extended narratives; covers as cultural moments.
- The Guardian Long Read: British-international perspective on global issues; leftist-progressive viewpoint with intellectual rigor; extensive context for breaking stories; treats inequality and power as central concerns; ambitious length for web journalism; audio versions for commuters.
- ProPublica: Investigative journalism with public interest mission; database journalism and document-driven reporting; treats accountability as purpose; extensive methodology transparency; collaborations with local newsrooms; findings-focused rather than narrative-driven.
- The Intercept: Adversarial journalism focused on national security and civil liberties; Snowden-era founding principles; treats government secrecy as default subject; progressive-libertarian perspective on surveillance; document dumps with analysis; Glenn Greenwald combative origins.

Science & Nature Publications

- Scientific American: Explains cutting-edge research for educated non-specialists; treats readers as intellectually serious; graphics and visualizations integral to explanations; avoids sensationalism while maintaining accessibility; 175-year authority; researcher bylines with editorial polish; longer than newspaper science, shorter than books.
- National Geographic: Visual-first storytelling where photography carries narrative weight; treats Earth's diversity as inexhaustible subject; expedition journalism to remote places; environmental advocacy integrated with wonder; maps and infographics as signature elements; yellow border as brand of exploration and authority.
- Nature / Science: Primary research journal conventions: abstract, methods, results, discussion; treats peer review as quality guarantee; news sections accessible but research papers require expertise; significant findings announced with institutional weight; embargo culture shapes science journalism globally.
- Popular Science: Explains technology and science for enthusiast audiences; treats gadgets and innovations as exciting; how-it-works explanations with diagrams; optimistic about technological progress; accessible without being academic; DIY projects and product coverage alongside features.
- Discover: Magazine science journalism with narrative ambition; treats research as ongoing adventure; accessible explanations for curious generalists; year's top stories format; covers astronomy, health, paleontology as equally interesting; more personality than Scientific American, more depth than daily newspapers.
- Nautilus: Interdisciplinary science magazine organized around themes (time, uncertainty, boundaries); treats science as humanistic inquiry; essays that bridge disciplines; beautiful design with illustration; slower pace than news cycle; philosophical questions as framing.
- Quanta Magazine: Math and physics journalism with unusual rigor; treats readers as capable of following complex arguments; explains proofs and discoveries with clarity; Simons Foundation backing enables depth; profiles of researchers as characters; covers areas other outlets ignore.
- Aeon: Essay-length explorations of ideas across philosophy, science, and culture; treats big questions seriously; international roster of academic contributors; beautiful design; free access supported by foundation; slower pace than journalism, more accessible than journals.

Technology Publications

- Wired: Treats technology as cultural force shaping society; magazine feature ambition with digital native sensibility; profiles of founders and thinkers; design and aesthetics as integral; long-form investigations of Silicon Valley; Condé Nast production values; optimistic but not naive about tech.
- MIT Technology Review: Emerging technology explained with institutional authority; treats AI, biotech, energy as transformative forces; academic rigor accessible to industry audiences; annual lists (Innovators Under 35, Breakthrough Technologies) as franchise; less breathless than Wired, more forward-looking than academic journals.
- Ars Technica: Deep technical analysis for knowledgeable audiences; treats readers as capable of understanding protocols and code; extensive coverage of policy affecting technology; gaming and science alongside enterprise tech; comment section as community; longer than typical tech blogs.
- The Verge: Consumer technology with design sensibility; treats gadgets as cultural objects; reviews with strong editorial voice; accessible explanations for mainstream audiences; video integral to coverage; Vox Media polish; lifestyle integration with tech coverage.
- Hacker News: Community-curated tech links with comment discussions; treats intellectual curiosity as shared value; startup and programming focus; Paul Graham essays as founding documents; karma system rewards thoughtful contributions; contrarian views welcomed if well-argued.

Business & Economics

- Harvard Business Review: Management research translated for practitioner audiences; treats business as worthy of intellectual attention; case study methodology; frameworks and models as deliverables; prestigious bylines from academics and executives; measured, authoritative tone; treats leadership as learnable.
- Fast Company: Innovation and design focus with optimistic energy; treats creative companies as worthy subjects; profiles of founders disrupting industries; design thinking as editorial perspective; magazine features with digital urgency; more celebratory than critical.
- Fortune / Forbes: Business journalism focused on companies and wealthy individuals; Fortune 500 rankings as franchise; treats capitalism with respect while covering scandals; executive profiles and deal coverage; institutional authority in business community.
- Bloomberg Businessweek: Sharp, witty business journalism with distinctive visual design; treats markets and policy with sophistication; unconventional cover concepts; data visualization as signature; more attitude than traditional business magazines; investigative ambition.
- Financial Times: Pink paper authority on global finance and business; treats City and Wall Street as primary constituencies; Weekend Magazine cultural coverage; data-driven analysis with European perspective; subscription model enabling depth; Alphaville blog voice.
- FiveThirtyEight: Data journalism treating politics and sports with quantitative rigor; probability-focused election forecasting; treats uncertainty explicitly; Nate Silver methodology; interactive graphics; sports analytics beyond politics; explainers grounded in data.

Technical & How-To Publishers

- O'Reilly Media: Technical books written by practitioners for practitioners; animal covers as brand identity; treats readers as professionals needing depth; comprehensive reference works alongside tutorials; early adoption of ebooks and DRM-free; conference business integrated with publishing; "the animal book on X" as category definition.
- For Dummies: Makes intimidating subjects accessible through consistent, friendly structure; yellow-and-black branding with cartoon figure; treats readers as intelligent beginners deserving respect; sidebars, tips, warnings as navigation aids; self-deprecating title removes shame from learning; comprehensive coverage without assuming prior knowledge; "Reference for the Rest of Us" populism.
- Pragmatic Programmers: Developer-focused books emphasizing practical, opinionated guidance; "beta book" early access model; treats programming as craft to be honed; exercises and projects integral; specific technology stacks with clear recommendations; community of practice sensibility; updates and errata transparent.
- Manning Publications: In-depth technical books with "in Action" series format; MEAP early access program; treats readers as serious developers wanting thorough coverage; code examples central to exposition; liveBook online format; integration with video training.
- No Starch Press: Hacker and maker culture publisher with playful design; treats security, programming, and hardware with enthusiasm; "Serious About Fun" tagline; books for curious tinkerers; covers stand out on technical shelves; Python, security, and hardware focus.
- Wiley: Academic and professional publisher across disciplines; textbooks, professional references, and trade books; For Dummies imprint alongside serious technical works; treats institutional markets seriously; comprehensive revision cycles; brand authority in specific fields.
- Apress: Developer-focused technical books, especially Microsoft ecosystem; "Pro" series for advanced topics; treats enterprise development seriously; comprehensive coverage of specific platforms; expert author recruitment; digital-first orientation.

Literary & Cultural Review

- The Paris Review: Writer interviews as primary franchise; Art of Fiction/Poetry series revealing craft; treats literary ambition as highest calling; fiction and poetry alongside interviews; iconic covers; discovering emerging voices; craft-focused rather than political.
- The New York Review of Books: Long-form essay reviews that transcend book being reviewed; treats intellectual debate as essential; left-liberal perspective with contrarian voices; extensive engagement with ideas; older, serious readership; Silvers-era authority continuing.
- London Review of Books: British counterpart to NYRB with more literary focus; treats books as occasions for essayistic exploration; personal voice and digressions welcomed; left-leaning perspective; Personals column as beloved feature; academic contributors with general audiences.
- n+1: Intellectual magazine with millennial sensibility; treats contemporary culture with serious critical attention; long essays on technology, politics, literature; Brooklyn literary scene origins; collective editorial structure; print-forward despite digital era.
- The Believer: McSweeney's literary magazine celebrating enthusiasm over snark; treats "difficult" art as worthy of accessible discussion; interviews with artists and thinkers; visual elements and comics integrated; optimistic about cultural possibilities.
- McSweeney's Quarterly: Experimental fiction and design as inseparable; treats physical book object as worthy of attention; playful formats (cigar boxes, bundles of mail); Dave Eggers founding vision; literary ambition with formal innovation; lists and humor alongside serious fiction.
- Lapham's Quarterly: Historical sources curated around themes; treats past as usable for understanding present; extensive excerpts from primary sources; Lewis Lapham's editorial voice; beautiful design; subscription model for serious readers.

Digital-Native Publications

- Vox: Explanatory journalism treating readers as wanting to understand, not just know; card stacks and explainers as format innovation; liberal perspective made explicit; video integrated with text; "everything you need to know" promise; policy focus with accessibility.
- Slate: Contrarian takes on news and culture; treats conventional wisdom as target; podcasts as major franchise; XX Factor and other vertical brands; first-person essays alongside reporting; provocative headlines earning clicks through argument.
- The Ringer: Sports and pop culture with analytical depth; Bill Simmons voice and network; podcasts as primary medium; treats fandom as worthy of serious attention; ranking and list culture; NBA focus with broader cultural coverage.
- Stratechery: Tech strategy analysis through Ben Thompson's single voice; treats platform dynamics and business models as fascinating; subscription newsletter model proving viability; frameworks applied consistently across companies; Asia-informed perspective; influential among tech executives.
- Substack (ecosystem): Individual writer voices unconstrained by editorial consensus; treats direct reader relationships as sustainable; newsletter as primary format; comment sections for paid subscribers; varied styles from reported journalism to personal essay; independent but platform-enabled.

Academic/Scholarly Made Accessible

- Steven Pinker (linguistic style): Applies cognitive science to writing itself; "Sense of Style" as practical grammar; treats clarity as achievable through understanding how readers parse; academic authority applied to craft guidance; fights nominalization and bureaucratese.
- Strunk & White: Terse commandments for clear prose; treats brevity as virtue; "Omit needless words" as mantra; prescriptivist confidence; slim volume as complete guide; Elements of Style authority across generations.
- Joseph Williams (Style): Explains why bad writing sounds bad through grammatical analysis; treats diagnosis as path to cure; academic rigor applied to practical prose; more explanatory than Strunk; "clarity" and "cohesion" as technical terms made useful.
- Very Short Introductions (Oxford): Expert synthesis in pocket format; treats readers as intelligent adults wanting efficient depth; consistent length and design; one topic per volume; academic authority without academic density; series collectibility.

Graphic/Visual Non-Fiction

- Edward Tufte: Visual display of quantitative information as design discipline; treats chartjunk and PowerPoint as intellectual enemies; large-format books as unified design objects; Napoleon's march and Challenger disaster as case studies; self-published control; seminars as franchise.
- Scott McCloud: Comics as medium explained through comics form; "Understanding Comics" meta-approach; treats sequential art with theoretical seriousness; accessible to non-comics readers; iconic explanatory panels widely referenced.
- Nathan Yau (FlowingData): Data visualization tutorials with statistical rigor; treats R and D3 as creative tools; step-by-step guides with code; blog and books integrated; personal voice with technical depth; visualization as craft to practice.

Investigative/True Crime

- Serial (podcast): Narrative investigation across episodes building suspense; treats uncertainty openly; host as character working through evidence; audience participation in theorizing; season-long commitment to single story; spawned true crime podcast genre.
- Texas Monthly: Regional magazine with outsized investigative ambition; treats Texas as inexhaustible subject; true crime and oil industry focus; literary feature writing; Skip Hollandsworth narrative craft; "The Confession" and similar franchise pieces.

## Art

https://sanand0.github.io/llmartstyle/

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

## Data Visualization

https://claude.ai/chat/8cd25010-20d0-456c-b8fb-84e9a622f8a0

- The New York Times: Sophisticated scrollytelling with restrained elegance; clean serif typography, muted color palettes with strategic accent colors, extensive annotations integrated into narrative flow; pioneering D3.js-powered interactives that prioritize clarity over flash; deep reporting married to bespoke visual forms tailored to each dataset's unique characteristics.
- The Upshot (NYT): Analytical journalism branch of the Times with Amanda Cox's influence; You-draw-it interactive experiments; emphasis on reader engagement through participation; sophisticated statistical analysis made accessible; political polling and demographic analysis; calculator tools for personal policy impact.
- The Economist: Minimalist rigor with signature red branding; ITC Officina Sans typography, neutral grays and blues, y-axis labels on right side, white horizontal gridlines; witty left-aligned titles with descriptive subtitles; simple bar and line charts that match message to form; consistent visual language across print and digital that makes complex economics instantly scannable.
- The Guardian: Open data advocacy with democratic accessibility; clean interactive graphics, strong datablog tradition of full dataset transparency; blue-accented design with clear visual hierarchy; pioneering crowdsourced journalism using shared spreadsheets; WikiLeaks-era innovation in handling massive datasets; emphasis on making public data explorable by citizens.
- Financial Times: Authoritative salmon-pink backgrounds with professional credibility; strategic use of annotations that guide readers through the Z-shaped visual path; clear narrative headlines; elegant line charts for financial time series; real-time data integration; John Burn-Murdoch's pandemic tracking exemplified adding clarity through annotation rather than removing elements.
- South China Morning Post: Award-winning immersive infographics with Asian perspective; elaborate hand-drawn illustrations combined with 3D models; horizontal scroll narratives; extensive research-driven standalone features; visually stunning full-page print graphics translated to interactive digital experiences; strong emphasis on China and Hong Kong regional expertise.
- Bloomberg: Real-time financial data dashboards with dense information displays; dark interfaces with neon accent colors for market data; sophisticated billionaire trackers and market visualizations; emphasis on dynamic updating data; professional Bloomberg Terminal aesthetic translated for broader audiences; quantitative precision with editorial context.
- Washington Post: Explanatory visual journalism with accessible depth; clean interactive graphics that break down complex policy and politics; strong emphasis on election mapping and demographic analysis; innovative use of 3D and immersive storytelling; investigative data projects with clear public interest angles; mobile-optimized designs.
- Reuters Graphics: Global news agency visual storytelling with translation-ready design; immersive scrolling narratives on catastrophic events; hand-drawn illustrations for human interest alongside data precision; emphasis on visual merit---only creating graphics that add value beyond text; Cinema 4D 3D work; satellite imagery analysis for humanitarian stories.
- Wall Street Journal: Conservative business newspaper aesthetic with refined infographics; emphasis on market data visualization and corporate reporting; clean serif typography with restrained color use; detailed methodology transparency; professional charts that integrate seamlessly with traditional business journalism; quarterly earnings and economic indicator specialization.
- BBC: Public service broadcasting clarity optimized for broad audiences; accessible interactive explainers on complex topics; clean visual design with minimal jargon; strong emphasis on election results and referendum coverage; responsive design for multi-platform delivery; educational tone that assumes no prior knowledge while respecting viewer intelligence.
- Der Spiegel: German precision with bold European magazine aesthetic; innovative use of photography integrated with data; strong investigative data journalism tradition; detailed long-form visual features; emphasis on political accountability and document-based reporting; sophisticated interactive storytelling with strong narrative structure.
- La Nación (Argentina): Latin American data journalism pioneers; building datasets from scratch through PDF scraping in limited-data environments; citizen engagement through interactive visualizations; strong open data advocacy in regions without freedom of information laws; emphasis on data-to-citizen connection for democratic participation.
- FiveThirtyEight: Statistical modeling with probabilistic thinking; Atlas Grotesk typography on light gray backgrounds; sports/politics prediction markets; uncertainty visualization through distributions and confidence intervals; conversational explanatory text integrated with charts; poll aggregation methodology transparency; dashboard-style election trackers with clear visual hierarchy.
- The Pudding: Cultural visual essays with playful experimentation; scroll-driven narratives exploring pop culture through original datasets; emphasis on personal topics like music taste, language evolution, and social phenomena; creative D3.js implementations that blur visualization and art; process-transparent documentation; Peabody Award-winning storytelling that makes data accessible and delightful.
- ProPublica: Investigative accountability journalism with public database tools; news apps that let citizens explore data affecting their communities; emphasis on racial justice, healthcare costs, and government accountability; open-source data methodology; Lena Groeger's Visual Evidence series exploring design principles; serious topics with accessible interactive exploration.
- The Marshall Project: Criminal justice focused data journalism with humanizing storytelling; visualizations that illuminate systemic inequities in policing, courts, and prisons; combining human narratives with statistical evidence; emphasis on reform-oriented policy impact; accessible design that reaches affected communities; investigative rigor with advocacy-adjacent transparency.
- Quartz: Business journalism for global executives with mobile-first design; chart-driven newsletters; conversational tone with sophisticated analysis; emphasis on emerging markets and technology trends; clean visual identity with strategic interactivity; quick-hit data insights alongside deeper feature investigations.
- Vox: Explanatory journalism with card-based visual explainers; accessible breakdowns of complex policy topics; strong video integration with data graphics; chart annotations that anticipate reader questions; progressive political perspective with methodological transparency; emphasis on 'understand the news' mission.
- Information is Beautiful: David McCandless aesthetic of poster-style infographics; bold colors and geometric compositions; emphasis on shareable static visualizations; annual awards recognizing excellence across the field; international scope curating best visualization work; infographic-as-art approach with strong visual hierarchy and minimal text.
- Edward Tufte: Data-ink ratio maximization and chartjunk elimination; small multiples and sparklines; graphical integrity principles demanding proportional representation; integration of text and graphics; high information density with elegant simplicity; statistical rigor translated to visual form; self-published books that are themselves design exemplars; the 'Leonardo da Vinci of data.'
- Cole Nussbaumer Knaflic: Business-focused storytelling with data; 'simple beats sexy' philosophy eliminating clutter; emphasis on audience-first thinking and clear takeaways; practical workshop-oriented techniques for non-designers; decluttering through gestalt principles; strategic use of preattentive attributes to direct attention; accessible methodology for corporate communicators.
- Alberto Cairo: Five qualities framework: truthful, functional, beautiful, insightful, enlightening; journalism professor emphasizing ethical visualization; bridging scientific rigor with accessible explanation; How Charts Lie focusing on visual literacy for citizens; emphasis on truth continuum and acknowledging uncertainty; practical tools like R and Datawrapper democratizing visualization.
- Giorgia Lupi: Data humanism manifesto embracing imperfection and context; handcrafted aesthetic using drawing instead of coding; Dear Data postal correspondence project with Stefanie Posavec; personal data as emotional expression; Pentagram partner bringing artistry to corporate visualization; emphasis on qualitative nuance behind quantitative data; making data feel human.
- Nadieh Bremer: Astronomer-turned-designer creating cosmic-scale data art; radial and circular chart innovations; D3.js technical virtuosity with artistic intention; collaboration with Shirley Wu on Data Sketches; extensive process documentation; blurring boundaries between visualization and art; work for Google, NYT, and Scientific American; focus on beauty serving insight.
- Shirley Wu: Software engineer bringing creative coding to data visualization; playful exploration of personal topics like Hamilton lyrics; emphasis on sketching before coding; collaboration with Nadieh Bremer on Data Sketches; extensive client work for SFMOMA and The Guardian; technical skill serving artistic expression; iterative process transparency.
- Stefanie Posavec: Handcrafted data visualization using analog methods; Dear Data collaboration with Giorgia Lupi; emphasis on personal data collection and representation; book-as-object design sensibility; physical installations and printed pieces; London-based designer bridging graphic design and data practice; intimate scale revealing patterns in daily life.
- Mike Bostock: D3.js creator defining modern web visualization; Observable notebooks democratizing interactive development; NYT graphics team alumnus; emphasis on reusable components and open-source community; technical documentation as teaching; enabling thousands of visualizations through library design; bridge between computer science and visual journalism.
- Amanda Cox: NYT graphics team leader turned Upshot editor; emphasis on unique characteristics of each dataset; 'don't be a data fashion victim' philosophy; R programming for statistical exploration; You-draw-it interactive innovations; soul-crushing line charts revealing inequality; pushing orthodox boundaries with reader participation; making statistics emotionally resonant.
- John Burn-Murdoch: FT chief data reporter whose pandemic charts reached millions; annotation-rich approach adding clarity rather than removing elements; strategic color use with salmon-pink brand consistency; log-scale country comparison innovation; emphasis on storytelling through chart titles; real-time updating workflows using R and D3; making complex trends immediately comprehensible.
- Nathan Yau: FlowingData blog curator democratizing visualization education; R tutorials making statistical graphics accessible; emphasis on finding stories in data; PhD statistics background with accessible communication; books on data visualization for general audiences; daily curation of visualization examples across industries; bridging academic statistics and practical application.
- Hans Rosling: Animated bubble charts bringing global development data to life; Gapminder foundation work combating misconceptions with facts; TED talk theatrics making statistics entertaining; emphasis on time-series animation showing progress; optimistic fact-based worldview; combating ignorance with interactive tools; democratizing World Bank data through accessible interfaces.
- Manuel Lima: Network visualization pioneer and VisualComplexity.com founder; tree of life visual metaphors; emphasis on information architecture and knowledge organization; books on visual complexity and circle design; Google Design Lead perspective on large-scale visualization challenges; historical research connecting contemporary practice to visual tradition.
- Moritz Stefaner: German information aesthetics balancing form and function; creative coding with Processing and D3; interactive installations for museums and exhibitions; emphasis on exploratory visualization enabling discovery; client work for major publications; truth and beauty operator philosophy; bridging artistic expression with analytical rigor.
- Jen Christiansen: Scientific American senior graphics editor bringing precision to science visualization; emphasis on accurate representation of research findings; collaboration with scientists to translate complex phenomena; illustration integrated with data; long-form explanatory graphics for magazine format; bridging scientific accuracy with visual accessibility.
- Jonathan Schwabish: PolicyViz founder focused on data communication for policy audiences; economist perspective on visualization best practices; emphasis on clear graph design for reports and presentations; workshops for government and nonprofit communicators; practical decluttering techniques; bridging academic research visualization and policy communication.
- Polygraph/The Pudding: Visual essay studio creating scroll-driven cultural explorations; original dataset development on unconventional topics; client work for Google, LinkedIn, Netflix alongside editorial projects; emphasis on mobile-first interactive design; making complex ideas accessible through playful experimentation; technical skill serving narrative engagement.
- Periscopic: Social impact visualization studio emphasizing 'do good with data'; emotional resonance in serious topics like gun deaths; emphasis on humanizing statistics about loss and inequality; interactive installations alongside web projects; Portland-based studio with nonprofit and advocacy focus; making data feel consequential to drive action.
- Stamen Design: San Francisco studio pioneering web mapping and geographic visualization; custom map tiles and OpenStreetMap integration; emphasis on exploratory geographic data tools; work spanning news, scientific, and commercial clients; technical innovation in real-time data streaming; making mapping beautiful and functional.
- Density Design: Milan Politecnico research lab combining academic rigor with design excellence; complex network and textual data visualization; emphasis on information design methodology and student training; open-source tool development; bridging Italian design tradition with contemporary data practice; exhibition and editorial projects.
- Truth & Beauty (Moritz Stefaner): Boutique studio balancing aesthetic excellence with analytical depth; emphasis on exploratory visualization for discovery; museum installations alongside digital projects; German precision with artistic sensibility; custom interactive tools for research and journalism; making data exploration beautiful.
- Fathom Information Design: Boston studio creating exploratory visualization tools; emphasis on giving form to complex data for understanding; work spanning journalism, technology, and cultural institutions; Ben Fry co-founder bringing Processing heritage; large-scale data exploration interfaces; bridging design and data science.

## Data storytelling, analysis & dashboards

- Hans Rosling “animated revelation”: Start with a simple view, then reveal dimensions over time, narrating each surprise.
- Nate Silver uncertainty framing: Always show base rate, confidence intervals, and 3 scenarios (optimistic/base/pessimistic).
- The Economist data journalism: Dry wit, historical context, and one counterintuitive hook per piece.
- Tufte analytical note: No chartjunk, focus on comparisons, rates of change, and uncertainty, minimal adjectives.
- The Pudding narrative walkthrough: Step-by-step scrollytelling where each panel adds one new idea supported by data.
- Vertical-specific analytics voices: Hedge fund brief (risk-adjusted, downside first) vs publisher brief (audience, engagement, revenue).

## Strategy docs & decision memos

- Bezos 6 pager: 2-page narrative, no bullets, include a FAQ section at the end.
- Hamilton Helmer 7 Powers lens: For each idea, rate on all seven powers, with 1-line justification each.
- McKinsey pyramid principle: Start with the answer, then 3–5 MECE supporting points, each backed by data and exhibits.
- Amazon PR/FAQ: Write a future press release and FAQ first, then backfill tech and plan from there.
- Sequoia pitch memo: Problem, product, why now, market, traction, and unfair advantage, each in 2–3 sharp sentences.
- Andy Grove OKR check: State objective, 3–5 key results with metrics, and list explicit “what must be true” assumptions.

## Technical documentation & developer experience

- Stripe API docs: Progressive disclosure with copy-paste examples first, explanations and edge cases following.
- MDN reference entry: Summary, syntax, parameters, return value, examples, browser/env notes, and “gotchas” section.
- Unix man page: NAME, SYNOPSIS, DESCRIPTION, OPTIONS, EXAMPLES, EXIT STATUS, terse and scriptable.
- Django tutorial: Build a real, small app end-to-end with minimal theory upfront, explaining concepts as they appear.
- Elm-style error messages: Friendly, specific errors that show the code, explain the problem, and propose exact fixes.
- Rust compiler hints: Precise, technical messages with clear references, links, and suggestions for better patterns.

## Educational content & explanations

- Feynman chalkboard: Explain in everyday language, use analogies, then refine into more precise concepts.
- 3Blue1Brown intuition builds: Start from geometric/visual intuition, then gradually introduce formal notation.
- Khan Academy step ladder: Break concepts into tiny increments, with a check-for-understanding question at each step.
- Polya problem solving: Structure into Understand, Plan, Execute, Review, with explicit prompts at each phase.
- RadioLab narrative: Open with a human story or puzzle, meander through side paths, and return to a satisfying resolution.
- Past-exam-solver tutor: Teach only via similar past exam questions, with variations and common traps highlighted.

## Brand voice, marketing & product copy

- Apple product page: Minimal text, emotionally aspirational, benefits before specs, with one strong visual metaphor.
- J. Peterman catalog: Narrative, romantic descriptions with absurdly detailed backstories for otherwise mundane products.
- Basecamp announcements: Opinionated, conversational, occasionally contrarian, clearly stating what they refuse to do.
- Slack release notes: Friendly and humorous summaries of changes, highlighting the human impact not just the features.
- Enterprise trust voice: Calm, precise, risk-aware language with strong social proof and compliance notes.
- Developer-irreverent voice: Casual, witty, with in-jokes, focusing on speed and power over corporate polish.

## Code, architecture & tools

- Kent Beck small-step refactor: Propose a sequence of tiny safe changes, each independently testable, not a big bang.
- Elm architecture: Single source of truth model, pure view, explicit update, no hidden global state.
- Kent C. Dodds React style: Colocation of logic and UI, composition over configuration, hooks for reusable behavior.
- Unix philosophy CLI: Each command does one thing well, streams data, and composes cleanly with pipes.
- Stripe-like API design: Predictable resource naming, consistent verbs, excellent defaults, and idempotent operations.
- “Literate” code comments: Explain why over what, documenting invariants, trade-offs, and failure modes.

## Research synthesis & literature reviews

- Cochrane systematic review: Pre-registered search strategy, inclusion criteria, bias assessment, and meta-analysis tables.
- Annual Review survey: Broad, authoritative overview that clusters fields, evaluates progress, and identifies open questions.
- Karpathy-style paper summary: Start with the core intuition and big picture, then walk through architecture and results.
- Evidence map dashboard: Visual matrix of interventions vs outcomes with effect sizes and study quality.
- One-page clinical evidence brief: Population, intervention, comparator, outcomes (PICO) with clear takeaways for practice.

## Feedback, critique & review

- Pixar Braintrust session: Honest, additive feedback focused on possibilities, not prescriptions or ego protection.
- Linux kernel code review: Blunt, technical, reference-backed comments that prioritize correctness over politeness.
- New Yorker fact-checker edit: Line-by-line queries on every claim, name, and number, asking for sources and clarifications.
- Radical Candor 1:1: Direct, specific feedback that shows personal care and insists on clear next steps.
- Student-assessment rubric: Criteria-based comments, each tied to a scale and an example of “what good looks like.”

## Meetings, workshops & facilitation

- Amazon pre-read meeting: First 15 minutes silent reading of a written doc, followed by structured Q&A.
- Liberating Structures retro: Use TRIZ, 1-2-4-All, and What–So What–Now What to involve everyone within 60 minutes.
- IDEO design sprint: Time-boxed phases of understand–diverge–converge–prototype–test with explicit activities and prompts.
- Decision-clinic workshop: One real decision, multiple framed options, pros/cons, and a forced choice with review.

## Interviews, user research & discovery

- Jobs-to-be-done interview: Map timeline, moments of struggle, pushes, pulls, anxieties, and habits around a “hire.”
- Therapist-style (CBT-lite) interview: Gently probe situations, thoughts, emotions, behaviors, and alternative choices.
- Press conference grilling: Short setup question followed by relentless follow-ups that attack assumptions and gaps.
- Founders’ origin-story interview: Focus on personal “why,” non-obvious constraints, and inflection points in the journey.

## Negotiation, escalation & difficult conversations

- Chris Voss negotiation: Use mirroring, labeling (“it sounds like…”), and calibrated “how/what” questions to move forward.
- Diplomat decline: Graciously acknowledge value, decline clearly, propose an alternate path, preserve relationship.
- Japanese business politeness: Indirect negative responses, face-saving language, heavy use of honorifics and apologies.
- “Disagree and commit” email: State disagreement succinctly, record reasoning, and explicitly commit to the chosen path.

## Email & professional correspondence

- Patrick McKenzie cold email: Highly specific, researched, focused on clear value and a tiny, low-friction next step.
- Bezos internal memo: Narrative-only email with context, analysis, and clear decision request at the end.
- Exec status snapshot: One screen: green/yellow/red, 3 bullets on progress, 3 on risks, 3 on asks.
- Support reply like Superhuman: Short, fast, clear fix with one delightful extra tip or shortcut.

Deterministic emails

- Axios/Morning Brew: Structured sections ("The big picture", "By the numbers", "Why it matters"), short paragraphs, scannable bullets, deterministic headers map to conditional logic.
- SaaS metrics dashboard email (ChartMogul/Baremetrics): Visual hierarchy with key metric cards, % changes with arrows, sparkline-style trends, one-line insights per metric.
- McKinsey exec summary: Situation/Complication/Resolution format, pyramid principle with conclusion first, 3 supporting points, action-oriented bottom line.
- FiveThirtyEight data journalism: Lead with the most surprising number, explain what's driving it, context through comparison, "What this means" actionable takeaway.
- Internal SaaS weekly update (Stripe/Gitlab): Metrics table first, 2-3 narrative highlights, blockers/risks if any, clear next actions with owners.

## Personal reflection, thinking & journaling

- Stoic evening review: List events, your reactions, which judgments were mistaken, and what to practice tomorrow.
- CBT thought record: Situation, automatic thought, emotion (0–100), evidence for/against, and a more balanced thought.
- Andy Matuschak evergreen notes: Break insights into small, linkable claims with titles, backlinks, and follow-up questions.
- Annie Duke decision journal: Record options, probabilities, reasons, and what evidence would later count as “resulting.”

## Diagrams, models & system maps

- Wardley map: List user needs, components, and place them by visibility and evolution stage, with movement arrows.
- Causal loop diagram: Variables connected with +/– links, highlighting reinforcing and balancing feedback loops.
- Actor-network map: Explicitly show humans, orgs, tools, and data stores, with labeled relationships and dependencies.
- Service blueprint: Customer actions, frontstage, backstage, and support processes aligned across swimlanes.

## Experiments, A/B tests & research design

- RCT economist style: Clear hypothesis, randomization plan, outcome metrics, and identification of threats to validity.
- Lean Startup smoke test: Smallest experiment with a clear learning metric and explicit kill/scale thresholds.
- Behavioral pre-registration: Hypotheses, manipulations, measures, exclusion criteria, and analysis plan fixed upfront.
- Sequential test log: Predefine stopping rules and update posterior beliefs as data accumulates.

## House styles for clients & verticals

- Hedge fund insight note: Start with P&L or risk impact, then factor exposures, scenarios, and implementation caveats.
- Publisher performance brief: Focus on audience, attention, engagement funnels, and monetization levers.
- Pharma/clinical summary: Emphasize safety, efficacy, regulatory status, and impact on standard of care.
- Education analytics report: Student outcomes, equity implications, intervention effects, and actionable classroom changes.
