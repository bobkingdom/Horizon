---
layout: default
title: "Horizon Summary: 2026-09-16 (EN)"
date: 2026-09-16
lang: en
---

> From 31 items, 13 important content pieces were selected

---

1. [DIY E-Ink Frame Detects Birds with BirdNET and Draws 1800s Illustrations](#item-1) ⭐️ 8.0/10
2. [Google Releases Gemini 3.8 Live and Extended Thinking Models](#item-2) ⭐️ 8.0/10
3. [TabPFN-3.5 Released as New SOTA Tabular Foundation Model](#item-3) ⭐️ 8.0/10
4. [Typesafe.ai Launches System One Models and Jev for Structured Inference](#item-4) ⭐️ 7.0/10
5. [Rheinmetall Open-Sources Battlesuite Weapon System Protocol Docs](#item-5) ⭐️ 7.0/10
6. [Developer Builds Linux GPU Driver for M4 Mac Mini in One Month Using LLMs](#item-6) ⭐️ 7.0/10
7. [AI Agent Strix Discovers Leaked GitHub Token in Baseten Repos in 25 Minutes](#item-7) ⭐️ 7.0/10
8. [Web Demo for Google's Gemini 3.8 Live Speech Models](#item-8) ⭐️ 7.0/10
9. [Solo Developer Trains 44M Ternary LLM at 1900 tok/s in 19.8 MB](#item-9) ⭐️ 7.0/10
10. [Capsule Packs Web Apps and Data into Single SQLite Files](#item-10) ⭐️ 6.0/10
11. [Laurie Voss on AI Shifting Software Work to Product Engineering](#item-11) ⭐️ 6.0/10
12. [Paper Argues Current AI Agents Cannot Trigger Recursive Self-Improvement](#item-12) ⭐️ 6.0/10
13. [MS MARCO Click-Translation Tables as Lightweight DSSM for BM25](#item-13) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [DIY E-Ink Frame Detects Birds with BirdNET and Draws 1800s Illustrations](https://github.com/arnegiacomo/fugleramme) ⭐️ 8.0/10

A GitHub project called Fugleramme builds an e-ink frame that uses the BirdNET neural network to detect bird calls and renders them as 1800s-style illustrations. The project blends machine learning, embedded hardware, and artistic output, offering high inspiration for builders seeking to create magical, nature-connected devices. BirdNET is a traditional convolutional neural network, not an LLM, capable of identifying 984 North American and European bird species by sound. The e-ink display pairs with low-power boards like ESP32 for long battery life.

hackernews · arnemunthekaas · Sep 15, 12:31 · [Discussion](https://news.ycombinator.com/item?id=49711544)

**Background**: BirdNET is a deep learning solution for avian diversity monitoring that uses a convolutional neural network to classify bird sounds from audio recordings.

<details><summary>References</summary>
<ul>
<li><a href="https://www.sciencedirect.com/science/article/pii/S1574954121000273">BirdNET: A deep learning solution for avian diversity monitoring - ScienceDirect</a></li>

</ul>
</details>

**Discussion**: Commenters praised the project's magical creativity and technical blend, noted that BirdNET is a traditional neural network rather than an LLM, and highlighted the fun and longevity of e-ink with ESP32 boards.

**Tags**: `#e-ink`, `#machine-learning`, `#embedded-systems`, `#DIY-hardware`, `#bird-classification`

---

<a id="item-2"></a>
## [Google Releases Gemini 3.8 Live and Extended Thinking Models](https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-3-8-live-gemini-3-8-live-extended-thinking/) ⭐️ 8.0/10

Google announced the Gemini 3.8 Live and Gemini 3.8 Live Extended Thinking models, optimized for real-time conversational AI with enhanced multilingual capabilities and low latency. The release improves real-time AI interactions for users worldwide, particularly in multilingual settings and enterprise workspace accounts, strengthening Google's position in conversational AI. The Extended Thinking variant targets high-complexity tasks with multi-step reasoning, while the base Live model emphasizes scale and grounding; both support voice input with accent handling and pleasant voices.

hackernews · leumon · Sep 15, 17:38 · [Discussion](https://news.ycombinator.com/item?id=49715947)

<details><summary>References</summary>
<ul>
<li><a href="https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-3-8-live-gemini-3-8-live-extended-thinking/">Introducing Gemini 3.8 Live and 3.8 Live Extended Thinking</a></li>
<li><a href="https://9to5google.com/2026/05/17/gemini-app-thinking-level/">Gemini app rolling out ‘Extended’ thinking level, new 3rd-party app integrations</a></li>

</ul>
</details>

**Discussion**: Users praised the models for excellent Afrikaans support, thick accent handling, low latency, and workspace account compatibility, though some questioned when Gemini might surpass competitors like Fable and Astra.

**Tags**: `#Gemini`, `#Google AI`, `#LLMs`, `#Real-time AI`, `#Multimodal`

---

<a id="item-3"></a>
## [TabPFN-3.5 Released as New SOTA Tabular Foundation Model](https://www.reddit.com/r/MachineLearning/comments/1wh4xhy/tabpfn35_is_released_as_the_next_sota_tabular/) ⭐️ 8.0/10

Prior Labs released TabPFN-3.5 today as the next state-of-the-art tabular foundation model, topping both TabArena and BeyondArena benchmarks for up to 1M rows and 20k features. The release advances practical tabular foundation models with specialized variants, potentially improving accuracy and efficiency for machine learning on structured data across industries. It includes TabPFN-3.5-Fast (6x faster in alpha), TabPFN-3.5-Thinking (API-based compute-accuracy tradeoff with +20 to +44 Elo gains), and TabPFN-3.5-Plus, leading by +250 Elo on text-rich data in BeyondArena.

reddit · r/MachineLearning · /u/tuanacelik · Sep 15, 16:18

**Background**: TabPFN refers to a series of foundation models designed specifically for tabular data tasks. TabArena and BeyondArena are living benchmarks evaluating model performance on tabular datasets under standardized conditions including IID, temporal, and grouped tasks.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/PriorLabs/TabPFN">GitHub - PriorLabs/ TabPFN : TabPFN : Foundation Model for Tabular...</a></li>
<li><a href="https://arxiv.org/abs/2506.16791">[2506.16791] TabArena: A Living Benchmark for Machine Learning on Tabular Data</a></li>
<li><a href="https://arxiv.org/pdf/2606.30410">Beyond IID: How General Are Tabular Foundation Models, Really?</a></li>

</ul>
</details>

**Tags**: `#tabular data`, `#foundation models`, `#machine learning`, `#SOTA benchmarks`, `#TabPFN`

---

<a id="item-4"></a>
## [Typesafe.ai Launches System One Models and Jev for Structured Inference](https://typesafe.ai/blog/introducing-system-one-models-and-jev) ⭐️ 7.0/10

Typesafe.ai announced System One Models and Jev for fast typed and structured inference as an alternative to general generative LLMs. The new system delivers millisecond-level inference at low cost for classification and structured tasks, affecting developers who need efficient alternatives to full LLMs. Jev processes arbitrary text input plus questions in yes/no, multiple-choice or score formats, achieving speeds in milliseconds at $0.042 per MTok according to documentation.

hackernews · albelfio · Sep 15, 19:25 · [Discussion](https://news.ycombinator.com/item?id=49717558)

<details><summary>References</summary>
<ul>
<li><a href="https://news.ycombinator.com/item?id=49717558">Introducing System One Models and Jev | Hacker News</a></li>

</ul>
</details>

**Discussion**: Commenters praised the home assistant demo and contract integration ideas while noting that speed comparisons to autoregressive LLMs may be misleading since Jev focuses only on structured output rather than general generation.

**Tags**: `#AI/ML`, `#structured output`, `#inference optimization`, `#LLMs`, `#typed models`

---

<a id="item-5"></a>
## [Rheinmetall Open-Sources Battlesuite Weapon System Protocol Docs](https://rheinmetall.github.io/onboardapi-documentation/9.10.0/index.html) ⭐️ 7.0/10

German defense firm Rheinmetall has released public documentation for its Battlesuite connected weapon system protocol at version 9.10.0 on GitHub, revealing a DDS-based middleware implementation for networked military systems. The open release offers rare visibility into proprietary military distributed systems technology from a major contractor, enabling broader industry analysis and comparisons with established defense standards for real-time data sharing. The protocol relies on DDS for data-centric connectivity with noted limitations in embedded environments due to dynamic memory use; community highlights parallels to TMS, DIS/HLA, and OMS architectures.

hackernews · summarity · Sep 15, 21:07 · [Discussion](https://news.ycombinator.com/item?id=49718928)

**Background**: DDS is an OMG standard middleware protocol designed for low-latency, reliable data distribution across distributed systems, commonly applied in high-reliability domains including defense applications.

<details><summary>References</summary>
<ul>
<li><a href="https://www.dds-foundation.org/what-is-dds-3/">What is DDS ?</a></li>
<li><a href="https://news.ycombinator.com/item?id=49718928">German Rheinmetall open-sources its Battlesuite connected weapon ...</a></li>

</ul>
</details>

**Discussion**: Discussion shows initial excitement followed by skepticism over DDS suitability for embedded real-time use, with users comparing it to TMS, DIS/HLA, and OMS while seeking lighter alternatives without dynamic allocation.

**Tags**: `#open-source`, `#distributed-systems`, `#DDS`, `#military-tech`, `#protocols`

---

<a id="item-6"></a>
## [Developer Builds Linux GPU Driver for M4 Mac Mini in One Month Using LLMs](https://codyho.dev/blog/gpu-driver/) ⭐️ 7.0/10

A developer created a working Linux GPU driver for the M4 Mac Mini in one month by using LLMs for reverse engineering undocumented Apple Silicon hardware. This demonstrates LLMs accelerating low-level driver development on complex undocumented hardware, potentially affecting open-source GPU support for newer Apple Silicon devices. The project generated substantial HN debate focused on the author's ex-Apple background, undisclosed LLM usage, and potential IP conflicts rather than code quality alone.

hackernews · ADevWithAnIdea · Sep 15, 19:30 · [Discussion](https://news.ycombinator.com/item?id=49717638)

**Discussion**: Community sentiment is mixed, with praise for the technical achievement using LLMs but strong concerns over ethics, IP issues from the author's ex-Apple ties, and Asahi Linux's no-AI policy preventing upstreaming; some note the code may be tainted and unusable in mainline Linux.

**Tags**: `#linux`, `#gpu-driver`, `#apple-silicon`, `#llm-assisted-coding`, `#reverse-engineering`

---

<a id="item-7"></a>
## [AI Agent Strix Discovers Leaked GitHub Token in Baseten Repos in 25 Minutes](https://www.strix.ai/blog/baseten-harbor-github-pat-takeover) ⭐️ 7.0/10

Security researchers used the Strix AI agent to locate a leaked GitHub personal access token for basetenbot in Docker build history, obtaining admin and push access to Baseten's production, GitOps, and customer repositories within 25 minutes. The incident shows how autonomous AI agents can rapidly surface critical credential leaks that affect production infrastructure, prompting faster security reviews across companies relying on public container images and CI pipelines. The token granted admin rights to the main product repo, GitOps cluster repo, Homebrew tap, and read/write access to private customer repositories; Baseten rotated the token after responsible disclosure on July 14.

hackernews · bearsyankees · Sep 15, 18:11 · [Discussion](https://news.ycombinator.com/item?id=49716476)

**Background**: Strix is an autonomous AI penetration testing agent that dynamically runs code to find and validate vulnerabilities such as exposed credentials in build artifacts.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.strix.ai/">Introduction - Strix</a></li>
<li><a href="https://github.com/usestrix/strix">GitHub - usestrix/ strix : Open-source AI penetration testing tool to find...</a></li>

</ul>
</details>

**Discussion**: Commenters praised Baseten's quick token rotation and project privatization but questioned whether the scan against a prospective vendor was pre-approved; others noted AI agents mainly accelerate discovery of issues that motivated humans could find rather than uncovering novel vulnerabilities.

**Tags**: `#security`, `#github`, `#ai-agents`, `#vulnerability-disclosure`, `#red-teaming`

---

<a id="item-8"></a>
## [Web Demo for Google's Gemini 3.8 Live Speech Models](https://simonwillison.net/2026/Sep/15/gemini-live/) ⭐️ 7.0/10

Google released Gemini 3.8 Live and Gemini 3.8 Live Extended Thinking speech-to-speech models on September 15, 2026. Simon Willison built a no-library browser UI that connects to the Gemini WebSocket endpoint for real-time voice conversations with interrupt support. The tool makes advanced real-time voice AI experimentation accessible directly in the browser, similar to OpenAI's GPT-Live family, helping developers test natural speech interactions without complex setup. The implementation uses the wss://generativelanguage.googleapis.com WebSocket endpoint and Web Audio API AudioContext for capture and playback, supporting model selection, voice presets, system prompts, and live interruption.

rss · Simon Willison · Sep 15, 22:47

**Background**: Speech-to-speech models process audio input and generate audio output for natural voice conversations with AI. The Gemini Live API offers a WebSocket interface for building low-latency, real-time dialogue applications.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-3-8-live-gemini-3-8-live-extended-thinking/">Introducing Gemini 3.8 Live and 3.8 Live Extended Thinking - Google Blog</a></li>
<li><a href="https://ai.google.dev/gemini-api/docs/models/gemini-3.8-live">Gemini 3 . 8 Live | Gemini API | Google AI for Developers</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Gemini`, `#Speech-to-Speech`, `#Google`, `#Tools`

---

<a id="item-9"></a>
## [Solo Developer Trains 44M Ternary LLM at 1900 tok/s in 19.8 MB](https://www.reddit.com/r/MachineLearning/comments/1wgzpli/i_trained_a_44m_parameter_quantized_llm_from/) ⭐️ 7.0/10

A solo developer trained SHADOW-50M, a 44M-parameter ternary LLM with weights in {-1,0,+1}, from scratch on 45B tokens. The complete model is 19.8 MB, runs at approximately 1,900 tokens per second on a laptop CPU, and uses 512-bit vocabulary fingerprints plus external calculation circuits instead of tool calls. This demonstrates extreme quantization and custom engineering that enables fully offline, high-speed inference on CPUs and browsers for edge AI applications. It highlights practical approaches to on-device reasoning and retrieval without relying on large floating-point models or external APIs. The model uses a 73,880-token vocabulary stored as fixed 512-bit fingerprints in a 4.7 MB table, a 159 KB compiled kernel, and memory-mapped archive retrieval at 1 bit per token. External circuits handle arithmetic, dates, and sorting by intercepting special tokens like [calc], while benchmarks show it trails a comparable bf16 Llama-style model on standard tests.

reddit · r/MachineLearning · /u/Final-Data-1410 · Sep 15, 12:59

**Background**: Ternary LLMs use weights restricted to the values -1, 0, and +1 to reduce model size and computation. Vocabulary fingerprints replace learned embedding tables with fixed binary representations for tokens. External calc circuits allow the model to delegate precise operations to hardcoded logic instead of generating answers internally.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/1.58-bit_large_language_model">1.58-bit large language model - Wikipedia</a></li>
<li><a href="https://github.com/jina-ai/embedding-fingerprints">jina-ai/embedding-fingerprints - GitHub</a></li>

</ul>
</details>

**Tags**: `#LLM`, `#quantization`, `#efficient inference`, `#edge AI`, `#machine learning`

---

<a id="item-10"></a>
## [Capsule Packs Web Apps and Data into Single SQLite Files](https://withcapsule.app/) ⭐️ 6.0/10

Capsule, a Rust tool using Tauri 2.0, packages HTML web apps, assets, and data such as localStorage or document collections into one portable SQLite file. It enables easy local persistence and sharing of web apps without servers, offering a privacy-focused option for developers and users who need portable, self-contained applications. Data entries include UUIDs and timestamps for merging file copies; apps lack direct filesystem access and need explicit internet permissions while supporting local or remote AI models.

hackernews · bashtian · Sep 15, 13:31 · [Discussion](https://news.ycombinator.com/item?id=49712278)

**Background**: Tauri is an open-source framework that builds cross-platform desktop and mobile applications using web frontends and a Rust backend, with version 2.0 released in 2024 adding mobile support.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/tauri-apps/tauri">GitHub - tauri-apps/tauri: Build smaller, faster, and more secure desktop and mobile applications with a web frontend. · GitHub</a></li>
<li><a href="https://en.wikipedia.org/wiki/Tauri_(software_framework)">Tauri (software framework) - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Users pointed to existing alternatives like the File System Access API and projects such as uapp, while questioning whether a dedicated runtime is needed instead of simply sharing the original application or hosting online.

**Tags**: `#web-apps`, `#sqlite`, `#tauri`, `#rust`, `#show-hn`

---

<a id="item-11"></a>
## [Laurie Voss on AI Shifting Software Work to Product Engineering](https://simonwillison.net/2026/Sep/14/laurie-voss/) ⭐️ 6.0/10

Laurie Voss argues that the collapsing costs of writing, reviewing, fixing, and operating code due to AI will leave software development focused solely on understanding user needs, precise definition, and usability. This shift redefines software roles in an era of abundant AI-generated code, emphasizing product engineering skills as the primary remaining value as software demand grows without limit. Voss notes that the per-piece cost of product engineering does not transfer across projects, making it the dominant task as the volume of software produced reaches infinity.

rss · Simon Willison · Sep 14, 14:34

**Tags**: `#generative-ai`, `#software-engineering`, `#product-management`, `#ai-impact`, `#agentic-engineering`

---

<a id="item-12"></a>
## [Paper Argues Current AI Agents Cannot Trigger Recursive Self-Improvement](https://www.reddit.com/r/MachineLearning/comments/1wgazy4/rsi_is_not_happening_r/) ⭐️ 6.0/10

A paper tested AI agents Codex/GPT-5.6 Sol and OpenClaw/Opus 4.8 on replicating unpublished NeurIPS papers, with original authors grading the outputs. The agents failed to perform open-ended ML research, leading the authors to conclude recursive self-improvement is not imminent. The findings challenge forecasts of rapid AI progress through agent-driven research automation, suggesting current systems lack the capability for independent, high-quality ML contributions that could accelerate self-improvement loops. The evaluation matched the model of delegating entire projects to agents and judging results; the arXiv paper is at https://arxiv.org/abs/2607.27191 and explicitly discusses explosive AI progress and RSI mechanisms.

reddit · r/MachineLearning · /u/we_are_mammals · Sep 14, 18:03

**Discussion**: The Reddit post author notes repeated poor engagement with little meaningful discussion or debate despite upvotes, expressing disappointment in the community's hivemind responses and misunderstandings of RSI.

**Tags**: `#AI agents`, `#recursive self-improvement`, `#machine learning`, `#AI capabilities`, `#research evaluation`

---

<a id="item-13"></a>
## [MS MARCO Click-Translation Tables as Lightweight DSSM for BM25](https://www.reddit.com/r/MachineLearning/comments/1wg3g03/ms_marco_clicktranslation_expansion_tables_poor/) ⭐️ 6.0/10

A developer released count-based translation tables derived from MS MARCO query-document pairs that expand documents in inverted indexes at indexing time, improving baseline BM25 performance as a linear alternative to DSSM. This approach offers a practical, low-cost method for semantic document expansion in information retrieval systems, enabling better search relevance without training deep neural networks. The method tokenizes queries and documents, counts cross-pair co-occurrences between units, retains top-k associations per document unit, and bakes expansions directly into the index; it handles only linear dependencies unlike full DSSM.

reddit · r/MachineLearning · /u/SpiritedTrip · Sep 14, 13:28

**Background**: DSSM is a deep neural network model developed by Microsoft Research for learning semantic similarity between queries and documents using clickthrough data. MS MARCO is a large-scale dataset of real user queries paired with relevant passages, commonly used for training and evaluating search models.

<details><summary>References</summary>
<ul>
<li><a href="https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/cikm2013_DSSM_fullversion.pdf">Learning Deep Structured Semantic Models for Web ...</a></li>
<li><a href="https://microsoft.github.io/msmarco/">MS MARCO</a></li>

</ul>
</details>

**Tags**: `#information-retrieval`, `#machine-learning`, `#semantic-search`, `#document-expansion`, `#MS-MARCO`

---