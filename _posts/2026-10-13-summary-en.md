---
layout: default
title: "Horizon Summary: 2026-10-13 (EN)"
date: 2026-10-13
lang: en
---

> From 33 items, 17 important content pieces were selected

---

1. [WiFi 7 Router Converted into 320 Msps SDR Receiver](#item-1) ⭐️ 8.0/10
2. [Python 3.15 Released with Explicit Lazy Imports via PEP 810](#item-2) ⭐️ 8.0/10
3. [Looped Diffusion Transformer Reuses Blocks for Efficient Generation](#item-3) ⭐️ 8.0/10
4. [E. coli Chemotaxis Reveals Single-Cell Intelligence Parallels to Neural Networks](#item-4) ⭐️ 7.0/10
5. [Blog Post Advocates Building Modern Web Apps in C with CGI](#item-5) ⭐️ 7.0/10
6. [Hackers Trigger Automatic Defrost in European Supermarket Fridges](#item-6) ⭐️ 7.0/10
7. [U-Space Introduces Label-Free Uncertainty Detection for LLMs](#item-7) ⭐️ 7.0/10
8. [learnc Optimizes Constants in C Code for JPEG and WebRTC Gains](#item-8) ⭐️ 7.0/10
9. [Robotics Compares World Action Models and VLAs as GPT-2 Moment](#item-9) ⭐️ 7.0/10
10. [RoBERTa AI-Text Detector Compressed to 97MB for Browser Inference](#item-10) ⭐️ 7.0/10
11. [shad0w Proxy Caches Local LLM Answers in Microseconds via Compact Table](#item-11) ⭐️ 7.0/10
12. [GLM-Legal AI Tool Discussed on HN for Benchmarks and Privacy](#item-12) ⭐️ 6.0/10
13. [Agent37 Launches Low-Cost AI Agent Sandboxes at Under 10% Typical Cost](#item-13) ⭐️ 6.0/10
14. [Phreak.ing Launches Retro WebRTC Phone Switch with DTMF Features](#item-14) ⭐️ 6.0/10
15. [Plug-in Balcony Solar Panels Expand Renewable Access](#item-15) ⭐️ 6.0/10
16. [Reddit Discusses Detecting AI Slop Papers at ICLR Review](#item-16) ⭐️ 6.0/10
17. [Call for CL4SM Contributions on Constrained ML for Science at NeurIPS Pre-Event](#item-17) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [WiFi 7 Router Converted into 320 Msps SDR Receiver](https://github.com/h0m3us3r/w1700k-sdr) ⭐️ 8.0/10

The GitHub project h0m3us3r/w1700k-sdr shows how to replace firmware on the MediaTek MT7996 chipset in the Gemtek W1700K WiFi 7 router to create a 320 Msps software defined radio receiver. This hack provides a low-cost path to high-bandwidth SDR reception at 5 GHz and 6 GHz bands, potentially enabling wider experimentation in radio applications without expensive dedicated hardware. The modified radio captures 14-bit IQ samples at up to 320 Msps across 2.4/5/6 GHz bands and streams data over 10 GbE using zero-copy UDP to a Linux host for spectrum analysis.

hackernews · djfergus · Oct 12, 12:41 · [Discussion](https://news.ycombinator.com/item?id=50055593)

**Background**: Software defined radio uses software to process radio signals instead of fixed hardware circuits. WiFi 7 routers employ advanced chipsets like the MediaTek MT7996 that handle wide bandwidths suitable for repurposing as receivers.

<details><summary>References</summary>
<ul>
<li><a href="https://www.rtl-sdr.com/turning-a-wi-fi-7-router-into-a-320-msps-sdr/">Turning a Wi-Fi 7 Router into a 320 Msps SDR - RTL-SDR</a></li>
<li><a href="https://daily.dev/posts/turn-a-wifi-7-router-into-a-320msps-software-defined-radio-receiver-38irzaw8t">Turn a WiFi 7 Router into a 320Msps Software Defined Radio ...</a></li>

</ul>
</details>

**Discussion**: Users praised the novelty and low cost for 320 Msps reception at 5 GHz while noting limitations to narrowband use cases. Comments highlighted the same developer's prior ESP32 SDR work and potential compatibility with boards like the Banana Pi R4.

**Tags**: `#SDR`, `#WiFi 7`, `#hardware hacking`, `#radio`, `#embedded systems`

---

<a id="item-2"></a>
## [Python 3.15 Released with Explicit Lazy Imports via PEP 810](https://simonwillison.net/2026/Oct/12/python-3-15/) ⭐️ 8.0/10

Python 3.15 has been released, adding explicit lazy imports from PEP 810 and unpacking in comprehensions from PEP 798, while dropping support for Python 3.10. Developers building cross-version tools can now drop 3.10 and use features from 3.11 onward, while lazy imports reduce startup latency for CLI tools and plugins with heavy dependencies. The syntax uses 'lazy import json' or 'lazy from pathlib import Path', deferring module loading until first use; unpacking allows [*sublist for sublist in lists] as shorthand for flattening.

rss · Simon Willison · Oct 12, 18:15

<details><summary>References</summary>
<ul>
<li><a href="https://peps.python.org/pep-0810/">PEP 810 – Explicit lazy imports | peps.python.org</a></li>

</ul>
</details>

**Tags**: `#Python`, `#Software Releases`, `#PEP 810`, `#Lazy Imports`, `#Programming Languages`

---

<a id="item-3"></a>
## [Looped Diffusion Transformer Reuses Blocks for Efficient Generation](https://www.reddit.com/r/MachineLearning/comments/1x49d61/looped_diffusion_transformer_the_same_blocks_run/) ⭐️ 8.0/10

The paper introduces Looped Diffusion Transformer (Looped-DiT, arXiv 2609.40305) that runs shared transformer blocks multiple times per denoising step instead of scaling model size. A 260M parameter model with deep supervision and self-modulating attention outperforms a 6.5x larger baseline using 4.9x less compute, and B/16 code plus weights are released under MIT license. This approach allows trading compute for quality at sampling time by adjusting loop depth without retraining, offering a new efficiency path for text-to-image diffusion models. It affects practitioners seeking better performance per FLOP in generative AI systems. Naive looping fails without deep supervision on every loop and self-modulating attention; depth is chosen at inference, with most gains before depth 3 on tested prompts. Inference time on M5 Pro rises from 23-24s at depth 1 to 43-47s at depth 4 using 100 Euler steps.

reddit · r/MachineLearning · /u/Fit-Ant2238 · Oct 12, 18:13

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2609.40305">[2609.40305] Looped Diffusion Transformer - arXiv.org</a></li>
<li><a href="https://github.com/OpenSenseNova/Looped-DiT">Looped-DiT: Looped Diffusion Transformer - GitHub</a></li>

</ul>
</details>

**Discussion**: The poster shared visual results from five prompts run at depths 1-4 on an M5 Pro, noting most visual improvement occurs by depth 3 with diminishing returns at depth 4, confirming flexible depth selection works as described.

**Tags**: `#diffusion models`, `#transformers`, `#efficient inference`, `#text-to-image`, `#generative AI`

---

<a id="item-4"></a>
## [E. coli Chemotaxis Reveals Single-Cell Intelligence Parallels to Neural Networks](https://jsomers.net/e-coli-chemotaxis/) ⭐️ 7.0/10

A 2024 article explores E. coli chemotaxis as an example of sophisticated intelligence in a single cell, with Hacker News comments examining its analogies to artificial neural networks. This crossover between biology and AI could inspire new approaches to neural network design by studying efficient single-cell signaling systems. Comments highlight that a single cell functions like an entire artificial neural network, noting real neurons possess properties absent in current ANNs and questioning how to leverage them for AI improvements.

hackernews · jsomers · Oct 11, 11:02 · [Discussion](https://news.ycombinator.com/item?id=50041866)

**Background**: E. coli chemotaxis uses a signaling pathway involving two-component regulatory systems to sense chemical gradients and direct flagellar motor rotation for movement toward nutrients or away from toxins.

<details><summary>References</summary>
<ul>
<li><a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC9788364/">Mechanisms of E . coli chemotaxis signaling pathways visualized...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Two-component_regulatory_system">Two-component regulatory system - Wikipedia</a></li>

</ul>
</details>

**Discussion**: HN users discussed how single cells resemble full ANNs with unique neuronal properties that could advance AI, referenced related books on evolution, and noted the article's elegant design while questioning links to electric motors.

**Tags**: `#biology`, `#chemotaxis`, `#AI inspiration`, `#neural networks`, `#systems biology`

---

<a id="item-5"></a>
## [Blog Post Advocates Building Modern Web Apps in C with CGI](https://prophitt.me/writing/a-modern-web-app-in-c) ⭐️ 7.0/10

A blog post titled 'A Modern Web App in C' promotes using C, CGI, and minimal tools like pledge and chroot instead of complex JavaScript/TypeScript stacks for web development. The post challenges the dominance of heavy modern web stacks and highlights potential benefits in simplicity, performance, and security for certain applications. It references older approaches like BCHS and busybox CGI support, with the author emphasizing privilege dropping and straightforward deployment over layered frameworks.

hackernews · prophittcorey · Oct 12, 16:13 · [Discussion](https://news.ycombinator.com/item?id=50058528)

**Background**: Common Gateway Interface (CGI) is a standard allowing web servers to run external programs for dynamic content generation in response to HTTP requests.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Common_Gateway_Interface">Common Gateway Interface - Wikipedia</a></li>

</ul>
</details>

**Discussion**: HN commenters expressed surprise at limited pushback, questioned the necessity of stacks like TypeScript + React + Next.js, and shared experiences with FastCGI, WebAssembly in C++, and alternatives like busybox while debating maintenance of projects like BCHS.

**Tags**: `#C programming`, `#Web development`, `#Minimalist architecture`, `#CGI`, `#Software engineering`

---

<a id="item-6"></a>
## [Hackers Trigger Automatic Defrost in European Supermarket Fridges](https://www.tomshardware.com/tech-industry/cyber-security/unprecedented-cyberattack-cripples-supermarket-fridges-across-europe-as-hackers-activate-automatic-defrosting-delivery-and-store-prices-also-impacted-by-incident) ⭐️ 7.0/10

A cyberattack on French supermarket chain Intermarché activated automatic defrost cycles in refrigeration systems across 150 stores via vulnerable legacy Danfoss controllers. This incident highlights vulnerabilities in industrial control systems and IoT devices within retail supply chains, potentially impacting food safety and store operations across Europe. Attackers exploited end-of-life controllers such as Danfoss SM800 and SC355 that carried known CVEs but remained in use due to replacement costs.

hackernews · Zeekaas · Oct 12, 12:16 · [Discussion](https://news.ycombinator.com/item?id=50055304)

**Background**: Legacy industrial control systems in refrigeration equipment are frequently connected to networks for remote diagnostics and efficiency monitoring, yet many run on hardware whose vendor support has ended.

<details><summary>References</summary>
<ul>
<li><a href="https://www.trout.software/blog/common-attack-vectors-in-legacy-ics">Common Attack Vectors in Legacy ICS and How to Stop Them</a></li>

</ul>
</details>

**Discussion**: Commenters noted the economic barriers to replacing outdated Danfoss controllers, questioned assumptions about internet connectivity for such devices, and speculated on links to similar incidents at US military bases.

**Tags**: `#cybersecurity`, `#IoT`, `#ICS`, `#legacy systems`, `#supply chain`

---

<a id="item-7"></a>
## [U-Space Introduces Label-Free Uncertainty Detection for LLMs](https://www.reddit.com/r/MachineLearning/comments/1x44f9m/uspace_uncovering_when_and_why_uncertainty_arises/) ⭐️ 7.0/10

U-Space introduces U-Lens, a Jacobian-based method that quantifies and classifies uncertainty types in LLM reasoning using a single forward pass without labels, training, or resampling. It multiplies a hidden-state projection onto four doubt directions by mean token entropy and outperforms multi-pass and supervised baselines on Gemma, Qwen, and Magistral models across four benchmarks. The approach provides an efficient, interpretable signal for model confidence that can be used to route uncertain answers, trigger retrieval, or request clarification without extra inference cost. It enables practical deployment of uncertainty-aware reasoning pipelines in open-weight models. The only model-specific component is a pre-fitted J-Lens derived from Anthropic’s global workspace work; once obtained, U-Space requires only unembedding rows and a single hidden state at the end of thinking. Forty-plus pre-fitted lenses are available on Hugging Face, and new lenses can be fit with roughly 100 unlabeled prompts.

reddit · r/MachineLearning · /u/AdRevolutionary3242 · Oct 12, 15:10

**Background**: The method builds on the Jacobian Lens (J-Lens) introduced in Anthropic’s global workspace paper, which extracts a sparse subspace of activations that functions like a global workspace by averaging the Jacobian of the final residual stream with respect to intermediate layers.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/research/global-workspace">A global workspace in language models \ Anthropic</a></li>
<li><a href="https://transformer-circuits.pub/2026/workspace/index.html">Verbalizable Representations Form a Global Workspace in Language...</a></li>

</ul>
</details>

**Tags**: `#uncertainty estimation`, `#large language models`, `#interpretability`, `#reasoning models`, `#machine learning`

---

<a id="item-8"></a>
## [learnc Optimizes Constants in C Code for JPEG and WebRTC Gains](https://www.reddit.com/r/MachineLearning/comments/1x4dlbm/learnc_fit_the_constants_in_existing_c_code_to/) ⭐️ 7.0/10

learnc tunes named constants in unmodified C code using a user-defined C score function and rewrites the file with optimized values. It delivers 9.1% BD-rate improvement on JPEG via stb_image_write.h and raises WebRTC VAD F1 from 0.810 to 0.859. The tool enables automatic tuning of legacy C constants without code changes, offering measurable gains in compression and audio detection tasks. It bridges machine learning with systems programming for practical improvements in widely used libraries. Gains were verified on held-out data with 128 constants for JPEG on Kodak images and all constants in vad_core.c for VAD; no JPEG benefit occurs below 1 bpp and it suits tens to hundreds of constants rather than large weight sets.

reddit · r/MachineLearning · /u/keep_up_sharma · Oct 12, 20:51

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/pdf/2401.04039">Bjøntegaard Delta (BD): A Tutorial Overview of the Metric ...</a></li>
<li><a href="https://github.com/wiseman/py-webrtcvad">GitHub - wiseman/py-webrtcvad: Python interface to the WebRTC ...</a></li>

</ul>
</details>

**Tags**: `#machine learning`, `#code optimization`, `#C programming`, `#JPEG compression`, `#audio processing`

---

<a id="item-9"></a>
## [Robotics Compares World Action Models and VLAs as GPT-2 Moment](https://www.reddit.com/r/MachineLearning/comments/1x38qpy/world_action_models_vs_vlas_robotics_just_had_its/) ⭐️ 7.0/10

A Reddit post in r/MachineLearning compares World Action Models and Vision-Language-Action (VLA) models, framing recent robotics advances as the field's GPT-2 moment. This comparison signals a potential paradigm shift in robotics, where scaling data and unified models could accelerate progress similar to early large language models. World Action Models integrate action prediction with environment modeling, showing gains across robot embodiments as training data scales, while VLAs combine vision, language, and action for tasks like manipulation.

reddit · r/MachineLearning · /u/moschles · Oct 11, 13:51

**Background**: World models in robotics predict environmental changes from actions, starting with labeled training data for perception. VLAs extend this by incorporating language instructions to guide robot behavior in real-world settings.

<details><summary>References</summary>
<ul>
<li><a href="https://roboflow.com/blog/world-models-in-robotics">World Models in Robotics : Build Better Data with Roboflow</a></li>
<li><a href="https://livingontheedge.beehiiv.com/p/the-next-robotics-moat-is-learning-to-act">The Next Robotics Moat Is Learning to Act</a></li>

</ul>
</details>

**Tags**: `#robotics`, `#machine learning`, `#VLAs`, `#world models`, `#AI`

---

<a id="item-10"></a>
## [RoBERTa AI-Text Detector Compressed to 97MB for Browser Inference](https://www.reddit.com/r/MachineLearning/comments/1x3vqip/compressed_a_roberta_aitext_detector_from_500_mb/) ⭐️ 7.0/10

A developer compressed a RoBERTa AI-text detector from roughly 500 MB to 97 MB and an image detector to 26 MB, enabling fully client-side browser inference via ONNX Runtime Web 1.30 with fine-tuning, WiSE-FT, and int4 quantization. This allows privacy-focused AI detection without uploading content to servers, advancing practical client-side machine learning deployment in web browsers across the industry. The text model stores embeddings as int4 with fp16 scales (19 MB plus 2 MB) dequantized in JS, while the transformer body uses mixed-precision quantization at 75 MB; inference runs at about 60 ms for 100 tokens on laptop hardware.

reddit · r/MachineLearning · /u/Alternative_Detail31 · Oct 12, 07:44

<details><summary>References</summary>
<ul>
<li><a href="https://onnxruntime.ai/docs/tutorials/web/">Web | onnxruntime</a></li>
<li><a href="https://onnxruntime.ai/">ONNX Runtime | Home</a></li>

</ul>
</details>

**Tags**: `#model compression`, `#ONNX Runtime Web`, `#client-side ML`, `#quantization`, `#AI detection`

---

<a id="item-11"></a>
## [shad0w Proxy Caches Local LLM Answers in Microseconds via Compact Table](https://www.reddit.com/r/MachineLearning/comments/1x3vkej/i_built_a_tiny_table_that_learns_your_local_llms/) ⭐️ 7.0/10

Developer released shad0w, a proxy for OpenAI-compatible servers like Ollama that logs classification outputs, builds a small table after roughly 1,000 examples, and serves repeats on CPU in microseconds at 95%+ model agreement. The tool delivers practical latency reductions for repetitive local LLM classification tasks, enabling faster responses in applications while preserving high accuracy and routing uncertain cases back to the model. shad0w works with any OpenAI-compatible endpoint, only answers when certified on held-out data, and demonstrated learning Snake gameplay to run at 10 moves per second where the LLM cannot; it is Apache-2.0 licensed with Python, JS, and C components.

reddit · r/MachineLearning · /u/gauravc2796 · Oct 12, 07:33

<details><summary>References</summary>
<ul>
<li><a href="https://pypi.org/project/shad0wllm/0.3.3/">shad 0 wllm · PyPI</a></li>

</ul>
</details>

**Tags**: `#LLM optimization`, `#caching`, `#local AI`, `#performance`, `#machine learning tools`

---

<a id="item-12"></a>
## [GLM-Legal AI Tool Discussed on HN for Benchmarks and Privacy](https://z.ai/blog/glm-legal) ⭐️ 6.0/10

GLM-Legal, a new legal AI tool, was featured in a Hacker News discussion noting its 20% benchmark pass rate along with privacy concerns and calls for mandatory human review. The discussion highlights ongoing challenges in applying AI to legal work where low accuracy, data privacy risks, and the need for human oversight directly affect legal rights and professional practice. Commenters cited Z.ai's prior workspace snapshotting practices, questioned the Harvey benchmark's validity for novel tasks, and referenced Anthropic's policy requiring qualified human review for high-stakes legal uses.

hackernews · ilreb · Oct 12, 16:11 · [Discussion](https://news.ycombinator.com/item?id=50058507)

<details><summary>References</summary>
<ul>
<li><a href="https://z.ai/blog/glm-legal">GLM-Legal: Advancing Agentic Legal Intelligence</a></li>

</ul>
</details>

**Discussion**: Users voiced skepticism about the 20% pass rate for novel legal situations, raised alarms over past privacy violations by Z.ai, and stressed that AI outputs in law require final human verification to avoid errors.

**Tags**: `#AI`, `#Legal Tech`, `#Benchmarks`, `#Privacy`, `#Hacker News`

---

<a id="item-13"></a>
## [Agent37 Launches Low-Cost AI Agent Sandboxes at Under 10% Typical Cost](https://news.ycombinator.com/item?id=50059096) ⭐️ 6.0/10

Agent37 (YC F26) launched low-cost sandboxes for AI agents averaging $0.37 per month, under 10% of typical provider costs, with a free plan enabled by optimizations. Lower costs make running AI agents more accessible for developers and startups, potentially accelerating adoption in the competitive AI tooling space amid rising demand for agent infrastructure. Optimizations include burst CPU/RAM management for agent patterns, using Hetzner and OVH hosts instead of hyperscalers, gVisor for shared memory and fast boots, and RAM-optimized servers; gVisor sandboxes lack Docker-in-Docker support.

hackernews · vishnukool · Oct 12, 16:46

**Background**: OpenClaw is an open-source AI agent that executes tasks via messaging apps, while agent harnesses provide frameworks to run and manage such AI agents with tools and external functions.

<details><summary>References</summary>
<ul>
<li><a href="https://openclaw.ai/">OpenClaw — Open -Source AI Assistant</a></li>
<li><a href="https://www.databricks.com/blog/ai-harness">What is an AI Agent Harness ? | Databricks Blog</a></li>

</ul>
</details>

**Discussion**: Commenters congratulated the launch but highlighted intense competition and risk of a price race to the bottom against funded players; others raised practical concerns like filesystem state persistence, cold start times, and whether pure price competition is sustainable without hardware differentiation.

**Tags**: `#AI agents`, `#sandboxes`, `#cloud infrastructure`, `#YC startup`, `#cost optimization`

---

<a id="item-14"></a>
## [Phreak.ing Launches Retro WebRTC Phone Switch with DTMF Features](https://phreak.ing/) ⭐️ 6.0/10

Phreak.ing introduces a web-based phone switch featuring phreaking aesthetics, interactive DTMF elements, and Easter eggs such as typing *#06#. The project revives nostalgic telephony interfaces in a modern browser setting using WebRTC, appealing to enthusiasts interested in retro tech and peer-to-peer voice communication. Users interact via DTMF captcha for registration, with some reporting microphone issues; the site supports WebRTC P2P voice features and includes no-JS background effects.

hackernews · rickcarlino · Oct 12, 21:39 · [Discussion](https://news.ycombinator.com/item?id=50063417)

**Background**: WebRTC enables real-time audio and video communication directly in web browsers through peer-to-peer connections without plugins. DTMF signaling uses dual-tone frequencies from telephone keypads to control calls and devices, a standard since the 1960s.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/WebRTC">WebRTC</a></li>
<li><a href="https://en.wikipedia.org/wiki/DTMF_signaling">DTMF signaling</a></li>

</ul>
</details>

**Discussion**: HN users praised the retro UI and background effects while noting difficulties with the DTMF captcha and microphone access; many expressed nostalgia for early phreaking culture and 2600 magazine.

**Tags**: `#web`, `#telephony`, `#webrtc`, `#retro`, `#phreaking`

---

<a id="item-15"></a>
## [Plug-in Balcony Solar Panels Expand Renewable Access](https://www.nationalgeographic.com/environment/article/balcony-plug-in-solar-panels-renewable-energy) ⭐️ 6.0/10

Plug-in balcony solar panels that connect directly to standard wall outlets are seeing growing adoption, already widespread in Germany with 800-watt limits and anti-islanding inverters, while facing regulatory and technical barriers elsewhere. This approach lowers installation barriers for homeowners, accelerating renewable energy adoption amid falling panel costs, though it highlights ongoing challenges in grid integration and safety standards across different regions. Inverters synchronize with grid AC and shut off output when unplugged, limiting power to 800 watts to avoid overloads; US users report issues with sensitive AFCI breakers tripping on newer construction.

hackernews · speckx · Oct 12, 14:19 · [Discussion](https://news.ycombinator.com/item?id=50056822)

**Background**: Balcony solar systems, known as Balkonkraftwerk in Germany, use microinverters for direct grid connection without professional installation, relying on standards that ensure safe anti-islanding protection.

<details><summary>References</summary>
<ul>
<li><a href="https://www.adac.de/rund-ums-haus/energie/versorgung/balkonkraftwerk/">Balkonkraftwerk : So lohnt sich 2026 eine Mini-PV-Anlage bis 800 Watt</a></li>
<li><a href="https://wattroi.com/us/ul-1741-compliance-guide">UL 1741 Compliance Guide 2025 – Plug-In Solar Inverter ...</a></li>

</ul>
</details>

**Discussion**: Commenters note the technology is proven and safe in Germany with automatic shutdown features, while US discussions focus on AFCI breaker compatibility and why these differ from unsafe generator backfeeding; some question the need for batteries or capacitors.

**Tags**: `#solar energy`, `#renewable energy`, `#balcony solar`, `#home energy`, `#grid integration`

---

<a id="item-16"></a>
## [Reddit Discusses Detecting AI Slop Papers at ICLR Review](https://www.reddit.com/r/MachineLearning/comments/1x3ve39/hows_iclr_reviewing_going_for_you_any/) ⭐️ 6.0/10

A Reddit thread on r/MachineLearning examines early ICLR 2025 reviewing on OpenReview, noting increased difficulty detecting AI-generated papers amid rising automated submissions. The discussion highlights emerging pressures on peer review integrity at major machine learning conferences as AI tools make low-quality submissions harder to spot. Reviewers report varying numbers of potential accepts versus AI-generated slop papers in their batches and question methods for reliable identification of automated content.

reddit · r/MachineLearning · /u/ade17_in · Oct 12, 07:22

**Background**: OpenReview serves as the open peer review platform used by ICLR and other venues to manage submissions and reviews with configurable policies.

<details><summary>References</summary>
<ul>
<li><a href="https://openreview.net/">Venues | OpenReview</a></li>

</ul>
</details>

**Tags**: `#ICLR`, `#peer review`, `#AI-generated papers`, `#machine learning`, `#OpenReview`

---

<a id="item-17"></a>
## [Call for CL4SM Contributions on Constrained ML for Science at NeurIPS Pre-Event](https://www.reddit.com/r/MachineLearning/comments/1x3vr5g/constrained_learning_for_scientific_modelling/) ⭐️ 6.0/10

A call for 2-page contributions has been issued for the CL4SM session at the ELLIs UnConference, a NeurIPS Paris pre-event scheduled for December 8, 2026, focusing on enforcing physical constraints such as conservation laws and symmetries in machine learning models for scientific systems. This session advances physics-informed machine learning by promoting models that avoid unphysical outputs, impacting fields like climate, fluids, and energy where data-driven predictions must align with known physical principles. Topics include soft constraint enforcement via penalties, hard enforcement through structure-preserving architectures, differentiable optimisation layers, and stability guarantees; submissions cover ongoing work, tutorials, or recently published papers with a deadline of October 30, 2026.

reddit · r/MachineLearning · /u/cici118 · Oct 12, 07:46

**Tags**: `#machine learning`, `#scientific modeling`, `#physics-informed ML`, `#constrained learning`, `#NeurIPS`

---