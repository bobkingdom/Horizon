---
layout: default
title: "Horizon Summary: 2026-06-16 (EN)"
date: 2026-06-16
lang: en
---

> From 40 items, 13 important content pieces were selected

---

1. [Fake LinkedIn Recruiter Delivers npm Backdoor via GitHub Repo](#item-1) ⭐️ 8.0/10
2. [Iroh 1.0 Released: P2P Library Adds Custom Transport Support](#item-2) ⭐️ 8.0/10
3. [HN Users Share Local Qwen Setups Replacing Claude for Daily Coding](#item-3) ⭐️ 8.0/10
4. [Salesforce to Acquire Fin for $3.6B in AI Agent Push](#item-4) ⭐️ 8.0/10
5. [Why AI Hasn’t Replaced Software Engineers, and Won’t](#item-5) ⭐️ 8.0/10
6. [Banned Book Library Embedded in Modified Wi-Fi Smart Light Bulb](#item-6) ⭐️ 7.0/10
7. [Hetzner Announces Major Cloud Server Price Increases](#item-7) ⭐️ 7.0/10
8. [TimescaleDB Hypercore Columnar Compression Achieves Up to 98% Ratio](#item-8) ⭐️ 7.0/10
9. [Technical Analysis of Commander Keen Engine Scrolling](#item-9) ⭐️ 7.0/10
10. [LLMs Show Model-Specific Preferences for Certain Character Names](#item-10) ⭐️ 7.0/10
11. [Cleo: 2B Qwen Fine-Tune Replicates Analyst Text-to-SQL Behavior](#item-11) ⭐️ 7.0/10
12. [Developer Shares Self-Hosted Homelab AI Dev Platform with Forgejo](#item-12) ⭐️ 6.0/10
13. [Error-Driven Predictive Learning Proposed as Neocortical Framework](#item-13) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Fake LinkedIn Recruiter Delivers npm Backdoor via GitHub Repo](https://roman.pt/posts/linkedin-backdoor/) ⭐️ 8.0/10

A developer received a LinkedIn message from a fake recruiter at a crypto startup who sent a public GitHub repository containing a malicious npm package with a hidden backdoor. The attack demonstrates evolving social-engineering tactics that target developers through job offers, potentially compromising machines and the broader software supply chain. The backdoor is buried in commented-out tests, executes via the npm prepare script on install, and runs arbitrary commands from a remote server; similar attacks have been reported multiple times in recent months.

hackernews · lwhsiao · Jun 15, 20:00 · [Discussion](https://news.ycombinator.com/item?id=48546294)

<details><summary>References</summary>
<ul>
<li><a href="https://www.bleepingcomputer.com/news/security/somebody-tried-to-hide-a-backdoor-in-a-popular-javascript-npm-package/">Somebody Tried to Hide a Backdoor in a Popular JavaScript npm Package</a></li>

</ul>
</details>

**Discussion**: Users reported encountering nearly identical attacks, expressed frustration with slow GitHub and LinkedIn response times for malicious content, and called for better cybercrime reporting channels.

**Tags**: `#security`, `#backdoor`, `#social-engineering`, `#npm`, `#linkedin`

---

<a id="item-2"></a>
## [Iroh 1.0 Released: P2P Library Adds Custom Transport Support](https://www.iroh.computer/blog/v1) ⭐️ 8.0/10

Iroh 1.0 has been released as the stable major version of the Rust-based application-layer P2P networking library after over four years of development, introducing support for custom transports in addition to IPv4, IPv6, and relays. This release enables application developers to build decentralized peer connections using dial keys instead of fragile IP addresses, offering an alternative to embedding Tailscale at the network layer and affecting P2P and decentralized system projects. Iroh supports only IPv4, IPv6, and relay transports by default but now allows custom transport implementations to avoid codebase complexity; it emphasizes modular networking and observability through extensive simulations and tests.

hackernews · chadfowler · Jun 15, 15:13 · [Discussion](https://news.ycombinator.com/item?id=48542480)

**Background**: P2P networking often relies on direct connections that break when IP addresses change, leading libraries like Iroh to promote stable identifiers called dial keys; custom transports extend this to additional protocols without bloating the core library.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/n0-computer/iroh">GitHub - n0-computer/iroh: IP addresses break, dial keys instead ...</a></li>
<li><a href="https://byteiota.com/iroh-1-0-peer-to-peer-networking/">Iroh 1.0: Dial Keys, Not IPs — P2P Hits Stable | byteiota</a></li>

</ul>
</details>

**Discussion**: Commenters compared Iroh to Tailscale at the application layer, praised custom transport extensibility for protocols like WebRTC, and questioned the need for such abstractions when IPv6 and QUIC exist, with some noting decentralization trends.

**Tags**: `#p2p-networking`, `#software-release`, `#tailscale`, `#rust`, `#decentralized-systems`

---

<a id="item-3"></a>
## [HN Users Share Local Qwen Setups Replacing Claude for Daily Coding](https://news.ycombinator.com/item?id=48542100) ⭐️ 8.0/10

Hacker News thread users report fully replacing Claude and GPT subscriptions with local models such as Qwen3.6 35B and Qwen 3.6 27B for daily coding work, sharing concrete setups and performance metrics. Growing adoption of local models highlights demand for privacy-preserving and zero-cost alternatives to paid cloud AI services, influencing how developers choose coding assistants in the open-source ecosystem. Reported setups include Pi coding harness on Mac Studio with 128GB RAM running Qwen3.6 35B at high speed, dual RTX 3090 GPUs achieving 150 tok/s, and llama.cpp with Qwen3.6-35b on a single RTX 3090.

hackernews · cloudking · Jun 15, 14:46

**Background**: Local LLMs run inference directly on user hardware for offline operation. Token per second (tok/s) is a common metric for measuring generation speed during coding assistance. Qwen models are open-source LLMs frequently used in these local setups.

<details><summary>References</summary>
<ul>
<li><a href="https://benchlm.ai/llm-speed">LLM Speed & Latency Comparison — Tokens/sec & Response Latency (2026)</a></li>
<li><a href="https://huggingface.co/Qwen/Qwen3-0.6B">Qwen / Qwen 3-0.6B · Hugging Face</a></li>

</ul>
</details>

**Discussion**: Users express satisfaction with Qwen-based local setups for most tasks due to privacy and cost savings, while noting the models are less capable than Claude and some still occasionally fall back to cloud services.

**Tags**: `#local LLMs`, `#AI coding tools`, `#open-source models`, `#LLM performance`, `#Hacker News`

---

<a id="item-4"></a>
## [Salesforce to Acquire Fin for $3.6B in AI Agent Push](https://www.salesforce.com/news/press-releases/2026/06/15/salesforce-signs-definitive-agreement-to-acquire-fin/?bc=HL) ⭐️ 8.0/10

Salesforce signed a definitive agreement to acquire AI customer support company Fin, formerly Intercom, for $3.6 billion to strengthen its position in the AI agent space. The acquisition allows Salesforce to directly compete with high-valued AI support startups like Sierra and Decagon while integrating advanced agents into its CRM ecosystem. The deal follows Fin's recent rebrand and comes amid competition from Sierra valued at $15.8 billion and Decagon at $4.5 billion, with Salesforce CEO Marc Benioff aiming to prevent external AI agents from becoming CRM control points.

hackernews · colesantiago · Jun 15, 12:08 · [Discussion](https://news.ycombinator.com/item?id=48540126)

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/AI_agent">AI agent</a></li>

</ul>
</details>

**Discussion**: Community sentiment is mixed, with some praising well-executed AI agents for superior support experiences while others question the long-term viability of dedicated helpdesk tools and criticize AI for fabricating responses or lacking human value.

**Tags**: `#Salesforce`, `#AI agents`, `#Acquisition`, `#Customer support`, `#M&A`

---

<a id="item-5"></a>
## [Why AI Hasn’t Replaced Software Engineers, and Won’t](https://simonwillison.net/2026/Jun/14/why-ai-hasnt-replaced-software-engineers/#atom-everything) ⭐️ 8.0/10

Arvind Narayanan and Sayash Kapoor argue AI will not trigger mass layoffs in software engineering, pointing to New York WARN Act data from March 2025 showing over 160 filings with zero AI-related layoffs reported. The analysis counters widespread AI job-loss hype with empirical evidence from a low-regulation field, implying broader workforce resilience and shaping AI ethics and employment policy debates. Key bottlenecks identified are deciding what to build, verifying deliverables with accountability, and deep human understanding of codebase, business, and context rather than code writing itself.

rss · Simon Willison · Jun 14, 23:54

**Tags**: `#AI`, `#software engineering`, `#job displacement`, `#employment`, `#AI ethics`

---

<a id="item-6"></a>
## [Banned Book Library Embedded in Modified Wi-Fi Smart Light Bulb](https://www.richardosgood.com/posts/banned-book-library/) ⭐️ 7.0/10

A developer created a project embedding a collection of banned books into a modified Wi-Fi smart light bulb that serves the files over its own wireless access point. This demonstrates creative applications of IoT devices for digital libraries and censorship resistance, potentially inspiring similar discreet projects amid growing content restrictions. The bulb runs modified firmware hosting an embedded web server to deliver EPUB files locally, with the device designed to blend in as ordinary lighting hardware.

hackernews · sohkamyung · Jun 15, 22:37 · [Discussion](https://news.ycombinator.com/item?id=48547985)

**Discussion**: Commenters praised the project's creativity and linked it to prior efforts like PirateBox and LibraryBox, while one noted potential ease of detection by power cycling and another highlighted mesh network extensions via Meshtastic.

**Tags**: `#DIY hardware`, `#IoT hacking`, `#digital libraries`, `#censorship resistance`, `#embedded systems`

---

<a id="item-7"></a>
## [Hetzner Announces Major Cloud Server Price Increases](https://docs.hetzner.com/general/infrastructure-and-availability/price-adjustment/#cloud-servers) ⭐️ 7.0/10

Hetzner has announced price adjustments for cloud servers linked to rising hardware costs, with documentation showing new rates and archive links for old prices. The increases affect cloud infrastructure users and reflect broader AI-driven hardware demand pressures on providers, potentially shifting market dynamics and costs for developers and businesses. Reports mention jumps up to 3x in some cases, far exceeding typical 25-50% rises, with new prices at docs.hetzner.com and old prices via web archive.

hackernews · tuhtah · Jun 15, 13:19 · [Discussion](https://news.ycombinator.com/item?id=48540844)

**Discussion**: HN commenters link the changes to AI boom effects like hardware scarcity and inequality, compare it to historical innovations, and question the unprecedented scale of the price jumps.

**Tags**: `#cloud infrastructure`, `#pricing`, `#Hetzner`, `#AI hardware costs`, `#Hacker News`

---

<a id="item-8"></a>
## [TimescaleDB Hypercore Columnar Compression Achieves Up to 98% Ratio](https://roszigit.com/en/blog/timescaledb-compression-hypercore) ⭐️ 7.0/10

The blog post details TimescaleDB's Hypercore engine converting row-based chunks into columnar format using segmentby and orderby parameters along with algorithms such as delta encoding, delta-of-delta, Gorilla XOR, and run-length encoding to reach up to 98% compression ratios in PostgreSQL. This approach significantly reduces storage needs for time-series workloads in PostgreSQL while aiming to preserve query performance, directly benefiting IoT, analytics, and monitoring applications that generate large volumes of timestamped data. Compression applies type-specific encoders independently per column followed by LZ as a final pass; custom indexes incorporate segmentby and orderby settings, and the hybrid row-columnar design allows selective decompression during queries.

hackernews · lkanwoqwp · Jun 15, 17:29 · [Discussion](https://news.ycombinator.com/item?id=48544451)

**Background**: TimescaleDB is a PostgreSQL extension designed for time-series data that organizes data into chunks and supports native compression to handle high-ingest workloads efficiently.

<details><summary>References</summary>
<ul>
<li><a href="https://roszigit.com/en/blog/timescaledb-compression-hypercore">TimescaleDB Compression: Hypercore and Columnar Storage with up to 98% Ratio in PostgreSQL</a></li>
<li><a href="https://github.com/timescale/docs.timescale.com-content/blob/master/using-timescaledb/compression.md">docs.timescale.com-content/using-timescaledb/compression.md at master · timescale/docs.timescale.com-content</a></li>

</ul>
</details>

**Discussion**: Commenters emphasize that compression must improve filter rejection or scan speed rather than merely trading IO for CPU; they mention alternatives like DeltaX on ClickBench, historical swinging-door methods for IoT, and note that Gorilla encoding already used delta-of-delta techniques similar to those in TimescaleDB.

**Tags**: `#TimescaleDB`, `#PostgreSQL`, `#time-series databases`, `#data compression`, `#columnar storage`

---

<a id="item-9"></a>
## [Technical Analysis of Commander Keen Engine Scrolling](https://forgottenbytes.net/commander_keen.html) ⭐️ 7.0/10

A technical write-up analyzes the Commander Keen game engine developed by id Software, detailing its smooth scrolling innovations via adaptive tile refresh on EGA hardware. The analysis highlights groundbreaking techniques that enabled side-scrolling games on early PCs, influencing id Software's later work and the broader evolution of PC gaming. Levels use 16x16 tiles tracked by unique IDs; the engine compares IDs to redraw only changed areas, leveraging EGA features for hardware scrolling instead of full software redraws.

hackernews · mfiguiere · Jun 15, 17:52 · [Discussion](https://news.ycombinator.com/item?id=48544781)

**Background**: Commander Keen is a series of side-scrolling platform games. Adaptive tile refresh is a technique that minimizes redraws by tracking moved tiles and using EGA hardware capabilities for efficient scrolling on limited 1990s PC hardware.

<details><summary>References</summary>
<ul>
<li><a href="https://fabiensanglard.net/ega/">Commander Keen's Adaptive Tile Refresh</a></li>
<li><a href="https://en.wikipedia.org/wiki/Adaptive_tile_refresh">Adaptive tile refresh</a></li>

</ul>
</details>

**Discussion**: Commenters recommend the book Masters of Doom for id Software history, suggest comparisons with SNES hardware efficiency, note similarities to Fabien Sanglard's writing style, and mention related resources like Cosmodoc for Cosmo’s Cosmic Adventure.

**Tags**: `#game engines`, `#retro computing`, `#id Software`, `#historical analysis`, `#Commander Keen`

---

<a id="item-10"></a>
## [LLMs Show Model-Specific Preferences for Certain Character Names](https://www.reddit.com/r/MachineLearning/comments/1u6mn3q/ai_language_models_have_favorite_names_and_we/) ⭐️ 7.0/10

LLMs exhibit strong model- and version-specific priors over character names that appear consistently in generated content, such as the correlated ensemble including Elena Vasquez and Marcus Chen often produced by Claude. This finding emerged as a side discovery during development of the Contrastive Decoding Diffing (CDD) method and is detailed in arXiv preprint 2606.02184. The discovery highlights systematic biases and hallucination patterns unique to individual models, which could improve detection of AI-generated text and affect reliability assessments across web content and research publications. Names travel as correlated ensembles across dozens of websites in roles such as volcano experts, podcast hosts, and authors of fabricated papers, with a third name later identified in the same ensemble and visual examples shown via AI-generated stock photos.

reddit · r/MachineLearning · /u/CebulkaZapiekana · Jun 15, 17:07

<details><summary>References</summary>
<ul>
<li><a href="https://www.emergentmind.com/papers/2605.25902">CDD: Verbatim Content Recovery via Diffing - emergentmind.com</a></li>

</ul>
</details>

**Tags**: `#LLMs`, `#AI biases`, `#Model analysis`, `#Hallucinations`, `#Research preprint`

---

<a id="item-11"></a>
## [Cleo: 2B Qwen Fine-Tune Replicates Analyst Text-to-SQL Behavior](https://www.reddit.com/r/MachineLearning/comments/1u6udpb/cleo_trying_to_fit_full_analyst_behavior_in_a_2b/) ⭐️ 7.0/10

Cleo is a 2B-parameter fine-tune of Qwen3.5-2B-Base that replicates full analyst behavior for text-to-SQL through a co-designed structured harness for unified training and inference. This demonstrates that small models can handle complex text-to-SQL tasks when training and inference use the same harness, enabling efficient deployment in resource-constrained industrial settings. Key capabilities include training on gather-repair-answer contracts, searching queries with live execution feedback, and co-designing the SQL safety layer with dialect handling and timeouts; the full harness, model, and datasets are open-sourced on GitHub and Hugging Face.

reddit · r/MachineLearning · /u/Dreeseaw · Jun 15, 21:43

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/html/2508.05387v3">Echo: Decoupling Inference and Training for Large-Scale RL Alignment on ...</a></li>

</ul>
</details>

**Tags**: `#text-to-SQL`, `#small LLMs`, `#fine-tuning`, `#open-source`, `#efficient ML`

---

<a id="item-12"></a>
## [Developer Shares Self-Hosted Homelab AI Dev Platform with Forgejo](https://rsgm.dev/post/ai-dev-platform/) ⭐️ 6.0/10

A developer published details of their personal homelab setup that integrates AI coding agents with Forgejo to enable automated development workflows and issue-driven code generation. This reflects rising interest in private, self-hosted AI tooling that combines version control with autonomous agents, potentially reducing reliance on cloud services for development teams. The setup uses Forgejo for repository hosting and actions, allowing AI agents to respond to commands in issues and generate pull requests; similar integrations with tools like opencode are discussed in comments.

hackernews · rsgm · Jun 15, 15:09 · [Discussion](https://news.ycombinator.com/item?id=48542433)

**Background**: Forgejo is a lightweight, self-hosted software forge written in Go that provides Git repository management, issue tracking, and continuous integration features for developers who prefer on-premises solutions.

<details><summary>References</summary>
<ul>
<li><a href="https://forgejo.org/">Forgejo – Beyond coding. We forge .</a></li>

</ul>
</details>

**Discussion**: Commenters describe similar projects, including running AI agents inside Forgejo action runners to create PRs from issue commands, challenges with context management across multiple rounds, and alternative stacks using n8n, Argo, and k3s for automated workflows.

**Tags**: `#homelab`, `#self-hosting`, `#AI agents`, `#devops`, `#Forgejo`

---

<a id="item-13"></a>
## [Error-Driven Predictive Learning Proposed as Neocortical Framework](https://www.reddit.com/r/MachineLearning/comments/1u6x8al/how_the_brains_learn_r/) ⭐️ 6.0/10

The paper proposes error-driven predictive learning via temporal derivatives as the only framework meeting computational, algorithmic, and implementational criteria for neocortical learning, implemented in the Axon spiking neuron simulator. This offers a biologically plausible alternative to back propagation that could substantially improve training times and lead to more scalable learning systems inspired by the brain. The framework relies on corticothalamic circuits and competitive kinase synaptic plasticity induction mechanisms, with demonstrations across cognitively motivated tasks in the Axon simulator using spiking neurons.

reddit · r/MachineLearning · /u/Terminator857 · Jun 15, 23:39

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Synaptic_plasticity">Synaptic plasticity - Wikipedia</a></li>

</ul>
</details>

**Discussion**: The post notes that such approaches could surpass back propagation and improve training efficiency substantially.

**Tags**: `#neuroscience`, `#machine learning`, `#biologically plausible learning`, `#predictive coding`, `#spiking neural networks`

---