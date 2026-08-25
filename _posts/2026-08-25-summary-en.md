---
layout: default
title: "Horizon Summary: 2026-08-25 (EN)"
date: 2026-08-25
lang: en
---

> From 35 items, 11 important content pieces were selected

---

1. [MS Paint Embeds Invisible GUID Watermarks in AI Images](#item-1) ⭐️ 8.0/10
2. [San Francisco Built as Interactive 3D Web Game from Apple Maps](#item-2) ⭐️ 7.0/10
3. [Jabber/XMPP Marks 25 Years of Digital Independence](#item-3) ⭐️ 7.0/10
4. [SeL4 Security Proofs Now Complete for AArch64](#item-4) ⭐️ 7.0/10
5. [Linux Pattern Turns SQLite Database into Executable Binary](#item-5) ⭐️ 7.0/10
6. [Unbounded Labs Releases Bartholomew, 2.82B Vintage LLM on Pre-1931 Text](#item-6) ⭐️ 7.0/10
7. [LLMs Generate Inherently Programmable 3D Objects as Spatial Software](#item-7) ⭐️ 7.0/10
8. [Delay-Corrected Bellman Operator for Constrained RL Under Stochastic Delays](#item-8) ⭐️ 7.0/10
9. [Xiaomi New ARM CPU Matches Apple Single-Thread Performance](#item-9) ⭐️ 6.0/10
10. [IP Shipyard to End Centralized IPFS Support by September 2026](#item-10) ⭐️ 6.0/10
11. [Anthropic Hits $65B Revenue as Premium Model Struggles](#item-11) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [MS Paint Embeds Invisible GUID Watermarks in AI Images](https://xusheng.dev/posts/reversing/mspaint_invisible_watermark/main/) ⭐️ 8.0/10

Microsoft Paint and Photos embed non-disableable invisible server-issued GUID watermarks into AI-manipulated images, including those generated locally with on-device models. The hidden identifiers can link images back to Microsoft accounts, enabling subpoenas that reveal user identity and undermining online anonymity for creators of memes or edited content. The invisible GUID watermark operates independently of any visible watermark toggle and is applied silently in the background without user notification or opt-out.

hackernews · ComputerGuru · Aug 24, 15:28 · [Discussion](https://news.ycombinator.com/item?id=49421158)

<details><summary>References</summary>
<ul>
<li><a href="https://xusheng.dev/posts/reversing/mspaint_invisible_watermark/main/">Microsoft Paint and Photos Embed Server-Issued GUIDs as Invisible ...</a></li>
<li><a href="https://byteiota.com/ms-paint-invisible-server-guid-watermark-ai-image/">MS Paint Embeds Invisible Server GUIDs in Every AI Image | byteiota</a></li>

</ul>
</details>

**Discussion**: Commenters view the AI feature as a distraction from the core privacy issue of secret unique identifiers; they express concern over subpoenas exposing personal data and criticize Microsoft's sloppy rollout of tracking features.

**Tags**: `#privacy`, `#watermarking`, `#Microsoft`, `#AI`, `#reverse-engineering`

---

<a id="item-2"></a>
## [San Francisco Built as Interactive 3D Web Game from Apple Maps](https://sf.thijs.gg/) ⭐️ 7.0/10

A browser-based 3D simulation at sf.thijs.gg lets users explore San Francisco in video game style using data extracted from Apple Maps. The project shows how proprietary geospatial data can be repurposed for accessible web experiences, sparking interest in 3D city recreations across mapping and gaming industries. It relies on reverse-engineered Apple Flyover 3D models stored in map tiles, though updated HEIF textures and authentication methods have made extraction more difficult.

hackernews · centrosphere · Aug 24, 17:05 · [Discussion](https://news.ycombinator.com/item?id=49422784)

**Background**: Apple Maps Flyover provides textured 3D satellite views of cities by serving authenticated 3D models from map tiles, and open-source efforts like the retroplasma repository document how to retrieve and render this data.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/retroplasma/flyover-reverse-engineering">GitHub - retroplasma/flyover-reverse-engineering: Reversing Apple's 3D satellite mode · GitHub</a></li>

</ul>
</details>

**Discussion**: Users praised the web-based experience and discussed technical hurdles with current Apple data formats, suggested features like street names and multiplayer, and shared personal emotional reactions from virtually revisiting familiar locations.

**Tags**: `#3D mapping`, `#web development`, `#geospatial data`, `#reverse engineering`, `#city simulation`

---

<a id="item-3"></a>
## [Jabber/XMPP Marks 25 Years of Digital Independence](https://gultsch.de/posts/25-years-of-digital-independence/) ⭐️ 7.0/10

A reflective post marks the 25-year milestone of Jabber/XMPP and stresses its focus on digital independence through open standards. Hacker News discussions examine the current ecosystem including projects like Movim and Fluux along with comparisons to Matrix. The milestone highlights ongoing relevance of federated open messaging protocols amid growing interest in decentralized alternatives to centralized platforms. It affects developers and users seeking independent, interoperable communication tools without reliance on big tech. Community members note successful migrations such as from Google Voice to jmp.chat using Dino and Cheogram clients, and experiments with XMPP for IoT agent communication via ejabberd servers. Limitations discussed include lack of major funding compared to Matrix and ideas for serverless extensions using Iroh networking.

hackernews · inputmice · Aug 24, 15:51 · [Discussion](https://news.ycombinator.com/item?id=49421536)

**Background**: XMPP, originally named Jabber, is an open communication protocol designed for instant messaging and presence information using XML. The architecture allows anyone to run their own server in a federated system similar to email, enabling interoperability across different providers with JID addresses.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/XMPP_protocol">XMPP protocol</a></li>
<li><a href="https://joinjabber.org/docs/faqs/faq/">FAQ | JoinJabber</a></li>

</ul>
</details>

**Discussion**: Commenters express strong affection for XMPP and optimism about projects like Movim and Fluux while regretting that Matrix received funding instead of improving XMPP. Users share practical experiences with migrations, telephony bridges, and custom agent communication setups, alongside ideas for future enhancements like E2EE integrations.

**Tags**: `#XMPP`, `#Jabber`, `#decentralized-messaging`, `#open-standards`, `#instant-messaging`

---

<a id="item-4"></a>
## [SeL4 Security Proofs Now Complete for AArch64](https://proofcraft.systems/news-2026/#2026-08-21) ⭐️ 7.0/10

The formal security proofs for the seL4 microkernel are now complete for AArch64 in the non-MCS, unicore configuration. This milestone strengthens trust in formally verified systems on AArch64 platforms used in embedded and security-critical applications. Proofs apply only to non-mixed criticality systems and unicore setups; side-channel attacks remain outside the verified properties.

hackernews · snvzz · Aug 24, 11:32 · [Discussion](https://news.ycombinator.com/item?id=49418255)

**Background**: seL4 is a third-generation L4 microkernel whose functional correctness and security properties have been established through mathematical proofs.

<details><summary>References</summary>
<ul>
<li><a href="https://sel4.systems/Verification/">Verification | seL4</a></li>
<li><a href="https://en.wikipedia.org/wiki/SeL4">seL4 - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Users highlighted the non-MCS unicore limitation, listed deployments such as GenodeOS and LionsOS, and raised concerns about side-channel attacks and Linux integration.

**Tags**: `#seL4`, `#formal-verification`, `#AArch64`, `#microkernel`, `#security`

---

<a id="item-5"></a>
## [Linux Pattern Turns SQLite Database into Executable Binary](https://simonwillison.net/2026/Aug/24/your-executable-is-a-sqlite-database/) ⭐️ 7.0/10

Farid Zakaria presents a technique that sets a SQLite file's application ID at offset 68 to SELF and stores ELF components in SQLite tables using a defined schema. A custom self-exec interpreter extracts and runs the pieces, with binfmt_misc registration allowing the kernel to invoke it automatically. This approach combines SQLite's structured storage with ELF executables and Linux's binfmt_misc, offering a novel way to package and execute programs that could influence systems programming and application distribution patterns. The schema is available at github.com/fzakaria/selfdb, the interpreter code is in C at self-exec.c, and binfmt_misc registration uses a magic match at byte 68 for the SELF identifier.

rss · Simon Willison · Aug 24, 11:38

**Background**: SQLite databases include a 4-byte application ID at offset 68 that can be set via PRAGMA to mark file type. binfmt_misc is a Linux kernel feature that registers custom binary formats and passes matching files to user-space interpreters for execution.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.kernel.org/admin-guide/binfmt-misc.html">Kernel Support for miscellaneous Binary Formats (binfmt_misc) — The Linux Kernel documentation</a></li>
<li><a href="https://www.sqlite.org/fileformat.html">Database File Format</a></li>

</ul>
</details>

**Tags**: `#Linux`, `#SQLite`, `#ELF`, `#executables`, `#systems programming`

---

<a id="item-6"></a>
## [Unbounded Labs Releases Bartholomew, 2.82B Vintage LLM on Pre-1931 Text](https://www.reddit.com/r/MachineLearning/comments/1vx94er/bart_a_vintage_llm_r/) ⭐️ 7.0/10

Unbounded Labs introduced Bartholomew (Bart), a 2.82B-parameter LLM trained from scratch on 20.1B tokens of English text written before 1931. The model, along with datasets, training code, and benchmarks, is open-sourced after three months and roughly $800 in costs. The experiment tests whether LLMs can produce original scientific ideas instead of memorization, directly addressing questions raised by Demis Hassabis. It advances research on model originality and provides new tools for the niche field of vintage LLMs. Bart was trained in five days on one H100 at 60% MFU; the team cleaned Harvard's Institutional Books corpus, created Vintage CORE benchmarks, and released a 416k-pair SFT dataset. All ablations, training runs, and methodology are publicly available.

reddit · r/MachineLearning · /u/soggydoggy8 · Aug 24, 17:20

**Tags**: `#LLM Training`, `#Historical Data`, `#AI Research`, `#Model Evaluation`, `#Open Source`

---

<a id="item-7"></a>
## [LLMs Generate Inherently Programmable 3D Objects as Spatial Software](https://www.reddit.com/r/MachineLearning/comments/1vxcc1h/r_using_ai_as_a_spatial_software_generator_to/) ⭐️ 7.0/10

Researchers present a method using LLMs to generate 3D objects as programmable spatial software code rather than monolithic meshes. Demos at nova3d.xyz and an associated GitHub repo illustrate hierarchical structures with built-in animation and adaptability. This enables 3D objects that are animation-ready and programmable from creation, offering advantages in hierarchy and environment adaptability over traditional AI generators. It could disrupt industrial design, game development, simulations, and AR/VR/XR industries. Objects support logic for varying compute environments like mobiles versus game engines and include hinge/socket articulations at authoring time. The approach currently lags behind mesh-based generators for complex organic shapes.

reddit · r/MachineLearning · /u/mhb_11 · Aug 24, 19:10

**Tags**: `#AI`, `#3D Generation`, `#LLMs`, `#Spatial Programming`, `#Machine Learning`

---

<a id="item-8"></a>
## [Delay-Corrected Bellman Operator for Constrained RL Under Stochastic Delays](https://www.reddit.com/r/MachineLearning/comments/1vx11hz/delaycorrected_bellman_operator_causal/) ⭐️ 7.0/10

The proposal introduces a delay-corrected Bellman operator that uses an adaptive effective discount learned from the consequence-delay distribution, along with an Interventional Consequence Net (ICN) for causal attribution in constrained RL. A contraction proof is provided that holds under unknown stochastic delays as part of Causal Consequence-Penalized Learning (CCPL). Standard constrained RL fails when violations are delayed and stochastic because it penalizes actions based on temporal proximity rather than actual causation, affecting real-world safe RL applications. This approach enables proper attribution and maintains theoretical guarantees, impacting constrained and safe reinforcement learning research. The Interventional Consequence Net requires access to the environment's structural causal model to generate pretraining labels and is not learned end-to-end from data alone, limiting applicability outside benchmark settings where the SCM is known. The contraction property of the delay-corrected operator holds despite unknown stochastic delays.

reddit · r/MachineLearning · /u/No_Cauliflower7923 · Aug 24, 12:11

<details><summary>References</summary>
<ul>
<li><a href="https://prismix.dev/news/f1072ba9e03c">Delay-corrected Bellman operator + causal attribution for ...</a></li>

</ul>
</details>

**Tags**: `#reinforcement learning`, `#constrained RL`, `#causal inference`, `#Bellman operator`, `#stochastic delays`

---

<a id="item-9"></a>
## [Xiaomi New ARM CPU Matches Apple Single-Thread Performance](https://twitter.com/lemire/status/2091894299289874926) ⭐️ 6.0/10

Xiaomi's Xring O3 CPU, based on ARM C1-Ultra design, achieves Geekbench single-core scores around 3945 matching Apple's M5 while delivering multi-core scores of 15221 with 10 cores. This development signals Xiaomi entering advanced mobile chip production as the third-largest smartphone maker, increasing competition for MediaTek and Qualcomm in ARM-based SoCs. The CPU uses ARM's standard design with Xiaomi handling only configuration, interconnects, and TSMC 3nm implementation rather than custom core design, and power efficiency data remains unavailable.

hackernews · tosh · Aug 24, 15:08 · [Discussion](https://news.ycombinator.com/item?id=49420873)

**Background**: ARM-based CPUs power most smartphones and tablets with designs licensed from ARM Holdings, while companies like Apple create fully custom cores that still follow the ARM instruction set for compatibility.

**Discussion**: Commenters note the chip is an off-the-shelf ARM design also used by MediaTek, emphasize the missing performance-per-watt metric critical for phones, and point out the multi-core advantage comes from using more cores than Apple's 6-core setups.

**Tags**: `#mobile-cpu`, `#arm`, `#xiaomi`, `#apple-silicon`, `#benchmarks`

---

<a id="item-10"></a>
## [IP Shipyard to End Centralized IPFS Support by September 2026](https://ipshipyard.com/blog/2026-the-end-of-ipfs-at-shipyard/) ⭐️ 6.0/10

IP Shipyard announced it will wind down all IPFS-related engineering, maintenance, and infrastructure operations, with the final day set for September 30, 2026. The team will shift to supporting individual maintainer grants while the broader IPFS project continues. The move transitions IPFS maintenance from a centralized engineering collective to a distributed grant model, affecting users and teams that relied on Shipyard's implementations. It underscores ongoing sustainability challenges for open-source decentralized infrastructure projects. Shipyard is one of multiple IPFS implementation maintainers and the overall IPFS project is not shutting down. Community discussions highlight alternatives such as Iroh built by former IPFS developers.

hackernews · iand · Aug 24, 15:48 · [Discussion](https://news.ycombinator.com/item?id=49421489)

**Background**: IPFS is a peer-to-peer protocol for decentralized file storage and sharing across distributed networks. Shipyard has acted as an independent engineering collective maintaining critical parts of the IPFS and libp2p stack used by hundreds of teams.

<details><summary>References</summary>
<ul>
<li><a href="https://ipshipyard.com/blog/2026-the-end-of-ipfs-at-shipyard/">The end of IPFS at Shipyard</a></li>

</ul>
</details>

**Discussion**: Commenters clarify that only Shipyard is sunsetting, not the IPFS project itself, and note the announcement's potential to mislead readers. Some express regret and recommend Iroh as a more sustainable alternative, while others criticize IPFS priorities like IPNS and the use of Google Forms for feedback.

**Tags**: `#IPFS`, `#decentralized-storage`, `#open-source-maintenance`, `#p2p-networks`, `#protocol-labs`

---

<a id="item-11"></a>
## [Anthropic Hits $65B Revenue as Premium Model Struggles](https://simonwillison.net/2026/Aug/23/anthropics-best-ai-model-struggles-to-attract-users-as-cheaper-t/) ⭐️ 6.0/10

Anthropic's annualized revenue reached $65 billion in July 2026, up from $47 billion in May, with 6,000 customers spending over $100,000 annually. Its Opus 5 model captured only 3.5% of spend per Ramp AI index, while OpenAI's revenue exceeded $40 billion after the GPT 5.6 launch. The figures show premium AI models face adoption hurdles despite strong company revenues, as users favor cheaper alternatives, influencing pricing and strategy across the LLM market. Ramp AI index data lists Opus 4.8 at 28% of Anthropic spend, Fable 5 at 8%, and Opus 5 at 3.5%; Anthropic projects Q3 profitability using the same model as Q2.

rss · Simon Willison · Aug 23, 20:24

**Tags**: `#Anthropic`, `#OpenAI`, `#AI revenue`, `#LLM market`, `#industry analysis`

---