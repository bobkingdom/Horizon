---
layout: default
title: "Horizon Summary: 2026-09-11 (EN)"
date: 2026-09-11
lang: en
---

> From 28 items, 16 important content pieces were selected

---

1. [Shopify Moves Mobile Apps from React Native Back to Swift and Kotlin](#item-1) ⭐️ 8.0/10
2. [OpenAI Releases Agents API for Customizable AI Agents](#item-2) ⭐️ 8.0/10
3. [Forgejo 16.0.4 Patches Critical RCE in Template Expansion](#item-3) ⭐️ 8.0/10
4. [Rust Elevated to Tier-1 Language Status at Microsoft](#item-4) ⭐️ 8.0/10
5. [trynix.dev Runs Any Nix Package in Browser via qemu-wasm VM](#item-5) ⭐️ 8.0/10
6. [Questions on Trusting OpenAI with Unpublished Math Research](#item-6) ⭐️ 7.0/10
7. [WebGPU Technique Lets Untrusted Sites Freeze Macs](#item-7) ⭐️ 7.0/10
8. [Google Signs 22-Year Deal for Half of Finnish Nuclear Plant Output](#item-8) ⭐️ 7.0/10
9. [Apple Announces iPhone Duo Dual-Screen Foldable Device](#item-9) ⭐️ 7.0/10
10. [Calif Research Claims AI-Built Zero-Click WeChat Worm](#item-10) ⭐️ 7.0/10
11. [348M Model Beats GPT-3 on Arithmetic via Column-by-Column Training](#item-11) ⭐️ 7.0/10
12. [Fly Connectome Fails Pong Task, Exposing neuPrint Bugs and Circuit Gaps](#item-12) ⭐️ 7.0/10
13. [NASA Decorrelation Stretch Technique Reveals Hidden Ancient Rock Art](#item-13) ⭐️ 6.0/10
14. [PlanetScale Launches Neki Sharded Postgres Solution](#item-14) ⭐️ 6.0/10
15. [Stanford Professor Launches Volunteer-Driven Probability for AI Class](#item-15) ⭐️ 6.0/10
16. [Analysis of Sante Model's 83.83 DiagnosisArena-MCQ Score Limitations](#item-16) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Shopify Moves Mobile Apps from React Native Back to Swift and Kotlin](https://shopify.engineering/back-to-native) ⭐️ 8.0/10

Shopify is migrating its mobile apps from React Native back to native Swift and Kotlin development, with AI tools assisting the transition as detailed in their engineering blog post. This reversal by a major company highlights shifting priorities in mobile development and could influence industry trends toward native implementations over cross-platform frameworks. The migration leverages AI coding assistance for inventorying screens and generating native code, though full polish still requires manual effort, as noted in related developer experiences.

hackernews · fnthawar2 · Sep 10, 14:09 · [Discussion](https://news.ycombinator.com/item?id=49643982)

**Discussion**: Developers report similar successful migrations using AI tools like Codex or Claude, with some feeling validated in preferring native code; others note that AI mainly speeds up but does not eliminate the need for prior planning and manual work.

**Tags**: `#mobile development`, `#React Native`, `#Shopify`, `#native apps`, `#cross-platform frameworks`

---

<a id="item-2"></a>
## [OpenAI Releases Agents API for Customizable AI Agents](https://developers.openai.com/api/docs/guides/agents-api/overview) ⭐️ 8.0/10

OpenAI has released an Agents API for building customizable AI agents that include tool integration and persistent state management. This provides a managed service that simplifies agent development and state handling, potentially speeding up adoption across developer tools and applications while sparking debates on vendor lock-in. The API allows optional self-hosting of sandboxes to reduce dependency, and focuses on plugging in external tools while managing persistent state across sessions.

hackernews · aquir · Sep 10, 19:43 · [Discussion](https://news.ycombinator.com/item?id=49649213)

<details><summary>References</summary>
<ul>
<li><a href="https://dev.to/icentric/building-persistent-ai-agents-a-devs-guide-to-state-management-and-long-running-workflows-42a0">Building Persistent AI Agents: A Dev's Guide to State Management and Long-Running Workflows - DEV Community</a></li>
<li><a href="https://composio.dev/content/ai-agent-integration-platforms">Best AI agent integration platforms (2026): comparison for developers | Composio</a></li>

</ul>
</details>

**Discussion**: Commenters discuss the evolving abstractions for agent services, note self-hosting options to avoid lock-in, observe the blurring line between raw LLMs and agent harnesses, and express concerns over vendor dependency versus features like reasoning tokens.

**Tags**: `#OpenAI`, `#AI Agents`, `#API`, `#LLMs`, `#Developer Tools`

---

<a id="item-3"></a>
## [Forgejo 16.0.4 Patches Critical RCE in Template Expansion](https://codeberg.org/forgejo/forgejo/src/branch/forgejo/release-notes-published/16.0.4.md) ⭐️ 8.0/10

Forgejo 16.0.4 patches a critical remote code execution vulnerability in template expansion during repository initialization affecting versions <=16.0.3. This vulnerability could allow attackers to execute arbitrary code on self-hosted Forgejo instances, impacting developers and organizations that rely on it for private Git hosting and requiring immediate updates. The flaw occurs when generating a new repository from a template: Forgejo clones the template, removes the .git folder, performs variable expansion on files listed in .forgejo/template, then initializes a new Git repository.

hackernews · weierstass · Sep 10, 15:57 · [Discussion](https://news.ycombinator.com/item?id=49645907)

**Background**: Forgejo is an open-source self-hosted software forge written in Go that provides Git repository hosting along with issue tracking, code review and related collaboration features.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Forgejo">Forgejo</a></li>
<li><a href="https://forgejo.org/">Forgejo – Beyond coding. We forge .</a></li>

</ul>
</details>

**Discussion**: Community members pointed to PR 14301 as the fix, noted Gitea is protected against the issues, and discussed the importance of reporting security incidents without shaming projects.

**Tags**: `#security`, `#RCE`, `#Forgejo`, `#vulnerability`, `#git`

---

<a id="item-4"></a>
## [Rust Elevated to Tier-1 Language Status at Microsoft](https://rustfoundation.org/media/guest-post-rust-is-tier-1-language-at-microsoft/) ⭐️ 8.0/10

Microsoft has officially designated Rust as a tier-1 language for internal development, placing it on equal footing with C++, C#, and TypeScript in terms of engineering support and tooling. This signals major industry validation for Rust in systems programming and supports Microsoft's ambitious plans to modernize large codebases, affecting developers working on Windows and enterprise software. Notable changes include replacing the LLVM backend with MSVC's backend for better integration, alongside ongoing work on C++ interop and automated migration tools targeting one billion lines of code by 2030.

hackernews · mmastrac · Sep 10, 13:39 · [Discussion](https://news.ycombinator.com/item?id=49643546)

**Background**: Tier-1 status at Microsoft means the language receives the highest level of internal tooling, debugging, and library support for production use across core projects.

<details><summary>References</summary>
<ul>
<li><a href="https://rustfoundation.org/media/guest-post-rust-is-tier-1-language-at-microsoft/">Guest Post: Rust Is Tier - 1 Language at Microsoft</a></li>
<li><a href="https://news.ycombinator.com/item?id=49643546">Rust Is Tier - 1 Language at Microsoft | Hacker News</a></li>

</ul>
</details>

**Discussion**: Commenters view the announcement as confirmation of Rust's maturity and a shift toward ecosystem integration rather than full rewrites, with discussion on MSVC integration, interop with C++ and Python, and ambitious automated migration goals.

**Tags**: `#Rust`, `#Microsoft`, `#Programming Languages`, `#Systems Programming`, `#Software Adoption`

---

<a id="item-5"></a>
## [trynix.dev Runs Any Nix Package in Browser via qemu-wasm VM](https://simonwillison.net/2026/Sep/10/trynix/) ⭐️ 8.0/10

trynix.dev launches an x86_64 Linux VM entirely in the browser using qemu-wasm, allowing any Nix package from the past 13 years to be booted interactively via URL, such as python3@3.6.2 from 2017. It also includes a GitHub Action called trynix-preview that lets users boot and review a pull request's build directly in the browser. This enables serverless testing of historical and reproducible software packages, benefiting developers who need to inspect old builds or review pull requests without infrastructure. It combines Nix's declarative packaging with WebAssembly to advance browser-based execution and code review workflows. Packages are URL-addressable and run inside a full Linux VM powered by the ktock/qemu-wasm port; the demo supports interactive shells but requires loading the package into the browser-based VM. Farid Zakaria describes it as his magnum opus of Nix work.

rss · Simon Willison · Sep 10, 23:44

**Background**: Nix is a package manager that installs each package into a unique directory for reproducibility. qemu-wasm is an experimental port of the QEMU emulator to WebAssembly, enabling full system emulation inside browsers.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/ktock/qemu-wasm">GitHub - ktock/qemu-wasm: QEMU on browser · GitHub</a></li>
<li><a href="https://en.wikipedia.org/wiki/Nix_(package_manager)">Nix (package manager) - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#Nix`, `#WebAssembly`, `#QEMU`, `#Browser VM`, `#Package Management`

---

<a id="item-6"></a>
## [Questions on Trusting OpenAI with Unpublished Math Research](https://mathstodon.xyz/@andreasthom/117240535270608201) ⭐️ 7.0/10

A Hacker News discussion examines concerns that OpenAI may incorporate unpublished mathematical research from user chats into model training without attribution or consent. This raises ethical issues around data usage in AI development and could affect researchers who share novel ideas with large language models. Comments note analogies to human collaborators, the possibility that pretraining improves model intuition from chats, and challenges in verifying whether specific data was used during RL on math problems.

hackernews · pred_ · Sep 10, 06:49 · [Discussion](https://news.ycombinator.com/item?id=49639408)

**Background**: Large language models undergo pretraining on extensive datasets and further RL to enhance performance on tasks like mathematics. User chats with AI systems can contain original research ideas shared during collaboration.

**Discussion**: Participants debate whether OpenAI's use of chats resembles unethical collaboration, note that both memorization and independent discovery can occur, and question the feasibility of quick verification of data usage settings.

**Tags**: `#AI ethics`, `#OpenAI`, `#LLM training`, `#data privacy`, `#academic integrity`

---

<a id="item-7"></a>
## [WebGPU Technique Lets Untrusted Sites Freeze Macs](https://auberon.xyz/blog/posts/deathray/) ⭐️ 7.0/10

A blog post titled The Deathray describes a simple untrusted webpage technique, likely using WebGPU, that freezes a Mac running Safari. The discovery expands concerns over browser hardware attack surfaces as vendors expose GPU access, affecting macOS users and future WebGPU adoption. The method fails to create a WebGPU context provider and configure GPUCanvasContext, causing persistent freezes that reopen on restart in Safari.

hackernews · auberonedu · Sep 10, 19:34 · [Discussion](https://news.ycombinator.com/item?id=49649124)

**Background**: WebGPU is a new web standard providing JavaScript access to the system's GPU for high-performance graphics and computations, intended to replace WebGL and supported in Safari since 2025.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/WebGPU">WebGPU</a></li>
<li><a href="https://developer.mozilla.org/en-US/docs/Web/API/WebGPU_API">WebGPU API - Web APIs | MDN</a></li>

</ul>
</details>

**Discussion**: Commenters recall historical browser exploits, caution against expanding hardware attack surfaces especially by Google, and note recovery difficulties on macOS including apps reopening the page after restart.

**Tags**: `#web-security`, `#browser-exploits`, `#macos`, `#webgpu`, `#hackernews`

---

<a id="item-8"></a>
## [Google Signs 22-Year Deal for Half of Finnish Nuclear Plant Output](https://www.bbc.com/news/articles/c8r6y4me2g6o) ⭐️ 7.0/10

Google has signed a 22-year contract with Finnish utility Fortum to purchase up to 50% of the electricity output from the Loviisa nuclear power plant to power its data centers. This deal highlights big tech companies securing dedicated nuclear power sources to meet the growing energy demands of AI data centers while supporting low-carbon electricity goals. The Loviisa plant has a capacity of about 1000 MW, and Finland's cool climate and low-emission grid make it attractive for data centers, though the utility limits any single buyer to maintain customer diversity.

hackernews · lukaspetersson · Sep 11, 00:42 · [Discussion](https://news.ycombinator.com/item?id=49652105)

**Discussion**: Commenters praised Google's move for supporting low-emission electricity in Finland and noted the plant's 1000 MW size; some discussed how utilities diversify customers and that AI infrastructure costs are borne by the companies rather than taxpayers.

**Tags**: `#Google`, `#Nuclear Energy`, `#Data Centers`, `#AI Infrastructure`, `#Sustainability`

---

<a id="item-9"></a>
## [Apple Announces iPhone Duo Dual-Screen Foldable Device](https://www.apple.com/iphone-duo/) ⭐️ 7.0/10

Apple announced the iPhone Duo, a dual-screen foldable device analyzed in a Hacker News thread scoring 1417 with 2450 comments. The device could push developers to optimize apps for foldables and place Apple in the expanding foldable market, affecting users and competitors. Notable features include Apple Pencil support for quick whiteboarding and potential fixes for hinge and crease issues, with a possible price near $2000.

hackernews · thecosmicfrog · Sep 9, 18:15 · [Discussion](https://news.ycombinator.com/item?id=49630931)

**Discussion**: Users show mixed reactions with excitement for Pencil support and hinge improvements but concerns over the $2000 price and first-generation risks; some prefer smaller phones while others welcome better foldable app development.

**Tags**: `#Apple`, `#iPhone`, `#foldables`, `#mobile hardware`, `#product announcement`

---

<a id="item-10"></a>
## [Calif Research Claims AI-Built Zero-Click WeChat Worm](https://simonwillison.net/2026/Sep/10/calif-research/) ⭐️ 7.0/10

Calif Research released a demo of WeWorm, a zero-click worm that spreads through WeChat voice calls on iOS and Android without any user interaction. The team used AI to discover an RCE bug and develop the exploit in about two days, then built the worm in one additional week. This demonstrates how AI can dramatically shorten the time required to create sophisticated zero-click exploits and worms, potentially lowering the barrier for attackers and affecting millions of WeChat users across platforms. The exploit succeeds even if the victim does not answer the call and hears nothing; Tencent has since mitigated the vulnerability. The project highlights AI handling most technical work while humans provide targeting and safety judgment.

rss · Simon Willison · Sep 10, 00:56

**Background**: A zero-click exploit targets vulnerabilities in apps like WeChat to execute code without user action. Remote code execution (RCE) allows attackers to run arbitrary commands on a victim's device after successful exploitation.

<details><summary>References</summary>
<ul>
<li><a href="https://cybersecuritynews.com/weworm-first-0-click-worm/">WeWorm - First 0-Click Worm Spreading Through WeChat Calls ...</a></li>
<li><a href="https://www.cyberkendra.com/2026/09/weworm-zero-click-wechat-worm-ios-android.html">WeWorm: Zero-Click WeChat Worm Hijacks iOS and Android</a></li>

</ul>
</details>

**Tags**: `#ai-security`, `#zero-click-exploit`, `#malware`, `#ai-research`, `#wechat`

---

<a id="item-11"></a>
## [348M Model Beats GPT-3 on Arithmetic via Column-by-Column Training](https://www.reddit.com/r/MachineLearning/comments/1wc7hmu/i_trained_a_348m_model_trained_from_scratch_on/) ⭐️ 7.0/10

A 348M parameter model trained from scratch on 22.7B tokens and fine-tuned for math achieves 99.4% average accuracy on nine GPT-3 arithmetic subtasks by learning explicit column operations with carries and borrows. This demonstrates that small models can outperform much larger ones on specific reasoning tasks when trained to show explicit step-by-step work rather than guessing answers directly. Extending place-value vocabulary from 6 to 19 names raised clean performance from 8 to 14 digits; the model generalizes to unseen place names like millions, but struggles with word problems at 4-16.5% and cannot perform division.

reddit · r/MachineLearning · /u/nkthebass · Sep 10, 03:28

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/datasets/shreeman-iyer/llm_arithmetic_training">shreeman-iyer/llm_ arithmetic _ training · Datasets at Hugging Face</a></li>

</ul>
</details>

**Tags**: `#machine learning`, `#LLMs`, `#arithmetic reasoning`, `#model training`, `#benchmarks`

---

<a id="item-12"></a>
## [Fly Connectome Fails Pong Task, Exposing neuPrint Bugs and Circuit Gaps](https://www.reddit.com/r/MachineLearning/comments/1wc67ci/i_tried_to_make_a_real_fly_connectome_learn_to/) ⭐️ 7.0/10

A Reddit post details an unsuccessful attempt to train a subgraph from the MaleCNS v1.0 fly connectome to play Pong using dopamine-style plasticity rules. Failure analysis uncovered a neuPrint regex bug, missing photoreceptor pathways, and zero-synapse motor neurons, while similar issues appeared in viral Doom and Minecraft projects. The case study demonstrates that rigorous validation of biological connectome models in simple tasks like Pong can expose hidden reconstruction errors and flawed assumptions before scaling to complex simulations. It affects researchers using MaleCNS v1.0 and neuPrint for computational neuroscience and reinforcement learning experiments. Auditing showed identical results with learning on or off due to motor neurons lacking sensory input; a revised courtship pathway produced divergence but only via global quieting rather than skill acquisition. The post links to a Medium article with full connectivity numbers and project comparisons.

reddit · r/MachineLearning · /u/oPeraza2007 · Sep 10, 02:28

**Background**: MaleCNS v1.0 provides the first complete EM reconstruction of the male Drosophila central nervous system with 166k neurons. neuPrint is an open tool that stores connectome data in a Neo4j graph database for querying synaptic connections.

<details><summary>References</summary>
<ul>
<li><a href="https://male-cns.janelia.org/">Male CNS Connectome - MaleCNS connectome</a></li>
<li><a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC9350508/">neuPrint : An open access tool for EM connectomics - PMC</a></li>

</ul>
</details>

**Tags**: `#connectomics`, `#fly brain`, `#reinforcement learning`, `#computational neuroscience`, `#Pong`

---

<a id="item-13"></a>
## [NASA Decorrelation Stretch Technique Reveals Hidden Ancient Rock Art](https://spinoff.nasa.gov/Manipulating_Satellite_Photos_Now_Reveals_Ancient_Images) ⭐️ 6.0/10

NASA's decorrelation stretch image processing method, originally developed for satellite photos, is now applied through the DStretch plugin to enhance and reveal faded ancient rock art images that were previously invisible. This NASA spinoff demonstrates how remote sensing tools can advance archaeology by uncovering cultural heritage details without physical intervention, benefiting researchers studying prehistoric sites worldwide. The technique removes inter-channel correlation in color images to stretch differences, with the DStretch plugin available since around 2005; users can replicate similar results in GIMP using LAB decomposition and contrast adjustments.

hackernews · gumby · Sep 10, 15:29 · [Discussion](https://news.ycombinator.com/item?id=49645437)

**Background**: Decorrelation stretch enhances color separation in multispectral images by reducing band-to-band correlation, a method documented in resources like the Algorithm Theoretical Basis Document from dstretch.com.

<details><summary>References</summary>
<ul>
<li><a href="https://www.dstretch.com/DecorrelationStretch.pdf">Algorithm Theoretical Basis Document for Decorrelation Stretch</a></li>

</ul>
</details>

**Discussion**: Commenters noted the technique's roots in remote sensing education and shared a GIMP workflow for similar results; some observed it has been available since 2005 and is not entirely new, while appreciating its practical success in archaeology.

**Tags**: `#image processing`, `#NASA spinoffs`, `#remote sensing`, `#archaeology`, `#false color imaging`

---

<a id="item-14"></a>
## [PlanetScale Launches Neki Sharded Postgres Solution](https://planetscale.com/blog/introducing-neki) ⭐️ 6.0/10

PlanetScale announced Neki, a sharded Postgres solution that scales real Postgres to hundreds of millions of QPS and petabytes of data with zero-downtime resharding. Neki brings horizontal scaling expertise from Vitess to Postgres users, potentially impacting teams running large-scale Postgres workloads who need better sharding without application changes. Neki remains closed-source and is being developed with design partners; community concerns focus on its consistency model under CAP theorem and lack of open-source availability compared to Multigres.

hackernews · simon_weber · Sep 10, 15:43 · [Discussion](https://news.ycombinator.com/item?id=49645686)

**Background**: Sharding horizontally partitions data across servers to handle larger scale. Vitess provides this for MySQL at companies like Slack and GitHub, while Multigres adapts similar ideas for Postgres.

<details><summary>References</summary>
<ul>
<li><a href="https://neki.dev/">Neki | Sharded Postgres by PlanetScale</a></li>
<li><a href="https://planetscale.com/docs/postgres/sharding">Horizontal sharding for Postgres - PlanetScale</a></li>
<li><a href="https://github.com/multigres/multigres">GitHub - multigres/multigres: Vitess for Postgres · GitHub</a></li>

</ul>
</details>

**Discussion**: Commenters criticized the launch post for lacking clear descriptions of Neki, raised concerns about eventual consistency suitability, and questioned the closed-source decision given PlanetScale's Vitess roots and Multigres competition.

**Tags**: `#postgres`, `#sharding`, `#distributed-databases`, `#planetscale`, `#database`

---

<a id="item-15"></a>
## [Stanford Professor Launches Volunteer-Driven Probability for AI Class](https://www.reddit.com/r/MachineLearning/comments/1wbf3ox/teach_ml_community_service_project_from_stanford_n/) ⭐️ 6.0/10

Stanford AI professor Chris Piech launched the free Probability for AI class at pai.stanford.edu, starting October 9 with applications due by end of September. The volunteer-driven program aims for a 1:10 teacher-student ratio and includes custom tools such as an AI text detection app built after one hour of learning. This initiative expands accessible AI education through a scalable volunteer model funded by an alum, potentially reaching thousands of students with light math backgrounds. It could influence broader community-driven teaching efforts in machine learning. Over 1,000 people have already applied to teach, and volunteers receive training via teachable agents plus Stanford teaching insights. The course remains entirely free with servers and tools covered by funding.

reddit · r/MachineLearning · /u/chrispiech · Sep 9, 07:54

**Tags**: `#Machine Learning`, `#Education`, `#Stanford`, `#Community Service`, `#AI Teaching`

---

<a id="item-16"></a>
## [Analysis of Sante Model's 83.83 DiagnosisArena-MCQ Score Limitations](https://www.reddit.com/r/MachineLearning/comments/1wbkxsa/what_santes_8383_on_diagnosisarenamcq_actually/) ⭐️ 6.0/10

A Reddit post analyzes the Sante model's 83.83 score on DiagnosisArena-MCQ for Ling-3.0-flash-Sante, noting it only measures multiple-choice diagnosis selection from four options given case information. This clarification matters because real clinical applications often require models to generate open-ended differentials rather than select from supplied options, affecting how medical LLMs are evaluated and deployed. Sante also reports 53.88 on MedXpertQA-Text and 45.73 on HealthBench Professional, an open-ended rubric-graded benchmark covering care consultation and documentation; the MCQ score does not assess generating differentials or choosing next investigations.

reddit · r/MachineLearning · /u/Expert_Coffee_203 · Sep 9, 13:01

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/html/2505.14107v2">DiagnosisArena: Benchmarking Diagnostic Reasoningfor Large Language Models</a></li>
<li><a href="https://medxpertqa.github.io/">MedXpertQA</a></li>

</ul>
</details>

**Tags**: `#AI benchmarks`, `#Medical AI`, `#LLM evaluation`, `#Model limitations`, `#Clinical reasoning`

---