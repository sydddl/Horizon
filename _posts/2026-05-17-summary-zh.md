---
layout: default
title: "Horizon Summary: 2026-05-17 (ZH)"
date: 2026-05-17
lang: zh
---

> From 99 items, 41 important content pieces were selected

---

1. [vLLM v0.21.0 发布：弃用 Transformers v4，要求 C++20](#item-1) ⭐️ 9.0/10
2. [最新开源模型发布：Gemma 4、DeepSeek V4 等](#item-2) ⭐️ 9.0/10
3. [廉价智能门铃漏洞可导致账户接管和通话劫持](#item-3) ⭐️ 9.0/10
4. [SGLang v0.5.12 全面支持 DeepSeek V4 推理](#item-4) ⭐️ 8.0/10
5. [Zerostack：基于 Unix 理念的纯 Rust 编码智能体](#item-5) ⭐️ 8.0/10
6. [NVIDIA 发布 SANA-WM：720p 一分钟视频生成的开源世界模型](#item-6) ⭐️ 8.0/10
7. [脱离 Tailwind，重新学习 CSS 结构](#item-7) ⭐️ 8.0/10
8. [《加速》对 AI 的预言在 2025 年成真](#item-8) ⭐️ 8.0/10
9. [现代生活过于复杂](#item-9) ⭐️ 8.0/10
10. [δ-mem：基于增量规则学习的固定大小在线记忆](#item-10) ⭐️ 8.0/10
11. [MitchellH 警告企业陷入 AI 精神病态](#item-11) ⭐️ 8.0/10
12. [Cerebras 600 亿美元 IPO 标志 AI 硬件里程碑](#item-12) ⭐️ 8.0/10
13. [新型 LLM 架构降低长上下文成本](#item-13) ⭐️ 8.0/10
14. [用 BPF 进行 Linux 内存管理的探索](#item-14) ⭐️ 8.0/10
15. [七个稳定内核发布修复 CVE-2026-46333](#item-15) ⭐️ 8.0/10
16. [Kubernetes v1.36：安全默认配置强化，AI 工作负载支持日趋成熟](#item-16) ⭐️ 8.0/10
17. [Anthropic 在 AWS 上推出 Claude 平台](#item-17) ⭐️ 8.0/10
18. [蚂蚁灵波开源 LingBot-VLA 后训练代码](#item-18) ⭐️ 8.0/10
19. [复制失败漏洞：Linux 页面缓存漏洞影响所有主流发行版](#item-19) ⭐️ 8.0/10
20. [Bun 从 Zig 重写为 Rust](#item-20) ⭐️ 8.0/10
21. [近期内核漏洞与攻击面缩减](#item-21) ⭐️ 8.0/10
22. [OxCaml 为 OCaml 提供数据竞争自由保证](#item-22) ⭐️ 8.0/10
23. [Bazel 远程缓存的内容定义分块去重](#item-23) ⭐️ 8.0/10
24. [AI 模型使传统开放式 CTF 竞赛过时](#item-24) ⭐️ 7.0/10
25. [Kioxia 与 Dell 在 2RU 服务器中塞入 10 PB](#item-25) ⭐️ 7.0/10
26. [Futhark 示例展示依赖类型在 GPU 编程中的应用](#item-26) ⭐️ 7.0/10
27. [3000 条文本描述提升视频生成模型的 3D 理解](#item-27) ⭐️ 7.0/10
28. [Linux 内核实时更新中的 HugeTLB 内存保留](#item-28) ⭐️ 7.0/10
29. [GitHub 试点通用无障碍代理](#item-29) ⭐️ 7.0/10
30. [JEP 533 加强 Java 结构化并发的异常处理](#item-30) ⭐️ 7.0/10
31. [百灵开源 Ring-2.6-1T 推理模型](#item-31) ⭐️ 7.0/10
32. [Grafana Pyroscope 2.0 实现规模化持续性能分析](#item-32) ⭐️ 7.0/10
33. [AdonisJS v7：端到端类型安全、重构模板、零配置 OpenTelemetry](#item-33) ⭐️ 7.0/10
34. [GitHub 推出 MCP 服务器集成，增强机密扫描](#item-34) ⭐️ 7.0/10
35. [熔岩灯随机性的无用性](#item-35) ⭐️ 7.0/10
36. [Zig 0.16 异步 I/O 博客文章](#item-36) ⭐️ 7.0/10
37. [订阅轰炸：一种不断增长的电子邮件攻击方式](#item-37) ⭐️ 7.0/10
38. [谷歌 IDE 发展史：从碎片化到云端](#item-38) ⭐️ 7.0/10
39. [Zulip 基金会成立以管理项目治理](#item-39) ⭐️ 7.0/10
40. [超多语言 Lisp：四种方言并排比较](#item-40) ⭐️ 7.0/10
41. [VLDB 论文提出高效 SSD 写入技术](#item-41) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [vLLM v0.21.0 发布：弃用 Transformers v4，要求 C++20](https://github.com/vllm-project/vllm/releases/tag/v0.21.0) ⭐️ 9.0/10

vLLM v0.21.0 正式弃用了对 Transformers v4 的支持，要求用户迁移到 Transformers v5，并且引入了 C++20 构建要求以兼容 PyTorch。此外，新增了 KV 卸载与混合内存分配器 (HMA) 的整合、支持思考预算的推测解码，以及用于 Blackwell GPU 的新 TOKENSPEED_MLA 后端。 此版本包含影响生产部署的重大变更，特别是弃用 Transformers v4 和 C++20 要求。KV 卸载与 HMA 的整合以及推测解码的改进，提升了大型语言模型的内存效率和推理速度。 迁移到 Transformers v5 可能需要修改代码，并且用户需要 C++20 兼容的编译器来构建 vLLM。HMA 集成实现了高效的 KV 缓存卸载到 CPU/GPU 内存，而 TOKENSPEED_MLA 后端支持在 NVIDIA Blackwell GPU 上运行 DeepSeek-R1 和 Kimi-K25 模型。

github · khluu · May 15, 08:44

**背景**: vLLM 是一个用于大型语言模型的高性能推理引擎，以其通过 PagedAttention 和连续批处理实现的高效内存管理而闻名。KV 卸载将键值缓存移动到 CPU/GPU 内存以减少 GPU 内存压力，而混合内存分配器 (HMA) 优化了不同存储层级间的内存分配。推测解码通过使用草稿模型预测输出来加速生成。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/vllm-project/vllm/issues/11382">[RFC]: Hybrid Memory Allocator · Issue #11382 · vllm -project/ vllm</a></li>
<li><a href="https://docs.vllm.ai/en/latest/api/vllm/v1/attention/backends/mla/tokenspeed_mla/">tokenspeed _ mla - vLLM</a></li>

</ul>
</details>

**标签**: `#vLLM`, `#LLM inference`, `#AI/ML`, `#release`, `#transformers`

---

<a id="item-2"></a>
## [最新开源模型发布：Gemma 4、DeepSeek V4 等](https://www.interconnects.ai/p/latest-open-artifacts-21-open-model) ⭐️ 9.0/10

近期多个重要开源 AI 模型相继发布，包括 Gemma 4、DeepSeek V4、Kimi K2.6、MiMo 2.5 和 GLM-5.1 等。CAISI 评估显示，DeepSeek V4 Pro 整体落后美国前沿模型约八个月。 这一系列发布标志着开源 AI 领域的快速进步和激烈竞争，为从业者提供了更强大和多样化的选择。CAISI 评估提供了模型能力与成本效益的客观基准，有助于部署决策。 CAISI 分析显示，DeepSeek V4 Pro 的 Elo 得分为 800，与 GPT-5.4 mini 的 749 相近，且在 7 个基准中有 5 个成本更低。但整体仍落后美国领先模型约八个月。

rss · Interconnects · May 16, 17:00

**背景**: CAISI（人工智能标准与创新中心）是美国国家标准与技术研究院（NIST）下属评估 AI 模型的机构。开源 AI 模型可公开获取，允许机构进行定制和部署。“open artifacts”简报汇集了值得关注的开源模型发布与分析。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.nist.gov/news-events/news/2026/05/caisi-evaluation-deepseek-v4-pro">CAISI Evaluation of DeepSeek V4 Pro | NIST</a></li>
<li><a href="https://dig.watch/updates/deepseek-v4-pro-caisi-us-nist-evaluation">DeepSeek V4 trails US frontier by eight months, according to CAISI ...</a></li>
<li><a href="https://calipsu.com/caisi-evaluation-deepseek-v4-pro/">CAISI Evaluation: DeepSeek V4 Pro Behind Frontier AI - Calipsu</a></li>

</ul>
</details>

**标签**: `#open models`, `#AI`, `#machine learning`, `#releases`, `#Gemma`

---

<a id="item-3"></a>
## [廉价智能门铃漏洞可导致账户接管和通话劫持](https://www.abgeo.dev/blog/anyone-can-ring-your-doorbell/) ⭐️ 9.0/10

一名安全研究人员发现了一款廉价智能门铃的严重漏洞，该漏洞可导致整个设备群的账户被接管和通话被劫持。攻击者能够获取任何用户的账户访问权限并拦截视频通话。 该漏洞突显了廉价物联网设备中存在的严重安全隐患，可能危及数千用户的隐私和安全。这凸显了智能家居产品需要更强的安全标准。 该漏洞据称允许对整个设备群进行账户接管，意味着攻击者可以危及同一制造商的所有设备。具体的门铃型号和制造商尚未披露，但研究人员提供了概念验证。

rss · Lobsters · May 16, 08:57

**背景**: 智能门铃是连接到互联网的物联网设备，允许用户通过应用程序查看和与访客通话。许多廉价型号缺乏适当的安全措施，容易受到攻击。账户接管是指攻击者未经授权访问用户账户，而通话劫持涉及拦截或重定向视频流。这是物联网设备安全漏洞更广泛模式的一部分。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://lobste.rs/s/yxj57x/cheap_smart_doorbell_allows_fleet_wide">Cheap smart doorbell allows fleet-wide account takeover and call hijacking | Lobsters</a></li>
<li><a href="https://www.aarp.org/personal-technology/video-doorbell-hacked/">Your Smart Video Doorbell May Not Be Secure, Consumer Reports Testing Shows</a></li>

</ul>
</details>

**标签**: `#security`, `#vulnerability`, `#IoT`, `#smart doorbell`

---

<a id="item-4"></a>
## [SGLang v0.5.12 全面支持 DeepSeek V4 推理](https://github.com/sgl-project/sglang/releases/tag/v0.5.12) ⭐️ 8.0/10

SGLang v0.5.12 为 DeepSeek V4 提供了全面的推理支持，包括张量并行、专家并行、上下文并行、数据并行注意力，以及 DeepGemm 和 FlashMLA 等众多内核优化。同时新增了对 Nvidia B300/B200/H200/H100/GB200/GB300 和 AMD MI35X 等硬件的支持。 此版本是 LLM 推理效率的重要里程碑，能够在多种硬件上更快、更可扩展地部署 DeepSeek V4 这一前沿模型。HiSparse KV 缓存卸载和 W4A4 MegaMoE 内核等优化减少了内存压力和延迟，惠及研究人员和生产部署。 值得关注的特性包括：HiSparse 可将不活跃的 KV 缓存卸载到 CPU 内存、统一的 Radix Tree（UnifiedTree）缓存管理，以及优化的预填充-解码分离。该版本还提供了统一的 Docker 镜像 `lmsysorg/sglang:v0.5.12`，支持所有 Nvidia GPU，并新增了对 Intern-S2-Preview 和 MiniCPM-V 4.6 等模型的支持。

github · Fridge003 · May 16, 18:23

**背景**: SGLang 是一个面向大语言模型的开源推理引擎，专为高吞吐量和低延迟而设计。DeepSeek V4 是一个拥有数千亿参数的混合专家模型。高效推理此类模型需要先进的并行技术和专用内核才能充分利用现代 GPU 硬件。预填充-解码分离将提示处理与令牌生成分开，以优化资源使用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.bentoml.com/llm/inference-optimization/prefill-decode-disaggregation">Prefill - decode disaggregation | LLM Inference Handbook</a></li>
<li><a href="https://www.lmsys.org/blog/2026-04-10-sglang-hisparse/">HiSparse : Turbocharging Sparse Attention with... | LMSYS Org</a></li>

</ul>
</details>

**标签**: `#inference`, `#DeepSeek`, `#LLM`, `#release`, `#optimization`

---

<a id="item-5"></a>
## [Zerostack：基于 Unix 理念的纯 Rust 编码智能体](https://crates.io/crates/zerostack/1.0.0) ⭐️ 8.0/10

Zerostack 是一个新发布的、基于 Unix 理念的编码智能体，完全用 Rust 编写，空闲时仅占用约 8MB 内存，工作时约 12MB。它强调最小的资源消耗和精简的代码库。 对于使用资源受限的笔记本电脑或虚拟机的开发者而言，Zerostack 提供了内存消耗大的编码智能体（如 Claude Code，可能占用数 GB 内存）的轻量级替代方案。其 Unix 理念设计和纯 Rust 实现为 AI 辅助编程带来了简单性和高效性。 该智能体不能通过 bash 执行任意代码，而是使用`edit`等受限制的工具，从而增强安全性。它目前支持 OpenAI 订阅，社区也表达了对更多提供商支持的兴趣。

hackernews · gidellav · May 16, 22:23 · [社区讨论](https://news.ycombinator.com/item?id=48164287)

**背景**: 编码智能体是自主执行编码任务（如编写、编辑和重构代码）的 AI 系统。Unix 哲学倡导小而专注、模块化的工具。Zerostack 将这些理念与 Rust 的性能和安全性相结合，旨在打造一个极简高效的智能体。

**社区讨论**: 评论者赞扬了其相比其他智能体的低内存使用量，有用户指出 Claude Code 占用数 GB 内存。其他人分享了类似项目或询问 OpenAI 订阅支持。还有关于安全性的讨论，强调不应让智能体拥有任意 shell 访问权限。

**标签**: `#rust`, `#coding-agent`, `#unix`, `#tools`

---

<a id="item-6"></a>
## [NVIDIA 发布 SANA-WM：720p 一分钟视频生成的开源世界模型](https://nvlabs.github.io/Sana/WM/) ⭐️ 8.0/10

NVIDIA 发布了 SANA-WM，这是一个拥有 26 亿参数的开源世界模型，能够生成 720p、时长一分钟的视频，并支持完整的六自由度相机控制。模型权重即将发布，代码已采用 Apache 2.0 许可证，模型权重则使用宽松的 NVIDIA 许可证。 SANA-WM 是开源世界模型在长时间视频生成和精确相机控制方面的重要进展，可能推动模拟、游戏和内容创作等应用。其宽松的许可方式有望加速 AI 领域的研究和采用。 该模型拥有 26 亿参数，原生训练支持一分钟 720p 分辨率视频生成。代码采用 Apache 2.0 许可证，模型权重则使用 NVIDIA 的开放模型许可证，允许商业使用和派生模型。然而，权重尚未公开，这引发了社区对“开源”宣称的质疑。

hackernews · mjgil · May 16, 12:06 · [社区讨论](https://news.ycombinator.com/item?id=48159445)

**背景**: 世界模型是一种 AI 系统，通过学习环境的内部表示来模拟可能的未来状态。六自由度相机控制指六个自由度：平移（前进/后退、左/右、上/下）和旋转（偏航、俯仰、横滚）。SANA-WM 基于 NVIDIA 的 SANA 架构，并使用虚幻引擎生成的合成数据进行训练。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://nvlabs.github.io/Sana/WM/">SANA - WM | Efficient Minute-Scale World Modeling</a></li>
<li><a href="https://arxiv.org/abs/2605.15178">[2605.15178] SANA - WM : Efficient Minute-Scale World Modeling with...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Six_degrees_of_freedom">Six degrees of freedom - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区成员对“开源”标签表示怀疑，因为模型权重尚未发布，有评论称“没权重就是空谈”。也有人指出代码采用 Apache 2.0 且模型许可证允许商业使用，但权重未能立即获取仍是争议点。部分评论还猜测使用了虚幻引擎的合成数据，并将输出与电子游戏美学相比较。

**标签**: `#world model`, `#video generation`, `#NVIDIA`, `#open-source`, `#AI research`

---

<a id="item-7"></a>
## [脱离 Tailwind，重新学习 CSS 结构](https://jvns.ca/blog/2026/05/15/moving-away-from-tailwind--and-learning-to-structure-my-css-/) ⭐️ 8.0/10

Julia Evans 发表了一篇文章，解释她决定放弃 Tailwind CSS，转而采用语义化 HTML 结合现代 CSS 结构技术。 这篇文章出自一位备受尊敬的作者之手，引发了关于 CSS 架构和 utility-first 框架权衡的重要讨论，影响开发者对前端样式的处理方式。 Evans 强调学习如何在不依赖 Tailwind 的 utility 类的情况下构建 CSS，重点关注可读性和可维护性。该文章在 Hacker News 上获得 457 分和 298 条评论，反映出社区的高度关注。

hackernews · Lobsters · May 16, 09:14 · [社区讨论](https://news.ycombinator.com/item?id=48158400)

**背景**: Tailwind CSS 是一个 utility-first CSS 框架，提供低层级 utility 类，允许开发者直接在 HTML 中构建设计。虽然它加快了开发速度，但批评者认为它可能导致糟糕的 HTML 语义和不可维护的代码。本文探讨了 CSS Modules 和语义化 HTML 等替代方案。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Tailwind_CSS">Tailwind CSS</a></li>

</ul>
</details>

**社区讨论**: 评论普遍称赞 Evans 坦诚的态度，但在解决方案上存在分歧：一些人主张 CSS Modules 更简单，另一些人则认为 Tailwind 的 utility-first 范式鼓励跳过更深的 CSS 学习。一个显著的观点是 Tailwind 颠倒了思考 HTML 和 CSS 的正确顺序。

**标签**: `#css`, `#tailwind`, `#frontend`, `#web-development`, `#semantic-html`

---

<a id="item-8"></a>
## [《加速》对 AI 的预言在 2025 年成真](https://www.antipope.org/charlie/blog-static/fiction/accelerando/accelerando.html) ⭐️ 8.0/10

一个 Hacker News 讨论指出，查尔斯·斯特罗斯 2005 年的小说《加速》准确预测了现代 AI 代理的能力及人类对其的依赖。 这场讨论凸显了科幻小说在预测技术趋势方面的价值，并提醒人们警惕过度依赖 AI 代理的风险。 小说中，主角在眼镜中运行 AI 代理来自动执行任务，一旦丢失眼镜便无法正常生活，这映照了当下人类与 AI 的交互模式。

hackernews · eamag · May 16, 11:36 · [社区讨论](https://news.ycombinator.com/item?id=48159241)

**背景**: 超人类主义是一种主张通过技术改善人类状况的哲学运动。《加速》描绘了一个人类与先进 AI 共同进化、最终走向后人类状态的未来。该小说以其对技术奇点的快节奏刻画以及对 AI 代理和人类依赖性的预见性观点而闻名。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Transhumanism">Transhumanism</a></li>

</ul>
</details>

**社区讨论**: 评论者对小说的预言表示惊叹，指出现代 AI 与书中描绘的代理高度相似。有人觉得它对依赖性的准确预测“令人恐惧”，而另一些人则欣赏其“合理的怪异性”以及从当前技术出发的因果链条。

**标签**: `#science-fiction`, `#AI-predictions`, `#transhumanism`, `#technology-trends`

---

<a id="item-9"></a>
## [现代生活过于复杂](https://user8.bearblog.dev/the-world-is-too-complicated/) ⭐️ 8.0/10

一篇文章及其引发的讨论反思了文明适应如何使生活变得过于复杂，导致人们与直接的、具体的现实脱节。 这在 Hacker News 社区中引起强烈共鸣，促使人们反思技术进步的代价以及在日益抽象的世界中寻找意义。 作者描述了自己生活在无法完全理解的技术、建筑和法律等系统中，这种感受在评论者中得到共鸣，他们渴望更直接、更本地化的工作形式。

hackernews · James72689 · May 16, 08:25 · [社区讨论](https://news.ycombinator.com/item?id=48158065)

**背景**: 现代文明改变了环境以适应人类需求，但这创造了一个庞大的相互依赖的系统网络。批评者认为，这种复杂性可能导致异化，因为个人依赖他们无法控制或完全理解的抽象概念。

**社区讨论**: 评论者分享了各种观点：terbo 引用了关于文明人无尽适应性的段落；keiferski 表达了对具有直接、具体成果的工作的渴望；cdrini 反思了人类智力源于偶然的意义；j_maffe 则呼应了生活在抽象、压缩生活中的感受。

**标签**: `#philosophy`, `#complexity`, `#technology`, `#society`, `#meaning`

---

<a id="item-10"></a>
## [δ-mem：基于增量规则学习的固定大小在线记忆](https://arxiv.org/abs/2605.12357) ⭐️ 8.0/10

研究人员提出了δ-mem，一种用于大型语言模型的固定大小在线记忆模块，通过增量规则学习将历史上下文压缩到状态矩阵中，无需扩展上下文窗口即可实现高效的长上下文保留。 这项工作解决了长期助手和代理系统中 LLM 高效积累和重用历史信息的日益增长的需求，可能降低记忆成本并实现更实用的长上下文应用。 δ-mem 模块使用一个固定大小的状态矩阵，通过增量规则学习逐步更新，该学习近似于对记忆更新的梯度下降，而无需存储所有过去令牌。该方法将上下文压缩到有界表示中，避免了长序列上全注意力的二次成本。

hackernews · 44za12 · May 16, 09:30 · [社区讨论](https://news.ycombinator.com/item?id=48158506)

**背景**: 像 GPT-4 这样的大型语言模型（LLM）依赖固定长度的上下文窗口；扩展它成本高昂，且不能保证有效利用上下文。增量规则是一种梯度下降学习规则，用于神经网络中通过最小化实际输出与期望输出的误差来更新权重。在线记忆技术旨在让 LLM 保留上下文窗口之外的信息，但先前的方法常面临容量或效率问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2605.12357">$δ$-mem: Efficient Online Memory for Large Language Models</a></li>
<li><a href="https://en.wikipedia.org/wiki/Delta_rule">Delta rule - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者强调需要透明地报告内存需求和吞吐量指标。有人对δ-mem 是否能真正改进缓存表示怀疑，因为将压缩记忆与不同的输入查询关联起来很困难。其他人则对固定大小状态能为智能体实现几乎无限的记忆持乐观态度，并提出了跨会话记住仓库指南等实际用例。

**标签**: `#LLM`, `#online memory`, `#delta rule`, `#compression`, `#attention`

---

<a id="item-11"></a>
## [MitchellH 警告企业陷入 AI 精神病态](https://twitter.com/mitchellh/status/2055380239711457578) ⭐️ 8.0/10

MitchellH 发表了一篇批评性观点，认为许多公司正非理性地过度依赖 AI 工具，可能导致软件开发的长期问题。 此事很重要，因为它指出了不加审慎评估就迫使用 AI 的趋势，可能损害软件质量、制造脆弱系统并扭曲工程文化。 该帖子包含管理层推行高 token 配额 AI 工具以及非工程师进行“氛围编程”的轶事，引发对隐藏技术债和安全风险的担忧。

hackernews · reasonableklout · May 15, 20:26 · [社区讨论](https://news.ycombinator.com/item?id=48153379)

**社区讨论**: 评论表达了沮丧与赞同的混合情绪：有人报告了自上而下使用 AI 的压力，另一些人担心 AI 生成的代码会引入隐藏缺陷，这些缺陷可能后来才暴露，一位用户将此过程比作“在吸烟时向服务器倒汽油”。

**标签**: `#AI`, `#software engineering`, `#technology criticism`, `#overhype`, `#workplace culture`

---

<a id="item-12"></a>
## [Cerebras 600 亿美元 IPO 标志 AI 硬件里程碑](https://www.latent.space/p/ainews-cerebras-60b-ipo-slowly-then) ⭐️ 8.0/10

Cerebras Systems 于 2026 年 5 月 14 日在纳斯达克上市，股票代码为 CBRS，通过首次公开募股筹集了 55.5 亿美元，成为近年来美国最大的科技 IPO 之一。 此次 IPO 表明市场对晶圆级 AI 芯片的信心强劲，可能加速 Cerebras 技术的采用，并加剧与传统 GPU 制造商的竞争。 Cerebras 股价开盘价为 350 美元，高于 185 美元的 IPO 发行价，该公司还通过与亚马逊和 OpenAI 的合作实现了业务多元化。

rss · Latent Space · May 16, 04:36

**背景**: Cerebras 开发晶圆级引擎（WSE），这是世界上最大的 AI 处理器，比 GPU 大 58 倍，专为超快深度学习训练设计，功耗更低。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Cerebras">Cerebras Systems - Wikipedia</a></li>
<li><a href="https://www.cnbc.com/2026/05/14/cerebras-cbrs-stock-trade-nasdaq-ipo.html">Cerebras (CBRS) starts trading on Nasdaq after IPO</a></li>
<li><a href="https://stockanalysis.com/stocks/cbrs/">Cerebras Systems (CBRS) Stock Price & Overview</a></li>

</ul>
</details>

**标签**: `#AI Hardware`, `#Cerebras`, `#IPO`, `#Semiconductors`, `#Finance`

---

<a id="item-13"></a>
## [新型 LLM 架构降低长上下文成本](https://magazine.sebastianraschka.com/p/recent-developments-in-llm-architectures) ⭐️ 8.0/10

Sebastian Raschka 的文章介绍了 Gemma 4 和 DeepSeek V4 等最新的开源权重 LLM，它们通过 KV 共享、压缩注意力以及流形约束（mHC）来降低长上下文处理的内存和计算开销。 这些技术解决了将 LLM 扩展到更长上下文的关键瓶颈，使得在文档分析、多轮对话等应用中大规模部署更加实用和高效。 KV 共享跨层重用键值缓存以减少内存占用，而压缩注意力在压缩的潜在空间中执行整个操作以降低计算成本。DeepSeek V4 的 mHC（流形约束）架构引入了带约束的并行流以稳定训练。

rss · Ahead of AI (Sebastian Raschka) · May 16, 11:33

**背景**: LLM 的长上下文处理受限于不断增长的键值（KV）缓存内存，该缓存存储了过去的 token 表示。KV 共享通过让多个解码器层共享同一个缓存来减少内存。压缩注意力在计算注意力之前将查询、键和值压缩到低维空间。mHC 架构使用多个并行流并通过流形约束来提高表示质量。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.promptlayer.com/research-papers/a-systematic-study-of-cross-layer-kv-sharing-for-efficient-llm-inference">A Systematic Study of Cross-Layer KV Sharing for... | PromptLayer</a></li>
<li><a href="https://arxiv.org/abs/2510.04476">[2510.04476] Compressed Convolutional Attention: Efficient Attention in a Compressed Latent Space</a></li>
<li><a href="https://aicybr.com/blog/deepseek-mhc-architecture">DeepSeek mHC : How Manifold Constraints Stabilize... | AiCybr Blog</a></li>

</ul>
</details>

**标签**: `#LLM`, `#attention mechanisms`, `#long-context`, `#open-weight models`

---

<a id="item-14"></a>
## [用 BPF 进行 Linux 内存管理的探索](https://lwn.net/Articles/1072538/) ⭐️ 8.0/10

Roman Gushchin 在 2026 年 Linux 存储、文件系统、内存管理和 BPF 峰会上探讨了使用 BPF 进行内存管理的潜力和障碍，指出目前尚无基于 BPF 的内存管理提案被合并到主线内核。 将 BPF 集成到内存管理中可以提供更灵活、可编程的资源控制，有利于容器化和云工作负载。这次讨论表明，将 BPF 扩展至网络和追踪之外的兴趣日益增长。 该环节之后是 Shakeel Butt 主持的讨论，探讨新的基于 BPF 的内存控制组接口的要求。障碍包括安全性、性能和兼容性问题。

rss · LWN.net · May 15, 14:54

**背景**: BPF（Berkeley Packet Filter）是一种 Linux 内核技术，允许在沙箱中运行内核空间程序，最初用于数据包过滤，现已扩展到多个子系统。内存控制组（cgroups）用于限制和管理进程组的内存使用。将两者结合可以实现细粒度、可编程的内存策略。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Berkeley_Packet_Filter">Berkeley Packet Filter - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Cgroups">cgroups - Wikipedia</a></li>

</ul>
</details>

**标签**: `#BPF`, `#memory management`, `#Linux kernel`, `#control groups`

---

<a id="item-15"></a>
## [七个稳定内核发布修复 CVE-2026-46333](https://lwn.net/Articles/1073060/) ⭐️ 8.0/10

Greg Kroah-Hartman 宣布发布七个稳定内核（7.0.8、6.18.31、6.12.89、6.6.139、6.1.173、5.15.207 和 5.10.256），这些内核包含针对 CVE-2026-46333 的补丁，该漏洞已有公开的概念验证利用代码。 此漏洞非常关键，因为 CVE-2026-46333 允许无特权的本地用户通过 ptrace 绕过读取 root 拥有的秘密，例如 SSH 主机私钥和/etc/shadow。系统管理员必须立即升级以防止对敏感凭据的未授权访问。 该漏洞最初由 Qualys 安全咨询团队报告，Jann Horn 在 2020 年提出了补丁。修复由 Linus Torvalds 于 2026 年 5 月 14 日提交为 Linux 内核树中的提交 31e62c2ebbfd。

rss · LWN.net · May 15, 13:34

**背景**: CVE-2026-46333，被称为'ssh-keysign-pwn'，是 Linux 内核 ptrace 访问检查路径中的一个严重漏洞。它允许无特权的本地攻击者绕过 ptrace 权限检查，获取由特权进程打开的文件描述符，例如 SSH 主机私钥。该利用结合了 mm 空页绕过和 pidfd_getfd 来窃取 SSH 主机密钥和其他秘密。稳定内核是长期支持版本，接收安全修复；这七个内核覆盖从 5.10 到 7.0 的版本。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://nvd.nist.gov/vuln/detail/CVE-2026-46333">NVD - CVE - 2026 - 46333</a></li>
<li><a href="https://almalinux.org/blog/2026-05-15-ssh-keysign-pwn-cve-2026-46333/">ssh-keysign-pwn (CVE-2026-46333) Patches Released</a></li>
<li><a href="https://github.com/0xdeadbeefnetwork/ssh-keysign-pwn">GitHub - 0xdeadbeefnetwork/ssh-keysign-pwn: Steal SSH host private keys and /etc/shadow via the ptrace_may_access mm-NULL bypass + pidfd_getfd. Pre-31e62c2ebbfd kernels. · GitHub</a></li>

</ul>
</details>

**标签**: `#linux-kernel`, `#security`, `#CVE`, `#stable-kernel`, `#vulnerability`

---

<a id="item-16"></a>
## [Kubernetes v1.36：安全默认配置强化，AI 工作负载支持日趋成熟](https://www.infoq.cn/article/kNkrHGzRvA7r6pRtlGB5?utm_source=rss&utm_medium=article) ⭐️ 8.0/10

Kubernetes v1.36（代号 Haru）于 2026 年发布，包含 70 项增强功能，其中用户命名空间、可变准入策略和细粒度 Kubelet API 授权进入通用可用性阶段，同时提升了 AI 和机器学习工作负载的支持。 此版本意义重大，因为它在默认情况下增强了 Kubernetes 集群的安全性，降低了错误配置的风险，并承认了 AI 工作负载在云原生环境中日益增长的重要性，为此类任务提供了更好的资源管理和调度能力。 值得注意的技术细节包括：用户命名空间进入 GA，可在内核级别更有效地隔离容器；以及新的 Workload API，通过将具有相似资源需求的 Pod 分组，实现工作负载感知的调度。

rss · InfoQ 中文站 · May 15, 20:00

**背景**: Kubernetes 是 Google 最初开发、现由云原生计算基金会维护的开源容器编排平台。它自动完成容器化应用的部署、扩展和管理。Kubernetes 的每个版本通常包含处于不同成熟阶段的功能：Alpha（实验性）、Beta（预发布）和 Stable/GA（通用可用性），其中 GA 功能默认启用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.infoq.com/news/2026/05/kubernetes-1-36-released/">Kubernetes v1.36 Released: Security Defaults Tighten as AI Workload Support Matures - InfoQ</a></li>
<li><a href="https://kubernetes.io/blog/2026/05/13/kubernetes-v1-36-advancing-workload-aware-scheduling/">Kubernetes v1.36: Advancing Workload-Aware Scheduling | Kubernetes</a></li>
<li><a href="https://en.wikipedia.org/wiki/Kubernetes">Kubernetes - Wikipedia</a></li>

</ul>
</details>

**标签**: `#Kubernetes`, `#release`, `#security`, `#AI`, `#cloud-native`

---

<a id="item-17"></a>
## [Anthropic 在 AWS 上推出 Claude 平台](https://www.infoq.cn/article/mjFmXfhf29SA5UFhr2QV?utm_source=rss&utm_medium=article) ⭐️ 8.0/10

Anthropic 宣布其 Claude AI 平台在亚马逊云服务（AWS）上可用，使企业能够通过 AWS 的基础设施访问 Claude 的功能。 这一整合显著扩大了企业对 Anthropic 先进 AI 模型的可及性，利用 AWS 广泛的客户基础和强大的云服务，推动 Claude 在商业应用中的采用。 Claude 是 Anthropic 开发的一系列大型语言模型，以其通过宪法 AI 和基于人类反馈的强化学习等技术关注安全性和伦理指南而闻名。

rss · InfoQ 中文站 · May 15, 18:12

**背景**: Anthropic 是一家专注于 AI 安全的研究公司，致力于构建可靠且可控的 AI 系统。其旗舰模型 Claude 是生成式预训练 Transformer，通过伦理考虑进行微调。AWS 提供云基础设施，AWS 上的 Claude 平台为企业客户提供可扩展、安全的部署。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Claude_(language_model)">Claude (language model) - Wikipedia</a></li>
<li><a href="https://platform.claude.com/docs/en/about-claude/models/overview">Models overview - Claude API Docs</a></li>
<li><a href="https://www.anthropic.com/">Home \ Anthropic</a></li>

</ul>
</details>

**标签**: `#AI`, `#AWS`, `#Claude`, `#Anthropic`, `#Cloud Computing`

---

<a id="item-18"></a>
## [蚂蚁灵波开源 LingBot-VLA 后训练代码](https://www.infoq.cn/article/5QHOQQCUdrGBBNfmm4Dk?utm_source=rss&utm_medium=article) ⭐️ 8.0/10

蚂蚁灵波开源了 LingBot-VLA 的完整后训练流程代码，声称仅需 150 条示教数据即可将模型适配到新机器人上。 这大幅降低了机器人适配所需的数据量，使基于 VLA 的机器人学习对数据有限的研究人员和从业者更加可及。 LingBot-VLA 在 9 种双机械臂配置的 20,000 小时真实世界数据上进行了预训练，开源代码涵盖了包括数据采集、微调和部署在内的完整后训练流程。

rss · InfoQ 中文站 · May 15, 10:08

**背景**: 视觉-语言-动作（VLA）模型结合了视觉感知、语言理解和动作生成，能从图像和文本指令直接输出机器人动作。后训练是一个关键步骤，利用额外的示教数据将预训练基础模型适配到特定机器人或任务上。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/Robbyant/lingbot-vla">GitHub - Robbyant/ lingbot - vla : A Pragmatic VLA Foundation Model</a></li>
<li><a href="https://huggingface.co/bazaar-research/lingbot-vla">bazaar-research/ lingbot - vla · Hugging Face</a></li>
<li><a href="https://en.wikipedia.org/wiki/Vision-language-action_model">Vision-language-action model - Wikipedia</a></li>

</ul>
</details>

**标签**: `#robot learning`, `#open source`, `#VLA`, `#transfer learning`

---

<a id="item-19"></a>
## [复制失败漏洞：Linux 页面缓存漏洞影响所有主流发行版](https://www.infoq.cn/article/1HucCJrazwgF7QNT232r?utm_source=rss&utm_medium=article) ⭐️ 8.0/10

一个名为“Copy Fail”（CVE-2026-31431）的新 Linux 内核漏洞被发现，允许无特权的用户向页面缓存执行受控的 4 字节写入，可能导致权限提升到 root。 该漏洞影响所有主流 Linux 发行版，包括 Ubuntu、RHEL、SUSE 和 Amazon Linux，并且有公开的 732 字节概念验证漏洞利用代码，构成重大安全风险，需要紧急修补。 该漏洞利用 AF_ALG 套接字家族与 splice()系统调用，触发 authencesn 加密模块中的临时写入错误，从而实现对页面缓存中脏页的受控写入。该漏洞已通过负责任的披露流程报告，补丁正在推出中。

rss · InfoQ 中文站 · May 15, 09:37

**背景**: Linux 页面缓存是内核组件，用于在内存中缓存文件数据以提高 I/O 性能。脏页是指在内存中已被修改但尚未写入磁盘的页面。该漏洞利用了 splice 操作中页面缓存页处理方式的缺陷，允许攻击者破坏内存中的文件数据。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Copy_Fail">Copy Fail - Wikipedia</a></li>
<li><a href="https://www.penligent.ai/hackinglabs/copy-fail-cve-2026-31431-a-linux-kernel-bug-that-turns-page-cache-into-root/">Copy Fail CVE-2026-31431, A Linux Kernel Bug That Turns Page Cache Into Root</a></li>
<li><a href="https://xint.io/blog/copy-fail-linux-distributions">Copy Fail: 732 Bytes to Root on Every Major Linux Distribution. - Xint</a></li>

</ul>
</details>

**标签**: `#Linux`, `#security`, `#vulnerability`, `#kernel`

---

<a id="item-20"></a>
## [Bun 从 Zig 重写为 Rust](https://en.liujiacai.net/2026/05/16/bun-rust-port/) ⭐️ 8.0/10

一篇博文分析了 Bun 将其 JavaScript 运行时从 Zig 重写为 Rust 的决定及其技术和生态影响。 Bun 是 Node.js 的热门替代品，从 Zig 转向 Rust 可能改变其性能表现和社区生态，也突显了 Rust 在系统编程领域的日益主导地位。 重写涉及将 Bun 的核心运行时（包括其 JavaScriptCore 集成和包管理器）从 Zig 移植到 Rust，这可能会影响稳定性和开发速度。

rss · Lobsters · May 16, 10:26

**背景**: Bun 是一个基于 JavaScriptCore 的 JavaScript 运行时、打包器和包管理器，最初使用 Zig 实现。Zig 是一种注重简洁和性能的底层系统编程语言，而 Rust 是一种内存安全且生态系统日益增长的底层语言。从 Zig 重写为 Rust 是一项引人注目的工程决策。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Bun_(software)">Bun (software) - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Zig_(programming_language)">Zig (programming language)</a></li>

</ul>
</details>

**标签**: `#Bun`, `#Rust`, `#JavaScript runtime`, `#rewrite`, `#software engineering`

---

<a id="item-21"></a>
## [近期内核漏洞与攻击面缩减](https://www.openwall.com/lists/oss-security/2026/05/16/3) ⭐️ 8.0/10

oss-security 邮件列表上发布了一份新分析，讨论了近期内核漏洞，并以 IPSEC 为例提出了缩减攻击面的方法。 内核漏洞分析与攻击面缩减对系统安全至关重要，该讨论为加固 Linux 内核提供了实用技术。 该帖子可能包含具体的漏洞利用技术，以及如何禁用或限制 IPSEC 模块以减少攻击面的方法。

rss · Lobsters · May 16, 14:18

**背景**: 内核是操作系统的核心，针对内核的漏洞利用可使攻击者获得完全控制权。攻击面缩减是指禁用不必要的功能以限制潜在入口点。IPSEC 是一组用于保护 IP 通信安全的网络协议套件，其内核模块可能成为漏洞利用的目标。

**标签**: `#kernel`, `#security`, `#exploits`, `#IPSEC`, `#attack surface`

---

<a id="item-22"></a>
## [OxCaml 为 OCaml 提供数据竞争自由保证](https://kcsrk.info/ocaml/oxcaml/x-ocaml/blogging/2026/05/07/data-race-freedom-in-oxcaml/) ⭐️ 8.0/10

OxCaml 在 OCaml 5.2.0 基础上引入编译时的数据竞争自由保证，并增加了运行时补丁。 这一进展在编译时防止数据竞争，解决了并发编程中的关键挑战，有望提高并发 OCaml 应用的安全性和可靠性。 OxCaml 被设计为 OCaml 的超集，所有合法的 OCaml 程序也是合法的 OxCaml 程序，目前基于 OCaml 5.2.0 并带有部分运行时补丁。

rss · Lobsters · May 16, 16:38

**背景**: 数据竞争发生在多个线程同时访问同一内存位置且缺乏适当同步时，会导致不可预测的行为。OCaml 传统上依赖不可变性来避免此类问题，但随着 OCaml 5 引入多核支持，并发编程变得更加普遍，数据竞争风险也随之增加。OxCaml 旨在通过静态保证来消除这类错误。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://oxcaml.org/">OxCaml | About</a></li>
<li><a href="https://github.com/oxcaml/oxcaml">GitHub - oxcaml/oxcaml: OCaml - Oxidized! · GitHub</a></li>

</ul>
</details>

**标签**: `#OCaml`, `#concurrency`, `#data race`, `#programming languages`

---

<a id="item-23"></a>
## [Bazel 远程缓存的内容定义分块去重](https://www.buildbuddy.io/blog/content-defined-chunking) ⭐️ 8.0/10

BuildBuddy 的博文解释了如何将内容定义分块（CDC）应用于 Bazel 的远程缓存，以提高去重效率。 这一优化减少了缓存存储和带宽使用，使 Bazel 构建在大规模项目中更快、更具成本效益。 内容定义分块根据文件内容将数据分割成可变长度块，相比固定大小块能实现更好的去重。

rss · Lobsters · May 17, 03:29

**背景**: 内容定义分块（CDC）是一种用于备份系统和去重存储的技术。它利用滚动哈希根据数据内容识别块边界，使得文件的更改仅影响少数数据块。Bazel 是一种构建工具，使用远程缓存共享构建产物；应用 CDC 可以减少冗余数据传输。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Content-Defined_Chunking">Content-Defined Chunking</a></li>
<li><a href="https://huggingface.co/docs/xet/chunking">Content - Defined Chunking Algorithm</a></li>
<li><a href="https://restic.net/blog/2015-09-12/restic-foundation1-cdc/">restic · Foundation - Introducing Content Defined Chunking (CDC)</a></li>

</ul>
</details>

**标签**: `#Bazel`, `#remote cache`, `#content-defined chunking`, `#build systems`, `#caching`

---

<a id="item-24"></a>
## [AI 模型使传统开放式 CTF 竞赛过时](https://kabir.au/blog/the-ctf-scene-is-dead) ⭐️ 7.0/10

一篇博客文章指出，前沿 AI 模型现在能够自动解决开放式 CTF 竞赛中的挑战，实际上破坏了这一形式，并削弱了参与者的学习体验。 这一转变挑战了 CTF 竞赛作为网络安全实践学习工具的根本目的，可能迫使组织者重新设计挑战或采用新形式以保留教育价值。 文章特别强调，LLM 可以在不理解底层概念的情况下解决挑战，将体验简化为复制粘贴练习，并指出挑战创建也受到影响，因为 AI 可以反混淆预期的解决方案。

hackernews · Lobsters · May 16, 07:01 · [社区讨论](https://news.ycombinator.com/item?id=48157559)

**背景**: CTF 竞赛是网络安全比赛，参与者通过解决挑战寻找隐藏的“flag”，通常采用 jeopardy 或 attack-defense 格式。自 1996 年以来，它们一直是网络安全教育的重要组成部分。最近，以 LLM 为驱动的 AI 工具出现，能够自主解决许多 CTF 挑战，引发了关于这一形式未来的疑问。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Capture_the_flag_(cybersecurity)">Capture the flag (cybersecurity) - Wikipedia</a></li>
<li><a href="https://ctf101.org/">CTF Handbook</a></li>
<li><a href="https://github.com/AykhanJ/CTF-Solver-Agent">GitHub - AykhanJ/ CTF - Solver -Agent: An LLM-powered agent that...</a></li>

</ul>
</details>

**社区讨论**: 评论者表达了 AI 破坏了参与和构建 CTF 挑战的挫败感，有人指出失去了协作学习的时刻。其他人指出这个问题反映了更广泛的教育挑战，还有人建议让 CTF 更难或调整挑战以抵抗 AI。

**标签**: `#AI`, `#CTF`, `#cybersecurity`, `#education`, `#LLM`

---

<a id="item-25"></a>
## [Kioxia 与 Dell 在 2RU 服务器中塞入 10 PB](https://www.blocksandfiles.com/flash/2026/05/14/kioxia-and-dell-cram-10-pb-into-slim-2ru-server/5240574) ⭐️ 7.0/10

Kioxia 和 Dell 展示了一款 2RU 服务器，利用超高密度 NAND 闪存驱动器可存储高达 10 PB 数据，面向超大规模数据中心。 这一里程碑突破了存储密度的极限，可能实现大规模数据整合并减少数据中心物理占用，对超大规模数据中心和高性能计算至关重要。 该系统采用 Kioxia 最新高密度 NAND SSD 集成到 Dell PowerEdge 服务器中，在 2RU 外形下实现 10 PB。仅驱动器成本估计超过 50 万美元，限制了初期采用仅限于超大规模数据中心、国防和研究预算。

hackernews · rbanffy · May 16, 17:12 · [社区讨论](https://news.ycombinator.com/item?id=48161997)

**背景**: 存储密度以每机架单元存储的数据量衡量；2RU 服务器高 2 个机架单元（3.5 英寸）。Kioxia 是从东芝分拆出来的领先 NAND 闪存制造商，Dell 是主要服务器供应商。谷歌、AWS 等超大规模数据中心需要巨大存储容量且占地最小。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Kioxia">Kioxia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Hyperscaler">Hyperscaler</a></li>

</ul>
</details>

**社区讨论**: 评论者提出高密度使其适用于轨道 CDN 缓存，但其他人指出成本高昂（仅驱动器超过 50 万美元）将限制于超大规模数据中心。有人幽默地称满 NIC 填满需 666 分钟，戏称为“撒旦 NAS”。另一评论批评文章最初混淆 TB 和 PB。

**标签**: `#storage`, `#data-center`, `#hardware`, `#high-density`, `#NAND`

---

<a id="item-26"></a>
## [Futhark 示例展示依赖类型在 GPU 编程中的应用](https://futhark-lang.org/examples.html) ⭐️ 7.0/10

Futhark 语言的官方示例页面展示了其依赖类型系统如何通过代码片段实现安全高效的 GPU 编程。该资源于 2020 年发布，提供了类型级数组长度追踪和并行数组操作的实际示例。 Futhark 的方法通过在编译时捕获大小不匹配错误来减少 GPU 代码中的 bug，解决了并行编程中的一个主要痛点。这使得高性能计算对函数式程序员更加友好，并推动了安全 GPU 编程的发展。 示例使用 Futhark 的依赖类型将数组长度编码在类型中，例如对 Vec<T,n>和 Vec<T,m>进行 concat 操作返回 Vec<T,n+m>。该语言是纯函数式的，可编译为 GPU 和多核 CPU 的高效并行代码。

hackernews · tosh · May 16, 09:50 · [社区讨论](https://news.ycombinator.com/item?id=48158606)

**背景**: Futhark 是一种静态类型、数据并行的数组语言，属于 ML 家族，由 DIKU 在 HIPERFIT 项目中开发。它专注于在 GPU 上以高性能执行函数式数据并行程序，使用扁平化变换进行优化。依赖类型允许在类型层面表达数组长度等约束，在编译时捕获错误。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Futhark_(programming_language)">Futhark (programming language)</a></li>
<li><a href="https://futhark-lang.org/">Why Futhark ?</a></li>
<li><a href="https://en.wikipedia.org/wiki/Array_language">Array language</a></li>

</ul>
</details>

**社区讨论**: 评论者讨论了与北欧符文字母表名称混淆的问题，但称赞了 Futhark 的依赖类型对数组安全性的贡献。一位用户表示在生产中使用 Futhark 两年没有遇到严重问题，并称赞维护者快速修复 bug。另一位用户称其为低级 GPU 语言中的“一束光”。

**标签**: `#Futhark`, `#GPU programming`, `#dependent types`, `#functional programming`, `#array language`

---

<a id="item-27"></a>
## [3000 条文本描述提升视频生成模型的 3D 理解](https://mp.weixin.qq.com/s?__biz=MzIzNjc1NzUzMw==&mid=2247891178&idx=3&sn=6012fc3aeb577e254889d2372effaa6f) ⭐️ 7.0/10

浙江大学与微软的研究人员提出了一种方法，仅使用 3000 条文本描述就能显著提升视频生成模型的三维理解能力，有效减少常见的物体变形和跨帧不一致等穿帮问题。 该方法解决了文本到视频生成模型的一个关键瓶颈——难以保持连贯的三维结构。它证明可通过简洁的文本提示注入大规模三维知识，为更逼真、物理合理的视频生成开辟了一条低成本道路。 该方法仅需 3000 条文本描述，无需大规模 3D 数据集或复杂的架构改动。它可能通过对预训练视频生成模型进行微调，使用明确描述深度、遮挡和物体恒存性等三维属性的文本提示。

rss · 量子位 · May 16, 04:04

**背景**: 当前的文本到视频模型（如 OpenAI 的 Sora 和 Google 的 Veo）在物体移动或旋转时经常出现穿帮，因为它们缺乏明确的三维推理能力。传统提升三维理解的方法需要大量标注的 3D 数据集或多视角训练，成本高昂且不一定可行。这项研究探索了一种轻量级替代方案，利用预训练模型中已有的知识，并通过有针对性的文本描述将其激活。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://deepmind.google/models/veo/">Introducing our state of the art video generation model Veo 3, and...</a></li>
<li><a href="https://www.youtube.com/watch?v=HK6y8DAPN_0">Introducing Sora — OpenAI’s text -to- video model - YouTube</a></li>

</ul>
</details>

**标签**: `#Video Generation`, `#3D Understanding`, `#Text-to-Video`, `#Computer Vision`, `#Research`

---

<a id="item-28"></a>
## [Linux 内核实时更新中的 HugeTLB 内存保留](https://lwn.net/Articles/1072531/) ⭐️ 7.0/10

在 2026 年 Linux 存储、文件系统、内存管理和 BPF 峰会上，Pratyush Yadav 主持了一场会议，讨论如何通过 kexec 切换机制在实时更新过程中保留 hugetlbfs 提供的内存。 此功能对于需要最小化停机时间的云端环境的实时内核更新至关重要；保留 HugeTLB 页面可确保使用大页面（例如数据库、虚拟机）的应用程序在更新时不丢失性能关键的内存映射。 该讨论基于近期关于 kexec 切换和实时更新编排器的工作，这些工作尚未完全合并；HugeTLB 保留需要谨慎处理通常较大且持久的内存区域。

rss · LWN.net · May 15, 13:27

**背景**: HugeTLB（大页面）是 2MB 或 1GB 等大尺寸内存页，用于减少具有大内存占用的应用程序的 TLB 未命中。实时内核更新允许在不完全重启的情况下替换正在运行的内核，通过 kexec 启动新内核并借助 kexec 切换（KHO）等机制保留状态。实时更新编排器（LUO）协调这个过程。保留 HugeTLB 页面具有挑战性，因为它们的分配和管理方式与普通页面不同。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://docs.kernel.org/next/kho/concepts.html">Kexec Handover Concepts — The Linux Kernel documentation</a></li>
<li><a href="https://docs.kernel.org/admin-guide/mm/hugetlbpage.html">HugeTLB Pages — The Linux Kernel documentation</a></li>
<li><a href="https://www.phoronix.com/news/Linux-6.19-Live-Update-LUO">Live Update Orchestrator "LUO" Merged For Linux 6.19 - Phoronix</a></li>

</ul>
</details>

**标签**: `#Linux kernel`, `#memory management`, `#live update`, `#HugeTLB`

---

<a id="item-29"></a>
## [GitHub 试点通用无障碍代理](https://github.blog/ai-and-ml/github-copilot/building-a-general-purpose-accessibility-agent-and-what-we-learned-in-the-process/) ⭐️ 7.0/10

GitHub 宣布正在试点一个实验性的通用无障碍代理，集成到 Copilot CLI 和 VS Code 中，帮助工程师自动修复无障碍问题并提供可靠的无障碍答案。 这一举措可能显著减少使 Web 应用无障碍所需的工作量，降低开发者的门槛，并改善残障用户的体验。 该代理有两个主要目标：提供即时的无障碍答案，以及在前端拉取请求中自动修复简单、客观的无障碍问题。

rss · GitHub Blog · May 15, 16:00

**背景**: 无障碍性确保软件能被残障人士使用。GitHub 的代理基于 Copilot，利用 AI 检测并修复常见的无障碍违反问题，如缺少替代文本或颜色对比度低，直接在开发工作流中简化修复过程。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.blog/ai-and-ml/github-copilot/building-a-general-purpose-accessibility-agent-and-what-we-learned-in-the-process/">Building a general-purpose accessibility agent—and what we learned in the process - The GitHub Blog</a></li>
<li><a href="https://letsdatascience.com/news/github-pilots-general-purpose-accessibility-agent-for-fronte-ed96073c">GitHub pilots general-purpose accessibility agent for frontend pull requests | Let's Data Science</a></li>
<li><a href="https://accessibility.github.com/documentation/guide/getting-started-with-agents/">Getting Started with GitHub Copilot Custom Agents for Accessibility</a></li>

</ul>
</details>

**标签**: `#accessibility`, `#AI agents`, `#GitHub`, `#experimental`

---

<a id="item-30"></a>
## [JEP 533 加强 Java 结构化并发的异常处理](https://www.infoq.cn/article/8jh0UiNm7SdaKzprlXWq?utm_source=rss&utm_medium=article) ⭐️ 7.0/10

JEP 533 已集成到 JDK 27，细化了 Java 结构化并发 API 中的异常处理和类型安全，特别关注了异常流的新方法。 这一增强提高了处理并发代码的 Java 开发者的可靠性和可观察性，使得管理结构化任务中的错误更加容易，并降低了静默失败的风险。 JEP 533 是结构化并发的第七次预览；它将 fork 方法改为返回 Subtask 而非 Future，并强化了异常处理，确保错误在任务作用域内正确传播。

rss · InfoQ 中文站 · May 15, 16:12

**背景**: 结构化并发将运行在不同线程中的相关任务组视为一个工作单元，简化了错误处理和取消。它首次在 JDK 21 中通过 JEP 453 预览。核心概念是 StructuredTaskScope，确保任务不能超出其启动的作用域。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openjdk.org/jeps/533">JEP 533 : Structured Concurrency (Seventh Preview)</a></li>
<li><a href="https://www.infoq.com/news/2026/05/jep-533-jdk-27/">JEP 533 Tightens Exception Handling in Java's Structured... - InfoQ</a></li>
<li><a href="https://docs.oracle.com/en/java/javase/21/core/structured-concurrency.html">Structured Concurrency - Java</a></li>

</ul>
</details>

**标签**: `#Java`, `#structured concurrency`, `#JDK 27`, `#exception handling`, `#concurrency`

---

<a id="item-31"></a>
## [百灵开源 Ring-2.6-1T 推理模型](https://www.infoq.cn/article/rtbXo0YG1cQ0kFwd2ueK?utm_source=rss&utm_medium=article) ⭐️ 7.0/10

百灵 AI 开源了其旗舰推理模型 Ring-2.6-1T，这是一个 1 万亿参数的大语言模型，旨在平衡效率、成本和能力。 此次发布为 AI 社区提供了一个强大而高效的开源模型，能够以较低成本运行推理，可能加速大语言模型在资源受限环境中的部署。 该模型具有 1 万亿参数，但专注于推理效率，可能通过稀疏激活或量化等技术实现，但公告中未披露具体方法。

rss · InfoQ 中文站 · May 15, 15:08

**背景**: 大语言模型通常需要大量计算资源进行训练和推理。像这样的开源推理模型允许开发者在自己的硬件上运行 AI，减少对云端 API 的依赖，并改善延迟和隐私。

**标签**: `#AI`, `#open-source`, `#large language model`, `#inference`

---

<a id="item-32"></a>
## [Grafana Pyroscope 2.0 实现规模化持续性能分析](https://www.infoq.cn/article/YlEaMXEjM9KhoKMayf63?utm_source=rss&utm_medium=article) ⭐️ 7.0/10

Grafana 发布了 Pyroscope 2.0，该版本实现了生产环境中可规模化的持续性能分析，使得团队能够以低开销对应用程序进行大规模性能分析。 持续性能分析日益被视为与指标、日志、追踪并列的第四大可观测性支柱；Pyroscope 2.0 的可扩展性使其能够更广泛地部署到生产环境，帮助团队优化资源使用和应用性能。 Pyroscope 是一个开源持续性能分析数据库，能够提供代码行级别的性能洞察；2.0 版本可能包含存储效率和查询性能的改进，以支持更大规模的集群。

rss · InfoQ 中文站 · May 15, 14:00

**背景**: 持续性能分析与传统性能分析不同，它在生产环境中以极低开销持续运行，提供代码行为的不间断可见性。它有助于识别性能瓶颈，如慢函数或内存泄漏。Pyroscope 于 2022 年被 Grafana 收购，并集成到 Grafana 生态系统中。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://pyroscope.io/">Open Source Continuous Profiling Platform</a></li>
<li><a href="https://grafana.com/oss/pyroscope/">Grafana Pyroscope OSS | Open source continuous profiling database</a></li>

</ul>
</details>

**标签**: `#Grafana`, `#Pyroscope`, `#continuous-profiling`, `#observability`, `#performance-analysis`

---

<a id="item-33"></a>
## [AdonisJS v7：端到端类型安全、重构模板、零配置 OpenTelemetry](https://www.infoq.cn/article/eucZu2CRSKKb7DRP6bDc?utm_source=rss&utm_medium=article) ⭐️ 7.0/10

AdonisJS v7 引入了全栈端到端的类型安全性，一个彻底重构的项目模板，以及零配置的 OpenTelemetry 集成以实现可观测性。 此版本通过类型安全减少运行时错误，并简化可观测性设置，显著提升开发者体验，使 AdonisJS 在与 NestJS 等其他 TypeScript 优先框架的竞争中更具优势。 端到端类型安全涵盖 HTTP 请求、数据库查询和 WebSocket 事件；零配置的 OpenTelemetry 支持可自动对框架进行插桩，无需手动配置。

rss · InfoQ 中文站 · May 15, 12:00

**背景**: AdonisJS 是一个用于 Node.js 的全栈 Web 框架，以其对开发者体验和内置工具的关注而闻名。OpenTelemetry 是一个开源的可观测性框架，提供供应商中立的 API 来收集追踪、指标和日志。在 v7 之前，AdonisJS 需要手动插桩才能实现可观测性，且类型安全仅限于框架的特定部分。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/OpenTelemetry">OpenTelemetry</a></li>
<li><a href="https://opentelemetry.io/">OpenTelemetry</a></li>

</ul>
</details>

**标签**: `#Node.js`, `#TypeScript`, `#Web Framework`, `#OpenTelemetry`, `#AdonisJS`

---

<a id="item-34"></a>
## [GitHub 推出 MCP 服务器集成，增强机密扫描](https://www.infoq.cn/article/Fz17LfX18bjZVBG31AIW?utm_source=rss&utm_medium=article) ⭐️ 7.0/10

GitHub 集成了 MCP（模型上下文协议）服务器，扩展了其机密扫描功能，更有效地检测暴露的机密。这一增强利用 AI 提升了跨仓库的安全性扫描。 该集成显著提升了开发者识别和缓解凭据泄露、API 密钥及其他敏感数据安全风险的能力。它强化了 GitHub 的安全态势，减少了软件供应链漏洞的攻击面。 MCP 服务器集成允许 AI 工具连接到 GitHub 的机密扫描引擎，实现开发过程中的实时检测。此次扩展覆盖了更多机密类型，并提供了更好的上下文告警。

rss · InfoQ 中文站 · May 15, 10:12

**背景**: MCP（模型上下文协议）是一种旨在使 AI 模型能够与外部系统（如 GitHub）交互的协议，提供上下文感知能力。GitHub 的机密扫描功能可自动检测公共和私有仓库中暴露的机密。通过集成 MCP，GitHub 可以利用 AI 提升检测准确率和覆盖率。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://apidog.com/blog/github-mcp-server/">How to Use GitHub MCP Server</a></li>

</ul>
</details>

**标签**: `#GitHub`, `#secret scanning`, `#security`, `#MCP server`, `#developer tools`

---

<a id="item-35"></a>
## [熔岩灯随机性的无用性](https://loup-vaillant.fr/articles/lava-lamps-and-randomness) ⭐️ 7.0/10

Loup Vaillant 认为熔岩灯并不是一种实用且有意义的密码学熵源，挑战了被广泛引用的“熔岩灯随机性”概念。 这一批评意义重大，因为它质疑了安全文化中的一个流行传说，促使人们对密码学熵源有更严谨的理解。 文章可能指出熔岩灯提供的熵值低、输出速度慢且难以可靠数字化，因此不适合作为主要熵源。

rss · Lobsters · May 16, 17:54

**背景**: 密码系统需要高质量的随机性来生成密钥和保护通信。一些组织（如 Cloudflare）使用熔岩灯等物理现象作为“熵墙”的一部分，提供不可预测的数据。然而，真正的随机性很难实现，大多数系统依赖加密安全的伪随机数生成器（CSPRNG），它们从多个源注入熵。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.cloudflare.com/learning/ssl/lava-lamp-encryption/">How Do Lava Lamps Help with Internet Encryption?</a></li>
<li><a href="https://en.wikipedia.org/wiki/Cryptographically_secure_pseudorandom_number_generator">Cryptographically secure pseudorandom number generator - Wikipedia</a></li>

</ul>
</details>

**标签**: `#randomness`, `#cryptography`, `#entropy`, `#security`, `#critical analysis`

---

<a id="item-36"></a>
## [Zig 0.16 异步 I/O 博客文章](https://lalinsky.com/2026/05/11/async-io-in-zig-016-today.html) ⭐️ 7.0/10

lalinsky 的一篇博客文章解释了如何在 Zig 0.16 中使用异步 I/O，展示了该版本中异步操作的新语言特性。 异步 I/O 对于构建高性能、非阻塞系统至关重要，Zig 的实现方式可能影响开发者在系统编程中编写并发代码的方式。 该文章可能涵盖了 Zig 的 async/await 语法、事件循环集成以及网络或文件 I/O 的实践示例，但未提供完整文章内容。

rss · Lobsters · May 17, 00:20

**背景**: Zig 是一种专注于健壮性和性能的系统编程语言，类似于 C 但具有现代特性。异步 I/O 允许程序在不阻塞主线程的情况下执行 I/O 操作，从而实现并发。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Zig_(programming_language)">Zig (programming language)</a></li>
<li><a href="https://ziglang.org/">Home ⚡ Zig Programming Language</a></li>

</ul>
</details>

**标签**: `#Zig`, `#async I/O`, `#programming`, `#systems programming`, `#language features`

---

<a id="item-37"></a>
## [订阅轰炸：一种不断增长的电子邮件攻击方式](https://cacm.acm.org/practice/subscription-bombing-email-under-attack/) ⭐️ 7.0/10

订阅轰炸（subscription bombing），也称为订阅洪水攻击，是一种新兴的攻击方式，攻击者将受害者订阅到数千个邮件列表，用大量垃圾邮件淹没其收件箱。这种策略正迅速成为一种复杂的拒绝服务（DoS）混淆技术。 订阅轰炸可能掩盖账户被盗或欺诈等其他恶意活动，对电子邮件安全构成严重威胁。它影响所有电子邮件用户和组织，需要更新防御策略。 这些攻击以短时间内高速爆发数千封邮件的形式进行，通常来自合法的邮件列表。攻击者使用自动化工具，利用许多订阅流程缺乏验证的漏洞，用受害者的电子邮件地址进行订阅。

rss · Lobsters · May 16, 18:44

**背景**: 订阅轰炸是邮件轰炸的一种变体，旨在淹没受害者的邮箱。与传统垃圾邮件不同，它使用合法的订阅服务，使过滤变得困难。攻击者还可能将其与其他攻击结合，以分散受害者对欺诈性收费或身份盗窃等恶意活动的注意力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://dl.acm.org/doi/10.1145/3797487">Subscription Bombing: Email under Attack | Communications of the ACM</a></li>
<li><a href="https://www.proofpoint.com/us/blog/email-and-cloud-threats/subscription-bombing-hides-real-cyberattacks">How Subscription Bombing Hides Real Cyberattacks | Proofpoint US</a></li>
<li><a href="https://tangent.com/dmarc/subscription-bombing">Subscription Bombing: What is it, why is it happening?</a></li>

</ul>
</details>

**标签**: `#cybersecurity`, `#email security`, `#spam`, `#attacks`

---

<a id="item-38"></a>
## [谷歌 IDE 发展史：从碎片化到云端](https://laurent.le-brun.eu/blog/a-history-of-ides-at-google) ⭐️ 7.0/10

一篇关于谷歌内部 IDE 历史的详细回顾，追溯了从碎片化工具生态到 Cider（基于 VSCode 前端的云端 IDE）的演变过程，目前已有 80%的谷歌工程师使用 Cider。 这段历史揭示了一家像谷歌这样的大型科技公司如何规模化地处理开发者工具问题，为软件工程团队提供了经验教训。它凸显了向云端 IDE 发展的行业趋势，以及与 VSCode 等流行编辑器集成的重要性。 文章介绍了 Cider 如何从技术写作者的简单网页编辑器，发展成 80%谷歌工程师使用的主流 IDE。文章还讨论了支撑基础设施，包括 Blaze 构建系统和庞大的单体仓库。

rss · Lobsters · May 16, 05:48

**背景**: 谷歌采用单体仓库（monorepo），即一个包含其大部分代码库的单一仓库，这需要专门的构建和依赖管理工具。内部构建系统 Blaze 后来以 Bazel 之名开源。谷歌的 IDE 从基于桌面的工具（如 Eclipse）演进到云端解决方案，最终形成了 Cider，它使用 VSCode 前端并运行在 Google Cloud 上。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Firebase_Studio">Firebase Studio - Wikipedia</a></li>
<li><a href="https://app.daily.dev/posts/a-history-of-ides-at-google-wby5ceelj">A History of IDEs at Google | daily.dev</a></li>
<li><a href="https://en.wikipedia.org/wiki/Bazel_(software)">Bazel (software) - Wikipedia</a></li>

</ul>
</details>

**标签**: `#IDEs`, `#Google`, `#software engineering`, `#history`

---

<a id="item-39"></a>
## [Zulip 基金会成立以管理项目治理](https://blog.zulip.com/2026/05/15/announcing-zulip-foundation/) ⭐️ 7.0/10

Zulip 项目宣布成立 Zulip 基金会，这是一个非盈利组织，旨在治理并确保这款开源聊天平台的长期可持续发展。 成立基金会标志着 Zulip 治理模式的重要一步，表明其致力于社区驱动开发和长期稳定，这对组织采用至关重要。 Zulip 基金会将负责项目的开发、治理和财务管理，其运作方式可能类似于 Apache 软件基金会等其他开源基金会。

rss · Lobsters · May 15, 20:28

**背景**: Zulip 是一款创建于 2012 年的开源团队聊天应用，以其基于主题的流式对话而闻名，被广泛用作 Slack 的免费替代品。基金会的成立有助于确保项目的独立性和社区参与。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Zulip">Zulip - Wikipedia</a></li>
<li><a href="https://zulip.com/">Zulip — organized team chat</a></li>

</ul>
</details>

**标签**: `#open-source`, `#zulip`, `#foundation`, `#governance`

---

<a id="item-40"></a>
## [超多语言 Lisp：四种方言并排比较](https://hyperpolyglot.org/lisp) ⭐️ 7.0/10

Hyperpolyglot.org 发布了一份详细的四种主要 Lisp 方言（Common Lisp、Racket、Clojure 和 Emacs Lisp）的并排比较，涵盖语法和特性。 这一资源帮助开发者和学习者理解 Lisp 方言之间的异同，有助于语言选择和跨方言开发。 该比较涵盖了四种 Lisp 方言的语法、数据类型、函数、宏以及其他特性。

rss · Lobsters · May 17, 03:20

**背景**: Lisp 是一族编程语言，以其独特的括号前缀记法和强大的宏系统而闻名。Common Lisp、Racket、Clojure 和 Emacs Lisp 是主要的方言，各有不同的设计目标：Common Lisp 是多范式语言，Racket 是面向语言编程的平台，Clojure 是运行在 JVM 上的函数式语言，而 Emacs Lisp 是 Emacs 的脚本语言。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Racket_(programming_language)">Racket ( programming language ) - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Clojure">Clojure - Wikipedia</a></li>

</ul>
</details>

**标签**: `#lisp`, `#comparison`, `#reference`, `#programming-languages`

---

<a id="item-41"></a>
## [VLDB 论文提出高效 SSD 写入技术](https://arxiv.org/pdf/2603.09927) ⭐️ 7.0/10

一篇题为《How to Write to SSDs》的研究论文在 VLDB 会议上发表，提出了高效、可靠写入 SSD 的新技术。 这项工作对数据库和存储系统意义重大，它解决了 SSD 写入优化的关键挑战，有望提升性能并延长设备寿命。 该论文收录于 VLDB 2025 会议论文集（第 19 卷），探讨了减少写入放大和提高写入可靠性的技术。

rss · Lobsters · May 16, 08:28

**背景**: SSD 使用 NAND 闪存，写入前需擦除整个块，导致写入放大。VLDB 会议是数据库与数据管理领域的顶级学术会议。优化 SSD 写入对现代存储密集型应用至关重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.vldb.org/conference.html">Very Large Data Bases (VLDB) Conferences</a></li>
<li><a href="https://www.easeus.com/computer-instruction/improve-ssd-read-and-write-speed.html">How to Improve SSD Read and Write Speed [2025 Newest] – EaseUS</a></li>

</ul>
</details>

**标签**: `#storage`, `#SSDs`, `#database`, `#performance`, `#systems`

---