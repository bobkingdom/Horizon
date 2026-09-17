---
layout: default
title: "Horizon Summary: 2026-09-17 (EN)"
date: 2026-09-17
lang: en
---

> From 30 items, 15 important content pieces were selected

---

1. [Nvidia Announces Native CUDA GPU Kernels in Rust](#item-1) ⭐️ 8.0/10
2. [Xiaomi Launches Live Dashboard for Mimo 2.6 Post-Training](#item-2) ⭐️ 8.0/10
3. [New Method Breaks 1.58-Bit Barrier for Ternary LLMs](#item-3) ⭐️ 8.0/10
4. [Performance Improvements in .NET 11](#item-4) ⭐️ 8.0/10
5. [AWS Cannot Restore Some Data from Iran-Damaged Middle East Facilities](#item-5) ⭐️ 8.0/10
6. [GoBench: New Benchmark Evaluates LLMs on 9x9 Go](#item-6) ⭐️ 8.0/10
7. [TabPFN-3.5 Released as New SOTA Tabular Foundation Model](#item-7) ⭐️ 8.0/10
8. [Engineering of US Strategic Petroleum Reserve Salt Cavern Storage](#item-8) ⭐️ 7.0/10
9. [E-ink Frame Detects Birdsong and Renders 1800s Illustrations](#item-9) ⭐️ 7.0/10
10. [TMLR Tests If Authors Can Explain Their Desk-Rejected Papers](#item-10) ⭐️ 7.0/10
11. [LARA: Low-Rank Residual Adapters for Composable Frozen LLM Behaviors](#item-11) ⭐️ 7.0/10
12. [44M Parameter Ternary LLM Achieves 1900 tok/s in 19.8 MB](#item-12) ⭐️ 7.0/10
13. [4B Model Claims 81% Faster Query Plans Than Postgres](#item-13) ⭐️ 6.0/10
14. [Blog Post Stresses That Backups Require Reliable Restoration](#item-14) ⭐️ 6.0/10
15. [Blog Post on Small Programming and Command-Line Tricks](#item-15) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Nvidia Announces Native CUDA GPU Kernels in Rust](https://developer.nvidia.com/blog/introducing-cuda-rust-two-tracks-for-writing-gpu-kernels/) ⭐️ 8.0/10

Nvidia announced two-track support for writing native CUDA GPU kernels directly in Rust on its developer blog. This enables Rust developers to target GPUs without C++ CUDA, potentially easing vendor lock-in and boosting ML ecosystem tools like Candle. The two-track approach builds on existing crates such as Hugging Face Candle, now under NVIDIA ownership, for native Rust kernel development.

hackernews · nonmaskable · Sep 16, 11:15 · [Discussion](https://news.ycombinator.com/item?id=49724881)

**Discussion**: Commenters welcomed the Rust direction and Candle integration but criticized CUDA's proprietary lock-in, preferring separate-kernel models like OpenCL or Triton; some noted the blog's unusual writing style.

**Tags**: `#Rust`, `#CUDA`, `#GPU Programming`, `#Nvidia`, `#Systems Programming`

---

<a id="item-2"></a>
## [Xiaomi Launches Live Dashboard for Mimo 2.6 Post-Training](https://mimo.xiaomi.com/rl/) ⭐️ 8.0/10

Xiaomi has launched a public live dashboard at mimo.xiaomi.com/rl/ that displays real-time training metrics for the reinforcement learning runs of Mimo 2.6 Pro and Flash models directly from the trainer's logs. This level of transparency in post-training could accelerate community understanding of LLM development and increase adoption of open models from Chinese firms like Xiaomi, putting pressure on closed providers such as OpenAI and Anthropic. The dashboard covers reinforcement-learning runs for mimo-v2.6-pro and mimo-v2.6-flash; earlier Mimo-v2.5-Pro scored 19% on DeepSWE 1.1 while top models reach 69-74%.

hackernews · krackers · Sep 16, 20:09 · [Discussion](https://news.ycombinator.com/item?id=49732270)

**Background**: LLM post-training adapts pre-trained base models through techniques such as reinforcement learning to improve instruction following and desired behaviors using curated data.

<details><summary>References</summary>
<ul>
<li><a href="https://mimo.xiaomi.com/rl/">mimo -v 2 . 6 RL</a></li>
<li><a href="https://en.wikipedia.org/wiki/Xiaomi_MiMo">Xiaomi MiMo - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Users report strong performance and low cost with prior MiMo versions for software engineering tasks, while others discuss implications for open-source AI competition and question whether public observation could affect model training.

**Tags**: `#AI`, `#LLM`, `#Xiaomi`, `#Machine Learning`, `#Open Source`

---

<a id="item-3"></a>
## [New Method Breaks 1.58-Bit Barrier for Ternary LLMs](https://arxiv.org/abs/2609.16338) ⭐️ 8.0/10

An arXiv paper presents a compression layout that reduces ternary LLM weights from 1.58 bits to 1.48 bits per weight by exploiting the observed 51% zero-weight frequency in real models. It delivers up to 1.28× faster ternary matrix-vector multiplication and 1.27× higher decode throughput on GPUs. This advance enables more efficient inference for ternary LLMs on CPUs and GPUs, with potential for custom ASIC hardware that could dramatically lower power consumption and memory needs in on-device AI applications. The BITCOS layout achieves measured gains of up to 1.18× on CPUs and 1.27× on GPUs across five platforms; the method applies only to storage format while runtime expansion to 1.58-bit representation remains necessary.

hackernews · matt_d · Sep 16, 20:59 · [Discussion](https://news.ycombinator.com/item?id=49732931)

**Background**: Ternary LLMs restrict weights to the values −1, 0, and +1, requiring approximately 1.58 bits per weight since log2(3) ≈ 1.58. Prior work established that such models can match full-precision quality when trained with quantization-aware methods.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2609.16338">[2609.16338] Breaking the 1.58-bit Barrier for Ternary LLMs</a></li>
<li><a href="https://arxiv.org/html/2609.16338">Breaking the 1.58-bit Barrier for Ternary LLMs</a></li>

</ul>
</details>

**Discussion**: Commenters noted the practical efficiency gains for ASIC and embedded use cases while questioning whether vector quantization might outperform ternary approaches; others highlighted that in-memory expansion to 1.58 bits is still required and discussed potential power benefits on custom silicon.

**Tags**: `#LLM quantization`, `#model compression`, `#ternary weights`, `#efficient inference`, `#AI hardware`

---

<a id="item-4"></a>
## [Performance Improvements in .NET 11](https://devblogs.microsoft.com/dotnet/performance-improvements-in-net-11/) ⭐️ 8.0/10

Microsoft published a detailed blog post on performance enhancements in .NET 11. The post highlights runtime improvements that benefit .NET developers and has generated positive community discussion on engineering quality. Key points include runtime async advancements and noticeable startup time gains reported in recent project migrations.

hackernews · soheilpro · Sep 15, 12:18 · [Discussion](https://news.ycombinator.com/item?id=49711424)

**Discussion**: Commenters praised the technical depth and solid engineering, expressed excitement about runtime async, and shared personal performance improvements from migrations.

**Tags**: `#.NET`, `#Performance`, `#Runtime`, `#C#`, `#Async`

---

<a id="item-5"></a>
## [AWS Cannot Restore Some Data from Iran-Damaged Middle East Facilities](https://www.wsj.com/world/middle-east/aws-says-it-cant-restore-some-data-from-mideast-facilities-struck-by-iran-ddcb7e5d) ⭐️ 8.0/10

AWS reports it cannot restore some customer data from Middle East data centers damaged by Iranian strikes. This incident challenges assumptions about cloud redundancy and durability guarantees, especially for customers subject to data residency constraints. Discussions reference force majeure clauses in AWS agreements, 11 9's durability claims for S3 storage classes, and UAE data residency rules that limit cross-region replication.

hackernews · berkeleyjunk · Sep 15, 21:41 · [Discussion](https://news.ycombinator.com/item?id=49719249)

**Discussion**: Commenters noted UAE health-sector data residency forcing local storage, questioned 11 9's durability after the incident, cited force majeure language from AWS contracts, and criticized absence of basic offsite backups.

**Tags**: `#AWS`, `#cloud infrastructure`, `#data durability`, `#disaster recovery`, `#data residency`

---

<a id="item-6"></a>
## [GoBench: New Benchmark Evaluates LLMs on 9x9 Go](https://www.reddit.com/r/MachineLearning/comments/1wi68jg/gobench_evaluating_llms_on_the_game_of_go_r/) ⭐️ 8.0/10

GoBench introduces an unsaturated benchmark where LLMs play 9x9 Go against a ladder of KataGo opponents ranging from random to superhuman strength. GPT-6 Astra reaches 2500 Elo while Codex with Astra and coding tools achieves 3560 Elo, showing r=0.83 correlation with ARC-AGI 2. This benchmark provides a novel, unsaturated way to measure general reasoning in LLMs that correlates strongly with ARC-AGI 2, potentially offering better signal on progress toward AGI than saturated tests. The leaderboard remains open for updates until saturation; public code and paper are available at the provided GitHub links. Best KataGo reaches 4400 Elo, highlighting the performance gap.

reddit · r/MachineLearning · /u/Roland31415 · Sep 16, 18:54

<details><summary>References</summary>
<ul>
<li><a href="https://arcprize.org/arc-agi/2">Arc-agi-2</a></li>
<li><a href="https://benchlm.ai/benchmarks/arc-agi-2">ARC-AGI-2 Leaderboard (September 2026): GPT-6 Astra Leads at 95%</a></li>

</ul>
</details>

**Tags**: `#LLM evaluation`, `#benchmarks`, `#reasoning`, `#Go`, `#ARC-AGI`

---

<a id="item-7"></a>
## [TabPFN-3.5 Released as New SOTA Tabular Foundation Model](https://www.reddit.com/r/MachineLearning/comments/1wh4xhy/tabpfn35_is_released_as_the_next_sota_tabular/) ⭐️ 8.0/10

Prior Labs released TabPFN-3.5 today as the new state-of-the-art tabular foundation model, topping both TabArena and BeyondArena benchmarks for datasets up to 1M rows and 20k features. The release advances tabular foundation models with practical variants, potentially improving accuracy and speed for structured data tasks across industries and strengthening benchmarks like TabArena. TabPFN-3.5 leads with +250 Elo over prior baselines on BeyondArena for text-rich and high-dimensional data; variants include 6x faster Fast, compute-for-accuracy Thinking via API, and Plus, with Thinking adding +20 Elo on BeyondArena.

reddit · r/MachineLearning · /u/tuanacelik · Sep 15, 16:18

**Background**: TabPFN is a transformer-based foundation model for tabular data that approximates Bayesian inference with a single forward pass. TabArena and BeyondArena are living benchmarks evaluating models on IID, temporal, and grouped tabular tasks.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2506.16791">[2506.16791] TabArena: A Living Benchmark for Machine Learning on Tabular Data</a></li>
<li><a href="https://arxiv.org/abs/2606.30410">[2606.30410] Beyond IID: How General Are Tabular Foundation Models, Really?</a></li>

</ul>
</details>

**Tags**: `#tabular data`, `#foundation models`, `#machine learning`, `#SOTA`, `#TabPFN`

---

<a id="item-8"></a>
## [Engineering of US Strategic Petroleum Reserve Salt Cavern Storage](https://johnjwang.com/post/2026/09/15/engineering-behind-us-strategic-petroleum-reserve) ⭐️ 7.0/10

The article explains how the US Strategic Petroleum Reserve stores crude oil in naturally sealed salt caverns created through solution mining, relying on salt's low permeability and pressure-induced self-sealing properties. This storage method enables secure, large-scale petroleum reserves without steel or concrete linings, directly supporting national energy security and infrastructure resilience against supply disruptions. Creating each barrel of storage space requires approximately seven barrels of raw water, and the reserve must retain 100-150 million barrels of oil to maintain operational pressure and cannot be drawn down to zero.

hackernews · johnjwang · Sep 15, 22:15 · [Discussion](https://news.ycombinator.com/item?id=49719596)

**Background**: Salt domes form when underground salt layers rise through overlying rock. Solution mining pumps fresh water into these formations to dissolve salt and create precise underground caverns suitable for oil storage.

<details><summary>References</summary>
<ul>
<li><a href="https://www.energy.gov/hgeo/opr/spr-storage-sites">SPR Storage Sites | Department of Energy</a></li>
<li><a href="https://en.wikipedia.org/wiki/Salt_dome">Salt dome - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters highlight salt's ability to seal fractures under pressure, question whether returning original brine could reduce erosion, note the ancient yet robust monitoring systems, and emphasize the operational need to keep substantial oil volumes in place.

**Tags**: `#engineering`, `#energy`, `#infrastructure`, `#petroleum`, `#geology`

---

<a id="item-9"></a>
## [E-ink Frame Detects Birdsong and Renders 1800s Illustrations](https://github.com/arnegiacomo/fugleramme) ⭐️ 7.0/10

A Show HN project called Fugleramme uses the BirdNET neural network to detect birdsong and displays matching 1800s-style illustrations on an e-ink frame. The project blends machine learning audio classification with e-ink displays and artistic rendering, inspiring builders to create magical, low-power devices that connect people with nature. BirdNET is a traditional convolutional neural network, not an LLM, and the frame pairs it with ESP32 or similar boards for long battery life on e-ink.

hackernews · arnemunthekaas · Sep 15, 12:31 · [Discussion](https://news.ycombinator.com/item?id=49711544)

<details><summary>References</summary>
<ul>
<li><a href="https://blog.tensorflow.org/2021/09/TinyML-Audio-for-everyone.html">End-to-end tinyML audio classification with the Raspberry Pi RP2040 — The TensorFlow Blog</a></li>
<li><a href="https://github.com/DeKUT-DSAIL/tinyml_audio_classification">GitHub - DeKUT-DSAIL/tinyml_audio_classification: Use TinyML on Raspberry Pi Pico to identify audio sounds of Hartlaub's turaco · GitHub</a></li>

</ul>
</details>

**Discussion**: Commenters praised the project as magical and highly inspirational for builders, noted BirdNET's traditional neural network architecture, highlighted e-ink's multi-year battery life with ESP32, and connected it to other recent bird-related DIY projects.

**Tags**: `#e-ink`, `#bird-detection`, `#machine-learning`, `#embedded-systems`, `#DIY-project`

---

<a id="item-10"></a>
## [TMLR Tests If Authors Can Explain Their Desk-Rejected Papers](https://www.reddit.com/r/MachineLearning/comments/1wid67h/tmlr_reached_out_to_the_authors_of_10_papers/) ⭐️ 7.0/10

TMLR's editor-in-chief contacted authors of 10 papers slated for desk rejection to assess their understanding. Results showed only one author answered all questions while most struggled with basic or technical details. The findings raise concerns about submission quality and author knowledge gaps in machine learning research, potentially affecting peer review standards and research integrity across academic publishing. Of the ten papers, three authors could not answer basic questions, three handled high-level ideas but faltered on details, one paper contained a major flaw, and others withdrew or missed meetings.

reddit · r/MachineLearning · /u/hihey54 · Sep 16, 23:20

**Tags**: `#machine learning research`, `#peer review`, `#academic publishing`, `#research integrity`, `#TMLR`

---

<a id="item-11"></a>
## [LARA: Low-Rank Residual Adapters for Composable Frozen LLM Behaviors](https://www.reddit.com/r/MachineLearning/comments/1whx9tr/lara_small_composable_behaviours_for_frozen_llms_p/) ⭐️ 7.0/10

LARA introduces low-rank residual adapters added to the residual stream of frozen LLMs, enabling small, independently trainable behaviors that can be loaded, blended, or routed via Mixture of Behaviors (MoBs). A PyTorch library with training code, MoBs demo, and writing style examples is available on GitHub, matching LoRA performance at equal parameter counts. This enables multiple specialized behaviors such as coding, maths, and medical tasks to share one frozen model instead of separate fine-tuned copies, advancing efficient and modular LLM adaptation for practical inference-time steering. LARA uses zero-initialized low-rank projections at selected layers to produce behavior artifacts of only a few MB that support token-by-token soft routing without modifying base model weights.

reddit · r/MachineLearning · /u/kertara · Sep 16, 13:28

**Background**: LoRA adds low-rank updates directly to weight matrices for parameter-efficient fine-tuning of LLMs. The residual stream consists of the additive skip connections within transformer layers where LARA inserts its adapters.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2607.28669">[2607.28669] LARA: Lightweight Adapters in the Residual Stream for Composable Adaptation and Alignment</a></li>
<li><a href="https://github.com/pfekin/LARA">GitHub - pfekin/LARA: Lightweight residual-stream adapters for frozen LLMs: match LoRA at equal parameters, add inference-time steering, and run many behaviors per token on a single model. · GitHub</a></li>

</ul>
</details>

**Tags**: `#LLM adaptation`, `#parameter-efficient fine-tuning`, `#LoRA`, `#composable models`, `#PyTorch`

---

<a id="item-12"></a>
## [44M Parameter Ternary LLM Achieves 1900 tok/s in 19.8 MB](https://www.reddit.com/r/MachineLearning/comments/1wgzpli/i_trained_a_44m_parameter_quantized_llm_from/) ⭐️ 7.0/10

A developer trained a 44M-parameter ternary LLM from scratch on 45B tokens, resulting in a 19.8 MB model that runs at approximately 1,900 tokens per second on CPU. This approach shows extreme compression and efficient inference for small models, enabling offline operation on edge devices and reducing reliance on large floating-point models. The model employs ternary {-1,0,+1} weights, fixed 512-bit vocabulary fingerprints instead of trained embeddings, external circuits for arithmetic and logic, and memory-mapped 1-bit attention states for record retrieval.

reddit · r/MachineLearning · /u/Final-Data-1410 · Sep 15, 12:59

**Background**: Ternary weights restrict parameters to -1, 0, or +1 values to achieve substantial model size reduction, as explored in 1.58-bit LLM research.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/1.58-bit_large_language_model">1.58-bit large language model - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#small language models`, `#model quantization`, `#efficient inference`, `#ternary weights`, `#edge AI`

---

<a id="item-13"></a>
## [4B Model Claims 81% Faster Query Plans Than Postgres](https://rohanbansal.com/qorl) ⭐️ 6.0/10

A 4 billion parameter model was trained to produce query plans claimed to be 81% faster than Postgres on a specific workload. The work explores applying large language models to database query optimization, an area where traditional heuristics dominate but ML approaches could yield gains. Tests used an 8 GB in-memory dataset, limited shared buffers, warmed queries, and read-only SELECTs with only primary key indexes, prompting concerns over overfitting and limited generalizability.

hackernews · polyphilz · Sep 16, 18:50 · [Discussion](https://news.ycombinator.com/item?id=49731285)

**Discussion**: Commenters highlight unrealistic experimental conditions, warn about LLM hallucinations producing invalid plans, and suggest that math-heavy optimization may benefit more from targeted neural heuristics than from general LLMs.

**Tags**: `#machine-learning`, `#database-optimization`, `#query-planning`, `#postgres`, `#llm`

---

<a id="item-14"></a>
## [Blog Post Stresses That Backups Require Reliable Restoration](https://filipovski.net/2026/09/16/backups-arent-simple.html) ⭐️ 6.0/10

A blog post titled "Backups Aren't Simple" explains that backups are complex because they must prioritize verifiable restoration over simple file copying. Hacker News comments share real data loss incidents and practical setups using tools such as Restic. This discussion highlights frequent pitfalls in data protection that affect sysadmins and everyday users who risk permanent loss without tested recovery processes. It connects to broader industry trends emphasizing restoration reliability in modern backup strategies. Comments reference the Veritas philosophy of focusing on restoration rather than backups, personal incidents involving lightning damage and cloud service changes, and implementations of 3-2-1 rules with Restic plus Backrest on CoreOS hosts.

hackernews · afilipovski · Sep 16, 20:27 · [Discussion](https://news.ycombinator.com/item?id=49732513)

<details><summary>References</summary>
<ul>
<li><a href="https://restic.net/">restic · Backups done right!</a></li>

</ul>
</details>

**Discussion**: Participants describe multiple personal data loss events and agree that restoration is the true goal of backups. They recommend Restic for deduplicated and encrypted backups while sharing links to established resources like jwz's backup documentation.

**Tags**: `#backups`, `#data-recovery`, `#sysadmin`, `#restic`, `#data-loss`

---

<a id="item-15"></a>
## [Blog Post on Small Programming and Command-Line Tricks](https://will-keleher.com/posts/small-programming-tricks-matter/) ⭐️ 6.0/10

A blog post sharing small programming and command-line tricks was posted on Hacker News, receiving 427 points and 191 comments focused on productivity habits. The discussion reveals how minor command-line habits can significantly boost developer efficiency and explores AI-assisted methods for discovering new techniques. Commenters highlighted tricks like Ctrl+r with fzf for history search, using the perf command via AI observation, and custom directory navigation scripts integrated with Zoxide.

hackernews · signa11 · Sep 16, 15:56 · [Discussion](https://news.ycombinator.com/item?id=49729000)

**Discussion**: Users agreed that forming habits around shortcuts is challenging and suggested writing them down or observing AI commands; some noted most people use computers inefficiently and shared specific navigation tips.

**Tags**: `#programming tips`, `#command line`, `#productivity`, `#software engineering`, `#hacker news`

---