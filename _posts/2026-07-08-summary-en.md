---
layout: default
title: "Horizon Summary: 2026-07-08 (EN)"
date: 2026-07-08
lang: en
---

> From 32 items, 17 important content pieces were selected

---

1. [EU Chat Control 1.0 and 2.0 Proposals Explained](#item-1) ⭐️ 8.0/10
2. [EU Mandates Driver Monitoring Cameras in All New Cars](#item-2) ⭐️ 8.0/10
3. [sqlite-utils 4.0 Adds Schema Migrations, Nested Transactions](#item-3) ⭐️ 8.0/10
4. [Tencent Releases Hy3 295B Apache 2.0 MoE Model](#item-4) ⭐️ 8.0/10
5. [MIRA: 5B-Parameter Multiplayer World Model Trained on Rocket League Released](#item-5) ⭐️ 8.0/10
6. [Kokoro Delivers High-Quality CPU-Friendly Local TTS](#item-6) ⭐️ 7.0/10
7. [Show HN: Davit, Native macOS UI for Apple Containers](#item-7) ⭐️ 7.0/10
8. [TorchJD: PyTorch Library for Multi-Loss Training via Jacobian Descent](#item-8) ⭐️ 7.0/10
9. [PhD Thesis Presents Differentiable Ray Tracing with JAX for Radio Modeling](#item-9) ⭐️ 7.0/10
10. [LLM Know-Say Gap Acts as Routing Problem Fixable by Hidden-State Probes](#item-10) ⭐️ 7.0/10
11. [ICML Paper Proposes Credit System to Improve ML Peer Reviews](#item-11) ⭐️ 7.0/10
12. [LingBot-Depth 2.0 Achieves SOTA Results via Sensor-Validity Masking](#item-12) ⭐️ 7.0/10
13. [LingBot-Vision Uses Masked Boundary Modeling for Self-Supervised Vision Pretraining](#item-13) ⭐️ 7.0/10
14. [StreetComplete App Simplifies OpenStreetMap Data Contributions](#item-14) ⭐️ 6.0/10
15. [30papers.com Curates 30 Essential ML Papers Attributed to Ilya Sutskever](#item-15) ⭐️ 6.0/10
16. [New Closed-Source Runtime 'l' Announced for K and Q Languages](#item-16) ⭐️ 6.0/10
17. [Paper Proposes Trusted LoRA Subspace to Block Fine-Tuning Poisoning](#item-17) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [EU Chat Control 1.0 and 2.0 Proposals Explained](https://fightchatcontrol.eu/chat-control-overview) ⭐️ 8.0/10

The overview explains Chat Control 1.0 as a temporary derogation from the ePrivacy Directive that permitted voluntary CSAM scanning until its extension to April 2026, while Chat Control 2.0 refers to the proposed permanent Child Sexual Abuse Regulation mandating scanning on encrypted communications. These proposals could force changes to end-to-end encryption across EU services, affecting millions of users and major providers like Google and Meta by introducing mandatory client-side or server scanning that raises broad surveillance risks. Chat Control 1.0 allowed but did not require scanning of unsuspected users and expires soon, while 2.0 aims for mandatory detection that may require either MITM decryption or non-modifiable on-device functionality similar to Apple's earlier CSAM scanner approach.

hackernews · gasull · Jul 7, 14:23 · [Discussion](https://news.ycombinator.com/item?id=48818311)

**Background**: End-to-end encryption protects message confidentiality by ensuring only sender and receiver can read content, while CSAM refers to child sexual abuse material that regulators seek to detect through scanning systems.

<details><summary>References</summary>
<ul>
<li><a href="https://fightchatcontrol.eu/chat-control-overview">Chat Control 1.0 vs 2.0 - Fight Chat Control</a></li>
<li><a href="https://en.wikipedia.org/wiki/Chat_Control">Chat Control - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters express strong opposition to the proposals as overbroad surveillance measures, question technical implementations like client-side scanning or MITM access, and highlight risks of false positives along with concerns that it undermines democracy and encryption for all users.

**Tags**: `#privacy`, `#encryption`, `#EU regulation`, `#surveillance`, `#CSAM`

---

<a id="item-2"></a>
## [EU Mandates Driver Monitoring Cameras in All New Cars](https://allaboutcookies.org/eu-mandatory-distracted-driver-system) ⭐️ 8.0/10

The European Union regulation now requires a driver monitoring camera in every new car sold to detect distracted driving. The mandate targets improved road safety across the EU but raises concerns about intrusive alerts and degraded user experience in modern vehicles. Commenters cite problems such as inaccurate cruise-control speed-limit detection and constant beeping, while noting accurate attention monitoring in systems like Ford BlueCruise.

hackernews · nickslaughter02 · Jul 7, 20:50 · [Discussion](https://news.ycombinator.com/item?id=48823557)

**Discussion**: Users report frustration with unturn-offable lane assist, unreliable remote functions, and excessive alerts, yet some recognize the potential safety gains from attention-monitoring nudges.

**Tags**: `#EU regulations`, `#automotive safety`, `#driver monitoring`, `#computer vision`, `#UX design`

---

<a id="item-3"></a>
## [sqlite-utils 4.0 Adds Schema Migrations, Nested Transactions](https://simonwillison.net/2026/Jul/7/sqlite-utils-4/#atom-everything) ⭐️ 8.0/10

sqlite-utils 4.0 was released as the first major version since 3.0 in 2020, introducing database schema migrations, nested transactions via db.atomic(), and compound foreign keys along with some breaking changes. This update brings powerful migration capabilities to the widely used sqlite-utils library, helping developers manage evolving SQLite schemas more reliably in Python projects and tools like Datasette. Migrations are defined in Python files using the Migrations class and table.transform() which recreates tables to overcome SQLite ALTER TABLE limits; they can be applied with the command uvx sqlite-utils migrate.

rss · Simon Willison · Jul 7, 19:32

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/simonw/sqlite-utils">GitHub - simonw/sqlite-utils: Python CLI utility and library for ...</a></li>

</ul>
</details>

**Tags**: `#sqlite`, `#python`, `#database-migrations`, `#sqlite-utils`, `#datasette`

---

<a id="item-4"></a>
## [Tencent Releases Hy3 295B Apache 2.0 MoE Model](https://simonwillison.net/2026/Jul/6/hy3/#atom-everything) ⭐️ 8.0/10

Tencent releases Hy3, a 295B-parameter Mixture-of-Experts model with 21B active parameters and 3.8B MTP layer parameters under Apache 2.0 license. The model is available in 598GB full and 300GB FP8 quantized forms with 256K context length on Hugging Face. Hy3 rivals flagship open-source models with 2-5x more parameters while remaining openly available, strengthening competition in the open-weight LLM space from a major Chinese lab. Developers and products can access it freely on OpenRouter until July 21st. The full model weights occupy 598GB while the FP8 quantized version is 300GB; it includes 3.8B MTP layer parameters and supports 256K context. Post-training used higher-quality data after feedback from over 50 products.

rss · Simon Willison · Jul 6, 23:57

**Background**: Mixture-of-Experts models activate only a subset of parameters per token to improve efficiency. FP8 quantization reduces weight precision to 8-bit floating point for smaller size and faster inference. MTP layers add multi-token prediction heads to the architecture.

<details><summary>References</summary>
<ul>
<li><a href="https://www.spheron.network/blog/fp8-quantization-inference-performance-hardware-explained/">What is FP8 Quantization? AI Inference Performance, Accuracy, and Hardware Support Explained (2026) | Spheron Blog</a></li>
<li><a href="https://sebastianraschka.com/llm-architecture-gallery/mtp/">Multi-Token Prediction (MTP) | Sebastian Raschka, PhD</a></li>

</ul>
</details>

**Tags**: `#LLM`, `#MoE`, `#Open Source Models`, `#Tencent`, `#AI Release`

---

<a id="item-5"></a>
## [MIRA: 5B-Parameter Multiplayer World Model Trained on Rocket League Released](https://www.reddit.com/r/MachineLearning/comments/1upofuw/mira_multiplayer_interactive_world_models_trained/) ⭐️ 8.0/10

MIRA, a 5B-parameter multiplayer interactive world model developed by General Intuition, Kyutai, and Epic Games, was trained on 10k hours of synthetic Rocket League data and released with a playable demo, technical report, and 1k-hour 4-player dataset. This release advances scalable multiplayer world models for dynamic physical simulations, enabling real-time interaction research in reinforcement learning and game AI with open resources for the community. The model runs four players at 20 fps on a single B200 GPU; it conditions on multiple agents' action streams to maintain coherence in complex interactions, as detailed in the associated arXiv paper.

reddit · r/MachineLearning · /u/MasterScrat · Jul 7, 07:59

**Background**: World models are internal simulators in reinforcement learning that learn environment dynamics to enable prediction, planning, and reduced real interactions, as discussed in recent surveys on RL and interactive simulations.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2607.05352">[2607.05352] Multiplayer Interactive World Models with ...</a></li>

</ul>
</details>

**Tags**: `#world models`, `#game AI`, `#reinforcement learning`, `#multiplayer simulation`, `#machine learning`

---

<a id="item-6"></a>
## [Kokoro Delivers High-Quality CPU-Friendly Local TTS](https://ariya.io/2026/03/local-cpu-friendly-high-quality-tts-text-to-speech-with-kokoro/) ⭐️ 7.0/10

Kokoro is an open-weight TTS model with 82 million parameters that achieves high-quality natural speech while running efficiently on CPUs without GPUs. It lowers barriers for local AI adoption by enabling high-quality text-to-speech on everyday hardware, benefiting accessibility tools and personal content readers. The model supports manual IPA pronunciation guides for handling homographs and has been integrated into web UIs, RSS podcast workflows, and browser extensions.

hackernews · speckx · Jul 7, 18:24 · [Discussion](https://news.ycombinator.com/item?id=48821576)

**Background**: Text-to-speech systems convert written text into audio, and many high-quality models previously demanded NVIDIA GPUs for inference.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/hexgrad/kokoro">GitHub - hexgrad/kokoro: https://hf.co/hexgrad/Kokoro-82M</a></li>

</ul>
</details>

**Discussion**: Users praise Kokoro for running well without GPUs, highlight its use in accessibility products and article readers, and share extensions for seamless webpage integration, though some note minor issues with single-word pronunciation.

**Tags**: `#TTS`, `#local AI`, `#CPU inference`, `#text-to-speech`, `#open-source models`

---

<a id="item-7"></a>
## [Show HN: Davit, Native macOS UI for Apple Containers](https://davit.app/) ⭐️ 7.0/10

Davit, a lightweight native Swift UI for Apple's container platform, was released on Show HN with its full source code available on GitHub. It offers a simple, native alternative to tools like OrbStack for managing Apple's new Linux containers on macOS, improving usability for developers on Apple silicon. The app is 17 MB, uses the ContainerAPIClient library directly, contains 5,015 lines of Swift across 28 commits, and is signed and notarized; it auto-downloads the container runtime on first launch.

hackernews · xinit · Jul 7, 18:44 · [Discussion](https://news.ycombinator.com/item?id=48821848)

**Background**: Apple Container is an open-source command-line tool introduced in 2025 that runs Linux containers as lightweight virtual machines on macOS, using a one-VM-per-container model optimized for Apple silicon and OCI-compatible images.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/wouterdebie/davit">GitHub - wouterdebie/davit: A native macOS UI for Apple's ...</a></li>
<li><a href="https://github.com/apple/container">GitHub - apple/container: A tool for creating and running ...</a></li>

</ul>
</details>

**Discussion**: Users praised its small size, native macOS feel, and quick functionality with images like nginx:latest; some noted its Claude-assisted development and suggested adding tutorials, while others compared it favorably to OrbStack.

**Tags**: `#Apple Containers`, `#macOS`, `#Swift`, `#UI tools`, `#Show HN`

---

<a id="item-8"></a>
## [TorchJD: PyTorch Library for Multi-Loss Training via Jacobian Descent](https://www.reddit.com/r/MachineLearning/comments/1upzxk2/torchjd_training_with_multiple_losses_in_pytorch_p/) ⭐️ 7.0/10

TorchJD, a PyTorch library implementing Jacobian descent methods for multi-loss optimization, has been accepted into the PyTorch ecosystem and now includes most existing methods from the literature for both Jacobian descent and scalarization approaches. It provides practitioners with an easy way to experiment with advanced multi-objective optimization techniques that can outperform simple loss averaging when objectives conflict, potentially improving training in multi-task learning and constrained models. The library extends autograd to compute Jacobians and supports various aggregators; scalarization remains cheaper in memory while Jacobian methods handle objective disagreement better.

reddit · r/MachineLearning · /u/Skeylos2 · Jul 7, 16:20

**Background**: Multi-loss training arises in multi-task learning, regularization, and constrained optimization where models must balance several objectives simultaneously. Traditional scalarization combines losses into one scalar before applying gradient descent, whereas Jacobian descent uses the full matrix of per-loss gradients to find updates that improve all objectives.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/TorchJD/torchjd">GitHub - SimplexLab/TorchJD: Library for Jacobian descent with PyTorch. It enables the optimization of neural networks with multiple losses (e.g. multi-task learning). · GitHub</a></li>
<li><a href="https://arxiv.org/abs/2406.16232">[2406.16232] Jacobian Descent for Multi-Objective Optimization</a></li>

</ul>
</details>

**Tags**: `#PyTorch`, `#Multi-task learning`, `#Optimization`, `#Machine Learning`, `#Jacobian descent`

---

<a id="item-9"></a>
## [PhD Thesis Presents Differentiable Ray Tracing with JAX for Radio Modeling](https://www.reddit.com/r/MachineLearning/comments/1upvkp5/phd_thesis_on_differentiable_ray_tracing_for/) ⭐️ 7.0/10

A Ph.D. thesis introduces differentiable ray tracing implemented in JAX for radio propagation modeling to enable gradient-based optimization and machine learning in wireless systems. The manuscript is structured as an accessible textbook with open-source libraries such as DiffeRT and covers physics fundamentals, GPU-accelerated algorithms, and practical applications. This work enables solving inverse problems in wireless communications by computing exact gradients through physical simulations, supporting next-generation system design that integrates machine learning directly with propagation modeling. The thesis details GPU-accelerated path tracing, discontinuity smoothing techniques for stable differentiation, and applications including channel modeling, localization, and material calibration, while relying on JAX packages such as equinox and optimistix.

reddit · r/MachineLearning · /u/jeertmans · Jul 7, 13:45

**Background**: Ray tracing simulates electromagnetic wave propagation using geometrical optics, while automatic differentiation frameworks like JAX allow computation of gradients through simulation code for optimization tasks.

<details><summary>References</summary>
<ul>
<li><a href="https://research.nvidia.com/publication/2024-10_learning-radio-environments-differentiable-ray-tracing">Learning Radio Environments by Differentiable Ray Tracing | Research</a></li>
<li><a href="https://docs.jax.dev/en/latest/notebooks/autodiff_cookbook.html">The Autodiff Cookbook — JAX documentation</a></li>

</ul>
</details>

**Tags**: `#PhD thesis`, `#Differentiable ray tracing`, `#JAX`, `#Autodiff`, `#Wireless communications`

---

<a id="item-10"></a>
## [LLM Know-Say Gap Acts as Routing Problem Fixable by Hidden-State Probes](https://www.reddit.com/r/MachineLearning/comments/1uqg3g1/the_llm_knowsay_gap_looks_like_a_routing_problem/) ⭐️ 7.0/10

A linear probe on mid-layer hidden states discriminates correct from incorrect LLM answers at type-2 AUROC 0.83-0.88 across five base models from 7B to 72B. Verbalized confidence remains near-random at 0.57-0.58 AUROC, but a minimal ten-parameter bridge routes the internal signal to outputs reaching 0.765 AUROC without changing base weights. This reveals that LLMs internally encode answer correctness yet fail to route it to generated tokens, enabling low-cost calibration improvements below frontier scale without retraining. The approach outperforms several single-pass baselines at roughly one-fifth the inference cost of multi-sample methods. The controller is supervised, inherits probe discrimination limits, and shows no performance difference when installed before or after alignment. It wins 13 of 15 comparisons against standard readouts and never inverts, unlike P(True) or answer log-probability.

reddit · r/MachineLearning · /u/Synthium- · Jul 8, 02:40

**Background**: Linear probes are simple classifiers trained on frozen intermediate activations to test whether a property is linearly decodable from network layers. Type-2 AUROC measures how well a signal discriminates correct from incorrect answers across thresholds, with 0.5 indicating chance performance.

<details><summary>References</summary>
<ul>
<li><a href="https://www.emergentmind.com/topics/linear-probes">Linear Probes: Neural Network Diagnostics - emergentmind.com</a></li>
<li><a href="https://en.wikipedia.org/wiki/Receiver_operating_characteristic">Receiver operating characteristic - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#LLMs`, `#Interpretability`, `#Model Calibration`, `#Probing`, `#AI Research`

---

<a id="item-11"></a>
## [ICML Paper Proposes Credit System to Improve ML Peer Reviews](https://www.reddit.com/r/MachineLearning/comments/1upjftu/icml_position_track_want_better_ml_reviews_stop/) ⭐️ 7.0/10

A position paper submitted to the ICML Position Track proposes a credit system that awards points to reviewers, authors, and organizers for positive actions such as completing reviews or providing constructive feedback. The proposal targets persistent accountability problems in machine learning conference peer review by replacing voluntary guidelines with tangible incentives, potentially raising review quality for the entire ICML community. Points can be earned for standard reviews (+1) or outstanding reviews (+3) and spent on perks including free registration or requesting extra reviewers; additional ideas include refundable submission fees and greater use of non-author reviewers.

reddit · r/MachineLearning · /u/choHZ · Jul 7, 03:32

**Tags**: `#peer review`, `#ICML`, `#machine learning conferences`, `#incentives`, `#academic publishing`

---

<a id="item-12"></a>
## [LingBot-Depth 2.0 Achieves SOTA Results via Sensor-Validity Masking](https://www.reddit.com/r/MachineLearning/comments/1upqghy/masked_depth_modeling_with_sensorvalidity_masking/) ⭐️ 7.0/10

Robbyant released LingBot-Depth 2.0, which uses sensor missing regions as natural masks for masked depth modeling instead of random dropout, reporting best RMSE on 7 of 8 benchmarks across multiple capture suites. This approach aligns training directly with real sensor failure distributions, potentially improving robustness in embodied AI and robotic spatial perception tasks where depth data is often incomplete. A controlled encoder-init study shows LingBot-Vision initialization outperforming alternatives at ViT-L and ViT-g scales, with performance gaps widening at larger data scales; only LingBot-Vision backbones are open-sourced under Apache-2.0.

reddit · r/MachineLearning · /u/Ok-Line2658 · Jul 7, 09:54

**Background**: Masked depth modeling treats depth estimation as an inpainting task within Transformer architectures, allowing the same framework to handle both monocular estimation and depth completion depending on the masking strategy applied to RGB-D inputs.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/Robbyant/lingbot-depth">GitHub - Robbyant/lingbot-depth: Masked Depth Modeling for Spatial Perception · GitHub</a></li>
<li><a href="https://arxiv.org/html/2601.17895v1">Masked Depth Modeling for Spatial Perception</a></li>

</ul>
</details>

**Tags**: `#depth estimation`, `#masked modeling`, `#computer vision`, `#embodied AI`, `#sensor masking`

---

<a id="item-13"></a>
## [LingBot-Vision Uses Masked Boundary Modeling for Self-Supervised Vision Pretraining](https://www.reddit.com/r/MachineLearning/comments/1up4cjh/lingbotvision_masked_boundary_modeling_for/) ⭐️ 7.0/10

LingBot-Vision introduces teacher-guided masked boundary modeling for self-supervised pretraining of Vision Transformers, achieving 0.296 NYUv2 linear-probe RMSE with a 1.1B model compared to 0.309 for DINOv3-7B while using 161M images. This approach demonstrates competitive dense perception performance with smaller models than DINOv3, potentially reducing compute needs for vision tasks like depth estimation and segmentation in robotics and autonomous systems. The method predicts dense boundary fields online from the teacher, forces boundary tokens into the student mask, recasts boundaries as categorical distributions, and applies a-contrario validation; public weights are available in four sizes under Apache-2.0, though results are self-reported without external verification.

reddit · r/MachineLearning · /u/StillThese3747 · Jul 6, 17:37

**Background**: Self-supervised pretraining for vision transformers often relies on masked modeling where random patches are hidden and reconstructed to learn representations without labels. DINOv3 is a recent self-distillation method that produces strong dense features for downstream tasks like depth estimation on datasets such as NYUv2.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/Robbyant/lingbot-vision">GitHub - Robbyant/lingbot-vision: Self-supervised learning ...</a></li>

</ul>
</details>

**Tags**: `#self-supervised learning`, `#vision transformers`, `#masked modeling`, `#boundary detection`, `#pretraining`

---

<a id="item-14"></a>
## [StreetComplete App Simplifies OpenStreetMap Data Contributions](https://streetcomplete.app/) ⭐️ 6.0/10

StreetComplete is an Android app that displays missing map data as simple quests on a map, allowing users to answer questions on-site to update OpenStreetMap without prior tagging knowledge. The app enables casual volunteers to improve the accuracy of OpenStreetMap, a key source of open geospatial data that powers many navigation and location services worldwide. Quests cover topics such as opening hours, existence of features, and crossing details, with the app available for Android phones and tablets as described on its official site and OpenStreetMap wiki.

hackernews · kls0e · Jul 7, 12:38 · [Discussion](https://news.ycombinator.com/item?id=48816883)

**Background**: OpenStreetMap is a collaborative project creating a free editable world map through volunteer contributions of data on roads, paths, and points of interest.

<details><summary>References</summary>
<ul>
<li><a href="https://streetcomplete.app/">StreetComplete</a></li>
<li><a href="https://en.wikipedia.org/wiki/StreetComplete">StreetComplete - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Users praise the app's beginner-friendly UI and fun quests but note limitations like duplicate data entry for crossings and desire for features such as adding roads; some mention alternatives like Every Door and raise concerns about commercial use of OSM data without reciprocity.

**Tags**: `#OpenStreetMap`, `#crowdsourcing`, `#mobile apps`, `#geospatial data`, `#open source`

---

<a id="item-15"></a>
## [30papers.com Curates 30 Essential ML Papers Attributed to Ilya Sutskever](https://30papers.com/) ⭐️ 6.0/10

A first-year CS student at Trinity College Dublin created 30papers.com as a side project to present 30 essential machine learning papers attributed to Ilya Sutskever in a beginner-friendly format with explanations. The site helps beginners access key ML research papers while reducing repeated queries to AI tools, though its broader impact remains limited due to questions about the list's origin and site usability. The project is a work in progress hosted on GitHub, with recent additions of toggles for page animations and backgrounds after user complaints about intensity and usability.

hackernews · notmcrowley · Jul 7, 15:58 · [Discussion](https://news.ycombinator.com/item?id=48819608)

**Discussion**: Commenters raised concerns about the unverified source of the paper list and lack of connection to Ilya Sutskever, while the author clarified it as a personal project and implemented UX improvements; suggestions included logical reading order and alternative beginner guides like Welch Labs.

**Tags**: `#machine learning`, `#research papers`, `#education`, `#beginner resources`, `#Ilya Sutskever`

---

<a id="item-16"></a>
## [New Closed-Source Runtime 'l' Announced for K and Q Languages](https://lv1.sh/) ⭐️ 6.0/10

A new closed-source runtime named 'l' for the K and Q array languages has been announced at lv1.sh, accompanied by a blog post explaining its design rationale. This addition expands options in the niche array programming space, potentially offering performance improvements, though its closed-source nature limits adoption compared to open alternatives. The runtime is proprietary and described as 'vibecoded' by commenters; it lacks public benchmarks against existing K implementations such as those listed on k.miraheze.org.

hackernews · skruger · Jul 7, 18:08 · [Discussion](https://news.ycombinator.com/item?id=48821378)

**Background**: K is a proprietary array processing language developed by Arthur Whitney and commercialized by KX Systems as the foundation for kdb+; Q serves as its query language for the same database system.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/K_programming_language">K programming language</a></li>
<li><a href="https://en.wikipedia.org/wiki/Q_(programming_language_from_Kx_Systems)">Q (programming language from Kx Systems) - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters express interest in the array language design space but criticize the closed-source approach and lack of open-source code; many point to existing open implementations like BQN, J, Klong, and ktye as preferable alternatives.

**Tags**: `#array programming`, `#K language`, `#runtime`, `#APL`, `#programming languages`

---

<a id="item-17"></a>
## [Paper Proposes Trusted LoRA Subspace to Block Fine-Tuning Poisoning](https://www.reddit.com/r/MachineLearning/comments/1uq68li/what_if_a_model_could_only_learn_what_trusted/) ⭐️ 6.0/10

A paper proposes constraining fine-tuning updates to a subspace spanned by trusted LoRA adapters to geometrically block certain malicious adaptations from poisoned data. The method was tested on 196 public LoRA adapters, including adaptive attacks, showing sharply reduced attack success while preserving useful adaptation. This approach offers a geometric defense for scenarios like company fine-tuning on user or external data and on-device assistants, limiting the space of learnable harmful behaviors without needing to detect every poison. It could impact AI safety practices in adversarial machine learning by restricting malicious fine-tuning directions. The defense restricts updates to variations represented in a trusted adapter pool rather than detecting poisons directly. Experiments covered adaptive attacks designed to bypass the constraint, with code and paper available at arxiv.org/abs/2607.05300 and github.com/infinition/z-manifold.

reddit · r/MachineLearning · /u/Bright_Warning_8406 · Jul 7, 20:00

**Background**: LoRA is a parameter-efficient fine-tuning technique that adapts large models using low-rank matrices instead of updating all parameters. Fine-tuning poisoning attacks involve injecting small amounts of malicious data to introduce hidden behaviors like backdoors triggered by specific patterns.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/LoRA_(machine_learning)">LoRA (machine learning) - Wikipedia</a></li>
<li><a href="https://arxiv.org/abs/2510.07192">[2510.07192] Poisoning Attacks on LLMs Require a Near-constant Number of Poison Samples</a></li>

</ul>
</details>

**Tags**: `#LoRA`, `#fine-tuning`, `#model poisoning`, `#adversarial ML`, `#AI safety`

---