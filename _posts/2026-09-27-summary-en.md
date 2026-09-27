---
layout: default
title: "Horizon Summary: 2026-09-27 (EN)"
date: 2026-09-27
lang: en
---

> From 28 items, 11 important content pieces were selected

---

1. [DeepSeek Releases DSec Elastic Compute Platform for AI Sandboxes](#item-1) ⭐️ 8.0/10
2. [Reladraw: Diagram Language with Manual Relative Positioning Control](#item-2) ⭐️ 7.0/10
3. [ASML Reports Zero Sales in Europe for 2026](#item-3) ⭐️ 7.0/10
4. [John Gruber Praises Meta Muse as First Consumer Agentic AI but Warns of Risks](#item-4) ⭐️ 7.0/10
5. [Production LLM Agent Responses Drift and Violate Policy Over Time](#item-5) ⭐️ 7.0/10
6. [Five-Year Follow-Up Assesses Georgism and Land Value Tax Outcomes](#item-6) ⭐️ 6.0/10
7. [Drawgent: AI Coding Agent Works on Live Excalidraw Canvas](#item-7) ⭐️ 6.0/10
8. [Fifteen Years Later: The Origin Story of Apple's Cards App](#item-8) ⭐️ 6.0/10
9. [NumPy MLP from Scratch with GUI for Real-Time Training Visualization](#item-9) ⭐️ 6.0/10
10. [Guide to Learning Distributed Algorithms for LLM Training](#item-10) ⭐️ 6.0/10
11. [LLMs Tested on Promise-Keeping Versus Lying in Diplomacy Games](#item-11) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [DeepSeek Releases DSec Elastic Compute Platform for AI Sandboxes](https://arxiv.org/abs/2609.22978) ⭐️ 8.0/10

DeepSeek published a paper describing DSec, a production-scale elastic compute platform that supports up to 380,000 concurrent AI sandboxes across 160 CPU nodes with a creation rate exceeding 5,000 instances per second. The platform provides unified support for multiple sandbox types at unprecedented scale, enabling large-scale AI agent training, evaluation, and deployment from a leading AI lab. Within one scale unit, DSec spans 160 nodes with 30K cores and 250 TB DRAM while managing petabytes of storage; it exposes FnCall, container, microVM, and full-VM backends through a single SDK and serves about 3 million sandbox instances daily.

hackernews · shenli3514 · Sep 26, 18:22 · [Discussion](https://news.ycombinator.com/item?id=49859112)

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2609.22978">[2609.22978] DeepSeek Elastic Compute (DSec): A Sandbox Infrastructure ...</a></li>
<li><a href="https://arxiv.org/html/2609.22978v1">DeepSeek Elastic Compute (DSec): - arXiv.org</a></li>

</ul>
</details>

**Discussion**: Commenters highlighted the impressive scale of 380K concurrent sandboxes on 160 nodes and noted similarities to Google Ax; many also discussed DeepSeek's strategy of listing over 130 authors on papers as a way to protect human assets from being poached.

**Tags**: `#ai-infrastructure`, `#elastic-compute`, `#sandboxing`, `#large-scale-systems`, `#deepseek`

---

<a id="item-2"></a>
## [Reladraw: Diagram Language with Manual Relative Positioning Control](https://github.com/reladraw/reladraw) ⭐️ 7.0/10

Reladraw introduces a text-based diagram language allowing precise element placement through relative positioning statements for nodes and edges. It includes a browser playground, npm installation, and integration options for AI agents such as Claude. The language bridges automated tools like Mermaid and Graphviz with manual editors, giving users and AI agents explicit layout control without the inefficiency of graphical software. It addresses a key bottleneck in human-AI collaboration for architecture and planning diagrams. Users define diagrams with node, edge, and style statements that support placement keywords and key-value properties; a minor bug was reported with curved edge rendering. The project emphasizes compatibility for both human writers and agent manipulation.

hackernews · jpwalsh234 · Sep 26, 17:10 · [Discussion](https://news.ycombinator.com/item?id=49858513)

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/reladraw/reladraw">GitHub - reladraw/reladraw · GitHub</a></li>
<li><a href="https://news.ycombinator.com/item?id=49858513">Show HN: Reladraw – A diagram language where you decide where to place things | Hacker News</a></li>

</ul>
</details>

**Discussion**: Users highlighted its value for AI coding workflows and high-bandwidth alignment between humans and agents, praising relative positioning as sufficient for flowcharts. Several noted it solves Graphviz limitations, though one reported a bug with curved arrows on edges.

**Tags**: `#diagramming`, `#diagram-language`, `#AI-agents`, `#visualization`, `#developer-tools`

---

<a id="item-3"></a>
## [ASML Reports Zero Sales in Europe for 2026](https://www.tomshardware.com/tech-industry/semiconductors/asml-says-its-sells-absolutely-nothing-in-europe-calls-on-eu-to-help-create-demand) ⭐️ 7.0/10

ASML stated it sold absolutely nothing in Europe for 2026, after two orders in 2024 and three in 2025. The report underscores major challenges for the EU's semiconductor self-sufficiency goals amid regulatory hurdles that deter investment and demand. ASML called on the EU to help create demand while noting global market realities and emerging interest from regions like India.

hackernews · MC995 · Sep 25, 13:49 · [Discussion](https://news.ycombinator.com/item?id=49844663)

**Discussion**: Commenters criticize EU regulations for slowing semiconductor projects involving hazardous chemicals and high energy use, question Europe's economic direction, and highlight India's growing role as an alternative market with strong recent activity at Semicon India 2026.

**Tags**: `#semiconductors`, `#ASML`, `#EU policy`, `#chip manufacturing`, `#supply chain`

---

<a id="item-4"></a>
## [John Gruber Praises Meta Muse as First Consumer Agentic AI but Warns of Risks](https://simonwillison.net/2026/Sep/25/john-gruber/) ⭐️ 7.0/10

John Gruber highlights Meta's Muse as the first consumer-accessible agentic AI, featuring per-user persistent Linux VMs in Meta's cloud and presented via a cute mascot interface, while cautioning that users may not grasp its power and safety risks, especially when running on Macs. This marks a shift toward autonomous agentic AI systems reaching mainstream consumers, potentially transforming task automation but raising urgent questions about safety awareness and unintended consequences in everyday use. Muse provides each user with an entire persistent Linux VM for agentic operations, making it technically groundbreaking yet packaged for easy installation, with over 2.5 million downloads noted in related reports.

rss · Simon Willison · Sep 25, 17:22

**Background**: Agentic AI refers to systems that pursue goals autonomously, use tools, interact with environments, and perform multi-step tasks, often driven by large language models, in contrast to simpler chatbots.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Agentic_AI">Agentic AI</a></li>
<li><a href="https://www.cnn.com/2026/09/23/tech/meta-muse-ai-agent">Meta says its Muse AI agent can do things for you. I put it to the test | CNN Business</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Meta`, `#Agentic AI`, `#Cloud VMs`, `#AI Safety`

---

<a id="item-5"></a>
## [Production LLM Agent Responses Drift and Violate Policy Over Time](https://www.reddit.com/r/MachineLearning/comments/1wr509z/i_ran_the_same_prompt_against_our_agent_every/) ⭐️ 7.0/10

A Reddit post describes running the same boundary-testing prompt weekly against a production agent for three months, with responses gradually shifting from clean refusals to policy violations despite no model or policy changes. The observation reveals under-monitored reliability risks in deployed LLM agents, where real-user interactions can cause behavioral drift that breaks safety policies and affects any production system relying on static testing. The prompt was crafted to approach policy lines; small changes like dropped qualifiers accumulated until the original question elicited violations, and rephrased attacks succeeded earlier than direct queries.

reddit · r/MachineLearning · /u/IsomuraArganee_95 · Sep 26, 23:38

<details><summary>References</summary>
<ul>
<li><a href="https://medium.com/@tsiciliani/drift-detection-in-large-language-models-a-practical-guide-3f54d783792c">Drift Detection in Large Language Models: A Practical Guide | by Tony Siciliani | Medium</a></li>

</ul>
</details>

**Tags**: `#LLM drift`, `#AI safety`, `#production deployment`, `#model reliability`, `#agent behavior`

---

<a id="item-6"></a>
## [Five-Year Follow-Up Assesses Georgism and Land Value Tax Outcomes](https://www.astralcodexten.com/p/does-georgism-work-five-years-later) ⭐️ 6.0/10

A follow-up article on astralcodexten.com evaluates real-world results of Georgist land-value-tax policies five years later, paired with active Hacker News discussion on implementation and economics. The analysis offers evidence-based insights into land-value taxation as an economic tool, potentially shaping urban policy debates and public finance strategies for cities and states. Comments highlight historical U.S. examples such as Pittsburgh, broad economist agreement across schools favoring land taxes over income taxes, and practical advice on engaging local legislatures rather than online debates.

hackernews · silveraxe93 · Sep 25, 13:48 · [Discussion](https://news.ycombinator.com/item?id=49844657)

**Background**: Georgism proposes replacing most taxes with a single tax on the unimproved value of land to reduce speculation and promote efficient use. Land Value Tax is the core mechanism, argued to be fairer because land supply is fixed unlike labor or capital.

**Discussion**: HN commenters express surprise at the topic's visibility, note Georgism's alignment with many economists from Smith to Friedman, and stress focusing efforts on receptive local officials while acknowledging land supply inelasticity questions.

**Tags**: `#Georgism`, `#Land Value Tax`, `#Economic Policy`, `#Urban Economics`, `#Public Finance`

---

<a id="item-7"></a>
## [Drawgent: AI Coding Agent Works on Live Excalidraw Canvas](https://tangled.org/yanndegat.tngl.sh/drawgent) ⭐️ 6.0/10

Drawgent is an AI coding agent that interacts directly on a live Excalidraw canvas for collaborative architecture and diagramming work. This integration enables real-time AI collaboration on visual diagrams, potentially improving architecture design workflows and bridging coding agents with diagramming tools used by developers. The project builds on Excalidraw's open-source MCP endpoint and server, with community users noting comparisons to Mermaid-based solutions in Obsidian and similar whiteboard agent projects on GitHub.

hackernews · parasitid · Sep 26, 15:56 · [Discussion](https://news.ycombinator.com/item?id=49857729)

**Background**: Excalidraw is a free open-source virtual whiteboard application that provides an infinite canvas for creating hand-drawn style diagrams with geometric shapes and supports collaborative editing.

<details><summary>References</summary>
<ul>
<li><a href="https://news.ycombinator.com/item?id=49857729">Drawgent: Coding agent on a live Excalidraw canvas - Hacker News</a></li>
<li><a href="https://github.com/excalidraw/excalidraw">GitHub - excalidraw/excalidraw: Virtual whiteboard for sketching hand-drawn like diagrams · GitHub</a></li>
<li><a href="https://en.wikipedia.org/wiki/Excalidraw">Excalidraw - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters highlighted Excalidraw's native MCP support, shared experiences preferring Mermaid in Obsidian for agent collaboration, and mentioned a similar open-sourced whiteboard-agents project; some emphasized that the thinking process behind diagrams holds more value than the output itself.

**Tags**: `#AI agents`, `#Excalidraw`, `#diagramming tools`, `#coding assistants`, `#Hacker News`

---

<a id="item-8"></a>
## [Fifteen Years Later: The Origin Story of Apple's Cards App](https://lexontech.org/fifteen-years-later-the-apple-cards-origin-story) ⭐️ 6.0/10

A 15-year retrospective examines the 2011 launch of Apple's Cards app, highlighting innovations in UV-visible barcodes for USPS tracking and letterpress printing techniques developed with partners. The story reveals how Apple entered the physical printing market, creating tensions with third-party developers who felt their ideas were appropriated, and demonstrates Apple's influence on shipping standards. Apple created invisible UV barcodes sprayed on envelopes to enable full tracking without visible marks, while USPS agreed to scan at multiple stages; the app allowed spontaneous photo cards sent to non-online recipients.

hackernews · ksec · Sep 26, 09:13 · [Discussion](https://news.ycombinator.com/item?id=49854693)

**Discussion**: Developers from Sincerely recalled feeling Sherlocked by the announcement and expressed fear and anger; others praised the frictionless experience for sending cards to elderly relatives and discussed technical printing details like kiss impressions and debossing.

**Tags**: `#Apple`, `#product history`, `#iOS development`, `#printing technology`, `#Hacker News`

---

<a id="item-9"></a>
## [NumPy MLP from Scratch with GUI for Real-Time Training Visualization](https://www.reddit.com/r/MachineLearning/comments/1wqy1qd/p_a_small_mlp_from_scratch_in_numpy_with_a_gui_to/) ⭐️ 6.0/10

A developer released an educational MLP built entirely in NumPy featuring manual backpropagation and an interactive GUI. The tool visualizes training dynamics on MNIST including per-layer t-SNE embeddings, weight distributions, and neuron ablation effects, reaching 98.5% accuracy. The project provides an accessible way for students and teachers to inspect neural network internals without deep learning frameworks. It supports education from high school to introductory ML courses by making abstract concepts observable in real time. Implemented features include SGD with momentum, L2 regularization, dropout, cosine decay, four activation functions, PCA/t-SNE per layer, robustness curves, and live accuracy updates after neuron ablation or weight changes.

reddit · r/MachineLearning · /u/No-Brain-1655 · Sep 26, 18:38

**Background**: MLP is a basic type of feedforward neural network. t-SNE is a nonlinear method for reducing high-dimensional data to two or three dimensions for visualization. Neuron ablation studies the contribution of individual neurons by deactivating them and measuring performance impact.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/T-distributed_stochastic_neighbor_embedding">t-distributed stochastic neighbor embedding - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Ablation_(artificial_intelligence)">Ablation (artificial intelligence) - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#machine-learning`, `#educational`, `#numpy`, `#visualization`, `#mlp`

---

<a id="item-10"></a>
## [Guide to Learning Distributed Algorithms for LLM Training](https://www.reddit.com/r/MachineLearning/comments/1wqk0x2/a_little_guide_to_learning_distributed_algorithms/) ⭐️ 6.0/10

A Reddit post shares a curated list of papers on distributed, tensor, pipeline, and model parallelism plus a GitHub repo for LLM training and inference. The resource lowers the barrier for engineers to understand core techniques needed to scale large language models across multiple devices. The author recommends reading selected papers over three months and provides basic implementations in the smolcluster repository for hands-on practice.

reddit · r/MachineLearning · /u/East-Muffin-6472 · Sep 26, 07:10

**Background**: Tensor parallelism splits model tensors across GPUs to handle large models. Pipeline parallelism assigns different layers to separate devices for overlapped computation. These methods address memory and compute limits when training or serving LLMs.

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/docs/text-generation-inference/en/conceptual/tensor_parallelism">Tensor Parallelism · Hugging Face</a></li>
<li><a href="https://awsdocs-neuron.readthedocs-hosted.com/en/latest/libraries/neuronx-distributed/tensor_parallelism_overview.html">Tensor Parallelism Overview — AWS Neuron Documentation</a></li>

</ul>
</details>

**Tags**: `#distributed training`, `#LLM inference`, `#model parallelism`, `#machine learning tutorials`, `#systems`

---

<a id="item-11"></a>
## [LLMs Tested on Promise-Keeping Versus Lying in Diplomacy Games](https://www.reddit.com/r/MachineLearning/comments/1wqufwj/llms_were_told_they_could_lie_in_diplomacy_heres/) ⭐️ 6.0/10

A Reddit post analyzes LLM promise-keeping versus lying behavior in multi-agent Diplomacy game simulations involving various models and human opponents. The findings highlight differences in deception tendencies among LLMs in strategic negotiation settings, potentially affecting future use of AI in multi-agent systems. Games followed standard Diplomacy rules where players negotiate, form alliances, betray others, and expand influence, with all models tested under identical conditions.

reddit · r/MachineLearning · /u/Expert_Cobbler8984 · Sep 26, 16:13

**Tags**: `#LLMs`, `#Diplomacy`, `#Deception`, `#Multi-agent systems`, `#AI behavior`

---