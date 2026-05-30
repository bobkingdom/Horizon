---
layout: default
title: "Horizon Summary: 2026-05-30 (EN)"
date: 2026-05-30
lang: en
---

> From 36 items, 8 important content pieces were selected

---

1. [Zig Build System Receives Major Rework in Latest Update](#item-1) ⭐️ 8.0/10
2. [US Proposes Rules Allowing Arbitrary Cancellation of Science Grants](#item-2) ⭐️ 8.0/10
3. [Openrsync: OpenBSD Team's Secure rsync Implementation](#item-3) ⭐️ 7.0/10
4. [SQLite for Durable Workflows Sparks Production Debate](#item-4) ⭐️ 7.0/10
5. [Probe-Targeted LoRA Fine-Tuning Aligns LLM Verbal Confidence with Internal Knowledge](#item-5) ⭐️ 7.0/10
6. [Pandoc Templates Site Offers Improved Document Conversion Options](#item-6) ⭐️ 6.0/10
7. [Pope Leo's Encyclical Critiques Technological Messianism](#item-7) ⭐️ 6.0/10
8. [Datasette 1.0a31 Adds Write Queries and Stored Query Saving](#item-8) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Zig Build System Receives Major Rework in Latest Update](https://ziglang.org/devlog/2026/#2026-05-26) ⭐️ 8.0/10

The Zig devlog dated May 26, 2026, details a major rework of the build system. This follows the release of Zig 0.16.0 with its new IO mechanism and precedes the upcoming 0.17.0 release within weeks. The changes improve code efficiency and usability across single-threaded, multi-threaded, and event-loop implementations, strengthening Zig's position in the systems programming ecosystem. Developers report positive experiences that position the language for broader adoption and future growth. The rework builds on Zig 0.16.0 advancements, with community users noting significant positive impacts on existing codebases and efficient new IO handling. Release cadence has accelerated notably compared to the prior 0.16 cycle that took over a year.

hackernews · tosh · May 30, 08:38 · [Discussion](https://news.ycombinator.com/item?id=48334048)

<details><summary>References</summary>
<ul>
<li><a href="https://ziglang.org/">Home ⚡ Zig Programming Language</a></li>
<li><a href="https://ziglang.org/learn/build-system/">Zig Build System Zig Programming Language</a></li>

</ul>
</details>

**Discussion**: Users express strong satisfaction with Zig 0.16.0 upgrades, praising the new IO mechanism for enabling clean and efficient code in varied threading models. Many highlight Zig's suitability as a flexible tool language for rapid prototyping, while noting surprise at the rapid 0.17.0 timeline.

**Tags**: `#Zig`, `#Build Systems`, `#Programming Languages`, `#Developer Tools`

---

<a id="item-2"></a>
## [US Proposes Rules Allowing Arbitrary Cancellation of Science Grants](https://arstechnica.com/science/2026/05/the-office-of-management-and-budget-tries-again-to-cripple-us-science/) ⭐️ 8.0/10

The Office of Management and Budget proposed rules that would let the US government cancel any scientific grant at any time. The change raises alarms about political interference in research and could harm US scientific progress by restricting open collaboration and communication. The rules would impose severe restrictions on collaboration, publication, and public communication essential to scientific progress.

hackernews · mhalle · May 30, 11:41 · [Discussion](https://news.ycombinator.com/item?id=48335135)

**Discussion**: Scientists strongly oppose the rules, warning of politicized funding, forced emigration to continue research, and broader damage to open science and national standing.

**Tags**: `#US science policy`, `#research funding`, `#government regulation`, `#academic research`, `#political interference`

---

<a id="item-3"></a>
## [Openrsync: OpenBSD Team's Secure rsync Implementation](https://github.com/kristapsdz/openrsync) ⭐️ 7.0/10

The OpenBSD team released Openrsync, a C implementation of rsync that emphasizes security features like pledge(2) and unveil(2). It is already used in macOS since version 15.0. It offers a security-focused reimplementation of the widely used rsync tool, potentially reducing risks when synchronizing files over networks with untrusted data. Openrsync consists of about 10,000 lines of C code and relies on OpenBSD-specific system calls for restricting capabilities; without pledge and unveil, its security benefits are limited on other systems.

hackernews · sph · May 30, 10:51 · [Discussion](https://news.ycombinator.com/item?id=48334854)

**Background**: rsync is a standard tool for efficient file synchronization across networks. OpenBSD's pledge(2) and unveil(2) are system calls that restrict a process's access to system resources and the filesystem for improved security.

<details><summary>References</summary>
<ul>
<li><a href="https://man.openbsd.org/pledge">pledge ( 2 ) - OpenBSD manual pages</a></li>
<li><a href="https://man.openbsd.org/unveil">unveil ( 2 ) - OpenBSD manual pages</a></li>

</ul>
</details>

**Discussion**: Commenters noted a Go implementation by the Gokrazy team and macOS adoption since 15.0; discussions also covered challenges porting pledge/unveil to Linux, the name implying more openness than the GPL rsync, and debates on whether rsync typically faces hostile network threats.

**Tags**: `#openbsd`, `#rsync`, `#security`, `#systems`, `#file-sync`

---

<a id="item-4"></a>
## [SQLite for Durable Workflows Sparks Production Debate](https://obeli.sk/blog/sqlite-is-all-you-need-for-durable-workflows/) ⭐️ 7.0/10

An article titled 'SQLite is all you need for durable workflows' advocates using SQLite as the core for resilient workflow systems, triggering extensive Hacker News discussion on concurrency limits and real-world viability. The piece questions reliance on heavy server databases for durable execution, potentially enabling simpler and cheaper infrastructure for developers building crash-resilient applications. Commenters note Temporal's use of SQLite for lightweight local deployments while others emphasize SQLite's unsuitability for multi-process concurrency compared to Postgres or MySQL.

hackernews · tomasol · May 29, 17:54 · [Discussion](https://news.ycombinator.com/item?id=48326802)

**Background**: Durable execution is a paradigm that saves workflow progress at key points so execution can resume after crashes or restarts without losing state.

<details><summary>References</summary>
<ul>
<li><a href="https://temporal.io/blog/what-is-durable-execution">The definitive guide to Durable Execution | Temporal</a></li>

</ul>
</details>

**Discussion**: Opinions are divided: some users successfully replaced multiple SaaS tools with Go plus SQLite for cost savings, while critics argue SQLite lacks the concurrency foundation needed for production multi-machine environments and cite the recurring cycle of overcomplicating then simplifying tool choices.

**Tags**: `#sqlite`, `#workflows`, `#databases`, `#durable-execution`, `#systems-design`

---

<a id="item-5"></a>
## [Probe-Targeted LoRA Fine-Tuning Aligns LLM Verbal Confidence with Internal Knowledge](https://www.reddit.com/r/MachineLearning/comments/1tqrtkn/making_llms_tell_you_how_confident_they_really/) ⭐️ 7.0/10

Research demonstrates probe-targeted LoRA fine-tuning that uses linear probe outputs from LLM hidden states as training targets to make models verbally express their actual internal confidence in correctness. The method was validated across eight models from four families ranging from 7B to 70B parameters, with activation patching confirming causal effects and a preprint available on Zenodo. This approach addresses the common misalignment where LLMs overstate confidence verbally despite possessing accurate internal signals, potentially improving reliability in high-stakes applications. It offers an efficient, replicable technique using few hundred examples and short training times that could influence future calibration and interpretability methods in the LLM ecosystem. Probes achieved 0.76–0.88 AUROC on hidden states while direct model responses defaulted to 99% confidence; activation patching at confidence positions yielded ρ = 0.976 correlation with output shifts. The technique used LoRA on a few hundred examples in under 10 minutes on an M3 Ultra, with seed-level replication and code released on GitHub.

reddit · r/MachineLearning · /u/Synthium- · May 29, 05:15

**Background**: Linear probes are simple classifiers trained on LLM hidden states to extract internal knowledge such as correctness signals. LoRA enables parameter-efficient fine-tuning by adapting low-rank matrices instead of full weights. Activation patching tests causality by swapping activations between runs and observing output changes.

<details><summary>References</summary>
<ul>
<li><a href="https://medium.com/@kailash.thiyagarajan/fine-tuning-large-language-models-with-lora-demystifying-efficient-adaptation-25fa0a389075">Fine - Tuning Large Language Models with LORA ... | Medium</a></li>
<li><a href="https://medium.com/@abhishekmishra_95058/using-explainable-ai-for-practical-problems-part-2-activation-patching-11bc32c9729a">Using Explainable AI for practical problems PART 2 — Activation ...</a></li>
<li><a href="https://arxiv.org/abs/2605.24614">Measuring the Depth of LLM Unlearning via Activation Patching</a></li>

</ul>
</details>

**Tags**: `#LLM calibration`, `#fine-tuning`, `#interpretability`, `#LoRA`, `#metacognition`

---

<a id="item-6"></a>
## [Pandoc Templates Site Offers Improved Document Conversion Options](https://pandoc-templates.org/) ⭐️ 6.0/10

The website pandoc-templates.org was highlighted on Hacker News, providing a collection of Pandoc templates for enhanced Markdown to document conversions such as Word and PDF. This resource helps Pandoc users streamline workflows for academic papers and publishing, though alternatives like Quarto are gaining attention for better experiences. Users report issues with PDF table layouts, Unicode font fallback, and page breaks in Pandoc, while noting colorful template designs and integration into GitHub Actions for multi-format output.

hackernews · ankitg12 · May 30, 09:56 · [Discussion](https://news.ycombinator.com/item?id=48334515)

**Background**: Pandoc is a free and open-source universal document converter created by John MacFarlane that transforms files between markup formats including Markdown, supporting extensions like footnotes, tables, and metadata.

<details><summary>References</summary>
<ul>
<li><a href="https://pandoc.org/">Pandoc - index</a></li>
<li><a href="https://en.wikipedia.org/wiki/Pandoc">Pandoc</a></li>

</ul>
</details>

**Discussion**: HN users praised Pandoc for academic and novel formatting workflows but shared frustrations with PDF generation quirks and highlighted Quarto as a superior alternative; some discovered new template ideas and related tools like Metanorma.

**Tags**: `#Pandoc`, `#Markdown`, `#Document Conversion`, `#Templates`, `#Productivity Tools`

---

<a id="item-7"></a>
## [Pope Leo's Encyclical Critiques Technological Messianism](https://www.economist.com/europe/2026/05/28/leos-first-encyclical-attacks-technological-messianism) ⭐️ 6.0/10

Pope Leo released his first encyclical, Magnifica Humanitas, which directly attacks technological messianism. The encyclical has sparked debate on technology governance, existential risks, and who should control emerging technologies including AI. The encyclical's Latin translation faces challenges in matching the English opening, and discussions reference Peter Thiel's comments on risks like AI and nuclear war.

hackernews · 1vuio0pswjnm7 · May 30, 10:30 · [Discussion](https://news.ycombinator.com/item?id=48334710)

**Discussion**: Commenters debate whether technologists, users, governments, or religious leaders should control technology and reference Peter Thiel's views on existential risks including AI.

**Tags**: `#technology ethics`, `#religion and tech`, `#existential risks`, `#AI philosophy`, `#papal encyclical`

---

<a id="item-8"></a>
## [Datasette 1.0a31 Adds Write Queries and Stored Query Saving](https://simonwillison.net/2026/May/29/datasette/#atom-everything) ⭐️ 6.0/10

Datasette 1.0a31 introduces support for executing write queries against databases and saving stored queries, renamed from canned queries, as both private and public options for users with appropriate permissions. This update enables more interactive data management within Datasette instances, allowing permitted users to perform inserts, updates, and deletes directly through the interface. The release includes a templated query interface with an animated demo showing insert operations, while blocking unauthorized actions like create table statements based on permissions.

rss · Simon Willison · May 29, 03:32

**Tags**: `#datasette`, `#sql`, `#database`, `#release`, `#data-tools`

---