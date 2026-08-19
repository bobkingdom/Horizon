---
layout: default
title: "Horizon Summary: 2026-08-19 (EN)"
date: 2026-08-19
lang: en
---

> From 23 items, 10 important content pieces were selected

---

1. [Apple Replaces Core Technology Fee with 5% Commission Model in EU](#item-1) ⭐️ 8.0/10
2. [Mojo Compiler and Toolchain Now Open Source Under Apache 2](#item-2) ⭐️ 8.0/10
3. [Qwen 3.8 27B Matches Frontier Models on Intelligence Index](#item-3) ⭐️ 8.0/10
4. [404 Media Tracks Rare Books Shipment to Amazon AI Facility](#item-4) ⭐️ 8.0/10
5. [Rust Port of Google's TurboQuant for Efficient Vector Search](#item-5) ⭐️ 7.0/10
6. [Trains Repurposed as Line Scanners for Slit-Scan Imaging](#item-6) ⭐️ 7.0/10
7. [Recovering a Bricked Framework AMD 7040 Laptop with $20 Tools](#item-7) ⭐️ 7.0/10
8. [RAM Prices Climb 500% in 12 Months](#item-8) ⭐️ 7.0/10
9. [Critique Exposes Flawed Benchmarks in Sparse Attention and KV Compression](#item-9) ⭐️ 7.0/10
10. [Open-source macOS app animates 3D fruit fly with real FlyWire connectome.](#item-10) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Apple Replaces Core Technology Fee with 5% Commission Model in EU](https://www.apple.com/newsroom/2026/08/apple-announces-changes-for-apps-in-the-european-union/) ⭐️ 8.0/10

Apple replaces its Core Technology Fee with a Core Technology Commission charging 5% on digital transactions for apps using alternative distribution in the EU. The update also removes the initial acquisition fee and store services fee while maintaining notarization requirements. This change addresses ongoing regulatory disagreements with the European Commission under the DMA and affects developers distributing apps outside the App Store. It impacts major reader apps and could influence similar policies in other regions. The 5% commission applies only to digital transactions in alternatively distributed apps; reader apps gain new promotion flexibility starting October 1, 2026. Notarization remains mandatory for safety compliance.

hackernews · newusertoday · Aug 18, 16:21 · [Discussion](https://news.ycombinator.com/item?id=49348055)

**Discussion**: Commenters note Apple already charges a developer program fee for R&D reimbursement and question why additional fees were needed. Some welcome the simplification for reader apps while others highlight continued notarization requirements as a limitation.

**Tags**: `#Apple`, `#EU regulations`, `#App Store`, `#DMA`, `#Developer fees`

---

<a id="item-2"></a>
## [Mojo Compiler and Toolchain Now Open Source Under Apache 2](https://simonwillison.net/2026/Aug/18/mojo-is-now-open-source/) ⭐️ 8.0/10

The Mojo programming language compiler and toolchain have been open-sourced under the Apache 2 license after the 1.0 release. The project has moved away from its original goal of becoming a full Python superset. This makes Mojo more accessible to developers in Python and AI ecosystems and could speed adoption for GPU programming. It fulfills a promise made since May 2023. Mojo is now positioned as its own language with Python-inspired syntax optimized for GPU programming rather than full Python compatibility. The roadmap change was noted around August 2025.

rss · Simon Willison · Aug 18, 21:39

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mojo_(programming_language)">Mojo (programming language) - Wikipedia</a></li>
<li><a href="https://mojolang.org/docs/roadmap/">Mojo roadmap | Mojo</a></li>

</ul>
</details>

**Tags**: `#programming-languages`, `#open-source`, `#mojo`, `#python`, `#ai-ml`

---

<a id="item-3"></a>
## [Qwen 3.8 27B Matches Frontier Models on Intelligence Index](https://simonwillison.net/2026/Aug/17/qwen-38-27b-scores-52/) ⭐️ 8.0/10

Qwen 3.8 27B scores 52 on the Artificial Analysis Intelligence Index, matching GPT-5.6 Luna and trailing GLM-5.2 and DeepSeek V4 Pro by one point. This demonstrates that a compact 27B model can reach performance levels of much larger frontier models, highlighting rapid gains in model efficiency within the AI industry. The compared models include a 753B GLM-5.2 and a 1.7T DeepSeek V4 Pro, while Qwen 3.8 27B achieves nearly identical results on the composite index.

rss · Simon Willison · Aug 17, 23:58

**Background**: The Artificial Analysis Intelligence Index is a composite benchmark measuring language model capabilities across reasoning, coding, knowledge, instruction following, and multi-step tasks. It aggregates results from evaluations such as GPQA Diamond, Humanity's Last Exam, and others.

<details><summary>References</summary>
<ul>
<li><a href="https://artificialanalysis.ai/evaluations/artificial-analysis-intelligence-index">Artificial Analysis Intelligence Index | Artificial Analysis</a></li>
<li><a href="https://artificialanalysis.ai/">AI Model & API Providers Analysis | Artificial Analysis</a></li>

</ul>
</details>

**Tags**: `#ai`, `#llms`, `#benchmarks`, `#qwen`, `#model-efficiency`

---

<a id="item-4"></a>
## [404 Media Tracks Rare Books Shipment to Amazon AI Facility](https://simonwillison.net/2026/Aug/17/we-tracked-a-shipment-of-rare-books-it-ended-at-an-amazon-ai-tra/) ⭐️ 8.0/10

404 Media placed an AirTag in a shipment of around 1,000 rare books ordered anonymously on Biblio, tracking it to Amazon's LAS8 facility in Las Vegas. The investigation exposes how companies acquire physical books for AI training data, highlighting opaque sourcing practices by major tech firms. The books reached the VGT3 area of the facility, confirmed by Amazon workers for destructive scanning; the entrance displays a dinosaur-with-book logo.

rss · Simon Willison · Aug 17, 15:21

**Tags**: `#AI training data`, `#data ethics`, `#Amazon`, `#investigative journalism`, `#book scanning`

---

<a id="item-5"></a>
## [Rust Port of Google's TurboQuant for Efficient Vector Search](https://github.com/RyanCodrai/turbovec) ⭐️ 7.0/10

RyanCodrai released Turbovec, a Rust implementation of Google's TurboQuant vector quantization algorithm on GitHub, supporting low-memory vector search for 10 million vectors in 4GB RAM with zero training. This enables faster development of vector indexes and reverse indexes with significantly reduced memory, benefiting vector databases, LLM inference, and nearest neighbor search applications across the machine learning ecosystem. Turbovec applies normalize then fixed random rotation for predictable quantization; community notes include links to ann-benchmarks showing FAISS is not state-of-the-art and the original TurboQuant open review comments.

hackernews · fittingopposite · Aug 18, 18:07 · [Discussion](https://news.ycombinator.com/item?id=49349898)

**Background**: TurboQuant is an online vector quantization algorithm from Google Research that compresses high-dimensional vectors while preserving geometric structure for applications like vector databases and KV cache compression.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/RyanCodrai/turbovec">GitHub - RyanCodrai/ turbovec : A vector index built on TurboQuant...</a></li>
<li><a href="https://research.google/blog/turboquant-redefining-ai-efficiency-with-extreme-compression/">TurboQuant: Redefining AI efficiency with extreme compression</a></li>
<li><a href="https://medevel.com/turbovec/">10M Vectors. 4GB RAM. Zero Training. Meet turbovec</a></li>

</ul>
</details>

**Discussion**: Commenters highlighted memory savings enabling smoother debugging, criticized the README for lacking human appeal, shared benchmark links showing newer methods outperform FAISS, and referenced the TurboQuant paper's open review for deeper insights.

**Tags**: `#rust`, `#vector-search`, `#quantization`, `#ann`, `#machine-learning`

---

<a id="item-6"></a>
## [Trains Repurposed as Line Scanners for Slit-Scan Imaging](https://philo.gay/linecam/) ⭐️ 7.0/10

A technical project captures images by fixing a camera to record a single pixel row as trains move past, turning the railway into a moving flatbed scanner for slit-scan photography. This creative hack demonstrates novel applications of everyday infrastructure for imaging and has sparked high engagement on Hacker News with users sharing similar experiments and tools. The method records one row of pixels over time as the train provides the scanning motion, producing distorted or abstract images depending on subject movement and speed.

hackernews · otherayden · Aug 18, 12:43 · [Discussion](https://news.ycombinator.com/item?id=49344825)

**Background**: Slit-scan photography exposes film or sensors through a narrow slit while the subject or medium moves, creating time-based distortions as described in traditional techniques using large-format cameras or video art.

<details><summary>References</summary>
<ul>
<li><a href="https://luk.staff.ugm.ac.id/fotografi/off/www.rit.edu/andpph/text-slit-scan.html">Slit - Scan Photography with Large Format Cameras</a></li>
<li><a href="https://www.lomography.com/magazine/283280-making-a-slit-scan-camera">Making a Slit Scan Camera · Lomography</a></li>

</ul>
</details>

**Discussion**: Commenters shared past experiments including 2008 train-track setups with iSight cameras, manual frame-splicing animations, and a web-based slit-scan toy for phones; some noted interesting error shots and speed-tracking ideas using mirrors.

**Tags**: `#photography`, `#slit-scanning`, `#hacking`, `#trains`, `#imaging`

---

<a id="item-7"></a>
## [Recovering a Bricked Framework AMD 7040 Laptop with $20 Tools](https://quantum5.ca/2026/08/16/fixing-bricked-amd-7040-series-framework-13-laptop-with-20-tools/) ⭐️ 7.0/10

A user detailed the recovery of a bricked Framework Laptop 13 with AMD 7040 series after a faulty BIOS update, employing pogo pins and low-cost hardware tools to reflash the firmware. This case underscores ongoing risks of firmware updates bricking repairable laptops and raises questions about manufacturer responsibility for faulty software and support for out-of-warranty recovery. Framework did not provide a flashing header on the board, requiring pogo pins; the author also notes missing official documentation for raw BIOS images and serial number restoration.

hackernews · jp_sc · Aug 18, 13:18 · [Discussion](https://news.ycombinator.com/item?id=49345220)

**Background**: Framework Laptop is a modular device promoted for right-to-repair with easily replaceable parts, and the AMD 7040 series uses firmware that can become corrupted during updates leading to unbootable states.

<details><summary>References</summary>
<ul>
<li><a href="https://quantum5.ca/2026/08/16/fixing-bricked-amd-7040-series-framework-13-laptop-with-20-tools/">Fixing a bricked AMD 7040 series Framework 13” laptop with $20 tools | Quantum</a></li>
<li><a href="https://community.frame.work/t/bricked-my-new-amd-7040-with-the-wrong-bios-update/77095">Bricked my new AMD 7040 with the wrong BIOS update - Framework Laptop 13 - Framework Community</a></li>
<li><a href="https://en.wikipedia.org/wiki/Framework_Laptop">Framework Laptop</a></li>

</ul>
</details>

**Discussion**: Commenters discussed legal liability for faulty BIOS updates, shared similar bricking experiences with other brands, and criticized Framework for not providing easier recovery options or extending warranties after official updates.

**Tags**: `#framework-laptop`, `#hardware-repair`, `#firmware`, `#bios-update`, `#right-to-repair`

---

<a id="item-8"></a>
## [RAM Prices Climb 500% in 12 Months](https://www.tomshardware.com/pc-components/ram/memory-prices-climb-500-percent-in-12-months-up-to-10x-the-lowest-ever-tracked-prices-128gb-of-ddr5-now-usd3-399) ⭐️ 7.0/10

RAM prices have surged 500% in 12 months, with 128GB of DDR5 now costing up to $3,399. Rising costs may push software developers toward better memory optimization as users face higher expenses. Prices have reached up to 10 times the lowest ever tracked levels, impacting users who need large amounts of RAM or storage.

hackernews · haunter · Aug 17, 17:52 · [Discussion](https://news.ycombinator.com/item?id=49334960)

**Discussion**: Commenters suggest high prices could drive software memory efficiency improvements similar to past resource crises, while raising concerns about hardware shortages forcing longer use of existing machines and a potential shift away from personal computing ownership.

**Tags**: `#RAM`, `#hardware-pricing`, `#memory-optimization`, `#semiconductors`, `#software-engineering`

---

<a id="item-9"></a>
## [Critique Exposes Flawed Benchmarks in Sparse Attention and KV Compression](https://www.reddit.com/r/MachineLearning/comments/1vqqqcs/how_to_make_any_sparse_attention_kv_compression/) ⭐️ 7.0/10

A detailed X post by researcher p_nawrot outlines common tactics used in papers on sparse attention and KV cache compression to inflate results, such as testing on single-needle retrieval without distractors, reusing old contaminated benchmarks, and not isolating contributions from sliding window attention or block size changes. These evaluation pitfalls undermine trust in efficiency claims for long-context LLMs, potentially leading researchers and practitioners to adopt methods that fail on realistic, diverse tasks and slowing genuine progress in model optimization. The post highlights issues with aggregated metrics on benchmarks like RULER, tuning only the proposed method while keeping baselines fixed, and using prompts that favor compression without sharing them; it notes most tasks pass under simple sliding window attention.

reddit · r/MachineLearning · /u/korec1234 · Aug 17, 12:18

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/pdf/2608.14191">KV Cache Compression Through the Lens of Transform Coding</a></li>

</ul>
</details>

**Tags**: `#sparse attention`, `#KV cache compression`, `#benchmark evaluation`, `#LLM efficiency`, `#research practices`

---

<a id="item-10"></a>
## [Open-source macOS app animates 3D fruit fly with real FlyWire connectome.](https://github.com/DenisSergeevitch/desktop-fly) ⭐️ 6.0/10

The GitHub project desktop-fly releases an open-source macOS application that renders a 3D fruit fly whose movements are driven by the published FlyWire whole-brain connectome of Drosophila melanogaster. The release demonstrates a transparent, non-commercial way to visualize connectome data on everyday hardware and invites broader public scrutiny of how neural wiring diagrams can be turned into behavior. The implementation maps scripted behaviors to connectome-triggered signals rather than running a full biophysical simulation; the project remains fully open source for inspection of these mappings.

hackernews · phoenix120 · Aug 18, 21:50 · [Discussion](https://news.ycombinator.com/item?id=49353221)

**Background**: FlyWire is a large consortium that produced the first complete synaptic-resolution connectome of an adult fruit fly brain by combining electron microscopy with community proofreading across 127 institutions.

<details><summary>References</summary>
<ul>
<li><a href="https://flywire.ai/">FlyWire</a></li>
<li><a href="https://www.nature.com/immersive/d42859-024-00053-4/index.html?error=cookies_not_supported&code=e9e9079a-e534-4fe6-b1ec-de4497de446d">The FlyWire connectome : neuronal wiring diagram of a complete fly...</a></li>

</ul>
</details>

**Discussion**: Commenters welcomed the open-source transparency compared with commercial claims, questioned whether the fly is truly controlled by the connectome or merely scripted, and raised concerns about modeling accuracy and ethical presentation.

**Tags**: `#neuroscience`, `#connectome`, `#macOS`, `#simulation`, `#open-source`

---