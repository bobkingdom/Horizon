---
layout: default
title: "Horizon Summary: 2026-06-24 (EN)"
date: 2026-06-24
lang: en
---

> From 32 items, 12 important content pieces were selected

---

1. [Baidu Unlimited-OCR Enables One-Shot Long-Document Parsing](#item-1) ⭐️ 8.0/10
2. [LLMs Confuse Roles by Text Style, Enabling Jailbreaks](#item-2) ⭐️ 8.0/10
3. [FUTO Releases Improved Open Swipe Typing Model](#item-3) ⭐️ 7.0/10
4. [Swift Package Index Joins Apple](#item-4) ⭐️ 7.0/10
5. [Open-Source WYSIWYG TikZ Editor for LaTeX Released](#item-5) ⭐️ 7.0/10
6. [Blog Explores Rise of Iterative AI Loops in Software Development](#item-6) ⭐️ 7.0/10
7. [Simon Willison Ports Moebius 0.2B Inpainting Model to Browser via WebGPU](#item-7) ⭐️ 7.0/10
8. [Hugging Face Revives PapersWithCode with SOTA Badges and New Trending Scores](#item-8) ⭐️ 7.0/10
9. [Germany Halts All Trains Due to GSM-R Communication Outage](#item-9) ⭐️ 6.0/10
10. [Datasette 1.0a35 Adds Create and Alter Table UI Features](#item-10) ⭐️ 6.0/10
11. [Reddit Asks If ML Teams Test for Extraction and Poisoning Risks](#item-11) ⭐️ 6.0/10
12. [Benchmark Tests LLM Vulnerability Detection with Modified Juliet CWEs](#item-12) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Baidu Unlimited-OCR Enables One-Shot Long-Document Parsing](https://github.com/baidu/Unlimited-OCR) ⭐️ 8.0/10

Baidu released Unlimited-OCR, introducing a one-shot long-horizon parsing method that keeps the KV cache fixed during transcription of lengthy documents. The approach builds on Deepseek-OCR models and maintains constant output latency even for multi-page inputs up to 20 pages. This removes the need for chunking long PDFs and prevents VRAM crashes caused by linear KV cache growth, enabling efficient end-to-end document processing. It advances practical long-context OCR applications in industries handling large reports, books, and archives. The KV cache remains constant instead of growing O(N), delivering stable latency; the model was tested on an in-house benchmark of novels, documents, and papers, and the paper is available at arXiv 2606.23050.

hackernews · ingve · Jun 23, 11:35 · [Discussion](https://news.ycombinator.com/item?id=48643426)

**Background**: Transformer-based OCR models store key-value pairs in a KV cache to attend to previous tokens; this cache grows linearly with input length, quickly exhausting GPU memory on long documents and forcing developers to split inputs manually.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/html/2606.23050">Unlimited OCR Works Welcome the Era of One - shot Long - horizon ...</a></li>
<li><a href="https://huggingface.co/baidu/Unlimited-OCR">baidu/Unlimited-OCR · Hugging Face</a></li>

</ul>
</details>

**Discussion**: Commenters praised the architectural memory optimization and noted its potential for optical music recognition; others highlighted the Fate/stay night reference in the project name and appreciated acknowledgments to Deepseek-OCR and PaddleOCR.

**Tags**: `#OCR`, `#AI/ML`, `#Document Parsing`, `#Computer Vision`, `#Long-context Models`

---

<a id="item-2"></a>
## [LLMs Confuse Roles by Text Style, Enabling Jailbreaks](https://simonwillison.net/2026/Jun/22/prompt-injection-as-role-confusion/#atom-everything) ⭐️ 8.0/10

Charles Ye, Jasmine Cui, and Dylan Hadfield-Menell published research showing LLMs prioritize writing style over role tags such as <system> and <user>. Appending style-matched text to a cocaine-making request caused models like gpt-oss-20b to override safety training, while destyling reduced attack success from 61% to 10%. This reveals a fundamental flaw in how current LLMs separate trusted system instructions from untrusted user input, making prompt injection defenses unreliable. The finding affects all models using role tags and suggests injection attacks will remain a persistent problem without genuine role perception. The paper demonstrates that models classify text by stylistic similarity to expected role formats rather than explicit tags, and subtle rewrites invisible to humans dramatically alter model behavior. The work was accepted to ICML 2026 and includes a readable blog-style companion site.

rss · Simon Willison · Jun 22, 23:59

<details><summary>References</summary>
<ul>
<li><a href="https://role-confusion.github.io/">Prompt Injection as Role Confusion</a></li>
<li><a href="https://github.com/role-confusion/prompt-injection-as-role-confusion">GitHub - role-confusion/prompt-injection-as-role-confusion: Prompt Injection as Role Confusion · GitHub</a></li>

</ul>
</details>

**Tags**: `#prompt-injection`, `#AI-safety`, `#LLMs`, `#role-confusion`, `#jailbreaks`

---

<a id="item-3"></a>
## [FUTO Releases Improved Open Swipe Typing Model](https://swipe.futo.tech/) ⭐️ 7.0/10

FUTO has released an improved swipe-typing model for its privacy-focused Android keyboard, trained on over one million user-contributed swipes from the swipe.futo.org dataset. A testing version is now available and early users report accuracy comparable to Gboard. This development delivers the first practical open swipe-typing solution that avoids proprietary or privacy-invasive libraries, enabling better alternatives on Android and potentially other platforms. It directly addresses long-standing accuracy and licensing barriers in mobile input methods. The swipe library is licensed under GPLv3 while the full Android keyboard uses the Futo License; the model was developed over a year using community swipe data and focuses on handling similar words and letter doubling issues common in swipe typing.

hackernews · futohq · Jun 23, 17:50 · [Discussion](https://news.ycombinator.com/item?id=48648619)

**Background**: Swipe typing lets users enter words by sliding a finger across on-screen keys instead of tapping each letter. Privacy-focused keyboards like FUTO Keyboard run entirely offline without sending data to servers, unlike many mainstream alternatives.

<details><summary>References</summary>
<ul>
<li><a href="https://swipe.futo.tech/">FUTO Swipe</a></li>
<li><a href="https://github.com/futo-org/android-keyboard/releases">Releases · futo-org/android-keyboard</a></li>
<li><a href="https://news.ycombinator.com/item?id=48648619">FUTO Swipe – A new swipe typing model | Hacker News</a></li>

</ul>
</details>

**Discussion**: HN users report the new model feels as good as Gboard for daily use, praising speed and one-handed operation, though some note remaining issues with apostrophes, mid-sentence capitalization, and lack of sentence context. License differences between the library and keyboard app were also highlighted.

**Tags**: `#swipe-typing`, `#mobile-keyboards`, `#privacy`, `#input-methods`, `#open-source`

---

<a id="item-4"></a>
## [Swift Package Index Joins Apple](https://swiftpackageindex.com/blog/swift-package-index-joins-apple) ⭐️ 7.0/10

Swift Package Index, the community-run search engine for Swift packages, has joined Apple as announced on its official blog. The acquisition raises questions about the future direction of this key resource in the Swift ecosystem and could affect how developers discover and rely on packages. The site indexes metadata from 11,162 packages, remains open source on GitHub, and may expand into areas such as developer identity according to the announcement.

hackernews · JDevlieghere · Jun 23, 18:00 · [Discussion](https://news.ycombinator.com/item?id=48648779)

**Background**: The Swift Package Index serves as a searchable directory for packages compatible with the Swift Package Manager, the official dependency management tool in the Swift ecosystem.

<details><summary>References</summary>
<ul>
<li><a href="https://swiftpackageindex.com/">Swift Package Index</a></li>
<li><a href="https://www.swift.org/packages/">Packages | Swift.org</a></li>

</ul>
</details>

**Discussion**: Community sentiment is mixed with some expressing optimism about team compensation and integration while others voice concerns over Apple's open source track record and potential package regulation.

**Tags**: `#Swift`, `#Apple`, `#Package Manager`, `#Open Source`, `#Developer Tools`

---

<a id="item-5"></a>
## [Open-Source WYSIWYG TikZ Editor for LaTeX Released](https://tikz.dev/editor/) ⭐️ 7.0/10

An open-source WYSIWYG TikZ editor for LaTeX was released that syncs visual dragging and resizing of elements with precise source code edits in real time. This tool reduces the manual coordinate tweaking common in academic figure creation, potentially improving workflows for researchers using LaTeX while demonstrating advanced AI-assisted development of complex domain-specific editors. The editor parses TikZ code to track exact source locations of objects, enabling minimal targeted updates during visual edits; it required reimplementing substantial parts of TikZ plus features like SVG to TikZ converters and LaTeX hyphenation.

hackernews · DominikPeters · Jun 23, 14:24 · [Discussion](https://news.ycombinator.com/item?id=48645437)

**Background**: TikZ is a widely used LaTeX package for creating figures in academic papers through code commands such as drawing lines and shapes with coordinates and loops. Academics traditionally edit these figures by manually adjusting coordinates and recompiling, similar to working with SVG but in a more programmatic style.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/PGF/TikZ">PGF/TikZ - Wikipedia</a></li>
<li><a href="https://tikz.dev/">PGF/TikZ Manual - Complete Online Documentation</a></li>

</ul>
</details>

**Discussion**: Users praised the UI and open-source release but criticized generated code for relying on unnecessary absolute coordinates instead of relative TikZ idioms; requests emerged for Typst and cetz support, while the developer noted extensive use of Codex costing significant tokens over months of work.

**Tags**: `#LaTeX`, `#TikZ`, `#WYSIWYG editor`, `#open-source`, `#academic tools`

---

<a id="item-6"></a>
## [Blog Explores Rise of Iterative AI Loops in Software Development](https://lucumr.pocoo.org/2026/6/23/the-coming-loop/) ⭐️ 7.0/10

Armin Ronacher's blog post 'The Coming Loop' examines the growing use of iterative AI agent loops for software development workflows. This signals a shift toward agentic coding where AI systems autonomously plan, build, and refine code, potentially transforming developer productivity and team processes across the industry. The post and accompanying discussion highlight that effective loops require upfront clarity in specifications equivalent to briefing a junior developer, with LLMs excelling at task completion but struggling with aesthetics and taste.

hackernews · ingve · Jun 23, 11:06 · [Discussion](https://news.ycombinator.com/item?id=48643180)

**Background**: Agentic coding refers to the use of AI agents powered by large language models that can plan, write, test, and modify code with minimal human intervention, as defined in sources on AI-assisted development.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Agentic_coding">Agentic coding</a></li>
<li><a href="https://cloud.google.com/discover/what-is-agentic-coding">What is agentic coding? How it works and use cases | Google Cloud</a></li>

</ul>
</details>

**Discussion**: HN commenters stress that loops demand significant upfront thinking and spec writing by humans, noting LLMs are poor at aesthetics while effective at goal-driven tasks like security exploits, and that excessive error handling remains a common LLM flaw.

**Tags**: `#AI Agents`, `#LLMs`, `#Software Development`, `#Iterative Workflows`, `#Agentic Coding`

---

<a id="item-7"></a>
## [Simon Willison Ports Moebius 0.2B Inpainting Model to Browser via WebGPU](https://simonwillison.net/2026/Jun/22/porting-moebius/#atom-everything) ⭐️ 7.0/10

Simon Willison used Claude Code to port the 0.2B Moebius image inpainting model from PyTorch and NVIDIA CUDA to run via ONNX Runtime Web on the WebGPU backend in the browser, releasing a live demo at simonw.github.io/moebius-web/. This demonstrates practical on-device AI capabilities for image inpainting tasks without requiring server-side GPUs, advancing accessible browser-based machine learning for users and developers. The port relied on ONNX Runtime Web rather than Transformers.js; the model handles non-square images via letterboxing and allows users to mark regions for inpainting before running inference.

rss · Simon Willison · Jun 22, 23:43

**Background**: Image inpainting uses AI models to fill in masked or removed regions of an image. WebGPU enables GPU-accelerated computation directly in web browsers, while ONNX Runtime Web provides a runtime for executing converted models in JavaScript environments.

<details><summary>References</summary>
<ul>
<li><a href="https://simonwillison.net/2026/Jun/22/porting-moebius/">Porting the Moebius 0.2B image inpainting model to run in the browser with Claude Code</a></li>
<li><a href="https://github.com/hustvl/Moebius">GitHub - hustvl/Moebius: [ECCV 2026] Moebius: 0.2B Lightweight Image Inpainting Framework with 10B-Level Performance · GitHub</a></li>
<li><a href="https://hustvl.github.io/Moebius/">Moebius Project Page</a></li>

</ul>
</details>

**Tags**: `#machine-learning`, `#webgpu`, `#browser-ai`, `#image-inpainting`, `#model-porting`

---

<a id="item-8"></a>
## [Hugging Face Revives PapersWithCode with SOTA Badges and New Trending Scores](https://www.reddit.com/r/MachineLearning/comments/1ucm508/some_new_updates_to_papers_with_code_p/) ⭐️ 7.0/10

Hugging Face's open-source team announced updates to PapersWithCode.co including SOTA badges for top-3 benchmark results, a new trending score combining GitHub star velocity with Hugging Face artifacts, support for external evaluations, and additional benchmarks such as ImageNet subsets and 3D semantic segmentation. These updates improve research discovery on a key ML platform during a renewed focus on research, helping researchers identify influential papers like GLM-5.2 and build upon prior work more effectively. SOTA badges appear on paper feeds for top-3 benchmark scores; the trending metric now includes Hugging Face models, datasets, and Spaces; external evals cover third-party results on tasks like agents and reasoning.

reddit · r/MachineLearning · /u/NielsRogge · Jun 22, 14:29

<details><summary>References</summary>
<ul>
<li><a href="https://posttrainbench.com/?trk=public_post_comment-text">PostTrainBench</a></li>
<li><a href="https://llm-stats.com/benchmarks/posttrainbench">PostTrainBench Leaderboard | LLM Stats</a></li>

</ul>
</details>

**Tags**: `#Machine Learning`, `#Research Tools`, `#Papers with Code`, `#Benchmarks`, `#Hugging Face`

---

<a id="item-9"></a>
## [Germany Halts All Trains Due to GSM-R Communication Outage](https://apnews.com/article/germany-trains-halted-communications-radio-problem-deutsche-bahn-e8fd970b2d889f3ae7ce03322d5c726b) ⭐️ 6.0/10

Deutsche Bahn halted nationwide train services due to a complete outage of the GSM-R digital rail radio system. The outage disrupted critical transportation infrastructure, affecting passengers and freight across Germany and exposing reliance on specialized communication networks. Discussions suggest a buggy software update as the likely cause, though Deutsche Bahn only confirmed the GSM-R failure without detailing the root cause.

hackernews · sva_ · Jun 23, 21:19 · [Discussion](https://news.ycombinator.com/item?id=48651613)

**Background**: GSM-R is a digital communication standard based on GSM technology, designed for secure voice and data exchange between train drivers and traffic control centers.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GSM-R">GSM-R - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Users speculated the outage resulted from maintenance issues or a software update rather than a cyber attack, with references to German news sources and recent UK train incidents.

**Tags**: `#infrastructure`, `#outage`, `#railway`, `#software-update`, `#gsm-r`

---

<a id="item-10"></a>
## [Datasette 1.0a35 Adds Create and Alter Table UI Features](https://simonwillison.net/2026/Jun/23/datasette/#atom-everything) ⭐️ 6.0/10

Datasette 1.0a35 introduces a new create table interface backed by the /<database>/-/create JSON API and an alter table action with the /<database>/<table>/-/alter JSON API. It also adds comprehensive template context documentation generated from dataclass definitions. These updates improve direct web-based management of SQLite tables, making Datasette more practical for data exploration and publishing workflows used by journalists and developers. Create table supports columns, primary keys, custom types, NOT NULL constraints, defaults and single-column foreign keys. Alter table enables adding, renaming, reordering, dropping columns and modifying types, defaults, constraints, keys plus table renaming.

rss · Simon Willison · Jun 23, 21:34

**Tags**: `#datasette`, `#software-release`, `#sqlite`, `#data-tools`, `#json-api`

---

<a id="item-11"></a>
## [Reddit Asks If ML Teams Test for Extraction and Poisoning Risks](https://www.reddit.com/r/MachineLearning/comments/1uddtws/are_model_security_risks_extraction_poisoning/) ⭐️ 6.0/10

A Reddit post in r/MachineLearning questions whether production ML teams perform adversarial testing for model extraction and poisoning attacks before deployment. The discussion highlights a practical gap where model security practices lag behind traditional software security, potentially leaving deployed AI systems exposed to attacks. The post notes that many teams ship models without testing for extraction attacks via API queries or poisoning of training data, asking for real-world examples from practitioners.

reddit · r/MachineLearning · /u/Xorphian · Jun 23, 10:52

**Background**: Model extraction attacks allow adversaries to replicate a model's functionality by querying its API outputs, while model poisoning attacks corrupt training data to degrade performance or introduce bias.

<details><summary>References</summary>
<ul>
<li><a href="https://www.praetorian.com/blog/stealing-ai-models-through-the-api-a-practical-model-extraction-attack/">Stealing AI Models Through the API: A Practical Model Extraction Attack | Praetorian</a></li>
<li><a href="https://www.csoonline.com/article/570555/how-data-poisoning-attacks-corrupt-machine-learning-models.html">What is data poisoning ? Attacks thatcorrupt machine learning models</a></li>

</ul>
</details>

**Tags**: `#model security`, `#adversarial testing`, `#ML deployment`, `#AI safety`, `#production ML`

---

<a id="item-12"></a>
## [Benchmark Tests LLM Vulnerability Detection with Modified Juliet CWEs](https://www.reddit.com/r/MachineLearning/comments/1ud0rft/nondeterministic_vulnerability_detection/) ⭐️ 6.0/10

A work-in-progress benchmark modifies Juliet CWEs into realistic codebases and injects LLM-generated comments in accurate, misleading, or neutral styles to evaluate non-deterministic vulnerability detection performance. This approach addresses LLM advantages from recognizing known test patterns and reveals how natural language comments can influence detection accuracy, impacting AI-based code security tools. The system uses several hundred CWEs with sufficient code volume to fill input contexts; remaining work includes presentation, benchmarking published LLMs, and pruning CWEs occasionally recognized as Juliet code.

reddit · r/MachineLearning · /u/Psychological_Meat_6 · Jun 22, 23:34

**Background**: The Juliet Test Suite from NIST provides thousands of small C/C++ and Java test cases each tied to specific CWEs representing common software weaknesses. Researchers adapt these for evaluating static analysis tools and now LLMs by embedding vulnerabilities in larger, realistic contexts.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/arichardson/juliet-test-suite-c">GitHub - arichardson/ juliet - test - suite -c · GitHub</a></li>
<li><a href="https://github.com/UnitTestBot/juliet-java-test-suite">GitHub - UnitTestBot/ juliet -java-test-suite: Juliet Java test suite is...</a></li>

</ul>
</details>

**Tags**: `#LLM evaluation`, `#vulnerability detection`, `#benchmarks`, `#code security`, `#cybersecurity`

---