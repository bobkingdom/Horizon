---
layout: default
title: "Horizon Summary: 2026-10-05 (EN)"
date: 2026-10-05
lang: en
---

> From 33 items, 12 important content pieces were selected

---

1. [ARC-AGI-3 Kaggle Scores Surge from 7% to 56% in 30 Days](#item-1) ⭐️ 8.0/10
2. [NeurIPS Paper Presents Minimal DynaBase for Zero-Shot Dynamical Systems Reconstruction](#item-2) ⭐️ 8.0/10
3. [Strata Runs 125B Qwen Model at 100+ Tokens/s on RTX 4090](#item-3) ⭐️ 7.0/10
4. [Simon Willison Urges Default Hard Budget Caps for Usage APIs](#item-4) ⭐️ 7.0/10
5. [Distilling Stockfish Value Function on 1B Positions with 3.9B Dataset Released](#item-5) ⭐️ 7.0/10
6. [ASRN: Copy Layer Uses Learned Hash Tables for Linear-Memory Language Models](#item-6) ⭐️ 7.0/10
7. [Nonobench: Open Benchmark Tests 49 LLMs on Nonogram Puzzles](#item-7) ⭐️ 7.0/10
8. [Reddit Post Praises Free 'Principles of Diffusion Models' Monograph](#item-8) ⭐️ 7.0/10
9. [F1 Drivers Frustrated by Bahrain Software Glitch Causing Power Loss](#item-9) ⭐️ 6.0/10
10. [GitHub Script Disables Apple Intelligence on macOS 27 to Free Disk Space](#item-10) ⭐️ 6.0/10
11. [Improper Redaction Exposes Google Data Center Water and Electricity Use](#item-11) ⭐️ 6.0/10
12. [Mirror Suit Robot Costume Dataset Released for CV Benchmarking](#item-12) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [ARC-AGI-3 Kaggle Scores Surge from 7% to 56% in 30 Days](https://www.reddit.com/r/MachineLearning/comments/1wxcd4k/top_arc%CE%B1gi3_scores_on_kaggle_just_went_from_7_to/) ⭐️ 8.0/10

Top scores on the ARC-AGI-3 Kaggle competition rose from 7% to 56% over the past 30 days. Small local models in constrained harnesses now exceed average human performance on the benchmark. The rapid gains on this benchmark, intentionally designed to highlight human superiority in novel tasks, signal accelerating progress in AI reasoning capabilities. This affects researchers tracking AGI development and the broader machine learning community focused on efficient learning. The Kaggle competition restricts participants to small local models only. The leaderboard update reflects performance on an interactive reasoning task involving exploration and adaptation without prior instructions.

reddit · r/MachineLearning · /u/we_are_mammals · Oct 4, 10:24 · [Discussion](https://www.reddit.com/r/MachineLearning/comments/1wxcd4k/top_arcαgi3_scores_on_kaggle_just_went_from_7_to/)

**Background**: ARC-AGI-3 is an interactive reasoning benchmark which challenges AI agents to explore novel environments, acquire goals on the fly, build adaptable world models, and learn continuously.

<details><summary>References</summary>
<ul>
<li><a href="https://arcprize.org/arc-agi/3">ARC - AGI - 3</a></li>

</ul>
</details>

**Tags**: `#ARC-AGI`, `#AI benchmarks`, `#Machine Learning`, `#Kaggle`, `#AGI progress`

---

<a id="item-2"></a>
## [NeurIPS Paper Presents Minimal DynaBase for Zero-Shot Dynamical Systems Reconstruction](https://www.reddit.com/r/MachineLearning/comments/1wxex8n/a_minimal_interpretable_architecture_for_zeroshot/) ⭐️ 8.0/10

The NeurIPS 2026 paper introduces DynaBase, a two-component architecture using a single-parameter affine map controlled by α and a context selector for zero-shot reconstruction of dynamical systems. DynaBase outperforms major time series and dynamical systems foundation models in long-term statistics and short-term predictions while preserving correct dynamical regimes, offering a cheap and interpretable alternative. The architecture uses α < 1 for fixed points, α = 1 for limit cycles, and α > 1 for chaotic attractors; training occurs via one-step linear regression or 1-parameter grid search.

reddit · r/MachineLearning · /u/DangerousFunny1371 · Oct 4, 12:49

**Background**: Dynamical systems reconstruction aims to learn generative models from time series that capture topological and geometrical properties of the underlying system. Zero-shot approaches apply pretrained models without task-specific fine-tuning.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/html/2607.14937">A Minimal Interpretable Architecture for Zero - Shot Reconstruction of...</a></li>

</ul>
</details>

**Tags**: `#dynamical systems`, `#zero-shot learning`, `#interpretable ML`, `#NeurIPS`, `#foundation models`

---

<a id="item-3"></a>
## [Strata Runs 125B Qwen Model at 100+ Tokens/s on RTX 4090](https://github.com/Niko1221/Strata) ⭐️ 7.0/10

The GitHub project Strata claims to deliver over 100 tokens per second inference for the 125B Qwen 3.8 Flash Next model on RTX 4090-class hardware through aggressive quantization. This approach could make very large language models runnable on consumer GPUs, lowering barriers for local inference and advancing decentralized AI deployment. User reports confirm speeds up to 124 tokens/s on RTX 4090, yet benchmarks show notably higher error rates than llama.cpp on vision tasks, with concerns over quality loss below 4-bit quantization.

hackernews · snehesht · Oct 4, 12:51 · [Discussion](https://news.ycombinator.com/item?id=49953495)

**Background**: Quantization lowers the numerical precision of model weights to reduce memory footprint and boost inference speed on hardware with limited VRAM such as the RTX 4090.

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/Qwen/Qwen3.8-Flash-Next">Qwen / Qwen 3 . 8 - Flash - Next · Hugging Face</a></li>
<li><a href="https://github.com/qwenlm/qwen3.8-flash-next">GitHub - QwenLM/ Qwen 3 . 8 - Flash - Next : Qwen 3 . 8 - Flash - Next is the...</a></li>

</ul>
</details>

**Discussion**: Users report achieving 124 tokens/s on RTX 4090 and 60 tokens/s on R9700, but others highlight significant quality degradation versus llama.cpp and skepticism toward sub-4-bit quants for complex tasks.

**Tags**: `#LLM inference`, `#quantization`, `#consumer hardware`, `#Qwen`, `#performance optimization`

---

<a id="item-4"></a>
## [Simon Willison Urges Default Hard Budget Caps for Usage APIs](https://simonwillison.net/2026/Oct/3/default-hard-budget-caps/) ⭐️ 7.0/10

On October 3, 2026, Simon Willison published a blog post calling for default hard budget caps on pay-by-usage services that cut off access after a set monthly limit and return errors instead of allowing overages. AI coding agents and personal agents lower the barrier to running code that consumes paid APIs, raising the risk of runaway costs while users are unaware, so hard caps protect individuals and businesses from surprise bills. Willison notes AWS launched monthly spend limits in September 2026 that pause projects when reached, while Google Cloud introduced Spend Caps in July; he argues these should be default with opt-in removal rather than warnings.

rss · Simon Willison · Oct 3, 23:34

**Tags**: `#AI agents`, `#cost management`, `#usage-based pricing`, `#cloud APIs`, `#LLM safety`

---

<a id="item-5"></a>
## [Distilling Stockfish Value Function on 1B Positions with 3.9B Dataset Released](https://www.reddit.com/r/MachineLearning/comments/1wxz5qq/distilling_stockfish_on_a_billion_positions_full/) ⭐️ 7.0/10

A project distilled the Stockfish value function into ResNet and ViT models using 1 billion positions from the new Gigafish dataset. The full 3.9 billion position dataset, derived from 37 months of Lichess games, is now available on Hugging Face. This work explores faster neural approximations of depth-limited Stockfish search, potentially creating compact models competitive with NNUE for chess engines. It contributes large-scale open data and hybrid architecture insights to ML applications in game AI. Hybrid ResNet/ViT models achieved the best results, while pure ViTs learned board representations slowly and CNNs benefited from geometric inductive biases early in training. Depth was held constant during distillation to focus on value function approximation.

reddit · r/MachineLearning · /u/microscope1024 · Oct 5, 04:11

**Background**: Stockfish is a leading chess engine that incorporates NNUE, a small efficiently updatable neural network for position evaluation. Model distillation trains a neural network to mimic the outputs of a larger system or search process like Stockfish's value function.

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/datasets/lukesalamone/gigafish-3.8b-d10">lukesalamone/ gigafish -3.8b-d10 · Datasets at Hugging Face</a></li>
<li><a href="https://blog.lukesalamone.com/posts/distilling-stockfish/">Distilling Stockfish with One Billion Positions :: Luke Salamone's Blog</a></li>

</ul>
</details>

**Tags**: `#machine learning`, `#chess AI`, `#model distillation`, `#datasets`, `#neural networks`

---

<a id="item-6"></a>
## [ASRN: Copy Layer Uses Learned Hash Tables for Linear-Memory Language Models](https://www.reddit.com/r/MachineLearning/comments/1wxs8qq/asrn_adaptive_sparse_recurrence_network_n/) ⭐️ 7.0/10

ASRN presents a copy layer for language models that employs learned hash tables to locate prior context matches and copy subsequent tokens, achieving linear memory usage relative to sequence length. The approach offers a novel method for efficient long-context handling in language models through hash-based copying, potentially impacting recurrent network architectures and memory-efficient inference. The design relies on learned hash tables for context matching within a single Reddit-posted proposal that currently lacks extensive empirical validation or comparisons to existing methods.

reddit · r/MachineLearning · /u/Mean-Disaster8380 · Oct 4, 22:17

**Tags**: `#machine learning`, `#language models`, `#efficient architectures`, `#recurrent networks`, `#hash tables`

---

<a id="item-7"></a>
## [Nonobench: Open Benchmark Tests 49 LLMs on Nonogram Puzzles](https://www.reddit.com/r/MachineLearning/comments/1wxa2bs/nonobench_an_open_benchmark_of_49_llms_on/) ⭐️ 7.0/10

Nonobench is a public benchmark that evaluates 49 LLMs on nonogram puzzles in standard mode with 30 puzzles from 5x5 to 15x15 grids and hard mode with ten 20x20 puzzles. The benchmark reveals sharp performance drops as grid size increases, providing a new open tool for assessing LLM reasoning capabilities across the AI industry. GPT-6 Astra solved all standard puzzles while Claude Opus 5.5 solved 8 of 10 hard puzzles; results use single attempts with 95% confidence intervals and output via OpenRouter or lab endpoints.

reddit · r/MachineLearning · /u/mauricekleine · Oct 4, 07:57

**Background**: Nonograms are logic puzzles also known as picross where solvers fill a grid using numerical clues for each row and column to reveal a picture.

<details><summary>References</summary>
<ul>
<li><a href="https://www.nonobench.com/">NonoBench – LLM Nonogram Puzzle Solving Benchmark</a></li>

</ul>
</details>

**Tags**: `#LLM benchmarks`, `#reasoning evaluation`, `#nonograms`, `#AI benchmarks`, `#open source`

---

<a id="item-8"></a>
## [Reddit Post Praises Free 'Principles of Diffusion Models' Monograph](https://www.reddit.com/r/MachineLearning/comments/1wwtpg6/the_principles_of_diffusion_models_by_lai_et_al/) ⭐️ 7.0/10

A Reddit user shared their review of the freely available monograph 'The Principles of Diffusion Models' by Chieh-Hsin Lai and Yang Song, highlighting its balance of mathematical rigor and intuition with dedicated appendices for deeper study. The monograph provides an accessible yet rigorous resource on diffusion models, a core technology in generative AI, targeted at researchers, graduate students, and practitioners with basic deep learning knowledge. The text is freely available on the official website, assumes basic deep learning knowledge, and benefits from prior familiarity with information theory, probability theory, and DDPMs; appendices support further mathematical exploration.

reddit · r/MachineLearning · /u/DenoisedNeuron · Oct 3, 18:04

<details><summary>References</summary>
<ul>
<li><a href="https://es.z-library.ec/book/Py6aqoqD96/the-principles-of-diffusion-models.html?dsource=recommend">The Principles of Diffusion Models | Chieh-Hsin Lai & Yang Song...</a></li>
<li><a href="https://magic-with-latents.github.io/latent/ddpms-series.html">DDPMs from scratch – The Latent: Code the Maths</a></li>

</ul>
</details>

**Tags**: `#diffusion models`, `#generative AI`, `#machine learning`, `#monograph`, `#educational resource`

---

<a id="item-9"></a>
## [F1 Drivers Frustrated by Bahrain Software Glitch Causing Power Loss](https://www.motorsport.com/f1/news/horrible-totally-unacceptable-powerless-f1-drivers-frustrated-by-bahrain-f1-software-glitch/10861968/) ⭐️ 6.0/10

F1 drivers were left powerless during the Bahrain race due to a software glitch, with the incident highlighting rapid firmware updates in safety-critical systems. This event raises questions about the reliability of embedded control systems in high-stakes racing environments and the processes for deploying fixes under time pressure. Community discussions note the unusual speed of coding and deploying a critical firmware patch in the field, contrasting it with typical extensive lab QA requirements for industrial or consumer products.

hackernews · llm_nerd · Oct 5, 01:54 · [Discussion](https://news.ycombinator.com/item?id=49959869)

**Discussion**: Commenters expressed surprise at the rapid in-field firmware update for a critical component and questioned whether such patches require extensive prior QA or root cause analysis. Some noted similarities to earlier season reliability issues while others asked about firmware sharing across cars or local track servers.

**Tags**: `#F1 racing`, `#software glitch`, `#firmware deployment`, `#embedded systems`, `#safety-critical software`

---

<a id="item-10"></a>
## [GitHub Script Disables Apple Intelligence on macOS 27 to Free Disk Space](https://github.com/omlahore/RemoveMacAI) ⭐️ 6.0/10

A GitHub repository named RemoveMacAI provides a script that disables Apple Intelligence features on macOS 27 and reclaims the associated disk space. The tool highlights increasing user demand for control over mandatory AI integrations in operating systems, affecting macOS users concerned about storage and unwanted features. The project gained traction on Hacker News with 444 upvotes and 280 comments, focusing on OS bloat and Apple strategy rather than providing extensive technical specifications.

hackernews · privacyisntdead · Oct 4, 19:42 · [Discussion](https://news.ycombinator.com/item?id=49957116)

**Discussion**: Users compared the need for third-party scripts to Windows de-crufting tools and questioned Apple's product strategy on AI toggles, while some defended the value of local models and blamed small SSD sizes instead.

**Tags**: `#macOS`, `#Apple Intelligence`, `#system optimization`, `#AI features`, `#bloatware removal`

---

<a id="item-11"></a>
## [Improper Redaction Exposes Google Data Center Water and Electricity Use](https://www.1011now.com/2026/09/30/more-questions-than-answers-about-lincolns-google-data-center-water-electricity-usage/) ⭐️ 6.0/10

Improper redaction in public documents revealed that a Google data center in Lincoln used 13 million gallons of water along with detailed electricity consumption figures. The disclosure has prompted local debate over the facility's environmental footprint and operational efficiency. The incident underscores growing scrutiny of data center resource consumption as AI infrastructure expands, directly affecting nearby communities concerned about water and energy demands. It also illustrates how transparency failures can amplify public questions about sustainability. The exposed figures show 13 million gallons of water usage, described as modest compared with another center exceeding 500 million gallons; commenters also flagged potential groundwater pollution risks beyond consumption alone.

hackernews · sensanaty · Oct 4, 19:37 · [Discussion](https://news.ycombinator.com/item?id=49957068)

**Discussion**: Commenters observed that 13 million gallons represents a relatively small volume and praised efforts to contextualize the numbers, while others noted larger facilities and raised groundwater pollution concerns. Some argued that debates should target AI and data centers directly rather than abstracted resource metrics, and shared anecdotes about local perceptions of efficiency measures.

**Tags**: `#data-centers`, `#google`, `#water-usage`, `#environmental-impact`, `#ai-infrastructure`

---

<a id="item-12"></a>
## [Mirror Suit Robot Costume Dataset Released for CV Benchmarking](https://www.reddit.com/r/MachineLearning/comments/1wx7jg6/here_are_some_pictures_of_a_robot_costume_wearing/) ⭐️ 6.0/10

A 425-image dataset featuring a custom faceted mirror suit on a robot costume was released, captured in high-contrast outdoor settings as RAW and JPEG files with SHA-256 manifests. The dataset targets extreme specular reflections, a known challenge that causes failures in bounding boxes, segmentation, and depth estimation for computer vision and spatial AI systems. It includes 100% uncompressed Camera-Master RAWs, high-resolution JPEGs, and forensic SHA-256 manifests, specifically designed to trigger model dropouts in depth cameras and CV algorithms.

reddit · r/MachineLearning · /u/5500kelvin · Oct 4, 05:21

**Tags**: `#computer-vision`, `#datasets`, `#machine-learning`, `#depth-estimation`, `#specular-reflections`

---