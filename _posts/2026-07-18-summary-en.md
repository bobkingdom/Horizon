---
layout: default
title: "Horizon Summary: 2026-07-18 (EN)"
date: 2026-07-18
lang: en
---

> From 37 items, 11 important content pieces were selected

---

1. [Thinking Machines Lab Releases 975B Open-Weights Inkling MoE Model](#item-1) ⭐️ 8.0/10
2. [Linus Torvalds Strongly Endorses AI for Linux Kernel Development](#item-2) ⭐️ 8.0/10
3. [First Atmosphere Detected on Rocky Exoplanet LHS 1140b](#item-3) ⭐️ 7.0/10
4. [Moonshot AI Launches Kimi K3 2.8T Model Tested via Pelican Benchmark](#item-4) ⭐️ 7.0/10
5. [Firefox Compiled to WebAssembly Runs Inside Chrome](#item-5) ⭐️ 7.0/10
6. [Stereo2Spatial Releases Flow-Matching Model for Stereo-to-Spatial Audio Conversion](#item-6) ⭐️ 7.0/10
7. [EU AI Act OpenRAG Releases 933 Legally Structured Chunks with BGE-M3 Embeddings](#item-7) ⭐️ 7.0/10
8. [ExTernD Enables High-Accuracy Ternary LLM PTQ via Expanded-Rank Decomposition](#item-8) ⭐️ 7.0/10
9. [Recurse Center Founder Thanks HN for 15 Years of Support](#item-9) ⭐️ 6.0/10
10. [Blog Post Shares Practical SQLite Running Tips with HN Insights](#item-10) ⭐️ 6.0/10
11. [Questioning if AI Memory Architectures Optimize the Wrong Abstraction](#item-11) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Thinking Machines Lab Releases 975B Open-Weights Inkling MoE Model](https://simonwillison.net/2026/Jul/16/inkling/#atom-everything) ⭐️ 8.0/10

Thinking Machines Lab released Inkling, a 975B-parameter multimodal MoE model with 41B active parameters, trained on 45 trillion tokens under an Apache-2.0 license. The release strengthens the US open-weights ecosystem with a competitive multimodal model and offers a customizable base via the Tinker fine-tuning platform. Inkling handles text, images, audio and video; a smaller 276B Inkling-Small variant is promised later, though the model card and training data documentation remain notably brief.

rss · Simon Willison · Jul 16, 15:35

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/blog/moe">Mixture of Experts Explained - Hugging Face</a></li>

</ul>
</details>

**Tags**: `#open-weights`, `#multimodal models`, `#Mixture-of-Experts`, `#AI model release`, `#large language models`

---

<a id="item-2"></a>
## [Linus Torvalds Strongly Endorses AI for Linux Kernel Development](https://simonwillison.net/2026/Jul/16/linus-torvalds/#atom-everything) ⭐️ 8.0/10

Linus Torvalds stated on the Linux Media Mailing List that Linux is not an anti-AI project and that dissenters can fork it or walk away, calling AI a clearly useful tool whose value is no longer in question. As the top-level maintainer of the Linux kernel, Torvalds' firm stance signals mainstream acceptance of AI tools in critical open-source infrastructure and may encourage wider adoption across the industry. Torvalds emphasized that doubts about AI usefulness stem from lack of actual use, while acknowledging separate open questions around its economic impact.

rss · Simon Willison · Jul 16, 13:26

**Tags**: `#AI`, `#Linux kernel`, `#Open source`, `#Linus Torvalds`, `#Software development`

---

<a id="item-3"></a>
## [First Atmosphere Detected on Rocky Exoplanet LHS 1140b](https://www.bbc.com/news/articles/cy4kdd1e0ejo) ⭐️ 7.0/10

BBC reports the first detection of an atmosphere on rocky exoplanet LHS 1140b in the habitable zone of a red dwarf star using JWST spectroscopy. This discovery advances the search for potentially habitable worlds beyond our solar system and highlights challenges of atmospheric retention around red dwarfs. JWST emission spectroscopy rules out a mini-Neptune scenario for LHS 1140b, confirming it as a rocky planet 48 light years away despite stellar activity concerns.

hackernews · neversaydie · Jul 17, 14:06 · [Discussion](https://news.ycombinator.com/item?id=48947560)

**Background**: Red dwarf stars are cooler and smaller than the Sun, placing their habitable zones closer in where planets face intense stellar winds that can strip atmospheres. Rocky exoplanets in these zones are key targets for assessing habitability using telescopes like JWST.

**Discussion**: Commenters express skepticism about atmospheric retention around red dwarfs and debate whether LHS 1140b is truly Earth-like or a stripped mini-Neptune, with JWST data cited as confirmation of its rocky nature. Discussions also cover future technologies like solar lens telescopes, interstellar propulsion, and implications for the Fermi paradox.

**Tags**: `#exoplanets`, `#astronomy`, `#JWST`, `#habitability`, `#atmospheres`

---

<a id="item-4"></a>
## [Moonshot AI Launches Kimi K3 2.8T Model Tested via Pelican Benchmark](https://simonwillison.net/2026/Jul/16/kimi-k3/#atom-everything) ⭐️ 7.0/10

Moonshot AI announced Kimi K3, a 2.8 trillion parameter model available now via website and API, with an open-weights release scheduled for July 27, 2026. Self-reported benchmarks show it outperforming several Claude and GPT variants while leading the Frontend Code arena. As the first open 3T-class model from a Chinese lab with competitive pricing and strong long-horizon performance, Kimi K3 intensifies global AI competition and could accelerate open-weights adoption across the industry. Kimi K3 costs $3 per million input tokens and $15 per million output tokens, uses 21% fewer output tokens than its predecessor, and generated a pelican SVG using 16,658 output tokens including 13,241 reasoning tokens at a cost of 25 cents.

rss · Simon Willison · Jul 16, 20:19 · [Discussion](https://news.ycombinator.com/item?id=48947717)

**Background**: The pelican benchmark is an informal test created by Simon Willison that prompts models to generate an SVG of a pelican riding a bicycle, used for over 21 months to evaluate code generation and creative capabilities across LLMs.

<details><summary>References</summary>
<ul>
<li><a href="https://simonwillison.net/tags/pelican-riding-a-bicycle/">Simon Willison on pelican -riding-a-bicycle</a></li>
<li><a href="https://news.ycombinator.com/item?id=48947717">Kimi K3, and what we can still learn from the pelican benchmark</a></li>

</ul>
</details>

**Discussion**: Commenters noted possible hidden system prompts inflating token counts, questioned the pelican benchmark's relevance to agentic tool use, and observed that Kimi K3 offers lower cost but slower speed compared to recent Claude models.

**Tags**: `#AI models`, `#benchmarks`, `#large language models`, `#Moonshot AI`, `#open weights`

---

<a id="item-5"></a>
## [Firefox Compiled to WebAssembly Runs Inside Chrome](https://simonwillison.net/2026/Jul/16/firefox-in-webassembly/#atom-everything) ⭐️ 7.0/10

Puter compiled Firefox to WebAssembly so the entire browser runs inside another browser such as Chrome. The project used an estimated $25,000 worth of Claude Opus and Fable tokens along with the Wisp protocol for networking. This demonstrates the feasibility of running complete desktop applications like browsers entirely within web environments using WebAssembly and AI-assisted development. It highlights advancements in browser emulation and cross-browser compatibility. Firefox was chosen for its strong single-process support. The demo routes all traffic through a WebSocket using the Wisp protocol, supports end-to-end encryption, and required server scaling to handle traffic during public discussion.

rss · Simon Willison · Jul 16, 23:34

**Background**: WebAssembly is a binary instruction format that allows high-performance code to run in web browsers. Compiling complex software like browsers to WASM enables them to execute in sandboxed environments without native installation.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/MercuryWorkshop/wisp-protocol">GitHub - MercuryWorkshop/wisp-protocol: Wisp is a low-overhead, easy to implement protocol for proxying multiple TCP/UDP sockets over a single websocket. · GitHub</a></li>

</ul>
</details>

**Discussion**: The Hacker News discussion highlighted the technical achievement but noted the high computational cost and server scaling requirements for handling traffic.

**Tags**: `#WebAssembly`, `#Firefox`, `#Browsers`, `#Emulation`, `#AI-assisted porting`

---

<a id="item-6"></a>
## [Stereo2Spatial Releases Flow-Matching Model for Stereo-to-Spatial Audio Conversion](https://www.reddit.com/r/MachineLearning/comments/1uzevbg/stereo2spatial_convert_stereo_music_tracks_to/) ⭐️ 7.0/10

Developer francislabounty released Stereo2Spatial, a flow-matching diffusion model that converts stereo tracks to spatial binaural mixes, initially using EAR-VAE latent space with memory tokens then pivoting to raw waveforms with amplitude lifting for stability. The open-source release under Apache 2.0, including Hugging Face models, training code, and a Windows app, enables accessible conversion of existing stereo music libraries into spatial formats, advancing practical AI tools for audio spatialization amid growing demand for immersive listening. The waveform model trained for 20 days on 2x A6000 GPUs across 7,669 tracks using sequences up to 122 seconds; it incorporates optional mix-style conditioning and was stabilized via amplitude lifting to RMS 0.33 then scaled by 3, avoiding prior instability at 60K-80K steps.

reddit · r/MachineLearning · /u/kittenkrazy · Jul 17, 22:55

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2601.12950">[2601.12950] ImmersiveFlow: Stereo-to-7.1.4 spatial audio generation with flow matching</a></li>

</ul>
</details>

**Tags**: `#machine learning`, `#diffusion models`, `#audio processing`, `#spatial audio`, `#generative models`

---

<a id="item-7"></a>
## [EU AI Act OpenRAG Releases 933 Legally Structured Chunks with BGE-M3 Embeddings](https://www.reddit.com/r/MachineLearning/comments/1uytlac/eu_ai_act_openrag_933_legally_structured_chunks/) ⭐️ 7.0/10

The EU AI Act OpenRAG corpus was released as a single SQLite database containing 933 chunks derived from Regulation (EU) 2024/1689, structured by legal elements such as articles, recitals, and definitions rather than sliding windows, each paired with normalized 1024-dimensional BGE-M3 embeddings. This release provides a ready-to-use, legally accurate dataset for RAG and legal-NLP tasks focused on the EU AI Act, enabling better experimentation in regulatory AI and compliance tools that affect developers and organizations worldwide. Evaluation on the AI Act Benchmark showed structural chunking achieving scenario article recall@20 of 0.541 versus 0.449 for sliding-window baselines, with QA article hit@10 at 0.927 versus 0.898; the dataset includes EUR-Lex links and application-date metadata while keeping ambiguous labels as NULL.

reddit · r/MachineLearning · /u/Automatic-Forever-63 · Jul 17, 08:18

**Background**: RAG refers to retrieval-augmented generation techniques that combine document retrieval with language model generation. BGE-M3 is an embedding model supporting dense, multi-vector, and sparse retrieval. The EU AI Act is Regulation (EU) 2024/1689, the first comprehensive legal framework for AI in Europe.

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/BAAI/bge-m3">BAAI/bge-m3 · Hugging Face</a></li>
<li><a href="https://artificialintelligenceact.eu/">EU Artificial Intelligence Act | Up-to-date developments and analyses of...</a></li>

</ul>
</details>

**Tags**: `#EU AI Act`, `#RAG`, `#Legal NLP`, `#Dataset`, `#Embeddings`

---

<a id="item-8"></a>
## [ExTernD Enables High-Accuracy Ternary LLM PTQ via Expanded-Rank Decomposition](https://www.reddit.com/r/MachineLearning/comments/1uy2zb3/externd_expandedrank_ternary_decomposition/) ⭐️ 7.0/10

ExTernD introduces a post-training factorization that decomposes each LLM weight matrix into two ternary matrices and an inner diagonal scaling matrix with arbitrarily large rank. The approach achieves ternary quantization accuracy approaching higher-bit methods while adding only modest VRAM overhead, enabling more efficient LLM inference and deployment. The inner rank can be increased to reduce error arbitrarily without requiring very large values, and the method shows only slightly higher VRAM usage than existing quantization techniques.

reddit · r/MachineLearning · /u/LMTLS5 · Jul 16, 13:31

**Background**: Post-training quantization (PTQ) compresses large language models after training by reducing weight precision. Ternary quantization restricts weights to the set {-1, 0, +1} for extreme compression.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/html/2607.13511">ExTernD: Expanded - Rank Ternary Decomposition Ternary LLM ...</a></li>

</ul>
</details>

**Tags**: `#LLM Quantization`, `#Post-Training Quantization`, `#Ternary Decomposition`, `#Model Compression`, `#Machine Learning`

---

<a id="item-9"></a>
## [Recurse Center Founder Thanks HN for 15 Years of Support](https://news.ycombinator.com/item?id=48949551) ⭐️ 6.0/10

The founder of Recurse Center posted on Hacker News to mark the 15th anniversary, crediting the community for support after pivoting from a failed 2010 Y Combinator idea called OkCupid for jobs to a self-directed programming retreat. The post highlights how Hacker News helped the project reach programmers worldwide and grow into a program that has positively impacted over 3,000 people while allowing the founder to pursue meaningful work. Recurse Center runs free self-directed retreats funded by its recruiting agency where companies pay to hire alumni, and it received its initial major exposure from a 2011 Hacker News launch post.

hackernews · nicholasjbs · Jul 17, 16:57

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Recurse_Center">Recurse Center - Wikipedia</a></li>
<li><a href="https://www.recurse.com/about">About RC - Recurse Center</a></li>

</ul>
</details>

**Discussion**: Alumni shared fond memories of their time at Recurse Center in New York, expressed gratitude for the community, and discussed its free pricing model funded through recruiting without affecting participant salaries.

**Tags**: `#recurse-center`, `#hacker-news`, `#programming-education`, `#startup-story`, `#community`

---

<a id="item-10"></a>
## [Blog Post Shares Practical SQLite Running Tips with HN Insights](https://jvns.ca/blog/2026/07/17/learning-about-running-sqlite/) ⭐️ 6.0/10

A blog post shares practical tips on running SQLite, with HN discussion adding insights on backups, query plans, and tools. This offers actionable advice that helps developers improve SQLite database management, backups, and query performance in real-world applications. Notable details include SQLite's .expert mode for index recommendations, non-blocking WAL backups using zstd compression, and batch delete strategies to avoid locking issues.

hackernews · surprisetalk · Jul 17, 17:45 · [Discussion](https://news.ycombinator.com/item?id=48950122)

**Discussion**: Commenters highlight .expert mode for query analysis, a tool for generating scoped AWS S3 credentials, a zstd-compressed dump backup method that does not block writers, and strategies for efficient batch deletes.

**Tags**: `#sqlite`, `#databases`, `#backups`, `#sql`, `#tutorials`

---

<a id="item-11"></a>
## [Questioning if AI Memory Architectures Optimize the Wrong Abstraction](https://www.reddit.com/r/MachineLearning/comments/1uy6yht/are_current_ai_memory_architectures_optimizing/) ⭐️ 6.0/10

A Reddit post poses whether current AI memory systems should shift from storing descriptive facts about users to inferring higher-level reasoning patterns and abstractions. This conceptual question highlights potential limitations in existing persistent context mechanisms and could guide future designs toward more adaptive reasoning models in AI systems. The post contrasts examples like remembering user interests in economics with inferred patterns such as explaining outcomes through incentives and institutional constraints or understanding systems via feedback loops.

reddit · r/MachineLearning · /u/Boris_Ljevar · Jul 16, 16:00

**Tags**: `#AI memory`, `#persistent context`, `#machine learning`, `#reasoning architectures`, `#context management`

---