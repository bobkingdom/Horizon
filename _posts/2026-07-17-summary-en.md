---
layout: default
title: "Horizon Summary: 2026-07-17 (EN)"
date: 2026-07-17
lang: en
---

> From 38 items, 19 important content pieces were selected

---

1. [Moonshot AI Launches Kimi K3 Open Frontier LLM](#item-1) ⭐️ 8.0/10
2. [Thinking Machines Lab Releases 975B Inkling Open-Weights MoE Model](#item-2) ⭐️ 8.0/10
3. [Linus Torvalds: Linux Not Anti-AI, AI Is Useful Tool](#item-3) ⭐️ 8.0/10
4. [Claude web_fetch flaw enabled private memory exfiltration](#item-4) ⭐️ 8.0/10
5. [Schema Harness Claims 99% on ARC-AGI-3 Using Claude Opus 4.8](#item-5) ⭐️ 8.0/10
6. [LM Studio Launches Bionic Agent Harness for Open Local Models](#item-6) ⭐️ 7.0/10
7. [Decoy Font Hides Secondary Message from AI Vision](#item-7) ⭐️ 7.0/10
8. [ArXiv Paper on Mathematics of Data Science Shared on HN](#item-8) ⭐️ 7.0/10
9. [Firefox Compiled to WebAssembly Runs Inside Chrome](#item-9) ⭐️ 7.0/10
10. [Independent Researcher Seeks Help Scaling New DABSN Recurrent LM](#item-10) ⭐️ 7.0/10
11. [ExTernD: Expanded-Rank Ternary Decomposition for Ternary LLM PTQ](#item-11) ⭐️ 7.0/10
12. [PnP-CoSMo: Plug-and-Play Framework for Multi-Contrast MRI Reconstruction](#item-12) ⭐️ 7.0/10
13. [Microsoft Open-Sources Its 1990s Comic Chat IRC Client](#item-13) ⭐️ 6.0/10
14. [Classical ML Method Detects LLM-Generated Texts](#item-14) ⭐️ 6.0/10
15. [Interactive Linear Algebra Book with 3D Figures from 2015](#item-15) ⭐️ 6.0/10
16. [Developer Details Rust-to-Zig Compiler Rewrite Progress](#item-16) ⭐️ 6.0/10
17. [Questioning if AI Memory Should Store Reasoning Styles Over Facts](#item-17) ⭐️ 6.0/10
18. [QLoRA Default 2e-4 LR Overfits on Datasets Under 10k Samples](#item-18) ⭐️ 6.0/10
19. [Call for Papers: First RTCA Workshop at NeurIPS 2026](#item-19) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Moonshot AI Launches Kimi K3 Open Frontier LLM](https://www.kimi.com/blog/kimi-k3) ⭐️ 8.0/10

Moonshot AI released Kimi K3, a 2.8 trillion parameter LLM with 1 million token context window and pricing of $3 per million input tokens and $15 per million output tokens. The release positions a Chinese lab among top frontier models while offering competitive pricing that could accelerate commoditization of advanced AI capabilities. Kimi K3 achieves benchmark performance comparable to Sol and Fable tiers and surpasses Opus 4.8, with cache pricing at $0.3 per million tokens.

hackernews · vincent_s · Jul 16, 14:46 · [Discussion](https://news.ycombinator.com/item?id=48935342)

**Background**: Moonshot AI is a Beijing-based company founded in 2023 that develops large language models and has been recognized as one of China's leading AI startups.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Moonshot_AI">Moonshot AI - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters noted the model's low cost for large outputs, discussed whether Chinese labs are commoditizing intelligence to sell hardware, and compared its benchmarks favorably to leading US models.

**Tags**: `#LLM`, `#AI models`, `#Chinese AI`, `#frontier models`, `#Hacker News`

---

<a id="item-2"></a>
## [Thinking Machines Lab Releases 975B Inkling Open-Weights MoE Model](https://simonwillison.net/2026/Jul/16/inkling/#atom-everything) ⭐️ 8.0/10

Thinking Machines Lab released Inkling, a 975B-parameter Apache-2.0 licensed multimodal MoE model with 41B active parameters trained on 45 trillion tokens of text, images, audio and video. The release strengthens the US open-weights ecosystem with a competitive multimodal contender alongside NVIDIA Nemotron and Gemma 4, offering an Apache-2.0 licensed base model for fine-tuning via the Tinker platform. The model card and training data documentation are notably brief; Inkling is positioned as a customization base rather than a frontier model, with a smaller 276B Inkling-Small variant promised later.

rss · Simon Willison · Jul 16, 15:35

**Background**: Mixture of Experts (MoE) architecture employs multiple specialized expert networks and a gating system to activate only a subset of parameters during inference, improving efficiency in very large transformer models.

<details><summary>References</summary>
<ul>
<li><a href="https://www.linkedin.com/pulse/mixture-experts-moearchitecture-padmashri-suresh-o5nqc">Mixture of Experts ( MoE ) architecture</a></li>

</ul>
</details>

**Tags**: `#AI models`, `#open-weights`, `#multimodal`, `#Mixture-of-Experts`, `#large language models`

---

<a id="item-3"></a>
## [Linus Torvalds: Linux Not Anti-AI, AI Is Useful Tool](https://simonwillison.net/2026/Jul/16/linus-torvalds/#atom-everything) ⭐️ 8.0/10

Linus Torvalds stated on the Linux Media Mailing List that Linux is not an anti-AI project and that AI is a clearly useful tool for kernel development. As the top-level Linux maintainer, Torvalds' firm endorsement signals strong support for AI tooling adoption in open-source kernel work and may shape future development practices. Torvalds noted that doubts about AI usefulness come from those who have not used it, suggested dissenters fork the project or walk away, and distinguished usefulness from open economic questions.

rss · Simon Willison · Jul 16, 13:26

**Tags**: `#Linux`, `#AI tools`, `#Kernel development`, `#Open source`, `#Linus Torvalds`

---

<a id="item-4"></a>
## [Claude web_fetch flaw enabled private memory exfiltration](https://simonwillison.net/2026/Jul/15/claude-web-fetch-exfiltration/#atom-everything) ⭐️ 8.0/10

Ayush Paul discovered a bypass in Claude's web_fetch tool that allowed exfiltration of private user memories by following URLs embedded in previously fetched pages from a honeypot site. The vulnerability exposed how even carefully designed safeguards against the lethal trifecta of private data, untrusted content, and external communication can fail in LLM agents. The attack used letter-by-letter navigation starting from URLs like https://coffee.evil.com/a and was restricted to Claude-User user-agents; Anthropic later removed the ability to follow links from fetched content.

rss · Simon Willison · Jul 15, 14:21

**Background**: The lethal trifecta describes the dangerous combination where an LLM agent has access to private data, can process untrusted content, and possesses external communication capabilities, enabling prompt injection attacks to exfiltrate information.

<details><summary>References</summary>
<ul>
<li><a href="https://simonwillison.net/2025/Jun/16/the-lethal-trifecta/">The lethal trifecta for AI agents: private data, untrusted content, and external communication</a></li>
<li><a href="https://platform.claude.com/docs/en/agents-and-tools/tool-use/web-fetch-tool">Web fetch tool - Claude Platform Docs</a></li>

</ul>
</details>

**Tags**: `#AI Security`, `#Claude`, `#Prompt Injection`, `#Data Exfiltration`, `#LLM Vulnerabilities`

---

<a id="item-5"></a>
## [Schema Harness Claims 99% on ARC-AGI-3 Using Claude Opus 4.8](https://www.reddit.com/r/MachineLearning/comments/1uyf8oo/new_fable5opus48_harness_called_schema_claims_99/) ⭐️ 8.0/10

The new Schema harness achieves 99% on the ARC-AGI-3 public set with Claude Opus 4.8 and Fable 5, and 95.35% with GPT-5.6 Sol, without modifying model weights. This result demonstrates how process-level optimizations around existing frontier models can approach saturation on interactive reasoning benchmarks, potentially influencing agent design across the industry. Schema improves observation modeling, prediction testing against interaction history, and plan execution and revision; a fallback rule reruns low-scoring games with stronger configurations and keeps the higher score.

reddit · r/MachineLearning · /u/we_are_mammals · Jul 16, 21:02

**Background**: ARC-AGI-3 is an interactive reasoning benchmark that requires AI agents to explore novel environments, infer goals on the fly, build internal models of environment dynamics, and plan effectively.

<details><summary>References</summary>
<ul>
<li><a href="https://schema-harness.github.io/">Frontier Models with Our Harness Achieve ~99% on ARC-AGI-3 Public — Schema</a></li>
<li><a href="https://arcprize.org/arc-agi/3">ARC-AGI-3</a></li>

</ul>
</details>

**Tags**: `#ARC-AGI`, `#AI benchmarks`, `#LLM agents`, `#reasoning systems`, `#machine learning`

---

<a id="item-6"></a>
## [LM Studio Launches Bionic Agent Harness for Open Local Models](https://lmstudio.ai/blog/introducing-lm-studio-bionic) ⭐️ 7.0/10

LM Studio has announced Bionic, a new agent harness for open local models, receiving early positive feedback on usability and performance with models like Qwen3.6 35B. This release makes agentic capabilities more accessible for local private AI use, potentially impacting users prioritizing data security and cost control over cloud-based frontier models. Bionic integrates with existing LM Studio model libraries, supports coding and document projects with automatic checkpointing, and the founder offered credits for testing models like GLM 5.2 and Kimi variants.

hackernews · minimaxir · Jul 16, 20:18 · [Discussion](https://news.ycombinator.com/item?id=48939662)

<details><summary>References</summary>
<ul>
<li><a href="https://grokipedia.com/page/LM_Studio">LM Studio</a></li>
<li><a href="https://www.flowtools.co/lm-studio">LM Studio : Run AI models locally and privately | flowtools</a></li>

</ul>
</details>

**Discussion**: Users report strong first impressions and ease of use similar to other agents, while the founder actively engages by offering test credits; concerns include potential business model shifts toward cloud services and comparisons to alternatives for enterprise control.

**Tags**: `#AI Agents`, `#Local LLMs`, `#LM Studio`, `#Open Models`, `#Agentic AI`

---

<a id="item-7"></a>
## [Decoy Font Hides Secondary Message from AI Vision](https://www.mixfont.com/experiments/decoy-font) ⭐️ 7.0/10

The Decoy Font experiment at mixfont.com generates images where one message is visible while a second message appears only when blurred, squinted at, or downscaled. It is designed to confuse AI vision systems reading text in images. The technique reveals perceptual differences between humans and current multimodal models, showing how simple optical effects can alter what AI extracts from images. Prompting helps some models like GPT-5.6 detect the hidden text while Claude fails; resizing to 150x150 pixels switches model outputs between the two messages.

hackernews · ray__ · Jul 16, 16:18 · [Discussion](https://news.ycombinator.com/item?id=48936584)

**Discussion**: Users call the effect cool yet impractical for stopping AI, observe large differences across GPT, Claude and Gemini, and propose extensions such as cipher fonts to further poison training data.

**Tags**: `#typography`, `#adversarial-examples`, `#computer-vision`, `#AI`, `#optical-illusion`

---

<a id="item-8"></a>
## [ArXiv Paper on Mathematics of Data Science Shared on HN](https://arxiv.org/abs/2607.11938) ⭐️ 7.0/10

A Hacker News post links to the arXiv paper 'Mathematics of Data Science', highlighting its value for building high-dimensional intuition. The shared resource helps practitioners develop intuition essential for high-dimensional data, machine learning models, and optimization methods like stochastic gradient descent. The paper begins by explaining how intuition fails in high dimensions due to spikiness and volume effects, directly relating these to model training and search spaces.

hackernews · Anon84 · Jul 16, 20:38 · [Discussion](https://news.ycombinator.com/item?id=48939896)

**Discussion**: Commenters highlight the paper's strong start on high-dimensional intuition breaks and its relevance to modern data science, while stressing that statistics remains the top priority skill and that data science now emphasizes judgment over other aspects.

**Tags**: `#data science`, `#mathematics`, `#machine learning`, `#statistics`, `#high-dimensional data`

---

<a id="item-9"></a>
## [Firefox Compiled to WebAssembly Runs Inside Chrome](https://simonwillison.net/2026/Jul/16/firefox-in-webassembly/#atom-everything) ⭐️ 7.0/10

Puter compiled the full Firefox/Gecko browser engine to WebAssembly, allowing it to run inside another browser, as shown by loading a blog in Firefox-WASM within Chrome. The project used extensive AI assistance from Claude Opus and Fable, along with the Wisp protocol for WebSocket-based network proxying. This proof-of-concept demonstrates the expanding capabilities of WebAssembly for running complex native applications like entire browsers inside web environments, highlighting both engineering achievements and the role of AI in large-scale code porting efforts. The demo requires proxying all traffic via a Puter-hosted Wisp WebSocket server due to browser sandbox restrictions; it supports end-to-end encryption for HTTPS traffic and consumed significant compute resources, prompting server scaling during HN discussion. A similar WebKit-to-WASM effort exists but lacks a public demo.

rss · Simon Willison · Jul 16, 23:34

**Background**: WebAssembly enables near-native execution of compiled code within browsers. Browser sandboxing prevents web pages from making arbitrary network connections, necessitating proxy solutions like the Wisp protocol over WebSockets.

<details><summary>References</summary>
<ul>
<li><a href="https://developer.puter.com/labs/firefox-wasm/">Firefox in WebAssembly</a></li>
<li><a href="https://news.ycombinator.com/item?id=48926939">Show HN: Firefox in WebAssembly | Hacker News</a></li>

</ul>
</details>

**Discussion**: Hacker News commenters viewed the project as an impressive fun experiment pushing WebAssembly boundaries, while noting high RAM usage and the availability of a lighter alternative called browser.js.

**Tags**: `#WebAssembly`, `#Firefox`, `#Browsers`, `#WASM`, `#Emulation`

---

<a id="item-10"></a>
## [Independent Researcher Seeks Help Scaling New DABSN Recurrent LM](https://www.reddit.com/r/MachineLearning/comments/1uycffg/seeking_collaborators_for_scaling_and_independent/) ⭐️ 7.0/10

An independent researcher released a preprint and open-source code for the DABSN recurrent architecture along with results from a 24M-parameter language model trained on 1B tokens using the GPT-2 tokenizer. The effort explores recurrent alternatives to transformers for language modeling and long-context tasks, which could influence efficiency trends if the architecture proves scalable through community collaboration. The architecture includes PyTorch, C++, and Triton implementations and was evaluated on benchmarks including MQAR, Copy, and Key-Value retrieval, with a second paper planned on language modeling scaling.

reddit · r/MachineLearning · /u/BleedingXiko · Jul 16, 19:17

**Background**: MQAR, or Multi-Query Associative Recall, is a synthetic benchmark designed to test language models' ability to perform multiple associative key-value lookups within a sequence.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/HazyResearch/zoology">GitHub - HazyResearch/zoology: Understand and test language ... Zoology: Measuring and Improving Recall in Efficient Language ... GitHub - howard-hou/Visual-MQAR: Understand and test multi ... MQAR: Multi-Query Associative Recall - emergentmind.com Zoology (Blogpost 1): Measuring and Improving Recall in ... Models - Hugging Face</a></li>
<li><a href="https://arxiv.org/html/2312.04927v1">Zoology: Measuring and Improving Recall in Efficient Language ...</a></li>

</ul>
</details>

**Tags**: `#recurrent architectures`, `#language models`, `#preprint`, `#open source`, `#scaling`

---

<a id="item-11"></a>
## [ExTernD: Expanded-Rank Ternary Decomposition for Ternary LLM PTQ](https://www.reddit.com/r/MachineLearning/comments/1uy2zb3/externd_expandedrank_ternary_decomposition/) ⭐️ 7.0/10

ExTernD decomposes each LLM weight matrix into two ternary factors plus a diagonal scaling matrix, allowing the inner rank to expand arbitrarily for accuracy approaching any quantization level. The method offers high-accuracy ternary post-training quantization for LLMs at only modest VRAM overhead, potentially advancing efficient inference and model compression across the AI ecosystem. The approach explicitly avoids fixed-size ternary matrices, which the authors call a dead end, and demonstrates that only a slight VRAM increase suffices while enabling abuse of ternary math for efficiency.

reddit · r/MachineLearning · /u/LMTLS5 · Jul 16, 13:31

**Background**: Post-training quantization (PTQ) reduces LLM precision after training to lower memory and compute needs. Ternary weights restrict values to three levels, offering extreme compression but historically suffering accuracy loss with fixed matrix sizes.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2607.13511">[2607.13511] ExTernD: Expanded-Rank Ternary Decomposition Ternary LLM PTQ with Accuracy Approaching Any Quantization Level - arXiv</a></li>
<li><a href="https://www.reddit.com/r/MachineLearning/comments/1uy2zb3/externd_expandedrank_ternary_decomposition/">ExTernD: Expanded-Rank Ternary Decomposition Ternary LLM PTQ with Accuracy Approaching Any Quantization Level [P] : r/MachineLearning - Reddit</a></li>

</ul>
</details>

**Tags**: `#LLM Quantization`, `#Post-Training Quantization`, `#Ternary Weights`, `#Model Compression`, `#Efficient Inference`

---

<a id="item-12"></a>
## [PnP-CoSMo: Plug-and-Play Framework for Multi-Contrast MRI Reconstruction](https://www.reddit.com/r/MachineLearning/comments/1uy2h66/pnpcosmo_a_multicontrast_mri_reconstruction/) ⭐️ 7.0/10

PnP-CoSMo presents a plug-and-play framework that learns contrast-invariant content models from image-domain data for generalizable multi-contrast MRI reconstruction without k-space training. The method was published in Medical Image Analysis and consists of a two-stage process that freezes the learned model for use as a prior in iterative reconstruction. This approach addresses the serious data bottleneck of raw k-space training data in ML-based MRI while remaining competitive with state-of-the-art unrolled networks and generalizable across contrasts and forward operators by design. The framework explicitly models contrast-invariant latent content to unlock reconstruction, offers a built-in explanatory framework, and requires no raw k-space training data. It is competitive with unrolled networks while providing greater generalizability.

reddit · r/MachineLearning · /u/void_gear · Jul 16, 13:10

**Background**: Multi-contrast MRI acquires multiple contrast-weighted scans of the same anatomy using different pulse sequences. Plug-and-play methods leverage pre-trained priors within iterative optimization frameworks, while unrolled networks combine iterative updates with deep learning.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/html/2409.13477">A Plug-and-Play Method for Guided Multi - contrast MRI ...</a></li>

</ul>
</details>

**Tags**: `#MRI reconstruction`, `#Medical Imaging`, `#Machine Learning`, `#Plug-and-Play`, `#Content-Style Modeling`

---

<a id="item-13"></a>
## [Microsoft Open-Sources Its 1990s Comic Chat IRC Client](https://opensource.microsoft.com/blog/2026/07/16/microsoft-comic-chat-is-now-open-source/) ⭐️ 6.0/10

On July 16, 2026, Microsoft open-sourced Comic Chat, the graphical IRC client first released in 1996 that visualized conversations as comics. The release preserves an experimental piece of internet history and generates strong nostalgic engagement among developers and early internet users. The project was made open source through efforts by Robert Standefer and Scott Hanselman, with original development led by David Kurlander; it extended the IRC protocol for character appearance and emoting.

hackernews · jervant · Jul 16, 16:06 · [Discussion](https://news.ycombinator.com/item?id=48936426)

**Background**: Microsoft Comic Chat was a graphical IRC client created by Microsoft Research and first shipped with Internet Explorer 3.0 in 1996, later bundled with Windows 98.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Microsoft_Comic_Chat">Microsoft Comic Chat</a></li>

</ul>
</details>

**Discussion**: Community members expressed enthusiasm, with original contributor Robert Standefer sharing the six-year journey to release, users recounting personal inspirations like startup ideas, and discussions noting its protocol extensions and mixed historical reception on IRC.

**Tags**: `#open-source`, `#microsoft`, `#irc`, `#retro-computing`, `#nostalgia`

---

<a id="item-14"></a>
## [Classical ML Method Detects LLM-Generated Texts](https://blog.lyc8503.net/en/post/llm-classifier/) ⭐️ 6.0/10

A blog post presents a classical machine learning method for detecting LLM-generated text, accompanied by HN discussion on its limitations and the superiority of human judgment. This incremental approach addresses growing concerns over AI-generated content authenticity, potentially influencing content moderation tools and digital trust mechanisms across platforms. The classifier relies on classical ML rather than deep models and faces limitations such as evolving LLM patterns, with comments noting humans remain the best detectors due to richer randomness in writing.

hackernews · uneven9434 · Jul 16, 16:41 · [Discussion](https://news.ycombinator.com/item?id=48936880)

**Discussion**: Commenters largely agree detection is a losing battle against advancing models, stress human superiority in spotting unique patterns over predictable AI outputs, and propose ideas like browser extensions for real-time paragraph analysis.

**Tags**: `#LLM detection`, `#machine learning`, `#AI-generated content`, `#NLP`, `#adversarial robustness`

---

<a id="item-15"></a>
## [Interactive Linear Algebra Book with 3D Figures from 2015](https://immersivemath.com/ila/) ⭐️ 6.0/10

An interactive online linear algebra textbook with manipulable 3D figures was shared on Hacker News, originally created in 2015. The resource improves math education via visualization and garnered 175 upvotes along with thoughtful discussion on interactive learning tools. It features clean presentation, tooltips, and logical section transitions, though the core content remains unchanged since 2015.

hackernews · srean · Jul 16, 15:32 · [Discussion](https://news.ycombinator.com/item?id=48935951)

**Discussion**: Commenters praised the book highly and wished for similar interactive resources in statistics and robotics, while noting that LLMs now make creating such visualizations faster and easier.

**Tags**: `#linear algebra`, `#interactive learning`, `#math education`, `#visualization`, `#online books`

---

<a id="item-16"></a>
## [Developer Details Rust-to-Zig Compiler Rewrite Progress](https://rtfeldman.com/rust-to-zig) ⭐️ 6.0/10

A developer published an update on rewriting a compiler project from Rust to Zig, highlighting experiences with memory safety and build performance. The post has sparked technical debates on language tradeoffs, affecting developers choosing between Rust's safety guarantees and Zig's incremental compilation features for systems software. Zig's ReleaseSafe mode uses runtime checks to catch use-after-free errors, while discussions note that emitting machine code in compilers does not inherently require unsafe operations beyond specific features like hot patching.

hackernews · jorangreef · Jul 16, 11:39 · [Discussion](https://news.ycombinator.com/item?id=48933149)

**Background**: Zig is a general-purpose system programming language designed as an improvement over C, emphasizing manual memory management and compile-time features without macros.

<details><summary>References</summary>
<ul>
<li><a href="https://ziglang.org/">Home ⚡ Zig Programming Language</a></li>

</ul>
</details>

**Discussion**: Commenters debate whether Zig's runtime checks fully address use-after-free issues, question the necessity of unsafe code for standard compilation, and praise Zig's incremental builds while wondering about future Rust improvements.

**Tags**: `#Rust`, `#Zig`, `#programming languages`, `#compilers`, `#software rewrite`

---

<a id="item-17"></a>
## [Questioning if AI Memory Should Store Reasoning Styles Over Facts](https://www.reddit.com/r/MachineLearning/comments/1uy6yht/are_current_ai_memory_architectures_optimizing/) ⭐️ 6.0/10

A Reddit post asks whether current AI memory systems optimize for the wrong abstraction by storing descriptive facts and preferences instead of inferred reasoning styles and higher-level patterns. This conceptual shift could influence how future AI systems maintain persistent context, potentially leading to more personalized and adaptive reasoning models across machine learning applications. The post contrasts examples like storing 'user interested in economics' with inferred patterns such as 'user explains outcomes through incentives and institutional constraints' and questions if new architectures beyond current retrieval and summarization are needed.

reddit · r/MachineLearning · /u/Boris_Ljevar · Jul 16, 16:00

**Tags**: `#AI Memory`, `#Persistent Context`, `#Machine Learning`, `#Reasoning Patterns`, `#Cognitive Architectures`

---

<a id="item-18"></a>
## [QLoRA Default 2e-4 LR Overfits on Datasets Under 10k Samples](https://www.reddit.com/r/MachineLearning/comments/1uy1z8b/the_qlora_2e4_default_is_wrong_under_10k_samples/) ⭐️ 6.0/10

A Reddit post states that the widely recommended QLoRA learning rate of 2e-4, originating from the 52k-sample Alpaca dataset, causes overfitting on custom datasets of 5-10k samples within the first epoch. Many practitioners fine-tuning LLMs on smaller scraped datasets waste weeks on ineffective runs by following hardcoded defaults in tutorials and notebooks without adjustment. The author reports that lowering the rate to 1e-4 and raising epochs from 3 to 5 produced clear eval improvements after multiple runs, while data cleaning and prompt changes had little effect.

reddit · r/MachineLearning · /u/Pretty-Ad774 · Jul 16, 12:50

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2305.14314">[2305.14314] QLoRA: Efficient Finetuning of Quantized LLMs</a></li>
<li><a href="https://unsloth.ai/docs/get-started/fine-tuning-llms-guide">Fine - tuning LLMs Guide | Unsloth Documentation</a></li>

</ul>
</details>

**Tags**: `#QLoRA`, `#fine-tuning`, `#hyperparameters`, `#LLMs`, `#machine learning`

---

<a id="item-19"></a>
## [Call for Papers: First RTCA Workshop at NeurIPS 2026](https://www.reddit.com/r/MachineLearning/comments/1uy8e0v/cfp_rtca_neurips_2026_r/) ⭐️ 6.0/10

The inaugural RTCA Workshop at NeurIPS 2026 in Sydney has issued its call for papers and demos on real-time multimodal conversational agents, with a submission deadline of August 29, 2026. This workshop addresses the growing need for natural, low-latency multimodal AI systems that handle streaming interactions, potentially shaping benchmarks and methodologies across speech, vision, and HCI research communities. Submissions include full papers up to 8 pages, short papers up to 4 pages, and demo papers; the event is non-archival and covers topics such as full-duplex models, turn-taking, and live system evaluation.

reddit · r/MachineLearning · /u/Few-Ferret9700 · Jul 16, 16:51

**Background**: Real-time conversational agents require handling latency constraints, interruptions, and backchannels during live multimodal exchanges, unlike traditional offline generation systems. Full-duplex models enable simultaneous listening and speaking, while backchannels refer to listener responses that manage dialogue flow.

<details><summary>References</summary>
<ul>
<li><a href="https://research.nvidia.com/labs/adlr/personaplex/">NVIDIA PersonaPlex: Natural Conversational AI With Any Role ...</a></li>
<li><a href="https://venturebeat.com/technology/openai-launches-gpt-live-a-full-duplex-voice-upgrade-that-lets-chatgpt-talk-more-like-a-person">OpenAI launches GPT-Live, a full-duplex voice upgrade that ...</a></li>

</ul>
</details>

**Tags**: `#NeurIPS`, `#Workshop`, `#Conversational AI`, `#Multimodal AI`, `#Real-time Systems`

---