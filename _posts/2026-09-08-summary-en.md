---
layout: default
title: "Horizon Summary: 2026-09-08 (EN)"
date: 2026-09-08
lang: en
---

> From 37 items, 22 important content pieces were selected

---

1. [LLM-Guided Evolution Sets 10 New Circle-Packing Records on Packomania](#item-1) ⭐️ 9.0/10
2. [OpenAI Details Coding Agents Accelerating Internal Research in 2026](#item-2) ⭐️ 8.0/10
3. [Longitudinal LLM Benchmarking Reveals Performance Drift Across 31k Measurements](#item-3) ⭐️ 8.0/10
4. [Factoring 512-bit RSA Keys from 1990s Certificate Authority](#item-4) ⭐️ 7.0/10
5. [D2's TALA Diagram Layout Engine Now Fully Open Source](#item-5) ⭐️ 7.0/10
6. [Jellyfin 12.0 Major Release Brings Performance Fixes](#item-6) ⭐️ 7.0/10
7. [Interactive Map Visualizes Los Angeles Building Growth 1880-2026](#item-7) ⭐️ 7.0/10
8. [Broadcom Pulls VDDK Downloads, Complicating VMware Exits](#item-8) ⭐️ 7.0/10
9. [OpenAI Chief Scientist on AI Defense vs Reckless Development](#item-9) ⭐️ 7.0/10
10. [Why Big-Bang Rewrites of Legacy Systems Usually Fail](#item-10) ⭐️ 7.0/10
11. [Tiny 417k-param RNN Generates Full Bad Apple Video Autonomously](#item-11) ⭐️ 7.0/10
12. [EmbedFlow Migrates Embedding Models with Zero Downtime via Reranking](#item-12) ⭐️ 7.0/10
13. [Rustuna: High-Performance Rust Implementation of Optuna Released](#item-13) ⭐️ 7.0/10
14. [Yandex Explores KV Cache Modification as LLM Agent Runtime](#item-14) ⭐️ 7.0/10
15. [PINNStudio: Free Open-Source No-Code GUI for PINNs](#item-15) ⭐️ 7.0/10
16. [IEEE T-PAMI EIC Confirms Missing Positive Review Caused Unjust Rejection](#item-16) ⭐️ 7.0/10
17. [GitHub Shares Reconstructed Stuxnet Source Code for Research](#item-17) ⭐️ 6.0/10
18. [LG Smart TVs Logging Audio and Snooping Devices Exposed](#item-18) ⭐️ 6.0/10
19. [Caltech Mathathon: First Research-Level Mathematics Hackathon](#item-19) ⭐️ 6.0/10
20. [Abusive crawlers drain more CPU than legitimate traffic on git.kernel.org](#item-20) ⭐️ 6.0/10
21. [Reddit Post Claims 95% Token Cut for Image LLM Inference](#item-21) ⭐️ 6.0/10
22. [ML Reproducibility Faces Growing Irrelevance in Research](#item-22) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [LLM-Guided Evolution Sets 10 New Circle-Packing Records on Packomania](https://www.reddit.com/r/MachineLearning/comments/1w9xlyi/llmguided_program_evolution_improves_10_bestknown/) ⭐️ 9.0/10

An LLM iteratively evolved an optimization algorithm from a simple seed solver, improving the best-known sum-of-radii solutions for N=101-114 on the Packomania csqv benchmark by 2.4-5.4% across 15 iterations. The approach achieved new state-of-the-art results on a respected optimization benchmark at only $27.72 in LLM cost with independent verification by Packomania, highlighting scalable LLM-guided program evolution for algorithmic discovery. Improvements were verified by an independent scorer that retained only successful algorithmic changes; the method used a scoreboard and history of prior attempts to guide proposals, with results accepted on packomania.com/csqv.

reddit · r/MachineLearning · /u/SIGH_I_CALL · Sep 7, 16:54

**Background**: Packomania maintains widely recognized benchmarks for circle-packing problems, including the csqv instances that require packing circles of varying radii into a container to minimize the sum of radii. The reported work applies LLM-guided program evolution rather than direct instance solving.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/html/2609.05093v1">LLM-Guided Program Evolution for Circle Packing:Breaking 10 ...</a></li>
<li><a href="https://packomania.com/">Packomania (52C17)</a></li>

</ul>
</details>

**Tags**: `#LLM`, `#program evolution`, `#optimization`, `#circle packing`, `#benchmark`

---

<a id="item-2"></a>
## [OpenAI Details Coding Agents Accelerating Internal Research in 2026](https://simonwillison.net/2026/Sep/6/research-acceleration-the-view-inside-openai/) ⭐️ 8.0/10

OpenAI published a blog post on September 6, 2026, describing how coding agents are reshaping researcher workflows as part of recursive self-improvement efforts toward AGI. A chart shows median daily AI spend per researcher rising sharply from near zero in February 2026 to roughly 600 dollars by late August 2026. The surge demonstrates OpenAI's practical use of AI tools to boost research productivity, potentially accelerating progress toward AGI and influencing industry-wide adoption of agentic workflows. The post notes that 2026 marked the year agentic engineering took off at OpenAI, with a possible trigger in late July when staff gained access to a model later released as GPT-6 Astra.

rss · Simon Willison · Sep 6, 23:57

**Background**: Recursive self-improvement describes AI systems that enhance their own capabilities, a concept central to AGI development. Coding agents are AI tools that autonomously handle coding tasks within researcher workflows.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Recursive_self-improvement">Recursive self-improvement - Wikipedia</a></li>
<li><a href="https://techcrunch.com/2026/05/28/rsi-is-the-new-agi-and-its-just-as-hard-to-pin-down/">RSI is the new AGI — and it’s just as hard to pin down</a></li>

</ul>
</details>

**Tags**: `#OpenAI`, `#AI agents`, `#Recursive Self-Improvement`, `#AGI`, `#Research tools`

---

<a id="item-3"></a>
## [Longitudinal LLM Benchmarking Reveals Performance Drift Across 31k Measurements](https://www.reddit.com/r/MachineLearning/comments/1w9llr4/measuring_llm_performance_drift_observations_and/) ⭐️ 8.0/10

A continuous evaluation framework was developed to track LLM performance drift through 31,352 repeated benchmark measurements across 49 API models in coding, reasoning, and tool-use tasks. Within-day score standard deviation was 2.80 points versus 8.43 points for between-day daily medians, with versioned configurations and change detection applied to distinguish real shifts from noise. API-served models change over time due to infrastructure and configuration updates, making static benchmark scores unreliable for long-term comparisons. This approach shifts evaluation from leaderboard snapshots to longitudinal monitoring, affecting model selection and reliability assessments across the AI industry. The methodology uses repeated execution-based evaluation instead of LLM judges, separates availability failures from valid outcomes, and withholds live task details to reduce contamination while publishing the overall design. Daily medians and change-point detection are proposed for handling noisy time series data.

reddit · r/MachineLearning · /u/ionutvi · Sep 7, 07:44

<details><summary>References</summary>
<ul>
<li><a href="https://data-today.net/llm-performance-drift-benchmark-variance/">LLM performance drift : why your benchmark scores... | Data Today</a></li>

</ul>
</details>

**Tags**: `#LLM benchmarking`, `#performance drift`, `#AI evaluation`, `#machine learning`, `#longitudinal measurement`

---

<a id="item-4"></a>
## [Factoring 512-bit RSA Keys from 1990s Certificate Authority](https://mcpherrin.ca/2026/09/07/rsa.html) ⭐️ 7.0/10

The author factored 512-bit RSA keys belonging to a 1990s Certificate Authority using consumer GPUs, successfully demonstrating the ability to break early SSL connections from that era. This highlights how weak historical cryptography remains vulnerable to modern hardware, affecting the security of archived encrypted traffic and underscoring the need for stronger key sizes in legacy systems. Factoring took roughly two days on a consumer GPU; a custom TLS implementation was required to target Netscape Communicator 4.51 with its clock set to 2000, as modern libraries dropped SSLv3 support.

hackernews · ahlCVA · Sep 8, 01:16 · [Discussion](https://news.ycombinator.com/item?id=49604637)

**Discussion**: Commenters expressed fascination with the historical reverse engineering but raised concerns about reliance on AI-generated code for parts of the work; others noted that much 1990s traffic used no encryption or fixed keys, and discussed long-term government storage of encrypted data for future decryption.

**Tags**: `#cryptography`, `#RSA`, `#security`, `#TLS/SSL`, `#historical-computing`

---

<a id="item-5"></a>
## [D2's TALA Diagram Layout Engine Now Fully Open Source](https://d2lang.com/blog/tala-is-open-source/) ⭐️ 7.0/10

D2 has announced that its TALA advanced auto-layout engine for diagrams is now fully open-source. The source code is available on GitHub under the Terrastruct organization. This provides developers with a high-quality open-source option for automatic diagram layout, particularly for software architecture diagrams. It may improve results over alternatives like ELK within the D2 ecosystem. TALA was previously proprietary and required a separate install from D2 to maintain separation between free and paid components. It is built with zero dependencies for its algorithms and works well beyond architecture diagrams.

hackernews · alixanderwang · Sep 7, 23:37 · [Discussion](https://news.ycombinator.com/item?id=49604150)

**Background**: D2 is a declarative diagramming tool that converts text syntax into generated diagrams, aimed at engineers rather than designers. TALA was developed in-house by Terrastruct specifically to handle complex node positioning, edge routing, and nesting in diagrams.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/terrastruct/tala">terrastruct/TALA: A diagram layout engine designed ... - GitHub</a></li>
<li><a href="https://d2lang.com/tour/tala/">TALA | D2 Documentation</a></li>

</ul>
</details>

**Discussion**: HN users welcomed the open-source release and noted TALA's improvements over ELK for some graph types, though results varied on specific examples like Go queue diagrams. Several shared experiences using D2 for architecture work and the difficulties of building custom layout solutions.

**Tags**: `#open-source`, `#diagramming`, `#layout-algorithms`, `#D2`, `#developer-tools`

---

<a id="item-6"></a>
## [Jellyfin 12.0 Major Release Brings Performance Fixes](https://jellyfin.org/posts/jellyfin-release-12.0/) ⭐️ 7.0/10

Jellyfin 12.0 was released after seven release candidates spanning from June 22 to September 1, introducing major updates and performance improvements over prior versions like 10.11.x. As a popular open-source alternative to Plex, this release strengthens options for self-hosting users managing large media libraries and may encourage more migrations from proprietary services. Users report smooth upgrades for libraries up to 40TB with only minor rescans needed, though subtitle handling in the Android client remains problematic with Chromecast streaming.

hackernews · 0xC0ncord · Sep 8, 01:56 · [Discussion](https://news.ycombinator.com/item?id=49604861)

**Background**: Jellyfin is a free and open-source media server designed to organize, manage, and stream personal media collections including movies, TV shows, and music to various client devices.

<details><summary>References</summary>
<ul>
<li><a href="https://jellyfin.org/">The Free Software Media System | Jellyfin</a></li>
<li><a href="https://en.wikipedia.org/wiki/Jellyfin">Jellyfin</a></li>

</ul>
</details>

**Discussion**: HN users praised the quick and painless upgrade process from older versions and expressed confidence in bug fixes after multiple release candidates, while highlighting persistent subtitle issues on Android clients as a key pain point.

**Tags**: `#jellyfin`, `#media-server`, `#open-source`, `#release`, `#self-hosting`

---

<a id="item-7"></a>
## [Interactive Map Visualizes Los Angeles Building Growth 1880-2026](https://lax-skyline.parcelscope.net/) ⭐️ 7.0/10

An interactive visualization at lax-skyline.parcelscope.net shows Los Angeles building construction dates from 1880 to 2026 based on assessor data. The map highlights urban growth patterns and the long-term effects of zoning policies on housing supply and city affordability. It relies on Los Angeles County assessor records and primarily displays ages of surviving buildings rather than all past construction.

hackernews · rustywasm · Sep 7, 18:52 · [Discussion](https://news.ycombinator.com/item?id=49601655)

**Discussion**: Users note the data shows surviving buildings only, discuss 1980s downzoning effects on affordability, historical transit networks, and prior visualization techniques using similar assessor sources.

**Tags**: `#data visualization`, `#urban planning`, `#Los Angeles history`, `#GIS`, `#zoning policy`

---

<a id="item-8"></a>
## [Broadcom Pulls VDDK Downloads, Complicating VMware Exits](https://www.virtualizationhowto.com/2026/09/leaving-vmware-just-got-harder-after-broadcom-pulled-vddk-downloads/) ⭐️ 7.0/10

Broadcom has removed public access to VDDK downloads from its developer portal. This directly hinders third-party tools used for migrating virtual machines out of VMware environments. The change increases lock-in for VMware customers considering moves to Hyper-V or Proxmox amid Broadcom's licensing shifts. It affects enterprise teams planning infrastructure migrations. VDDK supplies APIs for virtual disk access required by backup and migration software. Community notes indicate qemu-img can still convert VMDK files, though full migrations need additional configuration steps.

hackernews · josephcsible · Sep 7, 20:32 · [Discussion](https://news.ycombinator.com/item?id=49602699)

**Background**: VDDK is VMware's Virtual Disk Development Kit, a toolkit for building applications that manage virtual disks via vSphere Storage APIs. It has long supported data protection and cross-platform migration workflows.

<details><summary>References</summary>
<ul>
<li><a href="https://developer-stgv2.broadcom.com/sdks/vmware-virtual-disk-development-kit-vddk/latest/">VMware Virtual Disk Development Kit (VDDK)</a></li>
<li><a href="https://techdocs.broadcom.com/us/en/vmware-cis/vsphere/vsphere-sdks-tools/8-0/virtual-disk-development-kit-programming-guide/installing-the-development-kit/installing-the-vddk-package.html">Installing the VDDK Package</a></li>

</ul>
</details>

**Discussion**: Commenters lament Broadcom's focus on extraction over innovation, share successful Hyper-V and Proxmox migration stories, and confirm that basic VMDK conversions remain feasible with open-source tools despite the VDDK restriction.

**Tags**: `#VMware`, `#Broadcom`, `#Virtualization`, `#Migration`, `#Enterprise Infrastructure`

---

<a id="item-9"></a>
## [OpenAI Chief Scientist on AI Defense vs Reckless Development](https://simonwillison.net/2026/Sep/7/jakub-pachocki/) ⭐️ 7.0/10

Jakub Pachocki, OpenAI's Chief Scientist, stated that powerful aligned AI must be built quickly for defense against AI threats such as securing infrastructure and countering rogue agents. This highlights OpenAI's strategic focus on defensive AI systems while stressing the need to avoid reckless progress, influencing broader AI safety and ethics discussions in the industry. Pachocki emphasized that defensive AI will be a primary deployment focus but warned that uncertainty around AI progress must not excuse recklessness in development.

rss · Simon Willison · Sep 7, 22:26

**Tags**: `#ai-safety`, `#openai`, `#ai-ethics`, `#ai-alignment`, `#responsible-ai`

---

<a id="item-10"></a>
## [Why Big-Bang Rewrites of Legacy Systems Usually Fail](https://simonwillison.net/2026/Sep/6/theres-no-limit-to-how-bad-code-can-get/) ⭐️ 7.0/10

Simon Willison posted a detailed comment explaining why attempts to rewrite legacy code from scratch rarely succeed, citing misaligned incentives and the old system continuing to evolve as the business core. This insight highlights common pitfalls in managing technical debt, affecting engineering teams and organizations that consider large-scale system replacements instead of incremental improvements. Willison describes how the old team loses motivation for maintenance while the new team struggles with undocumented behavior, often resulting in two parallel systems or abandoned projects after months or years.

rss · Simon Willison · Sep 6, 09:08

**Tags**: `#technical debt`, `#software engineering`, `#legacy systems`, `#code rewrites`, `#refactoring`

---

<a id="item-11"></a>
## [Tiny 417k-param RNN Generates Full Bad Apple Video Autonomously](https://www.reddit.com/r/MachineLearning/comments/1wa8rub/generating_bad_apple_autonomously_from_a_single/) ⭐️ 7.0/10

A 417k-parameter recurrent dynamical system generates the full ~6,573-frame Bad Apple video autonomously from a single initial latent state (h0, c0) using closed-loop RNN transitions and a frame decoder, with no timestamp inputs at inference. This shows a compact recurrent formulation can achieve long-horizon autonomous video generation, offering an alternative to explicit time-conditioned models and enabling efficient deployment in constrained environments. The model totals 417,129 parameters (1.6 MB), runs above 200 FPS on RTX 4080 with 17.2 MB VRAM, was trained via rollout curriculum to K=512 plus state perturbation and second-difference regularization, yet generalizes beyond training horizon.

reddit · r/MachineLearning · /u/SEBADA321 · Sep 8, 00:05

**Tags**: `#recurrent neural networks`, `#video generation`, `#latent dynamics`, `#machine learning`, `#generative models`

---

<a id="item-12"></a>
## [EmbedFlow Migrates Embedding Models with Zero Downtime via Reranking](https://www.reddit.com/r/MachineLearning/comments/1wabmm7/my_lab_found_a_way_to_migrate_between_embedding/) ⭐️ 7.0/10

A research lab introduced EmbedFlow, which migrates between embedding models by reranking K documents from an existing index using the new model to match target retrieval quality without full re-indexing. The method was tested across 63 migrations on up to 1 million documents, with Qwen 4B to 8B achieving native performance at K=50, and integrates with Qdrant via pip install embedflow. This approach addresses the high cost and downtime of re-indexing billions of vectors when upgrading embedding models in large-scale RAG systems, potentially reducing migration time from months to near-instant. It affects teams maintaining production vector databases and local LLM applications by enabling seamless model upgrades. The technique works by selecting K documents from the source model's index and reranking them with the target model; determining sufficient K remains challenging. It supports Qdrant and was validated up to 1 million documents but remains self-reported without independent verification.

reddit · r/MachineLearning · /u/Potential_Low_1183 · Sep 8, 02:16

**Tags**: `#embeddings`, `#RAG`, `#vector databases`, `#model migration`, `#machine learning`

---

<a id="item-13"></a>
## [Rustuna: High-Performance Rust Implementation of Optuna Released](https://www.reddit.com/r/MachineLearning/comments/1w9nyhz/rustuna_a_highperformance_rust_implementation_of/) ⭐️ 7.0/10

The team released Rustuna on GitHub, a high-speed and memory-efficient Rust implementation of the Optuna hyperparameter optimization framework. It offers performance and security gains by removing Python dependencies to mitigate supply chain attacks while maintaining a compatible API for machine learning users. Rustuna features zero Python dependencies, lower memory footprint via native Rust management, and Optuna-compatible design, though full compatibility is not maintained in every case to prioritize speed.

reddit · r/MachineLearning · /u/c-bata · Sep 7, 10:01

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/optuna/rustuna">GitHub - optuna/ rustuna : A faster Optuna implementation in Rust ...</a></li>
<li><a href="https://optuna.org/">Optuna - A hyperparameter optimization framework</a></li>

</ul>
</details>

**Tags**: `#Rust`, `#Optuna`, `#Hyperparameter Optimization`, `#Machine Learning`, `#Performance`

---

<a id="item-14"></a>
## [Yandex Explores KV Cache Modification as LLM Agent Runtime](https://www.reddit.com/r/MachineLearning/comments/1w9myqc/kv_cache_as_an_agent_runtime_r/) ⭐️ 7.0/10

A Yandex research post examines modifying the KV-cache inference state to enable more interactive and responsive LLM agents. The approach builds on prior work including Hogwild! Inference and AsyncReasoning, with a preview of a Qwen3.8-27B model playing DOOM interactively. Treating KV-cache manipulation as an intermediate runtime axis could improve agent interactivity without the high cost of model changes or overly abstract harnesses. This may influence future LLM inference designs for real-time applications. The method leverages shared KV cache with Rotary Position Embeddings to support concurrent attention without additional fine-tuning, as shown in Hogwild! Inference evaluations on 512 LIMO tasks. AsyncReasoning demonstrates up to 80× reduction in time to first token while preserving reasoning accuracy.

reddit · r/MachineLearning · /u/_puhsu · Sep 7, 09:03

**Background**: KV cache stores key and value tensors during transformer inference to avoid recomputing attention for previous tokens. Papers such as Hogwild! Inference and AsyncReasoning from Yandex research demonstrate parallel and asynchronous generation using this cache structure.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2504.06261">Hogwild! Inference: Parallel LLM Generation via Concurrent Attention</a></li>
<li><a href="https://arxiv.org/html/2512.10931v1">Asynchronous Reasoning: Training-Free Interactive Thinking LLMs</a></li>

</ul>
</details>

**Tags**: `#LLM inference`, `#KV cache`, `#AI agents`, `#model runtime`, `#interactive systems`

---

<a id="item-15"></a>
## [PINNStudio: Free Open-Source No-Code GUI for PINNs](https://www.reddit.com/r/MachineLearning/comments/1w9a2i7/pinnstudio_a_free_opensource_nocode_gui_for/) ⭐️ 7.0/10

PINNStudio is a free open-source GUI that lets users define PDEs, boundary conditions, network architectures, and training schedules for PINNs through an interface without writing code from scratch. It automatically generates code using DeepXDE, runs training, and displays live loss curves and solution plots, with built-in templates for equations like Heat and Allen-Cahn. This tool lowers barriers for students and researchers with limited coding experience in scientific machine learning by eliminating boilerplate code for PINN problems. It enables faster workflows for both forward and inverse PDE problems, potentially accelerating adoption in physics-informed neural network applications. The application supports 1D or 2D domains, coupled multi-output PDE systems, custom training schedules, and both forward and inverse problems, with installation via pip install pinnstudio and source available on GitHub. It streams training logs and visualizes results directly in the app.

reddit · r/MachineLearning · /u/Impossible-Jello2749 · Sep 6, 22:19

**Background**: Physics-informed neural networks integrate neural networks with physical laws described by differential equations to solve forward and inverse problems with minimal data. They are commonly built using libraries like DeepXDE, which provides the foundation for handling PDE constraints during training.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Physics-informed_neural_networks">Physics-informed neural networks - Wikipedia</a></li>
<li><a href="https://www.mathworks.com/discovery/physics-informed-neural-networks.html">What Are Physics-Informed Neural Networks (PINNs)?</a></li>

</ul>
</details>

**Tags**: `#PINNs`, `#Scientific Machine Learning`, `#No-code Tools`, `#Open Source`, `#Physics-Informed Neural Networks`

---

<a id="item-16"></a>
## [IEEE T-PAMI EIC Confirms Missing Positive Review Caused Unjust Rejection](https://www.reddit.com/r/MachineLearning/comments/1w9v43o/update_eic_confirmed_ghost_reviewerhow_to_get/) ⭐️ 7.0/10

Following a six-month IEEE investigation, the T-PAMI Editor-in-Chief formally acknowledged that four reviews were received, confirming a positive fourth review had disappeared from the record and caused rejection despite three excellent scores. The incident exposes a serious peer-review integrity failure at a top machine learning journal, raising concerns about editorial processes and trust in academic publishing for researchers submitting to IEEE T-PAMI. The Associate Editor had inadvertently revealed reliance on negative comments from a nonexistent fourth reviewer; the actual fourth review was positive but vanished under the AE’s handling.

reddit · r/MachineLearning · /u/cussealin · Sep 7, 15:22

**Tags**: `#peer-review`, `#academic-publishing`, `#IEEE-T-PAMI`, `#research-integrity`, `#machine-learning`

---

<a id="item-17"></a>
## [GitHub Shares Reconstructed Stuxnet Source Code for Research](https://github.com/Sadpainy/Stuxnet) ⭐️ 6.0/10

A GitHub repository named Stuxnet has been posted as Show HN, sharing a reconstructed version of the infamous malware source code consisting of about 15,000 lines for research and education only. The release enables detailed analysis of a historic cyber weapon that targeted industrial control systems, raising awareness about security risks in critical infrastructure sectors worldwide. The project is explicitly limited to research and education, with community comments highlighting its code volume and referencing related literature such as the book Countdown to Zero Day.

hackernews · CMDDestory · Sep 7, 22:12 · [Discussion](https://news.ycombinator.com/item?id=49603546)

**Background**: Stuxnet was a sophisticated malware discovered around 2010 that specifically targeted Siemens programmable logic controllers in industrial environments. Industrial control systems manage processes in sectors such as power generation and manufacturing.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Industrial_control_system">Industrial control system - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters recommend the book Countdown to Zero Day, discuss USB propagation feasibility in real deployments, and suggest that more documentation would improve the reconstructed code's usability.

**Tags**: `#cybersecurity`, `#malware`, `#reverse-engineering`, `#stuxnet`, `#ics`

---

<a id="item-18"></a>
## [LG Smart TVs Logging Audio and Snooping Devices Exposed](https://www.youtube.com/watch?v=6IFVTcM28KA) ⭐️ 6.0/10

A video reveals LG smart TVs logging audio with the screen off and snooping on local devices, potentially affecting 216 million units. The exposure raises privacy concerns for smart TV users and fuels industry-wide discussions on IoT data practices and consent. LG contract terms require users to notify household members and guests that voices may be captured, while TVs store spying data until an internet connection is made.

hackernews · treve · Sep 7, 00:22 · [Discussion](https://news.ycombinator.com/item?id=49592375)

**Discussion**: Commenters criticize LG's contract terms as overly invasive, share experiences disabling network functions on older models, and express reluctance to purchase LG products due to privacy risks.

**Tags**: `#privacy`, `#smart-tv`, `#iot-security`, `#lg`, `#surveillance`

---

<a id="item-19"></a>
## [Caltech Mathathon: First Research-Level Mathematics Hackathon](https://mathathonchallenge.com/index.html) ⭐️ 6.0/10

Caltech undergraduates announced the Mathathon, the first hackathon devoted to research-level mathematics, organized to promote responsible AI use. The event links hackathon formats to advanced math research and responsible AI, potentially shaping student engagement with AI tools in academic settings. Organized by unpaid Caltech undergrads with all funding going to judges and participants, the event has no official affiliation with Caltech departments or sponsors.

hackernews · astroanax · Sep 7, 09:26 · [Discussion](https://news.ycombinator.com/item?id=49596055)

**Discussion**: Organizers stated they are unpaid undergrads focused on responsible AI use. Commenters raised concerns that extended LLM runtimes contradict traditional hackathon intensity, noted the weak CS department as a driver, and showed interest in testing math reasoning harnesses.

**Tags**: `#hackathon`, `#mathematics`, `#AI`, `#research`, `#education`

---

<a id="item-20"></a>
## [Abusive crawlers drain more CPU than legitimate traffic on git.kernel.org](https://simonwillison.net/2026/Sep/7/creepy-crawlies/) ⭐️ 6.0/10

Konstantin Ryabitsev reports that git.kernel.org spends more CPU rendering commits for scrapers than on all legitimate access including git clones, with 14 cores constantly rendering HTML across 5 geo-distributed nodes. This highlights the growing resource burden of abusive web crawlers on open infrastructure sites, raising concerns for similar projects like Datasette that serve large volumes of crawlable pages. The abusive traffic specifically targets HTML rendering of git commits, exceeding legitimate usage at any given time across the distributed nodes.

rss · Simon Willison · Sep 7, 23:08

**Tags**: `#crawling`, `#git`, `#web-scraping`, `#linux-kernel`, `#server-performance`

---

<a id="item-21"></a>
## [Reddit Post Claims 95% Token Cut for Image LLM Inference](https://www.reddit.com/r/MachineLearning/comments/1wab7ui/i_reduced_imageprocessing_token_usage_by_95/) ⭐️ 6.0/10

A Reddit post reports testing a new method on the MOMA Graph benchmark with 1,315 questions, achieving roughly 95% lower token usage than GPT-4o direct vision while maintaining similar accuracy. If validated across more benchmarks, this efficiency gain could significantly lower costs for multimodal AI applications and influence inference optimization trends in the industry. The author intentionally withholds implementation details as the method is still under development and seeks feedback on required evidence such as additional datasets and statistical significance.

reddit · r/MachineLearning · /u/angelinusbread · Sep 8, 01:57

**Tags**: `#multimodal AI`, `#VLM efficiency`, `#token optimization`, `#inference optimization`, `#AI benchmarks`

---

<a id="item-22"></a>
## [ML Reproducibility Faces Growing Irrelevance in Research](https://www.reddit.com/r/MachineLearning/comments/1w92eis/reproducibility_seems_to_be_headed_towards/) ⭐️ 6.0/10

A Reddit post argues that reproducibility in machine learning research is becoming a lost cause due to costly physical AI experiments reliant on unreliable demos and unverifiable performance claims from big tech companies. This development could erode trust in ML advancements and hinder scientific progress, especially as research shifts toward physical AI systems and corporate tools with strong financial incentives to exaggerate results. The post cites three main issues: expensive hardware requirements for physical experiments, selective demos that may fail outside recordings, and lack of proof for big tech claims on vague metrics, plus incentives against sharing code with competitors.

reddit · r/MachineLearning · /u/NeighborhoodFatCat · Sep 6, 17:29

**Tags**: `#reproducibility`, `#machine learning research`, `#physical AI`, `#big tech`, `#research practices`

---