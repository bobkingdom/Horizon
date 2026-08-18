---
layout: default
title: "Horizon Summary: 2026-08-18 (EN)"
date: 2026-08-18
lang: en
---

> From 32 items, 17 important content pieces were selected

---

1. [DuckDB v2.0 Preview Announces Major Features for Analytics](#item-1) ⭐️ 9.0/10
2. [Qwen 3.8 27B Scores 52 on Artificial Analysis Intelligence Index](#item-2) ⭐️ 8.0/10
3. [Qwen 3.8 27B Excels but Defaults to Overthinking](#item-3) ⭐️ 8.0/10
4. [Rust Adds Native Portable Safe GPU Offload via LLVM](#item-4) ⭐️ 7.0/10
5. [GitHub Outage Sparks Debate on AI Code Scaling Challenges](#item-5) ⭐️ 7.0/10
6. [Copilot Autofix Introduced Template Injection in Snowflake Jira Workflow](#item-6) ⭐️ 7.0/10
7. [OpenAI GPT 5.6 Sol Claimed as Best Vision Model Yet](#item-7) ⭐️ 7.0/10
8. [Blog Post and HN Debate Oppose AI-Generated Writing](#item-8) ⭐️ 7.0/10
9. [Guide to Disabling Intrusive AI Features in Software](#item-9) ⭐️ 7.0/10
10. [404 Media Tracks Rare Books to Amazon AI Training Facility](#item-10) ⭐️ 7.0/10
11. [Critique Exposes Weak Benchmarks in Sparse Attention Papers](#item-11) ⭐️ 7.0/10
12. [SSOG-Attention Offers Sum of Separable Gaussians as Sub-Quadratic SDPA Alternative](#item-12) ⭐️ 7.0/10
13. [Reddit Critique Questions ECA Paper's Core Channel Interaction Hypothesis](#item-13) ⭐️ 7.0/10
14. [Quake Shareware CD-ROM Cracked Due to Extra Full-Version Files](#item-14) ⭐️ 6.0/10
15. [Sun Clock Web App Visualizes Solar Events Using Suncalc](#item-15) ⭐️ 6.0/10
16. [SineKAN: KAN Variant Uses Sinusoidal Activations Instead of B-Splines](#item-16) ⭐️ 6.0/10
17. [Linear Attention Fails Long-Range Recall on Million-Token DNA Sequences](#item-17) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [DuckDB v2.0 Preview Announces Major Features for Analytics](https://duckdb.org/2026/08/17/duckdb-20-highlights) ⭐️ 9.0/10

A preview of DuckDB v2.0 has been released announcing major new features for analytical and hybrid workloads. This development could allow users to manage both OLTP and OLAP workloads in one database, affecting data engineers and analysts seeking simplified architectures. The preview highlights OLTP-like transactional processing speeds while noting the absence of full guarantees such as SERIALIZABLE optimistic concurrency.

hackernews · ibotty · Aug 17, 13:46 · [Discussion](https://news.ycombinator.com/item?id=49330781)

**Background**: DuckDB is an open-source column-oriented RDBMS designed for high performance on complex queries against large databases in embedded configurations.

<details><summary>References</summary>
<ul>
<li><a href="https://duckdb.org/">DuckDB – An in-process SQL OLAP database management system</a></li>
<li><a href="https://en.wikipedia.org/wiki/DuckDB">DuckDB - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Users express excitement about unified transactional and analytical use cases, real-world deployments on lower-end hardware, and realtime analytics pipelines, while raising concerns about the high commit volume possibly linked to AI assistance.

**Tags**: `#DuckDB`, `#database`, `#OLAP`, `#version-release`, `#analytics`

---

<a id="item-2"></a>
## [Qwen 3.8 27B Scores 52 on Artificial Analysis Intelligence Index](https://simonwillison.net/2026/Aug/17/qwen-38-27b-scores-52/) ⭐️ 8.0/10

Qwen 3.8 27B achieves a score of 52 on the Artificial Analysis Intelligence Index, matching GPT-5.6 Luna and trailing GLM-5.2 and DeepSeek V4 Pro 0813 by only one point. This result highlights how a compact 27B model can reach performance levels of much larger models, signaling major progress in LLM efficiency and accessibility. The GLM-5.2 model has 753B parameters while DeepSeek V4 Pro 0813 has 1.6B parameters; Qwen 3.8 27B is noted as open weights and highly verbose in evaluations.

rss · Simon Willison · Aug 17, 23:58

**Background**: The Artificial Analysis Intelligence Index is a synthesized metric that evaluates AI models across multiple benchmarks including agentic capabilities, long-context reasoning, and domain-specific tasks such as GPQA Diamond and SciCode.

<details><summary>References</summary>
<ul>
<li><a href="https://artificialanalysis.ai/models/qwen3-8-27b">Qwen 3 . 8 27 B - Intelligence, Performance & Price Analysis</a></li>
<li><a href="https://artificialanalysis.ai/">AI Model & API Providers Analysis | Artificial Analysis</a></li>

</ul>
</details>

**Tags**: `#ai`, `#llms`, `#generative-ai`, `#qwen`, `#model-performance`

---

<a id="item-3"></a>
## [Qwen 3.8 27B Excels but Defaults to Overthinking](https://simonwillison.net/2026/Aug/16/qwen-38-27b/) ⭐️ 8.0/10

Alibaba released the Apache 2 licensed Qwen3.8-27B, a 27B parameter vision-capable LLM that shows benchmark gains over both Qwen 3.6 27B and the closed Qwen 3.7-Plus. Simon Willison tested the model and noted its default xhigh reasoning effort setting leads to excessive token consumption and long runtimes. The 27B size suits local laptop inference while delivering competitive performance, making strong open-weight vision models more accessible for developers and researchers. Its overthinking default highlights trade-offs in reasoning controls that affect usability on consumer hardware. The model supports reasoning_effort levels including xhigh (default), medium, and low; one SVG generation task consumed 22,276 reasoning tokens and took 21 minutes. LM Studio's 17GB Q4_K_M quantized version was tested on M5 Max MacBook Pro and NVIDIA DGX Spark.

rss · Simon Willison · Aug 16, 22:00

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/Qwen/Qwen3.8-27B">Qwen/Qwen3.8-27B · Hugging Face</a></li>

</ul>
</details>

**Tags**: `#LLMs`, `#Qwen`, `#open-source AI`, `#vision-language models`, `#model benchmarks`

---

<a id="item-4"></a>
## [Rust Adds Native Portable Safe GPU Offload via LLVM](https://arxiv.org/abs/2608.13759) ⭐️ 7.0/10

An arXiv paper presents a zero-overhead GPU offload framework built directly into rustc and LLVM backends that enables automatic, efficient data movement between CPU and multi-vendor GPUs. The module leverages Rust's ownership and noalias guarantees and plans to add advanced interfaces later. This development allows Rust developers to run safe, portable GPU code without external bindings or vendor lock-in, potentially simplifying high-performance computing and LLM inference workloads. It aligns with broader trends toward native heterogeneous computing support in systems languages. The framework uses LLVM's Offload infrastructure for data transfer optimization and targets multi-vendor GPUs while remaining zero-overhead. No public code repository is mentioned in the abstract, and discussion notes it is still under active development.

hackernews · linggen · Aug 17, 17:54 · [Discussion](https://news.ycombinator.com/item?id=49334991)

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2608.13759">[2608.13759] GPU Offload in Rust: Portable, Safe, and Fast</a></li>
<li><a href="https://news.ycombinator.com/item?id=49334991">GPU Offload in Rust: Portable, Safe, and Fast | Hacker News</a></li>

</ul>
</details>

**Discussion**: Commenters appreciate the effort and see value for avoiding bindings in LLM engines, but question the LLVM route versus direct PTX/HIP or Vulkan+SPIR-V approaches. Some note the lack of published code and wonder if it targets HPC workloads or self-contained host binaries.

**Tags**: `#Rust`, `#GPU`, `#Systems Programming`, `#LLVM`, `#Parallel Computing`

---

<a id="item-5"></a>
## [GitHub Outage Sparks Debate on AI Code Scaling Challenges](https://www.githubstatus.com/incidents/zkxwbgr0cnmx) ⭐️ 7.0/10

GitHub users encountered the error message 'No server is currently available to service your request' during an outage that was initially unlisted on the status page but later documented at https://www.githubstatus.com/incidents/zkxwbgr0cnmx. The incident highlights GitHub's scaling difficulties amid surging traffic from LLM-generated code, potentially affecting developer productivity and trust in the platform's reliability. The outage lasted nearly three hours with persistent root cause investigation delays and prevented viewing of diffs in the web interface; commenters noted traffic growth by over an order of magnitude from AI code.

hackernews · SpyCoder77 · Aug 17, 13:35 · [Discussion](https://news.ycombinator.com/item?id=49330597)

**Discussion**: Commenters voiced frustration over the prolonged outage and eroding goodwill toward GitHub, with many attributing issues to unchecked LLM code volume and urging rate limits or higher pricing for non-paying users. Several users expressed interest in switching to more reliable, affordable alternatives supporting PRs, issues, CI, and static hosting.

**Tags**: `#github`, `#outage`, `#scaling`, `#llm`, `#developer-tools`

---

<a id="item-6"></a>
## [Copilot Autofix Introduced Template Injection in Snowflake Jira Workflow](https://www.wiz.io/blog/red-agent-snowflake-copilot-cicd-bug) ⭐️ 7.0/10

An AI-generated GitHub Actions workflow created via Copilot Autofix introduced a template injection flaw that allowed compromise of Snowflake's Jira instance. This case demonstrates real-world security risks of AI-generated CI/CD code, potentially affecting any organization using Copilot for workflow automation without additional safeguards. The flaw appeared in a file such as jira_issue.yml where unsanitized input enabled code injection via template expansion, and was flagged by the static analysis tool zizmor.

hackernews · galnagli · Aug 17, 14:18 · [Discussion](https://news.ycombinator.com/item?id=49331423)

**Background**: Template injection occurs when untrusted input is embedded directly into templates that are executed, allowing attackers to run arbitrary code. GitHub Actions workflows process inputs in run steps that can become vulnerable without proper escaping.

<details><summary>References</summary>
<ul>
<li><a href="https://portswigger.net/web-security/server-side-template-injection">Server-side template injection | Web Security Academy</a></li>
<li><a href="https://docs.github.com/en/code-security/concepts/code-scanning/autofix-for-code-scanning">About autofix for code scanning - GitHub Docs</a></li>

</ul>
</details>

**Discussion**: Users recommended running static analysis tools like zizmor in CI pipelines, noted YAML's inherent footguns, and debated the precise role of Copilot in the vulnerable pull request.

**Tags**: `#AI security`, `#GitHub Actions`, `#vulnerability`, `#Copilot`, `#CI/CD`

---

<a id="item-7"></a>
## [OpenAI GPT 5.6 Sol Claimed as Best Vision Model Yet](https://blog.roboflow.com/openai-gpt-5-6/) ⭐️ 7.0/10

A Roboflow blog post claims that OpenAI's GPT 5.6 Sol is the company's best vision model released to date. The release highlights rapid progress in multimodal AI vision capabilities and intensifies competition with models like Gemini 3.5 Flash for practical developer use cases. Community benchmarks indicate Gemini 3.5 Flash outperformed GPT 5.6 Sol on all tests except OCR while costing one-third as much.

hackernews · plurby · Aug 17, 12:09 · [Discussion](https://news.ycombinator.com/item?id=49329575)

**Discussion**: Commenters emphasize that Gemini 3.5 Flash surpassed GPT 5.6 Sol across nearly all benchmarks at lower cost, with additional notes on latency issues for robotics and occasional EXIF orientation errors in outputs.

**Tags**: `#AI/ML`, `#Vision Models`, `#OpenAI`, `#Benchmarks`, `#GPT`

---

<a id="item-8"></a>
## [Blog Post and HN Debate Oppose AI-Generated Writing](https://www.rickmanelius.com/p/aidr-ai-didnt-read) ⭐️ 7.0/10

A blog post titled AI;DR argues against posting AI-generated responses in personal or professional writing due to lack of authenticity and value. The piece prompted a Hacker News discussion with 568 upvotes and 359 comments in 2026. The discussion highlights growing resistance to AI content in communication, potentially affecting how professionals and individuals share ideas online and in workplaces. Commenters cite problems such as perceived intellectual laziness, excessive verbosity, jargon, over-confidence, and reduced nuance in AI outputs, with one suggesting to share only the original prompt.

hackernews · mooreds · Aug 17, 19:47 · [Discussion](https://news.ycombinator.com/item?id=49336573)

**Discussion**: Overall sentiment is negative, with users finding AI responses offensive and less valuable than human writing. Participants emphasize preference for authentic human voices and criticize readability issues in AI-assisted code and documentation.

**Tags**: `#AI-generated content`, `#Hacker News`, `#content quality`, `#AI ethics`, `#online communication`

---

<a id="item-9"></a>
## [Guide to Disabling Intrusive AI Features in Software](https://www.librarian.net/notoai/) ⭐️ 7.0/10

A practical guide was published on disabling or avoiding AI features in everyday software and services. HN users share workarounds including OS switches and specific tool recommendations. It highlights growing user pushback against forced AI integrations that raise privacy issues and operational costs. This affects everyday users seeking greater control over their devices and workflows. Recommendations include switching to Linux, using LibreWolf or Waterfox browsers, LibreOffice, and older iPhones to avoid AI. CarPlay requiring Siri without fallbacks is noted as a limitation.

hackernews · ColinWright · Aug 17, 14:07 · [Discussion](https://news.ycombinator.com/item?id=49331220)

**Discussion**: Users express frustration with forced AI like Siri in CarPlay and advocate switching to Linux over Mac or Windows. The guide author welcomes further suggestions for additions such as Codeberg.

**Tags**: `#AI avoidance`, `#privacy`, `#open source alternatives`, `#software tools`, `#user control`

---

<a id="item-10"></a>
## [404 Media Tracks Rare Books to Amazon AI Training Facility](https://simonwillison.net/2026/Aug/17/we-tracked-a-shipment-of-rare-books-it-ended-at-an-amazon-ai-tra/) ⭐️ 7.0/10

404 Media placed an AirTag in a shipment of around 1,000 rare books ordered via Biblio marketplace in July, confirming delivery to the VGT3 section of Amazon's LAS8 facility in Las Vegas. The investigation supplies direct evidence that Amazon is acquiring bulk rare books for AI training data, extending known practices by companies like Anthropic and raising data ethics issues. The facility entrance displayed a dinosaur-with-book logo; Amazon workers on forums confirmed VGT3 performs destructive book scanning for data purposes.

rss · Simon Willison · Aug 17, 15:21

<details><summary>References</summary>
<ul>
<li><a href="https://www.biblio.com/">Used Books and Rare Books from Antiquarian Booksellers - Biblio</a></li>

</ul>
</details>

**Tags**: `#AI training data`, `#book scanning`, `#Amazon`, `#data ethics`, `#investigative journalism`

---

<a id="item-11"></a>
## [Critique Exposes Weak Benchmarks in Sparse Attention Papers](https://www.reddit.com/r/MachineLearning/comments/1vqqqcs/how_to_make_any_sparse_attention_kv_compression/) ⭐️ 7.0/10

A detailed X post by p_nawrot, shared on Reddit, outlines common evaluation tricks that make sparse attention and KV cache compression methods appear effective, such as single-needle retrieval without distractors and aggregated metrics on saturated tasks. This highlights systemic issues in efficient transformer research that can mislead practitioners and slow genuine progress in long-context model optimization. The post recommends testing with real-data QA, diverse in-context learning, and isolated contributions while avoiding prompt tuning only on the proposed method or outdated baselines.

reddit · r/MachineLearning · /u/korec1234 · Aug 17, 12:18

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/pdf/2504.17768">The Sparse Frontier: Sparse Attention Trade-offs in Transformer LLMs</a></li>

</ul>
</details>

**Tags**: `#sparse attention`, `#KV cache compression`, `#benchmarks`, `#evaluation pitfalls`, `#efficient transformers`

---

<a id="item-12"></a>
## [SSOG-Attention Offers Sum of Separable Gaussians as Sub-Quadratic SDPA Alternative](https://www.reddit.com/r/MachineLearning/comments/1vpt6ay/ssogattention_sum_of_separable_gaussians_as_a/) ⭐️ 7.0/10

SSOG-Attention introduces a sum-of-separable-Gaussians method achieving O(N√N d) complexity as a scalable, faster alternative to standard dot-product attention (SDPA). Experiments demonstrate it beats SDPA on CIFAR-100 and matches performance on ImageNet-1k with faster convergence, lower memory use, and improved speed at scale. This approach could reduce the quadratic bottleneck in transformer attention for vision models, enabling more efficient training and inference on large datasets. It affects researchers and practitioners working on scalable deep learning architectures in computer vision. The method learns a few Gaussian atoms per head and steers them geometrically based on query tokens, factorizing into separable sums for the reduced complexity. It is an early-stage single-author project with results on CIFAR and ImageNet, accompanied by a blog and GitHub repository.

reddit · r/MachineLearning · /u/4rtemi5 · Aug 16, 10:06

**Background**: Scaled dot-product attention (SDPA) computes similarity scores of all image-tokens with all query tokens, resulting in O(N²·d) complexity. SSOG instead uses learnable Gaussian atoms that can be factorized into a separable sum of Gaussians.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/4rtemi5/ssog">GitHub - 4rtemi5/ssog: SSOG - Attention : Near-linear Visual-Attention...</a></li>
<li><a href="https://news.ycombinator.com/item?id=49318407">SSOG : Near linear Visual- Attention that doesn't score... | Hacker News</a></li>

</ul>
</details>

**Tags**: `#attention mechanisms`, `#transformers`, `#efficient ML`, `#sub-quadratic algorithms`, `#deep learning`

---

<a id="item-13"></a>
## [Reddit Critique Questions ECA Paper's Core Channel Interaction Hypothesis](https://www.reddit.com/r/MachineLearning/comments/1vptaw9/revisiting_the_efficient_channel_attention_paper/) ⭐️ 7.0/10

A Reddit post re-examines the 2019 ECA paper (12k citations) and argues its central hypothesis that 1D convolutions capture useful cross-channel interactions is conceptually flawed because channel dimensions lack topology and locality. The critique challenges assumptions behind a widely adopted attention module that improved on SE, potentially influencing future designs of efficient channel attention mechanisms in CNNs. Experiments on chess 6-piece endgame tablebases show ECA (k=3) achieving 96.68% accuracy while k=1 reaches 96.61% and a per-channel gate reaches 96.65%, indicating cross-channel interaction is not the key factor.

reddit · r/MachineLearning · /u/arkuto · Aug 16, 10:13

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/1910.03151">[1910.03151] ECA-Net: Efficient Channel Attention for Deep Convolutional Neural Networks</a></li>
<li><a href="https://arxiv.org/abs/1709.01507">[1709.01507] Squeeze-and-Excitation Networks - arXiv.org</a></li>

</ul>
</details>

**Tags**: `#channel attention`, `#ECA`, `#CNNs`, `#attention mechanisms`, `#paper critique`

---

<a id="item-14"></a>
## [Quake Shareware CD-ROM Cracked Due to Extra Full-Version Files](https://fabiensanglard.net/quake_shareware_cd/index.html) ⭐️ 6.0/10

The Quake shareware CD-ROM was announced July 3, 1996 and released August 30, then cracked by GNOMON with Quakecrk.zip only 39 days later because it contained extra full-version files on the disc. The incident reveals how 1990s CD-ROM capacity limits and distribution practices enabled rapid piracy, affecting game developers and shareware models at the time. The disc included full files that allowed easy unlocking, with some users speculating it may have been an intentional design choice, and the crack worked on Quake but not Final Doom.

hackernews · shdon · Aug 17, 22:06 · [Discussion](https://news.ycombinator.com/item?id=49338328)

**Discussion**: Commenters recalled using files from the cracked disc for decades, later buying official versions, praised the NIN soundtrack included on the CD, and shared memories of fast cracks appearing in newsgroups during the shareware era.

**Tags**: `#retro gaming`, `#software cracking`, `#Quake`, `#CD-ROM`, `#90s computing`

---

<a id="item-15"></a>
## [Sun Clock Web App Visualizes Solar Events Using Suncalc](https://sunclock.net/) ⭐️ 6.0/10

Sun Clock is a web app that visualizes solar events including sunrise, sunset, and golden hour by leveraging the suncalc JavaScript library. The tool provides practical value for photographers and outdoor enthusiasts by offering precise timing for optimal lighting conditions, while highlighting ongoing challenges in accurate solar calculations across latitudes. The suncalc author noted a recent major overhaul improving library precision, while users pointed out issues with hardcoded golden hour definitions and UI handling in polar regions where the sun may not set.

hackernews · Gecko4072 · Aug 17, 16:37 · [Discussion](https://news.ycombinator.com/item?id=49333824)

**Background**: Suncalc is a lightweight JavaScript library designed to compute sun and moon positions along with sunlight phases for any given location and time without external dependencies.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/mourner/suncalc">GitHub - mourner/suncalc: A tiny JavaScript library for calculating sun ...</a></li>

</ul>
</details>

**Discussion**: HN users praised the app's design and suggested enhancements such as map-based location comparisons, dynamic golden hour calculations based on sun angle, and better handling of polar day-night edge cases.

**Tags**: `#web-app`, `#astronomy`, `#javascript`, `#visualization`, `#solar-time`

---

<a id="item-16"></a>
## [SineKAN: KAN Variant Uses Sinusoidal Activations Instead of B-Splines](https://www.reddit.com/r/MachineLearning/comments/1vqdode/r_sinekan_kolmogorovarnold_networks_using/) ⭐️ 6.0/10

A Reddit post shares an arXiv paper and GitHub repo introducing SineKAN, a Kolmogorov-Arnold Network variant that replaces B-splines with sinusoidal activation functions. This incremental variant provides an alternative activation approach for KANs and may encourage further exploration of activation functions in neural network research. The work is detailed in arXiv paper 2407.04149 with code at github.com/ereinha/SineKAN and has appeared in a peer-reviewed MDPI publication.

reddit · r/MachineLearning · /u/jacobgorm · Aug 17, 00:46

**Background**: Kolmogorov-Arnold Networks are neural architectures inspired by the Kolmogorov-Arnold representation theorem that replace fixed weights with learnable univariate functions, typically implemented via B-splines rather than the fixed activations used in standard multilayer perceptrons.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2407.04149">[2407.04149] SineKAN : Kolmogorov-Arnold Networks Using Sinusoidal...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Kolmogorov-Arnold_Networks">Kolmogorov-Arnold Networks</a></li>

</ul>
</details>

**Tags**: `#Kolmogorov-Arnold Networks`, `#Neural Networks`, `#Activation Functions`, `#Machine Learning`, `#Research Paper`

---

<a id="item-17"></a>
## [Linear Attention Fails Long-Range Recall on Million-Token DNA Sequences](https://www.reddit.com/r/MachineLearning/comments/1vpqwdc/how_can_we_solve_longrange_recall_in_linear/) ⭐️ 6.0/10

A Reddit post shows linear attention models and HyenaDNA achieve only ~25% accuracy, near random chance, on needle-in-haystack tasks for 1M-token DNA sequences, while reaching 50-60% at 16K context. The finding reveals a potential core limitation of linear attention's compressed state for precise retrieval, affecting efficient long-context modeling in genomics and similar domains. Attempts to modify the architecture yielded only marginal improvement to 27%; HyenaDNA showed the same failure, and common fixes like external memory or hybrids were noted as alternatives.

reddit · r/MachineLearning · /u/No-Coffee-8227 · Aug 16, 07:47

**Background**: Linear attention replaces softmax attention to reduce memory costs on long sequences such as 1M-token DNA. HyenaDNA applies Hyena operators to enable single-nucleotide modeling at million-token scale.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2306.15794">[2306.15794] HyenaDNA: Long-Range Genomic Sequence Modeling ... GitHub - HazyResearch/hyena-dna: Official implementation for ... HyenaDNA: learning from DNA with 1 Million token context Benchmarking DNA foundation models for genomic and genetic ... HyenaDNA: Long-Range Genomic Sequence Modeling at Single ... [PDF] HyenaDNA: Long-Range Genomic Sequence Modeling at ... LongSafari/hyenadna-large-1m-seqlen · Hugging Face</a></li>
<li><a href="https://arxiv.org/html/2402.18668v1">Simple linear attention language models balance the recall-throughput tradeoff</a></li>

</ul>
</details>

**Tags**: `#linear-attention`, `#long-context-modeling`, `#DNA-sequence-modeling`, `#efficient-transformers`, `#needle-in-haystack`

---