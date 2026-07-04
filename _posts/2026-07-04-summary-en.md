---
layout: default
title: "Horizon Summary: 2026-07-04 (EN)"
date: 2026-07-04
lang: en
---

> From 32 items, 13 important content pieces were selected

---

1. [Contrastive Decoding Diffing Recovers Verbatim Finetuning Data from Logits](#item-1) ⭐️ 8.0/10
2. [AMD MI355X Achieves 2626 Tokens/s for GLM-5.2 at Lower Cost Than Blackwell](#item-2) ⭐️ 7.0/10
3. [SearXNG: Free Open-Source Privacy-Focused Metasearch Engine](#item-3) ⭐️ 7.0/10
4. [Guide to Running State-of-the-Art LLMs Locally on High-End Hardware](#item-4) ⭐️ 7.0/10
5. [Pegasus Spyware Targets EU Parliament Member Investigating Surveillance](#item-5) ⭐️ 7.0/10
6. [Current AI Launches Open Source AI Gap Map v0.1](#item-6) ⭐️ 7.0/10
7. [Mistral Releases Leanstral 1.5 LLM for Lean 4 Proofs](#item-7) ⭐️ 6.0/10
8. [Josh Comeau Reports 50%+ Revenue Drop in Dev Courses Due to AI](#item-8) ⭐️ 6.0/10
9. [Simon Willison on Letting Fable Use Its Own Judgement](#item-9) ⭐️ 6.0/10
10. [llm-coding-agent 0.1a0 Released as Claude-Style Coding Agent Library](#item-10) ⭐️ 6.0/10
11. [Simon Willison Uses DSPy to Refine Datasette Agent SQL Prompts](#item-11) ⭐️ 6.0/10
12. [Geoffrey Litt's 'Understand to Participate' Principle for AI Coding](#item-12) ⭐️ 6.0/10
13. [Questioning Practicality of Safety Training for Open-Weight LLMs](#item-13) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Contrastive Decoding Diffing Recovers Verbatim Finetuning Data from Logits](https://www.reddit.com/r/MachineLearning/comments/1umn2dk/contrastive_decoding_diffing_cdd_recovering/) ⭐️ 8.0/10

Researchers introduce Contrastive Decoding Diffing (CDD), a method that recovers verbatim finetuning data from narrowly tuned LLMs using only grey-box logit access without weights or activations. On the SDF benchmark, CDD achieves 4+/5 verbatim recovery scores on 19/20 organism-model pairs across four model families, outperforming Activation Difference Lens (ADL). This advances LLM privacy and security research by showing that finetuning data can be extracted with minimal access, affecting model providers and users concerned about data leakage. It highlights risks in using LLM-generated synthetic data for training. CDD contrasts base and finetuned model logits directly with a single default configuration, requiring no per-organism calibration or layer selection. An incidental finding revealed the recurring fictional persona 'Dr. Elena Rodriguez' across unrelated domains due to its prevalence in Claude Sonnet 3.6 synthetic data.

reddit · r/MachineLearning · /u/CebulkaZapiekana · Jul 3, 19:01

**Tags**: `#LLM security`, `#model extraction`, `#finetuning analysis`, `#contrastive decoding`, `#AI safety`

---

<a id="item-2"></a>
## [AMD MI355X Achieves 2626 Tokens/s for GLM-5.2 at Lower Cost Than Blackwell](https://www.wafer.ai/blog/glm52-amd) ⭐️ 7.0/10

A blog post claims the AMD MI355X delivers 2626 tokens per second per node running GLM-5.2 at over twice lower cost than NVIDIA Blackwell GPUs. The result signals intensifying competition in AI accelerators and could give hyperscalers cheaper alternatives for large-scale LLM inference deployments. The benchmark uses mxfp4 quantization under production-like batch sizes and reports noticeable accuracy loss versus fp8, while sustained throughput rather than single-request latency is measured.

hackernews · latchkey · Jul 3, 21:49 · [Discussion](https://news.ycombinator.com/item?id=48780417)

<details><summary>References</summary>
<ul>
<li><a href="https://au.finance.yahoo.com/news/amd-gains-nvidia-lisa-su-201608311.html">AMD gains on Nvidia? Lisa Su reveals new chips in heated AI...</a></li>
<li><a href="https://www.promptzone.com/priya_sharma_fc23f454/glm-52-runs-2626-toks-on-amd-mi355x-3ooh">GLM-5.2 Runs 2626 tok/s on AMD MI 355 X - PromptZone</a></li>

</ul>
</details>

**Discussion**: Commenters stress the importance of declaring quantization levels in headlines, highlight accuracy degradation from fp8 to mxfp4, and request performance-per-watt figures plus clearer consumer pricing details.

**Tags**: `#AI hardware`, `#AMD MI355X`, `#NVIDIA Blackwell`, `#LLM inference`, `#performance benchmarking`

---

<a id="item-3"></a>
## [SearXNG: Free Open-Source Privacy-Focused Metasearch Engine](https://github.com/searxng/searxng) ⭐️ 7.0/10

SearXNG, a fork of the discontinued searX project, aggregates results from up to 280 search services while ensuring no user tracking or profiling occurs. It provides a key privacy tool for users seeking alternatives to mainstream search engines and supports integrations with local AI models for offline, consent-based workflows. Users report slower results and occasional CAPTCHAs from backends like DuckDuckGo, while tools like TinySearch optimize context for agent use and JSON output enables RAG applications.

hackernews · theanonymousone · Jul 3, 20:15 · [Discussion](https://news.ycombinator.com/item?id=48779454)

**Background**: A metasearch engine queries multiple independent search engines and aggregates their results into a single output without maintaining its own index.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/SearXNG">SearXNG</a></li>
<li><a href="https://docs.searxng.org/">SearXNG Documentation (2026.7.3+21773bbb2)</a></li>
<li><a href="https://en.wikipedia.org/wiki/Metasearch_engine">Metasearch engine</a></li>

</ul>
</details>

**Discussion**: Users praise SearXNG for daily privacy-focused searching and local model tool calling, with some noting speed trade-offs and CAPTCHA issues; the original searX creator shared a new project called Hister for full-text indexing.

**Tags**: `#open-source`, `#search-engine`, `#privacy`, `#metasearch`, `#local-ai`

---

<a id="item-4"></a>
## [Guide to Running State-of-the-Art LLMs Locally on High-End Hardware](https://github.com/jamesob/local-llm) ⭐️ 7.0/10

Jamesob released a GitHub guide on running SOTA LLMs locally that details hardware builds starting at a $40k budget with multiple high-end GPUs and practical setup advice for model inference. The guide highlights tradeoffs between expensive local hardware and cloud APIs, influencing AI developers and enthusiasts weighing cost, performance, and privacy in model deployment decisions. Builds rely on techniques like quantization and pruning for models such as GLM-5.2, with commenters noting actual costs often exceed $50k and performance may lag behind services like Claude Opus.

hackernews · livestyle · Jul 3, 15:03 · [Discussion](https://news.ycombinator.com/item?id=48775921)

**Background**: Quantization is a technique that converts high-precision model weights to lower precision formats such as INT8 to reduce memory requirements during inference. Model inference is the process of deploying a trained LLM to generate predictions or outputs on new input data.

<details><summary>References</summary>
<ul>
<li><a href="https://www.ibm.com/think/topics/quantization">What is Quantization? | IBM</a></li>
<li><a href="https://www.ibm.com/think/topics/ai-inference">What is AI Inference? - Machine learning</a></li>

</ul>
</details>

**Discussion**: Commenters express skepticism about the high costs of local builds versus cloud subscriptions, discuss alternatives like 128GB unified memory setups, and raise concerns over quantized model quality and potential backdoors.

**Tags**: `#local LLMs`, `#AI hardware`, `#model inference`, `#quantization`, `#open-source AI`

---

<a id="item-5"></a>
## [Pegasus Spyware Targets EU Parliament Member Investigating Surveillance](https://citizenlab.ca/research/member-of-committee-investigating-spyware-hacked-with-pegasus/) ⭐️ 7.0/10

Citizen Lab reported that European Parliament member Stelios Kouloglou's iPhone was infected with Pegasus spyware on or around October 21, 2022, and again on March 6-7, 2023. The infections overlapped with a campaign targeting Russian and Belarusian exiles, pointing to a Pegasus operator active across multiple European countries. The incident highlights risks of state-sponsored surveillance reaching EU institutions and lawmakers tasked with oversight of spyware. It raises concerns about accountability and the potential compromise of sensitive parliamentary and personal data. Forensic analysis confirmed the infections with high confidence, and the device may have exposed both personal medical information and confidential government documents. No details were released on the specific Pegasus customer responsible.

hackernews · ledoge · Jul 3, 20:38 · [Discussion](https://news.ycombinator.com/item?id=48779683)

**Background**: Pegasus is a zero-click spyware developed by Israel's NSO Group that allows remote access to smartphones without user interaction. Citizen Lab is a University of Toronto research group specializing in investigating digital espionage and threats to human rights.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Pegasus_(spyware)">Pegasus (spyware) - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Citizen_Lab">Citizen Lab</a></li>

</ul>
</details>

**Discussion**: Commenters noted possible involvement of EU states like Greece, Poland, and Italy in Pegasus use, questioned the lack of work-personal device separation policies in the EU Parliament, and expressed concern that member states are contributing to the spyware's proliferation against their own officials.

**Tags**: `#pegasus`, `#spyware`, `#cybersecurity`, `#surveillance`, `#european-parliament`

---

<a id="item-6"></a>
## [Current AI Launches Open Source AI Gap Map v0.1](https://simonwillison.net/2026/Jul/3/open-source-ai-gap-map/#atom-everything) ⭐️ 7.0/10

Current AI launched the Gap Map v0.1 which catalogs 421 open source AI products including 266 tools, 85 models, 50 datasets and 20 hardware projects across 14 categories. The map provides a public non-profit resource for tracking the open source AI ecosystem with data released under an MIT license, backed by $400 million in commitments from a global partnership founded in 2025. The project includes 1,184 YAML files on GitHub plus notebooks and schemas, while tracking 16,185 GitHub repositories in total with the remaining 24,400 artifacts left uncategorized for now.

rss · Simon Willison · Jul 3, 22:04

**Tags**: `#open source AI`, `#AI ecosystem mapping`, `#non-profit AI`, `#AI resources`, `#gap analysis`

---

<a id="item-7"></a>
## [Mistral Releases Leanstral 1.5 LLM for Lean 4 Proofs](https://mistral.ai/news/leanstral-1-5/) ⭐️ 6.0/10

Mistral announces Leanstral 1.5, a specialized LLM for generating formal proofs in Lean 4. The release advances AI tools for theorem proving and formal verification, potentially aiding developers and mathematicians in creating reliable software and proofs. The announcement includes comparisons to frontier LLMs from half a year ago and highlights a bug-finding example in a Zigzag decoding library that drew community scrutiny.

hackernews · programLyrique · Jul 3, 22:33 · [Discussion](https://news.ycombinator.com/item?id=48780801)

**Background**: Lean 4 is an open-source proof assistant and functional programming language based on the calculus of constructions, used for writing formally verified code and mathematical proofs.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Lean_4">Lean 4</a></li>

</ul>
</details>

**Discussion**: Commenters expressed skepticism about the bug-finding example's realism, noted that model comparisons use outdated LLMs from months ago, and questioned the exclusive focus on Lean 4 versus other provers like Isabelle/HOL.

**Tags**: `#AI`, `#LLMs`, `#Formal Verification`, `#Lean`, `#Theorem Proving`

---

<a id="item-8"></a>
## [Josh Comeau Reports 50%+ Revenue Drop in Dev Courses Due to AI](https://simonwillison.net/2026/Jul/3/josh-w-comeau/#atom-everything) ⭐️ 6.0/10

Josh W. Comeau reports his new course Whimsical Animations is on track to sell roughly one-third as many copies as typical launches, with his two existing courses also showing significantly lower sales than last year. This anecdotal report highlights how AI is disrupting the paid developer education market, with fewer learners willing to invest in courses amid job uncertainty and free LLM alternatives. Comeau identifies a double impact from AI where people fear developer jobs may disappear soon and LLMs offer personalized tutoring without consent or compensation for original creators, with other course creators reporting similar 50%+ revenue drops.

rss · Simon Willison · Jul 3, 21:25

**Tags**: `#AI impact`, `#online education`, `#developer courses`, `#LLMs`, `#market trends`

---

<a id="item-9"></a>
## [Simon Willison on Letting Fable Use Its Own Judgement](https://simonwillison.net/2026/Jul/3/judgement/#atom-everything) ⭐️ 6.0/10

Simon Willison shared tips from a Fireside Chat recommending that Fable and Opus use their own judgement for tasks like deciding when to write tests or selecting lower-power models for subagents. This approach optimizes efficiency and reduces token consumption on high-cost models like Fable before upcoming price increases, allowing more work to be completed within limits. A specific prompt directs Claude Code to delegate coding tasks to subagents using models like Sonnet or Haiku based on judgement, with the main model handling review and synthesis.

rss · Simon Willison · Jul 3, 18:51

**Background**: Fable is Anthropic's advanced AI model focused on software engineering and coding tasks, while Claude Code is their agentic tool that edits files and runs commands in developer environments.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/news/claude-fable-5-mythos-5">Claude Fable 5 and Claude Mythos 5 \ Anthropic</a></li>
<li><a href="https://www.anthropic.com/product/claude-code">Claude Code | Anthropic's agentic coding system \ Anthropic</a></li>

</ul>
</details>

**Tags**: `#AI prompting`, `#Claude AI`, `#prompt engineering`, `#AI tools`, `#software development`

---

<a id="item-10"></a>
## [llm-coding-agent 0.1a0 Released as Claude-Style Coding Agent Library](https://simonwillison.net/2026/Jul/2/llm-coding-agent/#atom-everything) ⭐️ 6.0/10

Simon Willison released llm-coding-agent 0.1a0, a new Python library that implements a Claude-style coding agent on top of the LLM framework. The early alpha demonstrates how the evolving LLM library can serve as an agent framework and adds an experimental option to the growing space of LLM coding agents. The package provides file tools including edit_file, read_file, list_files, search_files and execute_command, plus a CodingAgent Python API; it is installable via uvx and supports commands like llm code --yolo.

rss · Simon Willison · Jul 2, 19:33

<details><summary>References</summary>
<ul>
<li><a href="https://pypi.org/project/llm/">llm · PyPI</a></li>
<li><a href="https://github.com/simonw/llm">GitHub - simonw / llm : Access large language models from the...</a></li>

</ul>
</details>

**Tags**: `#LLM agents`, `#coding tools`, `#Python`, `#AI development`, `#open source`

---

<a id="item-11"></a>
## [Simon Willison Uses DSPy to Refine Datasette Agent SQL Prompts](https://simonwillison.net/2026/Jul/2/dspy-datasette-agent-prompts/#atom-everything) ⭐️ 6.0/10

Simon Willison ran an experiment with DSPy to evaluate and improve the system prompts used by Datasette Agent for generating read-only SQL queries against data. Using GPT-4.1 mini and nano models, the test identified issues such as column-name guessing caused by schema listings that only include table names. The work shows how DSPy can systematically optimize prompts in LLM agents that interact with databases, potentially increasing accuracy and reducing error-retry loops in data exploration tools. A key finding recommends either including column names in the prompt's schema listing or softening the advice against calling describe_table when information is already available.

rss · Simon Willison · Jul 2, 18:25

**Background**: DSPy is a framework designed to program and optimize language model applications rather than manually tuning prompts. Datasette Agent is an AI assistant that writes and executes SQL queries to answer questions about data stored in Datasette.

<details><summary>References</summary>
<ul>
<li><a href="https://agent.datasette.io/">Datasette Agent : an AI assistant for Datasette to help explore and...</a></li>
<li><a href="https://simonwillison.net/2026/May/21/datasette-agent/">Datasette Agent | Simon Willison’s Weblog</a></li>

</ul>
</details>

**Tags**: `#DSPy`, `#Prompt Engineering`, `#Datasette`, `#LLM Agents`, `#SQL`

---

<a id="item-12"></a>
## [Geoffrey Litt's 'Understand to Participate' Principle for AI Coding](https://simonwillison.net/2026/Jul/2/understand-to-participate/#atom-everything) ⭐️ 6.0/10

Simon Willison shares Geoffrey Litt's 'understand to participate' principle from his AIE talk, stressing the need to maintain code understanding when collaborating with AI coding agents to avoid cognitive debt. This principle helps developers stay active participants in AI-assisted coding projects rather than accumulating cognitive debt that limits future creative input and project fluency. Litt argues that a rich set of mental concepts is required to think creatively about code changes, and the AIE talk recording plus his Twitter thread are recommended for further details.

rss · Simon Willison · Jul 2, 17:07

**Tags**: `#AI coding agents`, `#cognitive debt`, `#human-AI collaboration`, `#software engineering`

---

<a id="item-13"></a>
## [Questioning Practicality of Safety Training for Open-Weight LLMs](https://www.reddit.com/r/MachineLearning/comments/1um9bs7/what_does_safe_ai_look_like_d/) ⭐️ 6.0/10

A Reddit post by /u/Aaron_Rock questions how practical it is to defend open-weight LLMs against post-release fine-tuning that removes refusal behaviors, noting that uncensored variants appear rapidly after new model releases. This raises key issues for AI safety and model governance, as rapid bypassing of safety training could affect the viability of open-weight releases and influence decisions on whether to invest in such training at all. The post highlights that fine-tuning to break safety can take as little as 30 minutes with an automated script, and asks whether increasing attacker costs or reducing reliability of safety removal would still count as a useful outcome even without perfect prevention.

reddit · r/MachineLearning · /u/Aaron_Rock · Jul 3, 09:07

**Background**: Open-weight LLMs release model parameters publicly, enabling users to perform fine-tuning on targeted datasets to adapt behavior, in contrast to closed models where weights remain inaccessible.

<details><summary>References</summary>
<ul>
<li><a href="https://www.linkedin.com/pulse/open-weights-llms-in-depth-analysis-adoption-usage-performance-jha-kymhc">Open - Weights LLMs : In-Depth Analysis of Adoption, Usage, and...</a></li>
<li><a href="https://medium.com/thought-vector/open-weight-llms-a-strategic-advantage-for-enterprise-ai-1c4859ea6885">Open - Weight LLMs : A Strategic Advantage for Enterprise AI | Medium</a></li>

</ul>
</details>

**Tags**: `#AI Safety`, `#LLMs`, `#Fine-tuning`, `#Open-weight models`, `#Model Governance`

---