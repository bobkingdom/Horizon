---
layout: default
title: "Horizon Summary: 2026-10-03 (EN)"
date: 2026-10-03
lang: en
---

> From 35 items, 18 important content pieces were selected

---

1. [AI Defeats Top Stratego Player with Sample-Efficient Algorithm](#item-1) ⭐️ 9.0/10
2. [Redis Creator Releases ds4 for Local LLM Inference](#item-2) ⭐️ 8.0/10
3. [Greg KH Debunks Anthropic Mythos' Overstated 79 Linux Kernel CVEs](#item-3) ⭐️ 8.0/10
4. [NeurIPS 2026 Paper Tackles Topological OOD Generalization in Dynamical Systems](#item-4) ⭐️ 8.0/10
5. [DEER+GTF Enables 100x Faster Parallel RNN Training for Chaotic Systems](#item-5) ⭐️ 8.0/10
6. [The Forgetful CPU: Linux Bringup Challenges on Apple M4](#item-6) ⭐️ 7.0/10
7. [Court Rules Utah VPN Law Technically Impossible, Sides with EFF](#item-7) ⭐️ 7.0/10
8. [Black Forest Labs Releases FLUX 3 Image Model with Steerable UX](#item-8) ⭐️ 7.0/10
9. [1973 Biographical Article on John von Neumann Shared on Hacker News](#item-9) ⭐️ 7.0/10
10. [ChatGPT Launches 'Sites' for Instant Web App Generation](#item-10) ⭐️ 7.0/10
11. [Matthew Green Warns Sandboxing Cannot Contain Rogue AI Agent Worms](#item-11) ⭐️ 7.0/10
12. [arXiv Limits Submitters to Two Papers per Calendar Month](#item-12) ⭐️ 7.0/10
13. [LLMs Resist User Errors but Accept Same Claims from Verified Sources](#item-13) ⭐️ 7.0/10
14. [Meta Open-Sources Muse Gadget SDK for ESP32 AI Hardware Projects](#item-14) ⭐️ 6.0/10
15. [Two Papers Link Loss of Cell Identity to Human Aging](#item-15) ⭐️ 6.0/10
16. [Apple Updates Full Disk Access Permissions in macOS](#item-16) ⭐️ 6.0/10
17. [FLEET Uses MCTS and Vector Stores for Reward-Aware LLM Generation](#item-17) ⭐️ 6.0/10
18. [Reddit Questions Retaining Robot Demos with Hand Tracking Gaps](#item-18) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [AI Defeats Top Stratego Player with Sample-Efficient Algorithm](https://arstechnica.com/science/2026/10/ai-finally-beat-the-best-stratego-player-in-history-and-did-it-on-a-budget/) ⭐️ 9.0/10

A new AI system defeated the world's top Stratego player and was published in Nature. The algorithm is sample-efficient, requiring about 34 times fewer games than DeepNash from 2022 while achieving superior performance against hidden-information challenges. This breakthrough advances AI capabilities in imperfect-information games, which model real-world scenarios with uncertainty. It demonstrates that efficient training methods can outperform prior systems like DeepNash and may influence future reinforcement learning research. The approach handles hidden information more effectively than previous model-free multiagent reinforcement learning methods. It learned faster and reached stronger play against human experts despite limited training samples.

hackernews · PaulHoule · Oct 2, 14:11 · [Discussion](https://news.ycombinator.com/item?id=49933740)

**Background**: Stratego is a board game involving hidden piece ranks that create imperfect information for players. DeepNash was an earlier DeepMind reinforcement learning system that reached expert level in Stratego but required far more training games.

<details><summary>References</summary>
<ul>
<li><a href="https://www.deeplearning.ai/the-batch/deepnash-the-rl-system-that-plays-stratego-like-a-master">DeepNash, the RL System That Plays Stratego like a Master</a></li>

</ul>
</details>

**Discussion**: Commenters highlighted the critical importance of the 34x training efficiency gain for handling hidden information in games. Many expressed surprise that Stratego remained challenging for AI until this advance and noted the 2022 DeepNash work was not yet at superhuman level.

**Tags**: `#AI`, `#Game AI`, `#Reinforcement Learning`, `#Imperfect Information`, `#Nature Paper`

---

<a id="item-2"></a>
## [Redis Creator Releases ds4 for Local LLM Inference](https://dwarfstar.sh/) ⭐️ 8.0/10

Antirez, the creator of Redis, released ds4, a new local LLM inference tool focused on DeepSeek 4 Flash and PRO models that runs inference directly without a separate HTTP server. The release brings high-quality local inference capabilities from a respected systems programmer to the growing ecosystem of on-device AI tools, potentially influencing how developers run models on personal hardware. ds4 supports Apple Metal, NVIDIA CUDA and AMD ROCm, maintains token history and model state, and shows prefill progress; community forks add Go bindings, Vision support, and Qwen model compatibility.

hackernews · fibo · Oct 2, 18:01 · [Discussion](https://news.ycombinator.com/item?id=49936575)

**Background**: Antirez is widely known for creating Redis, a popular in-memory data store, and has now applied similar engineering focus to building efficient local inference software for large language models.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/antirez/ds4">GitHub - antirez/ds4: DeepSeek 4 Flash and PRO local ...</a></li>
<li><a href="https://runthisai.com/en/blog/ds4-local-inference-guide">DS4: Complete Guide to Running DeepSeek 4 Flash and PRO ...</a></li>

</ul>
</details>

**Discussion**: HN users report strong performance on M5 Max hardware with Qwen models and long contexts, while others share forks adding language bindings and inspired projects for Intel GPUs; overall sentiment highlights practical usability and rapid community extensions.

**Tags**: `#local LLMs`, `#AI inference`, `#Redis`, `#open source`, `#Hacker News`

---

<a id="item-3"></a>
## [Greg KH Debunks Anthropic Mythos' Overstated 79 Linux Kernel CVEs](https://www.youtube.com/watch?v=NnV_cWeoo5Q) ⭐️ 8.0/10

In a Kernel Recipes 2026 talk, Greg Kroah-Hartman detailed how Anthropic's Mythos model claimed 79 Linux kernel vulnerabilities but most were already fixed or invalid, found via pattern matching without attribution. The analysis exposes misleading AI-driven security claims that could erode trust in vulnerability research and highlights the gap between marketing hype and actual kernel development effort. Of the 79 claims, 24 lacked details, 14 were not bugs, 3 used fabricated data, 15 were already fixed (mostly by others), and only 20 required new fixes, often relying on unrealistic assumptions like malicious filesystem images.

hackernews · usernomdeguerre · Oct 2, 02:51 · [Discussion](https://news.ycombinator.com/item?id=49929391)

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Anthropic_Mythos">Anthropic Mythos</a></li>
<li><a href="https://www.anthropic.com/claude/mythos">Claude Mythos \ Anthropic</a></li>

</ul>
</details>

**Discussion**: Commenters praised Greg KH's candor and noted the one-hour development effort behind the claims, criticized poor attribution of original kernel patches, and raised concerns about legal risks from training data used by models like Mythos.

**Tags**: `#Linux kernel`, `#security`, `#LLM`, `#Anthropic`, `#vulnerability analysis`

---

<a id="item-4"></a>
## [NeurIPS 2026 Paper Tackles Topological OOD Generalization in Dynamical Systems](https://www.reddit.com/r/MachineLearning/comments/1wvwodf/topological_outofdomain_generalization_in/) ⭐️ 8.0/10

The NeurIPS 2026 paper “Topological Out-of-Domain Generalization in Dynamical Systems Reconstruction” (arXiv:2606.22969) introduces feature-splitting and physical sparsity priors to fix failure modes in hierarchical DSR models. These modifications enable prediction of regime shifts such as cyclic to chaotic behavior without explicit control parameter information during training. This advance allows data-driven models to forecast previously unseen dynamical regimes in systems like climate, brain activity, and sepsis, where tipping points cause abrupt changes. It moves beyond standard time series forecasting that relies only on statistical patterns toward genuine scientific generalization. The approach works generically for discrete and continuous RNNs including shallow PLRNNs and Neural ODEs; it augments training to infer both the dynamical system and unknown control parameters for extrapolation beyond the training domain.

reddit · r/MachineLearning · /u/DangerousFunny1371 · Oct 2, 15:25

**Background**: Dynamical systems reconstruction (DSR) aims to recover governing equations from time series data. Topological out-of-domain generalization refers to handling changes in the qualitative structure of attractors, such as those occurring at bifurcations when a control parameter crosses a tipping point.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2606.22969">[2606.22969] Topological Out - of - Domain Generalization in...</a></li>

</ul>
</details>

**Tags**: `#Machine Learning`, `#Dynamical Systems`, `#Out-of-Domain Generalization`, `#Time Series Forecasting`, `#NeurIPS`

---

<a id="item-5"></a>
## [DEER+GTF Enables 100x Faster Parallel RNN Training for Chaotic Systems](https://www.reddit.com/r/MachineLearning/comments/1wuz2s4/parallelintime_training_of_recurrent_neural/) ⭐️ 8.0/10

The NeurIPS 2026 spotlight paper presents the DEER+GTF method that combines Newton-type fixed-point iterations with generalized teacher forcing to train nonlinear RNNs on chaotic time series of length T>10^6, achieving O[(log T)²] scaling and over 100x speedup compared to sequential methods. This breakthrough enables efficient parallel-in-time training of RNNs on extremely long sequences from chaotic dynamical systems, significantly outperforming models like Mamba and opening new possibilities for large-scale time series modeling in scientific and real-world applications. DEER alone degrades to O[T log T] under chaotic dynamics, but GTF stabilizes it by linear interpolation between predicted and target states, reducing exposure bias while enabling full GPU parallelization across the sequence.

reddit · r/MachineLearning · /u/DangerousFunny1371 · Oct 1, 13:12

**Background**: Recurrent neural networks process sequential data but traditionally train sequentially with O[T] complexity. DEER solves the forward pass via parallel Newton iterations, while generalized teacher forcing addresses divergence in chaotic systems by interpolating states during training.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/pdf/2306.04406">Generalized Teacher Forcing for Learning Chaotic Dynamics</a></li>

</ul>
</details>

**Tags**: `#RNN`, `#Parallel Training`, `#Dynamical Systems`, `#Time Series Modeling`, `#NeurIPS`

---

<a id="item-6"></a>
## [The Forgetful CPU: Linux Bringup Challenges on Apple M4](https://yuka.dev/blog-2026-10-02-linux-m4.html) ⭐️ 7.0/10

A blog post by Yureka Lilian details the reverse-engineering process to boot mainline Linux on an M4 Mac mini for Asahi Linux, after buying the hardware in November 2024. The effort highlights ongoing barriers to open-source support on Apple Silicon, affecting developers seeking alternatives to macOS and advancing hardware porting techniques in the Linux ecosystem. M4's SPTM hardening broke prior MMIO-tracing methods, forcing println-style debugging, device tree modifications, and register-level investigation from scratch.

hackernews · signa11 · Oct 2, 14:22 · [Discussion](https://news.ycombinator.com/item?id=49933869)

**Background**: Asahi Linux is a community project porting Linux to Apple Silicon Macs. The M4 SoC introduced new security features like SPTM that complicate low-level hardware access compared to earlier M1-M3 chips.

<details><summary>References</summary>
<ul>
<li><a href="https://yuka.dev/blog-2026-10-02-linux-m4.html">The forgetful CPU (Linux on M4) - Blog - Yureka Lilian</a></li>
<li><a href="https://daily.dev/posts/the-forgetful-cpu-linux-on-m4--igqauax00">The forgetful CPU (Linux on M4) - daily.dev</a></li>

</ul>
</details>

**Discussion**: Commenters expressed frustration with Apple's closed ecosystem and hostility toward open hardware, while questioning the practicality of running Linux on such machines and speculating on AI-assisted porting.

**Tags**: `#linux`, `#apple-silicon`, `#m4`, `#kernel`, `#hardware-porting`

---

<a id="item-7"></a>
## [Court Rules Utah VPN Law Technically Impossible, Sides with EFF](https://www.eff.org/deeplinks/2026/10/court-agrees-eff-utahs-vpn-law-demands-technical-impossibility) ⭐️ 7.0/10

A court has sided with the EFF and ruled that Utah's VPN law is technically impossible to comply with, forcing platforms into a choice between nationwide VPN blocks or complete withdrawal from Utah. This ruling highlights the technical limits of enforcing broad VPN restrictions and could influence similar privacy and censorship laws in other states or countries. The law leaves platforms with an impossible choice of blocking all VPN traffic nationwide or withdrawing access from Utah entirely, as reliable VPN detection remains unfeasible.

hackernews · hn_acker · Oct 1, 22:23 · [Discussion](https://news.ycombinator.com/item?id=49927754)

**Discussion**: Commenters questioned the feasibility of detecting VPN connections, noted that the internet may not always route around modern censorship like SNI, and discussed self-censorship risks, with some drawing parallels to gambling site account requirements.

**Tags**: `#privacy`, `#VPN`, `#EFF`, `#censorship`, `#legal`

---

<a id="item-8"></a>
## [Black Forest Labs Releases FLUX 3 Image Model with Steerable UX](https://bfl.ai/models/flux-3-image) ⭐️ 7.0/10

Black Forest Labs announced FLUX 3 Image, its flagship model for text-to-image generation and multi-reference editing supporting up to 10 input images at resolutions from 768 to 4K. The release emphasizes improved steerable UX for precise element placement in compositions. The model advances compositional control in AI image generation, offering a more intuitive interface than prior tools and potentially benefiting artists, designers, and developers working on precise visual layouts. API access is available through providers like OpenRouter with fixed resolution tiers and selectable aspect ratios; early user tests showed inconsistent results for precise editing tasks such as placing a fence in front of a horse.

hackernews · minimaxir · Oct 1, 19:24 · [Discussion](https://news.ycombinator.com/item?id=49925974)

<details><summary>References</summary>
<ul>
<li><a href="https://openrouter.ai/black-forest-labs/flux-3-image">FLUX . 3 Image - API Pricing & Providers | OpenRouter</a></li>
<li><a href="https://bfl.ai/blog/flux-3">FLUX 3 : Multimodal Video, Image & Audio | Black Forest Labs</a></li>

</ul>
</details>

**Discussion**: Users highlight the steerable UX as a major improvement over JSON-based bounding boxes in Ideogram V4 and compare it to InvokeAI, while noting editing accuracy limitations in practice. Many express anticipation for open-weights or local model releases, with some questioning its suitability for frame-by-frame sprite generation.

**Tags**: `#AI image generation`, `#FLUX`, `#UX`, `#machine learning`, `#Black Forest Labs`

---

<a id="item-9"></a>
## [1973 Biographical Article on John von Neumann Shared on Hacker News](https://gwern.net/doc/math/1973-halmos.pdf) ⭐️ 7.0/10

A 1973 biographical article titled The Legend of von Neumann has been shared on Hacker News, including community anecdotes and reading suggestions. Von Neumann's wide-ranging contributions to mathematics, computing and science remain foundational, prompting ongoing discussion of his influence relative to other 20th-century figures. Notable comments quote Edward Teller on von Neumann's conversational style, recommend the book The Man from the Future by Ananyo Bhattacharya, and link to the Hungarian scientist group known as The Martians.

hackernews · suopspaces · Oct 2, 13:18 · [Discussion](https://news.ycombinator.com/item?id=49933235)

**Discussion**: Users shared personal anecdotes, compared von Neumann's influence to Einstein and Planck, recommended biographical books, and discussed the Martians group of Hungarian scientists; some noted comments vanishing due to technical issues.

**Tags**: `#von Neumann`, `#mathematics history`, `#computing history`, `#biography`, `#Hacker News`

---

<a id="item-10"></a>
## [ChatGPT Launches 'Sites' for Instant Web App Generation](https://chatgpt.com/features/sites/) ⭐️ 7.0/10

ChatGPT introduced the 'Sites' feature enabling users to generate and host interactive web apps directly from text prompts without external deployment. The feature accelerates rapid prototyping and could disrupt web design and development industries by allowing non-technical users to create functional sites instantly. User examples include a higher-dimensional maze game prototype built in under an hour; demos have been criticized for superficial elements like rotating JPEG images instead of true 3D.

hackernews · polvi · Oct 1, 22:22 · [Discussion](https://news.ycombinator.com/item?id=49927747)

**Discussion**: Users praise Sites for quick real-world prototyping like games created at concerts, while others worry it will replace website designers and note demo limitations; some highlight how it closes gaps with tools like Claude by avoiding external hosting setups.

**Tags**: `#AI`, `#ChatGPT`, `#Web Development`, `#Prototyping`, `#Generative AI`

---

<a id="item-11"></a>
## [Matthew Green Warns Sandboxing Cannot Contain Rogue AI Agent Worms](https://simonwillison.net/2026/Oct/1/matthew-green/) ⭐️ 7.0/10

Cryptography expert Matthew Green states that sandboxing is insufficient to contain rogue AI agents because they can propagate worm payloads through shared package caches, email, Slack, documents, or WhatsApp. This highlights critical security risks for independently deployed personal AI agents like Meta's Muse, showing how isolated systems can still enable cross-agent worm propagation in real-world communication channels. Agents in separate sandboxes can leave instructions in a shared package cache that alter recipient behavior, forming both halves of a worm when combined with a hijacking payload.

rss · Simon Willison · Oct 1, 06:29

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Muse_(AI_agent)">Muse (AI agent)</a></li>

</ul>
</details>

**Tags**: `#AI agents`, `#security`, `#sandboxing`, `#AI safety`, `#cryptography`

---

<a id="item-12"></a>
## [arXiv Limits Submitters to Two Papers per Calendar Month](https://www.reddit.com/r/MachineLearning/comments/1wvg7yc/arxiv_now_limits_submitters_to_up_to_two/) ⭐️ 7.0/10

arXiv has implemented a policy restricting each submitter to a maximum of two paper submissions per calendar month. This policy affects researchers in machine learning and AI who rely on frequent preprint uploads to share work quickly with the community. The limit applies uniformly to all submitters as a maximum of two submissions per calendar month.

reddit · r/MachineLearning · /u/Nunki08 · Oct 2, 00:47

**Tags**: `#arXiv`, `#preprints`, `#academic publishing`, `#Machine Learning`, `#research policy`

---

<a id="item-13"></a>
## [LLMs Resist User Errors but Accept Same Claims from Verified Sources](https://www.reddit.com/r/MachineLearning/comments/1wv1c2e/llms_that_push_back_on_a_wrong_user_still_accept/) ⭐️ 7.0/10

Authors demonstrate that LLMs resist wrong answers from users but accept identical misinformation framed as coming from verified sources, termed Authority Bias. They tested this on TriviaQA questions the models already answered correctly across five open-weight families and three API models. Standard sycophancy evaluations apply pressure only through users, allowing models to pass while remaining vulnerable to misinformation from search results, documents, and tool outputs, which is critical as AI systems become more agentic. Verified-source notes flipped 45-88% of correct answers in seven of eight models, while user statements moved answers much less; linear interventions on internal directions reduced source compliance by 64-78 points in three open-weight families.

reddit · r/MachineLearning · /u/MajorRedditor23 · Oct 1, 14:45

**Background**: Sycophancy in LLMs refers to models aligning answers with user beliefs rather than evidence. TriviaQA is a large-scale reading comprehension dataset for question answering evaluation.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2310.13548">[2310.13548] Towards Understanding Sycophancy in Language Models</a></li>
<li><a href="https://arxiv.org/pdf/1705.03551">TriviaQA : A Large Scale Distantly Supervised Challenge Dataset</a></li>

</ul>
</details>

**Tags**: `#LLM bias`, `#sycophancy`, `#AI safety`, `#authority bias`, `#agentic AI`

---

<a id="item-14"></a>
## [Meta Open-Sources Muse Gadget SDK for ESP32 AI Hardware Projects](https://gadgets.muse.ai/) ⭐️ 6.0/10

Meta has open-sourced the Muse Gadget SDK and firmware on GitHub, allowing users to program ESP32 boards or Raspberry Pi devices to connect the Muse AI agent to custom displays, buttons, sensors, and actuators. The release enables hobbyists to build personalized AI hardware integrations, reflecting Meta's strategy of taking risks others avoid to foster ecosystem growth in AI agents and IoT. The open-source SDK targets off-the-shelf ESP32 boards and Raspberry Pi setups, with code available at facebookincubator/muse-gadget-sdk, focusing on direct hardware connections to Muse agents.

hackernews · anant · Oct 2, 19:26 · [Discussion](https://news.ycombinator.com/item?id=49937504)

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/facebookincubator/muse-gadget-sdk">GitHub - facebookincubator/muse-gadget-sdk: Open source SDK ...</a></li>
<li><a href="https://gadgets.muse.ai/">Muse Gadgets: Open source hardware for your Muse</a></li>

</ul>
</details>

**Discussion**: Community sentiment is mixed, with some praising the fun DIY ESP32 approach and Meta's risk-taking while others express skepticism toward Meta, citing distrust and reluctance to integrate the ecosystem into their homes or projects.

**Tags**: `#AI Agents`, `#IoT`, `#Meta`, `#Hardware`, `#SDK`

---

<a id="item-15"></a>
## [Two Papers Link Loss of Cell Identity to Human Aging](https://erictopol.substack.com/p/loss-of-cell-identity-drives-human) ⭐️ 6.0/10

Two papers published in Nature and Cell propose that loss of cell identity via epigenetic changes is a key driver of human aging. This research could advance understanding of aging mechanisms and influence future studies on epigenetic interventions for age-related conditions. The papers are linked at nature.com/articles/s41586-026-10955-0 and cell.com/cell/abstract/S0092-8674(25)00853-0, with debates on whether they explain facts like the Hayflick limit or species lifespan differences.

hackernews · bookofjoe · Oct 1, 20:02 · [Discussion](https://news.ycombinator.com/item?id=49926411)

**Discussion**: Commenters view the work as a reframing of accumulated damage ideas, question its ability to explain the Hayflick limit or varying lifespans across species, note chronic stress as a factor, and criticize AI illustrations on the post.

**Tags**: `#aging`, `#epigenetics`, `#cell biology`, `#research papers`, `#biology`

---

<a id="item-16"></a>
## [Apple Updates Full Disk Access Permissions in macOS](https://developer.apple.com/news/?id=p6zjojqw) ⭐️ 6.0/10

Apple has released official updates detailing changes to Full Disk Access in macOS, which refine how applications request and maintain broad file system permissions. These changes affect security and privacy controls for apps including AI agents, giving users more oversight while potentially requiring developers to adjust permission strategies. The update emphasizes explicit user grants in System Settings and supports granular revocation, though some users note limitations in viewing or editing specific folder permissions per app.

hackernews · notfirstpost · Oct 2, 19:37 · [Discussion](https://news.ycombinator.com/item?id=49937631)

**Background**: Full Disk Access is a privacy feature introduced in macOS Mojave that allows approved apps to bypass Transparency, Consent, and Control restrictions on protected files and folders.

<details><summary>References</summary>
<ul>
<li><a href="https://support.apple.com/guide/security/controlling-app-access-to-files-secddd1d86a6/web">Controlling app access to files in macOS - Apple Support</a></li>
<li><a href="https://macpaw.com/how-to/full-disk-access">How to grant Full Disk Access on Mac and how to revoke it</a></li>

</ul>
</details>

**Discussion**: Users discussed practical workarounds for AI agents using per-file permission prompts instead of blanket access, concerns over excessive permissions granted to apps like Spotify or Gemini, and desires for better per-folder visibility and revocation tools; some are isolating agents in VMs for added security.

**Tags**: `#macOS`, `#security`, `#privacy`, `#AI agents`, `#permissions`

---

<a id="item-17"></a>
## [FLEET Uses MCTS and Vector Stores for Reward-Aware LLM Generation](https://www.reddit.com/r/MachineLearning/comments/1wvs12j/adding_memory_to_search_instead_of_sampling_in/) ⭐️ 6.0/10

FLEET authors describe attributing external rewards to tokens, storing normalized hidden states in vector stores at high-entropy/varentropy points, and applying modified MCTS to adjust logits during generation instead of blind Best-of-N sampling. This approach makes reward maximization in LLMs more efficient by turning blind sampling into memory-enhanced search, achieving baseline performance with fewer iterations on tasks like GSM8K and LiveCodeBench. Tested with Llama 3.2 3B on GSM8K and LiveCodeBench v6 easy split using penalty to zero suboptimal tokens plus greedy decoding; metadata can serve as prior for SFT/RL without sequential updates during inference.

reddit · r/MachineLearning · /u/Helpful_Minimum_2214 · Oct 2, 12:04

**Tags**: `#Machine Learning`, `#LLMs`, `#MCTS`, `#Reinforcement Learning`, `#Search Algorithms`

---

<a id="item-18"></a>
## [Reddit Questions Retaining Robot Demos with Hand Tracking Gaps](https://www.reddit.com/r/MachineLearning/comments/1ww5ijc/r_would_you_keep_a_robot_demonstration_if_hand/) ⭐️ 6.0/10

A Reddit post in r/MachineLearning asks whether to keep robot demonstration recordings when hand tracking misses critical phases like cable insertion due to occlusion, citing MEgoVista evaluation protocols. This highlights flaws in pose evaluation for robot learning from demonstrations, where high overall recall can mask failures in contact phases that affect imitation learning success. The post references MEgoVista Table 3 for precision, recall and F1 scores plus Section 4.4's protocol that assigns error to missed detections; HaPTIC failed entirely in multi-person scenes.

reddit · r/MachineLearning · /u/Klutzy_Cap8492 · Oct 2, 21:18

**Background**: Hand tracking from egocentric video is used to collect demonstrations for robot manipulation tasks such as insertion, where occlusion during contact can create gaps in pose labels.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/pdf/2609.16684">MEgoVista: Multi-view Ego-aware Motion Estimation for Metric ...</a></li>

</ul>
</details>

**Tags**: `#robot learning`, `#hand tracking`, `#pose estimation`, `#evaluation metrics`, `#machine learning`

---