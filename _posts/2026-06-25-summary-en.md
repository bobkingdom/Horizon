---
layout: default
title: "Horizon Summary: 2026-06-25 (EN)"
date: 2026-06-25
lang: en
---

> From 41 items, 21 important content pieces were selected

---

1. [OpenAI Unveils Jalapeño Custom AI Inference Chip with Broadcom](#item-1) ⭐️ 9.0/10
2. [GLM-5.2 Open-Weight Model Closes Gap on Proprietary AI Agents](#item-2) ⭐️ 8.0/10
3. [Krea Releases Open-Weights 12B SOTA Text-to-Image Model](#item-3) ⭐️ 8.0/10
4. [Superhuman Generals.io Agent Trained via JAX and Vision Transformers](#item-4) ⭐️ 8.0/10
5. [DeepSWE: New Benchmark Tests Frontier Models on Real Code Writing](#item-5) ⭐️ 8.0/10
6. [Qualcomm Acquires AI Startup Modular for ~$4B Deal](#item-6) ⭐️ 7.0/10
7. [RubyLLM Offers Unified Ruby Access to Major AI Providers](#item-7) ⭐️ 7.0/10
8. [Google Adds Computer Use Feature to Gemini 3.5 Flash](#item-8) ⭐️ 7.0/10
9. [NVIDIA 45°C Cooling Design Cuts Data Center Water Use to Near Zero](#item-9) ⭐️ 7.0/10
10. [John Carmack Reflects on Early Mistakes at id Software](#item-10) ⭐️ 7.0/10
11. [Nub Adds Bun-like Features to Stock Node.js via Preload Hooks](#item-11) ⭐️ 7.0/10
12. [Tom MacWright Warns of LLM-Generated Anonymity in Hiring](#item-12) ⭐️ 7.0/10
13. [Datasette 1.0a35 Adds Create and Alter Table Interfaces](#item-13) ⭐️ 7.0/10
14. [Papers with Code curates top open-source OCR models and benchmarks](#item-14) ⭐️ 7.0/10
15. [HDD-RoPE Offers High-Dimensional Dynamic Rotary Positional Embeddings](#item-15) ⭐️ 7.0/10
16. [Spreadsheet Compares LLM Inference Pricing Across 7 Providers](#item-16) ⭐️ 7.0/10
17. [uv 0.11.24 Adds CPython 3.15 Beta Support and Relocatable Environments](#item-17) ⭐️ 6.0/10
18. [Bunny.net Makes Bunny DNS Free with No Query Fees](#item-18) ⭐️ 6.0/10
19. [PR Spam on Open Source Projects Resembles Early 2000s Email Spam](#item-19) ⭐️ 6.0/10
20. [Simon Willison Converts MDN Data to 66MB SQLite Database](#item-20) ⭐️ 6.0/10
21. [Simon Willison Builds OPFS + Pyodide Test Harness for Datasette Lite](#item-21) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [OpenAI Unveils Jalapeño Custom AI Inference Chip with Broadcom](https://techcrunch.com/2026/06/24/openai-unveils-its-first-custom-chip-built-by-broadcom/) ⭐️ 9.0/10

OpenAI announced its first custom AI inference chip, Jalapeño, co-developed with Broadcom in nine months using OpenAI models to accelerate the design process. This move signals OpenAI's push into custom hardware to cut inference costs by about 50 percent and reduce reliance on external GPU suppliers in the competitive AI ecosystem. The Jalapeño chip targets LLM inference workloads, forms the start of a multi-generation platform, and is manufactured by TSMC.

hackernews · jamdesk · Jun 24, 17:47 · [Discussion](https://news.ycombinator.com/item?id=48663324)

**Background**: Inference chips run trained AI models to produce outputs rather than train them from scratch. Custom silicon allows optimization for specific tasks like large language model serving compared to general-purpose processors.

<details><summary>References</summary>
<ul>
<li><a href="https://openai.com/index/openai-broadcom-jalapeno-inference-chip/">OpenAI and Broadcom unveil LLM-optimized inference chip | OpenAI</a></li>
<li><a href="https://byteiota.com/openai-jalapeno-chip-50-cheaper-inference-targets-nvidia/">OpenAI Jalapeño Chip : 50% Cheaper Inference Targets... | byteiota</a></li>

</ul>
</details>

**Discussion**: Commenters expressed skepticism about claims that OpenAI models meaningfully accelerated chip design and noted TSMC as the manufacturer. Others discussed future architectures with weights embedded in silicon and compared the effort to Google TPUs and startups like Taalas.

**Tags**: `#AI hardware`, `#custom chips`, `#OpenAI`, `#inference accelerators`, `#semiconductors`

---

<a id="item-2"></a>
## [GLM-5.2 Open-Weight Model Closes Gap on Proprietary AI Agents](https://www.interconnects.ai/p/glm-52-is-the-step-change-for-open) ⭐️ 8.0/10

Z.ai released GLM-5.2, an open-weight model that scores 62.1% on SWE-bench Pro and 81.0% on Terminal-Bench 2.1, matching or approaching Claude Opus 4.8 and GPT-5.5. The release demonstrates that open-weight models from Chinese labs can deliver competitive agent performance at lower cost, potentially broadening access beyond expensive proprietary services. GLM-5.2 also reaches 48.9% on NL2Repo and outperforms prior GLM-5.1 versions across benchmarks, though it trails top closed models on some tasks and requires high token usage.

hackernews · vantareed · Jun 23, 03:23 · [Discussion](https://news.ycombinator.com/item?id=48639840)

**Background**: SWE-bench evaluates language models on real GitHub software issues while Terminal-Bench tests agent performance in terminal environments; open-weight models allow local or cheaper deployment compared to closed APIs.

<details><summary>References</summary>
<ul>
<li><a href="https://registry.ollama.ai/library/glm-5.2">GLM - 5 . 2 is Z.ai’s flagship model for the era of long-horizon tasks.</a></li>
<li><a href="https://www.swebench.com/">SWE - bench Leaderboards</a></li>

</ul>
</details>

**Discussion**: Users praise the model's intelligence and affordability for coding tasks but report extremely high token consumption that quickly exhausts paid quotas, alongside occasional service reliability issues.

**Tags**: `#open-weight LLMs`, `#AI agents`, `#benchmarks`, `#Chinese AI labs`, `#model performance`

---

<a id="item-3"></a>
## [Krea Releases Open-Weights 12B SOTA Text-to-Image Model](https://www.krea.ai/blog/krea-2-technical-report) ⭐️ 8.0/10

Krea has released the open weights for Krea 2, a 12B parameter state-of-the-art text-to-image model, along with a detailed technical report covering data curation, architecture, RL pipelines, and infrastructure. Two versions are available: the full model and Krea 2 Turbo, which is guidance- and timestep-distilled for faster inference at 8 steps. This release provides a high-performing open-weights alternative for local image generation, enabling broader access and experimentation outside closed commercial systems. It stands out among locally hostable models, often matching or exceeding others except slower closed models like Ideogram 4. The Turbo variant achieves strong results in seconds versus minutes for competitors, though it struggles with specific prompts like nine-pointed stars or overcrowded scenes. The report emphasizes keeping the output manifold wide for diverse styles rather than narrow presets.

hackernews · mattnewton · Jun 23, 15:31 · [Discussion](https://news.ycombinator.com/item?id=48646659)

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Diffusion_model">Diffusion model</a></li>
<li><a href="https://www.ai21.com/glossary/foundational-llm/open-weights-model/">What is an Open-Weights Model? | AI21</a></li>

</ul>
</details>

**Discussion**: Commenters praised the depth of the technical report on training infrastructure and data practices rarely shared publicly. Discussions focused on self-hosting options, strong benchmark results versus Ideogram 4, and appreciation for the model's style diversity, though some noted it fights older challenges in the field.

**Tags**: `#AI`, `#image generation`, `#open-weights`, `#diffusion models`, `#technical report`

---

<a id="item-4"></a>
## [Superhuman Generals.io Agent Trained via JAX and Vision Transformers](https://www.reddit.com/r/MachineLearning/comments/1uei2yg/i_made_a_superhuman_generalsio_agent_with/) ⭐️ 8.0/10

A researcher trained a self-play RL agent for Generals.io that reached #1 on the human 1v1 leaderboard by combining behavior cloning with RL fine-tuning, then reimplementing the full pipeline in JAX and replacing CNNs with Vision Transformers. A detailed guide, fast JAX simulator, and agent code were released as open source. The work shows how scaling compute and modern architectures can outperform hand-crafted priors in imperfect-information real-time strategy games, offering reusable tools and lessons for the broader reinforcement learning and game AI communities. Key improvements came from switching from NumPy/Torch to JAX for better scaling and adopting Vision Transformers instead of CNNs; the project originated as a master's thesis and emphasizes investing in scaling over ad-hoc patches.

reddit · r/MachineLearning · /u/shrekofspeed · Jun 24, 16:18

**Tags**: `#reinforcement learning`, `#self-play`, `#JAX`, `#Vision Transformer`, `#game AI`

---

<a id="item-5"></a>
## [DeepSWE: New Benchmark Tests Frontier Models on Real Code Writing](https://www.reddit.com/r/MachineLearning/comments/1ue0hlp/deepswe_new_benchmark_looking_at_how_well_todays/) ⭐️ 8.0/10

DeepSWE is a new open-source benchmark with contamination-free tasks spanning 91 repositories across 5 languages and using behavior-based verification to evaluate frontier models' code-writing performance. This benchmark addresses contamination and complexity issues in prior evaluations like SWE-bench Pro, offering a more trustworthy assessment that could better guide development of AI coding agents and real-world deployment choices. Tasks are written from scratch rather than adapted from commits, prompts are shorter yet require 5.5 times more code and twice the output tokens than SWE-bench Pro, and verifiers test software behavior instead of implementation details.

reddit · r/MachineLearning · /u/we_are_mammals · Jun 24, 02:03

**Background**: SWE-bench evaluates AI models on resolving real GitHub issues from repositories. Benchmark contamination happens when models encounter test data during pretraining, resulting in misleading performance scores rather than genuine capability.

<details><summary>References</summary>
<ul>
<li><a href="https://www.swebench.com/">SWE-bench Leaderboards</a></li>
<li><a href="https://www.mindstudio.ai/blog/ai-benchmark-contamination-swebench-pro-deepswe">AI Benchmark Contamination : Why SWEBench Pro... | MindStudio</a></li>

</ul>
</details>

**Tags**: `#AI benchmarks`, `#code generation`, `#software engineering`, `#machine learning evaluation`, `#coding agents`

---

<a id="item-6"></a>
## [Qualcomm Acquires AI Startup Modular for ~$4B Deal](https://www.reuters.com/business/qualcomm-buy-ai-startup-modular-2026-06-24/) ⭐️ 7.0/10

Qualcomm announced its acquisition of AI startup Modular, developer of the Mojo programming language, in a deal valued at approximately $4 billion. The acquisition bolsters Qualcomm's AI software capabilities and supports its push into high-performance AI and RISC-V ecosystems beyond mobile and edge devices. Modular was founded by Chris Lattner; the move aligns with Qualcomm's other AI-related acquisitions such as Tenstorrent and Ventana amid competition with NVIDIA in inference and training markets.

hackernews · timmyd · Jun 24, 13:49 · [Discussion](https://news.ycombinator.com/item?id=48659798)

**Background**: Mojo is an in-development programming language created by Modular that combines Python usability with C-level performance for AI workloads and is available for Linux and macOS.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mojo_(programming_language)">Mojo ( programming language ) - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters expressed surprise at the timing of the acquisition and mixed views on Mojo's Python-like design; some questioned Qualcomm's fit in high-end AI markets while others noted its strategic RISC-V and AI portfolio expansion.

**Tags**: `#AI`, `#acquisition`, `#Qualcomm`, `#Modular`, `#Mojo`

---

<a id="item-7"></a>
## [RubyLLM Offers Unified Ruby Access to Major AI Providers](https://rubyllm.com/) ⭐️ 7.0/10

RubyLLM is a Ruby framework that delivers unified access to major AI providers with usability comparable to Vercel's AI SDK. The framework simplifies AI integration for Ruby developers and could speed LLM adoption within Ruby ecosystems and applications. Users note solid out-of-the-box flexibility yet report caching failures for xAI completions, missing native responses API support, and observability challenges during retries.

hackernews · doener · Jun 24, 14:41 · [Discussion](https://news.ycombinator.com/item?id=48660711)

<details><summary>References</summary>
<ul>
<li><a href="https://ai-sdk.dev/">AI SDK</a></li>

</ul>
</details>

**Discussion**: Developers praise RubyLLM's ease of use and balance of flexibility, while raising concerns about caching bugs, incomplete responses API coverage, and limited tracing for API call history.

**Tags**: `#Ruby`, `#AI`, `#LLM`, `#Framework`, `#Developer Tools`

---

<a id="item-8"></a>
## [Google Adds Computer Use Feature to Gemini 3.5 Flash](https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-computer-use-gemini-3-5-flash/) ⭐️ 7.0/10

Google introduces computer use capabilities in Gemini 3.5 Flash, enabling the model to interact with computer interfaces for task completion. This advances agentic AI development in a widely used model, potentially impacting how users automate desktop and browser tasks across the industry. Users report failures on complex tasks like PDF data extraction after multiple iterations and note the absence of coding agent features comparable to Claude or Codex.

hackernews · swolpers · Jun 24, 17:21 · [Discussion](https://news.ycombinator.com/item?id=48662999)

<details><summary>References</summary>
<ul>
<li><a href="https://agentic.ai/c/browser-computer-use">Browser & Computer Use - Agentic AI Tools | Agentic. ai</a></li>
<li><a href="https://lapu.ai/computer-use-ai">Computer Use AI : Anthropic, Operator, Desktop Agents</a></li>

</ul>
</details>

**Discussion**: HN users express frustration with Gemini's error handling on repetitive tasks, lack of MCP support and coding workflows versus competitors, and skepticism about the practicality of computer use due to speed and security issues.

**Tags**: `#Gemini`, `#AI agents`, `#Google AI`, `#LLM capabilities`, `#agentic AI`

---

<a id="item-9"></a>
## [NVIDIA 45°C Cooling Design Cuts Data Center Water Use to Near Zero](https://blogs.nvidia.com/blog/liquid-cooling-ai-factories/) ⭐️ 7.0/10

NVIDIA published a blog post describing a 45°C liquid cooling architecture for AI data centers that uses dry coolers to exhaust heat and nearly eliminates water consumption. The architecture reduces both energy and water usage in AI data centers, supporting more sustainable scaling of AI infrastructure amid growing power and resource demands. The direct-to-chip liquid cooling operates at up to 45°C coolant input temperature, higher than the 30-35°C range of most existing liquid-cooled systems, removing the need for mechanical refrigeration or evaporative cooling.

hackernews · nitin_flanker · Jun 24, 14:10 · [Discussion](https://news.ycombinator.com/item?id=48660178)

<details><summary>References</summary>
<ul>
<li><a href="https://techstory.in/the-45c-breakthrough-nvidias-liquid-cooling-architecture-solves-data-center-water-crisis/">NVIDIA Liquid Cooling Design Cuts Water to Near Zero</a></li>
<li><a href="https://www.guru3d.com/story/nvidia-unveils-liquid-cooling-design-for-ai-data-centers/">NVIDIA Unveils 45 ° C Liquid Cooling Design for AI Data Centers</a></li>

</ul>
</details>

**Discussion**: Commenters question the novelty versus prior liquid cooling designs, express doubt about claims of truly zero water consumption, and propose synergies with district heating systems while noting climate dependencies.

**Tags**: `#data-centers`, `#liquid-cooling`, `#AI-infrastructure`, `#energy-efficiency`, `#NVIDIA`

---

<a id="item-10"></a>
## [John Carmack Reflects on Early Mistakes at id Software](https://twitter.com/ID_AA_Carmack/status/2069799283369345247) ⭐️ 7.0/10

John Carmack reflected on his mistakes at id Software, including pushing teams too hard without allowing slack as the company matured and noting that Quake gutted the company. This provides valuable lessons on leadership and team management in the game development industry, highlighting the risks of sustained high-intensity work. Carmack specifically mentioned not appreciating how maturing companies need more slack and that running people at startup intensity constantly wears them out, with Quake's impact being a key point.

hackernews · shadowtree · Jun 24, 15:56 · [Discussion](https://news.ycombinator.com/item?id=48661825)

**Discussion**: Commenters discussed Sandy Petersen's perspective on the events, debated whether Quake was worth the cost to the company, and noted the shift in creative energy after key staff left.

**Tags**: `#game-development`, `#john-carmack`, `#id-software`, `#leadership`, `#software-history`

---

<a id="item-11"></a>
## [Nub Adds Bun-like Features to Stock Node.js via Preload Hooks](https://github.com/nubjs/nub) ⭐️ 7.0/10

Nub enhances Node.js with Bun-like features including TypeScript transpilation, custom module resolution, and polyfills by using a --require preload hook powered by the oxc compiler packaged as a Node-API add-on. This approach delivers improved developer experience on the standard Node runtime without requiring a switch to Bun, potentially broadening access to modern JavaScript tooling while preserving compatibility with Node's engine and standard library. All enhancements remain purely additive as code ultimately executes on Node's actual implementations; the creator is Colin McDonnell, author of Zod and former Bun contributor, with early user reports indicating successful monorepo migrations and high speed.

hackernews · colinmcd · Jun 24, 14:14 · [Discussion](https://news.ycombinator.com/item?id=48660267)

**Background**: Node.js supports preload hooks via the --require flag and module customization through registerHooks to modify resolution and loading behavior. Oxc is a Rust-based high-performance JavaScript toolchain used here for fast transpilation.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/oxc-project/oxc">GitHub - oxc-project/oxc: ⚓ A collection of high-performance JavaScript tools.</a></li>
<li><a href="https://nodejs.org/api/module.html">Modules : ` node : module ` API | Node . js v26.3.0 Documentation</a></li>

</ul>
</details>

**Discussion**: Commenters praised the idea and noted the creator's background with Zod and Bun; users reported seamless monorepo adoption with zero issues, while some raised questions about ESM support nuances and comparisons to native TypeScript execution in recent Node versions.

**Tags**: `#Node.js`, `#Bun`, `#TypeScript`, `#Developer Tools`, `#Show HN`

---

<a id="item-12"></a>
## [Tom MacWright Warns of LLM-Generated Anonymity in Hiring](https://simonwillison.net/2026/Jun/24/tom-macwright/#atom-everything) ⭐️ 7.0/10

Tom MacWright reported seeing job applications clearly co-written by LLMs that link to LLM-generated portfolio sites and GitHub projects with purely LLM-generated commit messages. This development makes candidate profiles generic and impersonal, preventing employers from learning anything personal about applicants beyond the tools they use. MacWright notes that perfected LLM-generated resumes tell nothing true about the person and create accidental anonymity through over-reliance on AI assistance.

rss · Simon Willison · Jun 24, 18:13

**Tags**: `#ai`, `#careers`, `#llm`, `#hiring`, `#authenticity`

---

<a id="item-13"></a>
## [Datasette 1.0a35 Adds Create and Alter Table Interfaces](https://simonwillison.net/2026/Jun/23/datasette/#atom-everything) ⭐️ 7.0/10

Datasette 1.0a35 introduces new Create table and Alter table interfaces backed by JSON APIs at /<database>/-/create and /<database>/<table>/-/alter. These support defining columns, primary keys, constraints, defaults, foreign keys, plus column add/rename/reorder/drop and table rename operations. The update brings direct web-based schema management to Datasette, reducing reliance on external SQL tools and improving accessibility for data exploration workflows. It affects data journalists, developers, and users building custom data applications on the platform. The features are implemented via new endpoints documented in the JSON API section, with the alter dialog also including a drop table option; additional template context documentation was added as a stable API until version 2.0.

rss · Simon Willison · Jun 23, 21:34

**Tags**: `#datasette`, `#database`, `#release`, `#json-api`, `#data-tools`

---

<a id="item-14"></a>
## [Papers with Code curates top open-source OCR models and benchmarks](https://www.reddit.com/r/MachineLearning/comments/1ueiam6/find_the_best_opensource_ocr_models_in_one_place/) ⭐️ 7.0/10

A Reddit post links to a Papers with Code overview aggregating major OCR benchmarks and top open models with code and papers. Baidu released Unlimited OCR, a 3B-parameter model using Reference Sliding Window Attention on top of DeepSeek OCR, while Mistral released OCR 4 available only via API. The curation helps users select effective OCR tools for digitizing documents, supporting agentic RAG and multimodal AI workflows across companies. Recent releases from Baidu and Mistral highlight rapid progress in open and commercial OCR solutions. Recommended benchmarks include OlmOCRBench from Ai2 and OmniDocBench from Shanghai AI Laboratory, with top models being Chandra OCR 2 from Datalab and Mistral OCR v4. Unlimited OCR introduces R-SWA for efficient long-sequence handling and is hosted on Hugging Face.

reddit · r/MachineLearning · /u/NielsRogge · Jun 24, 16:26

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/baidu/Unlimited-OCR">baidu/Unlimited-OCR · Hugging Face</a></li>
<li><a href="https://www.emergentmind.com/topics/reference-sliding-window-attention-r-swa">Reference Sliding Window Attention ( R - SWA )</a></li>

</ul>
</details>

**Tags**: `#OCR`, `#Open Source Models`, `#Papers with Code`, `#Document AI`, `#Multimodal AI`

---

<a id="item-15"></a>
## [HDD-RoPE Offers High-Dimensional Dynamic Rotary Positional Embeddings](https://www.reddit.com/r/MachineLearning/comments/1uelcm9/high_dimensional_dynamic_rotary_positional/) ⭐️ 7.0/10

HDD-RoPE introduces high-dimensional dynamic rotary positional embeddings via cumulative matrix products, achieving faster validation loss convergence than xPos on TinyStories with a GPT-2-like model (n_blocks=4, d_model=768). This approach extends standard RoPE by treating sequence positions as multidimensional and data-dependent, potentially improving transformer training efficiency and modeling of complex structures like sentences or paragraphs. It breaks queries and keys into 4D chunks yielding 6 rotation axes instead of pairs of two, with rotations made data-dependent; full math, architecture details, and replication code are available at https://github.com/mikayahlevi/hdd-rope/.

reddit · r/MachineLearning · /u/mikayahlevi · Jun 24, 18:16

**Background**: Standard RoPE rotates query-key pairs at predefined rates to encode relative positions in sequences. xPos is an enhancement to RoPE that improves extrapolation and reduces attention score oscillations for longer sequences.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/jploski/RotaryEmbedding">GitHub - jploski/RotaryEmbedding: Comparison of RoPE and xPos positional embeddings used in LLMs</a></li>
<li><a href="https://github.com/lucidrains/rotary-embedding-torch">GitHub - lucidrains/rotary-embedding-torch: Implementation of Rotary Embeddings, from the Roformer paper, in Pytorch · GitHub</a></li>
<li><a href="https://arxiv.org/abs/2305.07759">[2305.07759] TinyStories: How Small Can Language Models Be and Still Speak Coherent English?</a></li>

</ul>
</details>

**Tags**: `#Transformers`, `#Positional Embeddings`, `#RoPE`, `#Machine Learning`, `#Deep Learning`

---

<a id="item-16"></a>
## [Spreadsheet Compares LLM Inference Pricing Across 7 Providers](https://www.reddit.com/r/MachineLearning/comments/1ueavxn/i_compiled_llm_inference_pricing_across_7/) ⭐️ 7.0/10

A Reddit post shares a spreadsheet compiling public LLM inference pricing data from 7 providers including OpenRouter, DeepSeek, Together AI, Fireworks, and Groq, with emphasis on dramatic variations in cached input token costs. Cached input pricing can make repeated contexts like system prompts or RAG pipelines tens of times cheaper than standard rates, shifting focus from headline token prices to provider caching policies for cost optimization in production workloads. The sheet tracks input/output pricing, context windows, and cached input rates where available, noting that the same model can cost multiple times more depending on the provider and that some providers document caching poorly.

reddit · r/MachineLearning · /u/Technomadlyf · Jun 24, 11:28

**Background**: Prompt caching reuses processed tokens for stable prefixes such as long system prompts, allowing providers to charge reduced rates on cache hits. This feature appears in pricing from multiple LLM inference services and directly affects costs for agents and multi-turn applications.

<details><summary>References</summary>
<ul>
<li><a href="https://www.truefoundry.com/blog/provider-agnostic-prompt-caching-llm-gateway">Provider-Agnostic Prompt Caching : How an LLM Gateway Normalizes...</a></li>

</ul>
</details>

**Tags**: `#LLM pricing`, `#inference costs`, `#caching`, `#AI providers`, `#cost optimization`

---

<a id="item-17"></a>
## [uv 0.11.24 Adds CPython 3.15 Beta Support and Relocatable Environments](https://github.com/astral-sh/uv/releases/tag/0.11.24) ⭐️ 6.0/10

uv version 0.11.24 was released on 2026-06-23, adding support for CPython 3.15.0b3 and making project environments relocatable under preview. This update improves compatibility with upcoming Python versions and allows easier portability of environments across systems, benefiting developers using uv for package and project management. Notable changes include a compact index for lazy version maps for performance, fixes for exclude-newer disabling, archive collisions, and Fish shell activation scripts, along with cleanup of partial tool installs.

github · github-actions[bot] · Jun 23, 21:16

**Background**: uv is an extremely fast Python package and project manager written in Rust that aims to replace tools like pip and virtualenv. Relocatable environments allow virtual environments to be moved to different directories or machines without breaking paths.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/astral-sh/uv">GitHub - astral-sh/uv: An extremely fast Python package and project manager, written in Rust. · GitHub</a></li>

</ul>
</details>

**Tags**: `#uv`, `#python`, `#package-manager`, `#release`, `#astral-sh`

---

<a id="item-18"></a>
## [Bunny.net Makes Bunny DNS Free with No Query Fees](https://bunny.net/blog/were-making-bunny-dns-free/) ⭐️ 6.0/10

Bunny.net announced that Bunny DNS no longer charges for DNS queries and now includes free DNS hosting for up to 500 domains per account. All features including smart records and health monitoring are available without enterprise plans or query limits. The change strengthens Bunny.net as a competitive EU-based alternative to Cloudflare for DNS services and may attract users concerned about geopolitics or seeking simpler pricing. It highlights a privately funded European provider focusing on organic growth rather than loss-leader tactics. The service runs on a dual-stack anycast network supporting IPv4 and IPv6 with no per-request billing or query caps. Users can import zones but may need to manually add certain records such as HTTPS records.

hackernews · dabinat · Jun 24, 08:50 · [Discussion](https://news.ycombinator.com/item?id=48657030)

<details><summary>References</summary>
<ul>
<li><a href="https://bunny.net/blog/were-making-bunny-dns-free/">We’re making Bunny DNS free</a></li>
<li><a href="https://bunny.net/dns/">Bunny DNS | The #1 Scriptable DNS Platform | bunny.net</a></li>

</ul>
</details>

**Discussion**: Commenters welcomed the EU-based alternative to Cloudflare for geopolitical reasons and praised the company's organic growth model with minimal outside funding. Some users reported successful migrations while noting minor import limitations such as missing HTTPS records.

**Tags**: `#DNS`, `#Pricing`, `#Bunny.net`, `#Cloudflare alternative`, `#Infrastructure`

---

<a id="item-19"></a>
## [PR Spam on Open Source Projects Resembles Early 2000s Email Spam](https://www.greptile.com/blog/prs-on-openclaw) ⭐️ 6.0/10

A blog post draws parallels between today's spam pull requests on open source projects and early-2000s email spam while highlighting community suggestions for mitigation. This highlights ongoing challenges for open source maintainers dealing with spam, potentially affecting project sustainability and contributor experience in the GitHub ecosystem. The post notes parallels including volume and low-quality contributions, with suggestions like PR limits recently added by GitHub.

hackernews · dakshgupta · Jun 24, 14:32 · [Discussion](https://news.ycombinator.com/item?id=48660579)

**Discussion**: Commenters suggest GitHub's new PR limits, reputation systems based on organizations, in-person meetings for contributors, and token credit donations as solutions, while noting differences from email spam handling.

**Tags**: `#open-source`, `#pull-requests`, `#github`, `#spam`, `#maintainer-tools`

---

<a id="item-20"></a>
## [Simon Willison Converts MDN Data to 66MB SQLite Database](https://simonwillison.net/2026/Jun/24/browser-compat-db/#atom-everything) ⭐️ 6.0/10

Simon Willison converted the MDN browser-compat-data repository into a ~66MB SQLite database using AI-generated scripts built with sqlite-utils and Claude Code. The database is hosted on GitHub with open CORS headers, enabling direct browser access and exploration via Datasette Lite for web developers needing queryable compatibility information. AI tools including Claude Code for web and Codex Desktop generated the build script and GitHub Actions workflow that force-pushes the database to an orphan db branch.

rss · Simon Willison · Jun 24, 23:59

**Background**: MDN browser-compat-data is Mozilla's repository containing detailed browser support information for web platform features. sqlite-utils is a Python library and CLI tool for creating and populating SQLite databases efficiently.

<details><summary>References</summary>
<ul>
<li><a href="https://sqlite-utils.datasette.io/">sqlite - utils</a></li>
<li><a href="https://developer.mozilla.org/en-US/blog/introducing-mdn-mcp-server/">Introducing the MDN MCP server</a></li>

</ul>
</details>

**Tags**: `#SQLite`, `#browser-compatibility`, `#MDN`, `#data-conversion`, `#AI-tools`

---

<a id="item-21"></a>
## [Simon Willison Builds OPFS + Pyodide Test Harness for Datasette Lite](https://simonwillison.net/2026/Jun/23/opfs-pyodide/#atom-everything) ⭐️ 6.0/10

Simon Willison created an OPFS + Pyodide test harness at tools.simonwillison.net/opfs-pyodide to explore persistent SQLite file editing in Datasette Lite using the Origin Private File System API. This experiment could enable persistent client-side SQLite storage in browser-based Python applications like Datasette Lite, advancing web-only data tools without server dependencies. The playground UI was generated with Claude Code for web and tests OPFS performance across browsers for optimized file operations in Pyodide WebAssembly environments.

rss · Simon Willison · Jun 23, 18:58

**Background**: OPFS provides a private, high-performance storage endpoint in the browser via the File System API. Pyodide runs Python in WebAssembly, powering Datasette Lite as a fully client-side data exploration tool.

<details><summary>References</summary>
<ul>
<li><a href="https://developer.mozilla.org/en-US/docs/Web/API/File_System_API/Origin_private_file_system">Origin private file system - Web APIs | MDN</a></li>
<li><a href="https://github.com/simonw/datasette-lite">GitHub - simonw/datasette-lite: Datasette running in your browser using WebAssembly and Pyodide · GitHub</a></li>

</ul>
</details>

**Tags**: `#Pyodide`, `#OPFS`, `#Datasette`, `#WebAssembly`, `#Browser APIs`

---