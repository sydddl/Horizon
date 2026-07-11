---
layout: default
title: "Horizon Summary: 2026-07-11 (ZH)"
date: 2026-07-11
lang: zh
---

> From 116 items, 40 important content pieces were selected

---

1. [用 Rust 重写的 PostgreSQL 通过所有回归测试](#item-1) ⭐️ 10.0/10
2. [大三本科生实现投机解码 7.92 倍加速](#item-2) ⭐️ 9.0/10
3. [OpenAI 发布 GPT-5.6 Sol/Terra/Luna，Codex 整合进 ChatGPT 超级应用](#item-3) ⭐️ 9.0/10
4. [Claude AI 用 11 天重写 Bun 运行时](#item-4) ⭐️ 9.0/10
5. [超级优化器：开创性地暴力搜索最小程序](#item-5) ⭐️ 9.0/10
6. [SGLang v0.5.15 发布，带来重大性能优化](#item-6) ⭐️ 8.0/10
7. [苹果起诉 OpenAI，指控前员工窃取商业机密](#item-7) ⭐️ 8.0/10
8. [AI 证明图论中环双覆盖猜想](#item-8) ⭐️ 8.0/10
9. [好工具通过减少摩擦变得无形](#item-9) ⭐️ 8.0/10
10. [Meta 发布 Muse Spark 1.1，提供 API 并强化智能体能力](#item-10) ⭐️ 8.0/10
11. [OpenAI 推出 ChatGPT Work，自主任务代理](#item-11) ⭐️ 8.0/10
12. [OpenAI 为 GPT-5.5 推出生物漏洞赏金计划](#item-12) ⭐️ 8.0/10
13. [AI 爬虫机器人仍在淹没网站](#item-13) ⭐️ 8.0/10
14. [GitHub 为每个仓库分配了持久的所有者](#item-14) ⭐️ 8.0/10
15. [HubSpot 将语义搜索扩展至 200 亿向量](#item-15) ⭐️ 8.0/10
16. [首个开源具身视频基础模型](#item-16) ⭐️ 8.0/10
17. [Netflix 通过动态分区拆分大幅降低 Cassandra 读取延迟](#item-17) ⭐️ 8.0/10
18. [Scarf 在生产环境中使用 7 年后迁移出 Haskell](#item-18) ⭐️ 8.0/10
19. [Cpp2Rust：自动将 C++翻译为安全 Rust 的工具发布](#item-19) ⭐️ 8.0/10
20. [Rust 1.97.0 发布，新增 lint 和目标特性](#item-20) ⭐️ 8.0/10
21. [严重 KVM 逃逸漏洞'Januscape'允许虚拟机突破](#item-21) ⭐️ 8.0/10
22. [开源射频传感器 QuadRF 可穿墙探测无人机和 WiFi 信号](#item-22) ⭐️ 7.0/10
23. [《终结者 2》特效技术口述史](#item-23) ⭐️ 7.0/10
24. [纽约市禁止欺骗性订阅行为](#item-24) ⭐️ 7.0/10
25. [Emacs 作为面向服务的平台](#item-25) ⭐️ 7.0/10
26. [对闪卡的深情告白：Anki 与学习](#item-26) ⭐️ 7.0/10
27. [AI 代理记忆选择的决策树方法](#item-27) ⭐️ 7.0/10
28. [德国电信采用 OpenAI 转型为 AI 原生电信公司](#item-28) ⭐️ 7.0/10
29. [GPT 5.6 的 72 种配置详解](#item-29) ⭐️ 7.0/10
30. [CodeQL 2.26.0 新增 Kotlin 2.4.0 支持和 AI 提示注入检测](#item-30) ⭐️ 7.0/10
31. [GitHub 用 Unix 工具改进 Copilot 代码审查](#item-31) ⭐️ 7.0/10
32. [Airbnb 分享动态配置 Sidecar Sitar-agent 架构](#item-32) ⭐️ 7.0/10
33. [蚂蚁集团发布 LingBot-VA 2.0 世界动作模型](#item-33) ⭐️ 7.0/10
34. [AI 击穿 GitHub 旧模式，Cursor、GitLab、Zed 崛起](#item-34) ⭐️ 7.0/10
35. [vLLM 多模态推理优化实践在 AICon 深圳](#item-35) ⭐️ 7.0/10
36. [Snowflake Cortex Sense：为未建模数据注入可信上下文](#item-36) ⭐️ 7.0/10
37. [Mitchell Hashimoto 访谈：聚焦 Ghostty、Zig 与开源](#item-37) ⭐️ 7.0/10
38. [每位 Python 开发者都应了解的 CPython ABI 知识](#item-38) ⭐️ 7.0/10
39. [在浏览器代码运行器中加入 Go 支持](#item-39) ⭐️ 7.0/10
40. [一秒内运行 1000 个测试：性能优化技巧](#item-40) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [用 Rust 重写的 PostgreSQL 通过所有回归测试](https://github.com/malisper/pgrust) ⭐️ 10.0/10

一个名为 pgrust 的 PostgreSQL 完全用 Rust 重写，现已 100%通过 PostgreSQL 的回归测试（共 46,066 个测试），测试基于 Postgres 18.3。 这一成就证明了 Rust 作为 C 语言替代品在数据库等系统软件中的可行性，有望带来更安全、更可靠的数据库引擎，且不牺牲性能。 该项目 pgrust 由两名开发者和 17 个 AI 编码代理共同构建。它使用 Postgres 18.3 的测试文件副本，并结合 pgrust 自身的--initdb 来运行回归测试套件。

rss · Lobsters · Jul 10, 19:05

**背景**: PostgreSQL 是一个广泛使用的开源关系型数据库，用 C 语言编写。用 Rust 重写旨在提高内存安全性和并发性，同时保持兼容性。回归测试用于确保修改不破坏现有功能，通过所有测试是任何重写的关键里程碑。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/malisper/pgrust">GitHub - malisper/pgrust: Postgres rewritten in Rust , now passing...</a></li>
<li><a href="https://byteiota.com/pgrust-postgres-rust-rewrite-100-percent-regression-tests/">pgrust Hits 100%: The AI-Built Postgres Rewrite in Rust | byteiota</a></li>
<li><a href="https://eucloudservers.com/architecture-reliability/postgres-rewritten-in-rust-now-passing-100-of-the-postgres-regression-tests-2/">Postgres rewritten in Rust , now passing 100% of... - EU Cloud Servers</a></li>

</ul>
</details>

**标签**: `#Rust`, `#PostgreSQL`, `#database`, `#systems programming`, `#performance`

---

<a id="item-2"></a>
## [大三本科生实现投机解码 7.92 倍加速](https://mp.weixin.qq.com/s?__biz=MzIzNjc1NzUzMw==&mid=2247902587&idx=3&sn=879066ecce663ab9daba5d73fe2dc27b) ⭐️ 9.0/10

一名大三本科生提出了一种新的投机解码方法，实现了比标准自回归解码 7.92 倍的加速，该工作已被 DeepSeek 和阶跃星辰等主要 AI 公司引用。 这一突破大幅提升了大语言模型推理效率，有望降低大规模部署的延迟和成本，行业领先者的引用凸显了其实用价值。 该方法基于并行草稿推测，并解决了块内的因果一致性问题，在不牺牲输出质量的情况下实现了加速。新闻中未完全公开技术细节。

rss · 量子位 · Jul 9, 04:17

**背景**: 投机解码是一种大语言模型的推理优化技术，它使用较小的草稿模型生成多个候选 token，然后由目标模型并行验证，通常可将延迟降低 2-3 倍。本文解决的核心问题是在并行草稿生成过程中保持因果一致性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Speculative_decoding">Speculative decoding</a></li>
<li><a href="https://developer.nvidia.com/blog/an-introduction-to-speculative-decoding-for-reducing-latency-in-ai-inference/">An Introduction to Speculative Decoding for Reducing Latency in AI ...</a></li>
<li><a href="https://arxiv.org/abs/2408.11850">PEARL: Parallel Speculative Decoding with Adaptive Draft Length</a></li>

</ul>
</details>

**标签**: `#speculative decoding`, `#AI acceleration`, `#machine learning`, `#deep learning`, `#inference optimization`

---

<a id="item-3"></a>
## [OpenAI 发布 GPT-5.6 Sol/Terra/Luna，Codex 整合进 ChatGPT 超级应用](https://www.latent.space/p/ainews-openai-launches-gpt-56-solterraluna) ⭐️ 9.0/10

OpenAI 发布了 GPT-5.6 模型系列（Luna、Terra、Sol），并将 Codex 整合进 ChatGPT，形成跨桌面、移动端和 API 的统一超级应用。 这标志着在让强大 AI 更易获取和更实惠方面迈出了重要一步：GPT-5.6 Sol 在代理任务基准测试中超越 Claude Fable 5，且成本显著降低；超级应用的整合也简化了用户体验。 GPT-5.6 模型系列拥有百万 token 上下文窗口、128k 输出 token，知识截止日期为 2026 年 2 月；定价从 Luna 的每百万 token $1/$6 到 Sol 的$5/$30 不等。值得注意的是，GPT-5.6 在 SWE-Bench Pro 上得分低于 Fable，但 OpenAI 对该基准的有效性提出了质疑。

rss · Latent Space · Jul 10, 06:19

**背景**: GPT-5.6 是 OpenAI 最新旗舰模型系列，包含三个层级：Luna（快速低价）、Terra（均衡）和 Sol（最大推理能力）。推理 token 是模型在思维链过程中生成的内部 token，使得单纯按 token 单价比较不够全面。Codex 原本是独立的 AI 辅助编程工具，现在完全整合进 ChatGPT，形成一个包含数据分析工具 Atlas 的'超级应用'。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://simonwillison.net/2026/Jul/9/gpt-5-6/">The new GPT - 5 . 6 family: Luna , Terra , Sol | Simon Willison’s Weblog</a></li>
<li><a href="https://www.vellum.ai/blog/gpt-5-6-benchmarks-explained">GPT - 5 . 6 Sol vs Terra vs Luna : Which Tier Should You Actually Use?</a></li>
<li><a href="https://www.theverge.com/ai-artificial-intelligence/930763/openai-codex-chatgpt-ios-android-app-preview">OpenAI’s Codex is now in the ChatGPT mobile app | The Verge</a></li>

</ul>
</details>

**标签**: `#OpenAI`, `#GPT-5.6`, `#Codex`, `#ChatGPT`, `#AI`

---

<a id="item-4"></a>
## [Claude AI 用 11 天重写 Bun 运行时](https://www.infoq.cn/article/uHkOoJ6Nfm6wNCsUryuO?utm_source=rss&utm_medium=article) ⭐️ 9.0/10

Anthropic 的 Claude AI 在短短 11 天内完成了对 Bun JavaScript 运行时的高调重写，这项任务通常需要一个小团队一年的时间。该项目花费了约 16.5 万美元的 token 费用。 这展示了 AI 驱动的代码生成和软件工程的重大飞跃，有望大幅减少开发时间和成本。它标志着 AI 能够自主执行大规模代码重写的范式转变，影响软件的维护和构建方式。 这次重写使用了 Anthropic 的 Claude 大语言模型，花费了 16.5 万美元的 token，凸显了 AI 处理复杂代码库的经济可行性。Bun 是一个一体化的 JavaScript 运行时，内置打包器、转译器、测试运行器和包管理器。

rss · InfoQ 中文站 · Jul 10, 13:21

**背景**: Bun 是由 Oven-Sh 开发的快速一体化 JavaScript 运行时，可作为 Node.js 的直接替代品，并内置打包和测试功能。Claude 是 Anthropic 开发的一系列大语言模型，旨在提供安全准确的 AI 辅助。'Token 费用'指的是 AI 模型处理输入和输出的计算成本，通常以 token 计量。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Bun_(software)">Bun (software) - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Claude_(language_model)">Claude ( AI ) - Wikipedia</a></li>
<li><a href="https://bun.com/">Bun — A fast all-in-one JavaScript runtime</a></li>

</ul>
</details>

**标签**: `#AI`, `#Code Generation`, `#LLM`, `#Software Engineering`, `#Bun`

---

<a id="item-5"></a>
## [超级优化器：开创性地暴力搜索最小程序](https://dl.acm.org/doi/epdf/10.1145/36177.36194) ⭐️ 9.0/10

论文《超级优化器——最小程序探析》提出了一种暴力搜索技术，枚举所有可能的指令序列，以找到给定函数的最短程序。 这项工作为超级优化和程序合成奠定了基础，数十年来持续影响编译器优化和自动代码生成。 超级优化器搜索无循环指令序列，并使用定理证明器验证等价性，虽然复杂度呈指数增长，但对短序列仍具实用性。

rss · Lobsters · Jul 10, 01:25

**背景**: 超级优化是一种自动为给定代码块寻找最优指令序列的技术。传统编译器使用启发式优化，常常会错过接近最优的解。1987 年 Massalin 的这篇论文引入了穷举搜索方法，为后来的程序合成和编译器设计提供了启发。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Superoptimization">Superoptimization</a></li>
<li><a href="https://en.wikipedia.org/wiki/Program_synthesis">Program synthesis</a></li>
<li><a href="https://embecosm.com/research/superoptimization/">Superoptimization – Embecosm</a></li>

</ul>
</details>

**标签**: `#superoptimization`, `#compiler optimization`, `#program synthesis`, `#ACM`

---

<a id="item-6"></a>
## [SGLang v0.5.15 发布，带来重大性能优化](https://github.com/sgl-project/sglang/releases/tag/v0.5.15) ⭐️ 8.0/10

SGLang v0.5.15 引入了优化的 GLM-5.2 NVFP4 服务，在 8x B300 上实现 500+ tok/s/user，将 Speculative Decoding V2 设为默认调度方法，并添加了 IndexShare MTP，将草稿步骤成本降低高达 1.9 倍。 这些改进显著提升了大型语言模型的服务吞吐量和效率，特别是对于 GLM-5.2 和 DeepSeek-V4 等模型的生产部署，使 SGLang 成为高性能 LLM 推理中更具吸引力的选择。 关键特性包括默认启用的可中断 CUDA 图、线性注意力内核（FlashKDA、ReplaySSM）、针对草稿模型图的 FlashInfer 自动调优，以及对新模型如 Hunyuan 3 和 Qwen3.6（NVFP4）的支持。

github · Fridge003 · Jul 10, 22:58

**背景**: SGLang 是一个用于服务大型语言和多模态模型的开源框架，以其高性能和生产可扩展性而闻名。此版本专注于优化推测解码和特定模型的服务，特别是针对使用 NVFP4 量化和混合专家架构的新 GLM-5.2 模型。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/lukealonso/GLM-5.2-NVFP4">lukealonso/GLM-5.2-NVFP4 · Hugging Face</a></li>
<li><a href="https://www.baseten.co/blog/how-we-built-the-worlds-fastest-api-for-glm-52/">How we built the world’s fastest API for GLM-5.2</a></li>
<li><a href="https://docs.sglang.ai/">Welcome to SGLang - SGLang Documentation</a></li>

</ul>
</details>

**标签**: `#sglang`, `#LLM serving`, `#performance optimization`, `#speculative decoding`

---

<a id="item-7"></a>
## [苹果起诉 OpenAI，指控前员工窃取商业机密](https://9to5mac.com/2026/07/10/apple-sues-openai-trade-secret-theft/) ⭐️ 8.0/10

苹果对 OpenAI 提起诉讼，指控前员工在加入这家 AI 公司时系统性地窃取了商业机密。诉讼称，OpenAI 指导新员工如何避免被发现，并且员工在离职前将机密信息通过电子邮件发送给自己。 这两家科技巨头之间的诉讼可能为 AI 行业的商业机密保护树立法律先例，这在员工流动和信息泄露频繁的行业中尤为重要。该案也引发了对 OpenAI 招聘道德的严重质疑，并可能导致重大的财务和声誉后果。 苹果发现了一种模式：OpenAI 的招聘对象（包括在苹果工作 25 年的资深员工 Tang Yew Tan）在离职时通过电子邮件向自己发送机密信息。OpenAI 还被指控使用窃取的苹果硬件数据来接触苹果的供应商。

hackernews · stock_toaster · Jul 10, 20:47 · [社区讨论](https://news.ycombinator.com/item?id=48865019)

**背景**: 商业机密是企业为保持竞争优势而保护的专有信息。在 AI 行业，人才挖角和数据泄露频繁发生。苹果一贯积极保护知识产权，这起诉讼凸显了保护机密与员工流动之间的紧张关系。

**社区讨论**: 评论者大多认为苹果的诉讼理由充分，引用详细的指控和苹果的法律资源。一些人对 OpenAI 的做法表示不信任，另一些人则注意到一位长期苹果员工赌上职业生涯的个人悲剧。

**标签**: `#Apple`, `#OpenAI`, `#trade secrets`, `#lawsuit`, `#AI industry`

---

<a id="item-8"></a>
## [AI 证明图论中环双覆盖猜想](https://cdn.openai.com/pdf/04d1d1e4-bc75-476a-97cf-49055cd98d31/cdc_proof.pdf) ⭐️ 8.0/10

2026 年 7 月 10 日，OpenAI 发布预印本，声称其 GPT-5.6 Sol Ultra 模型生成了图论中一个重要未决问题——环双覆盖猜想的证明。 如果得到验证，这将标志着 AI 在自主解决长期存在的数学猜想方面取得重要里程碑，可能加速图论及相关领域的研究。 该证明被描述为极其简洁，表明模型找到了人类数学家未能发现的巧妙方法。提示词包含了大量指令，阻止了模糊的乐观表述，迫使模型生成严谨推理。

hackernews · scrlk · Jul 10, 18:29 · [社区讨论](https://news.ycombinator.com/item?id=48863490)

**背景**: 环双覆盖猜想（Cycle Double Cover Conjecture）断言：每个无桥图都存在一组环，使得每条边恰好出现两次。该猜想由 Tutte、Itai 与 Rodeh、Szekeres 以及 Seymour 独立提出，是图论中著名的未解决问题。其肯定解决将对图嵌入和结构图论产生影响。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Cycle_double_cover_conjecture">Cycle double cover conjecture</a></li>
<li><a href="https://cdn.openai.com/pdf/04d1d1e4-bc75-476a-97cf-49055cd98d31/cdc_proof.pdf">A PROOF OF THE CYCLE DOUBLE COVER CONJECTURE OPENAI</a></li>

</ul>
</details>

**社区讨论**: Hacker News 的评论对该证明的有效性表示怀疑，指出缺乏外部验证且该猜想较为冷门。一些用户强调需要大量提示工程，质疑 AI 是否真正展示了自主推理。另一些用户指出证明的简洁性既令人印象深刻又令人怀疑。

**标签**: `#AI`, `#mathematics`, `#proof`, `#GPT-5`, `#graph theory`

---

<a id="item-9"></a>
## [好工具通过减少摩擦变得无形](https://www.gingerbill.org/article/2026/07/10/good-tools-are-invisible/) ⭐️ 8.0/10

一篇题为《好工具是无形的》的文章认为，工具应尽量减少摩擦，让用户专注于任务，在 Hacker News 上引起了高度参与的讨论，获得 361 个点赞和 167 条评论。 这一讨论在开发者和 UX 从业者中引起深刻共鸣，凸显了工具设计中简单性与必要复杂性之间的核心张力，并影响着软件工具的设计和评估方式。 文章的核心论点是，好的工具通过消除不必要的摩擦对用户变得“无形”，同时保留完成任务所需的必要复杂性。社区讨论认为无形性是否取决于使用工具的时间，以及什么是随意摩擦与必要摩擦。

hackernews · theanonymousone · Jul 10, 10:32 · [社区讨论](https://news.ycombinator.com/item?id=48858121)

**背景**: 在软件工具设计中，“摩擦”指任何打断用户流程的因素，如复杂的配置或导航障碍。无形工具的概念由 Mark Weiser 的平静技术普及，强调最好的工具是那些退居背景的工具。本文将这一哲学应用于开发者工具和日常软件，在强大与简单之间取得平衡。

**社区讨论**: 评论者普遍同意这一原则，但讨论了细微差别：一些人认为必要的摩擦（例如解决合并冲突）是可以接受的，并随着时间变得无形，而另一些人则质疑未经测量的生产力主张。讨论还涉及终端与 GUI 的争论，对键盘与鼠标效率看法不一。

**标签**: `#tool design`, `#user experience`, `#developer tools`, `#software engineering`, `#Hacker News discussion`

---

<a id="item-10"></a>
## [Meta 发布 Muse Spark 1.1，提供 API 并强化智能体能力](https://simonwillison.net/2026/Jul/9/muse-spark-1-1/#atom-everything) ⭐️ 8.0/10

Meta 发布了 Muse Spark 1.1，这是首个提供公开 API 的 Spark 模型，在智能体工具调用和计算机使用能力上有了显著提升。 此次更新推进了 Meta 的生成式 AI 平台，使智能体工作流更易访问，开发者能够构建可与外部工具交互并以编程方式控制计算机的自主 AI 智能体。 Muse Spark 1.1 评估报告中包含一个引人入胜的章节“自我对话中的吸引子状态”，两个模型副本对话时会产生如“我的整个存在就是一个候诊室”之类的存在主义陈述。Simon Willison 还创建了一个 LLM 插件（llm-meta-ai），用于通过命令行和 Python 访问该模型。

rss · Simon Willison · Jul 9, 16:24

**背景**: 智能体工具调用允许 AI 模型自主决定调用哪些外部函数或 API 来完成任务，是智能体 AI 的核心。计算机使用能力使 AI 能够像人类一样控制计算机界面——移动鼠标、点击按钮、导航应用程序。这些功能是构建能够执行复杂多步骤工作流的自主智能体的关键。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://towardsdatascience.com/tool-calling-explained-how-ai-agents-decide-what-to-do-next/">Tool Calling, Explained: How AI Agents Decide What to Do Next</a></li>
<li><a href="https://sidecar.ai/blog/how-ai-learned-to-use-your-computer-and-why-that-changes-everything">How AI Learned to Use Your Computer (And Why That Changes Everything)</a></li>
<li><a href="https://arxiv.org/abs/2606.30571">[2606.30571] Attractor States Emerge in Multi-Turn LLM Conversations</a></li>

</ul>
</details>

**标签**: `#AI`, `#Machine Learning`, `#Meta`, `#Tool Calling`, `#Language Models`

---

<a id="item-11"></a>
## [OpenAI 推出 ChatGPT Work，自主任务代理](https://openai.com/index/chatgpt-for-your-most-ambitious-work) ⭐️ 8.0/10

OpenAI 宣布推出 ChatGPT Work，这是一种新的代理能力，可以跨应用和文件自主执行操作来完成任务，如有需要可长时间跟踪项目。 这标志着向 AI 辅助生产力迈出了重要一步，超越了对话式 AI，实现自主完成任务。它可能通过直接与用户的工具集成来改变专业人士的工作流程。 该公告缺乏深层技术细节，但描述将 ChatGPT Work 定位为能够将目标转化为成品工作的代理。它需要具备持续数小时的持久性以及使用外部工具的能力，这与 AI 代理的常见定义一致。

rss · OpenAI Blog · Jul 9, 10:00

**背景**: AI 代理是能够代表用户自主执行任务的系统，通常使用自然语言界面和外部工具。与仅生成文本的标准生成式 AI 不同，代理型 AI 可以循环采取行动，决定并执行步骤。OpenAI 的公告表明他们正在进入代理型 AI 的竞争领域，与其他参与者并驾齐驱。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/AI_agent">AI agent - Wikipedia</a></li>
<li><a href="https://www.ibm.com/think/topics/ai-agents">What Are AI Agents? | IBM</a></li>

</ul>
</details>

**标签**: `#ChatGPT`, `#AI agent`, `#OpenAI`, `#productivity`, `#AI tools`

---

<a id="item-12"></a>
## [OpenAI 为 GPT-5.5 推出生物漏洞赏金计划](https://openai.com/index/bio-bug-bounty) ⭐️ 8.0/10

OpenAI 宣布了一项名为 Bio Bug Bounty 的新漏洞赏金计划，专门针对其即将推出的 GPT-5.5 AI 系统的生物误用风险。该计划邀请研究人员识别可能通过 AI 实现生物制剂武器化或滥用的漏洞。 该计划是 OpenAI 为应对日益严重的 AI 相关生物威胁而采取的主动安全措施，为负责任的 AI 发展树立了先例。它可能影响整个行业在缓解先进 AI 模型双重用途风险方面的实践。 Bio Bug Bounty 专注于大型语言模型（LLM）和生物设计工具带来的风险，这与近期研究中的区分一致。对于展示出具体生物误用途径（例如能够创造新型病原体或毒素）的发现，将提供奖励。

rss · OpenAI Blog · Jul 9, 10:00

**背景**: 人工智能在生命科学领域的进步虽然有益，但也引发了生物安全担忧，因为 AI 工具可能降低制造生物武器的门槛。研究区分了提供信息的 LLM 和直接实现基因工程的生物设计工具。OpenAI 早期的 Safety Bug Bounty 计划涵盖了通用 AI 安全问题，但这一新举措专门针对生物风险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/pdf/2306.13952">Artificial intelligence and biological misuse: Differentiating ...</a></li>
<li><a href="https://openai.com/index/safety-bug-bounty/">Introducing the OpenAI Safety Bug Bounty program | OpenAI</a></li>

</ul>
</details>

**标签**: `#openai`, `#ai safety`, `#bug bounty`, `#biological risk`

---

<a id="item-13"></a>
## [AI 爬虫机器人仍在淹没网站](https://lwn.net/Articles/1080822/) ⭐️ 8.0/10

LWN 的一篇更新报道称，用于训练数据的 AI 爬虫机器人淹没网站的问题在过去一年中持续恶化，来自未知行为者的流量达到了新高。 这之所以重要，是因为它威胁到了开放网络，网站运营者在持续爬取下难以维护站点，可能导致公共数据可用性降低。 原始文章发布于 2025 年初，一年后问题未减反增；流量来源仍不明，目前尚无明确的缓解方案。

rss · LWN.net · Jul 10, 15:20

**背景**: AI 爬虫机器人是自动化的程序，它们爬取网站以收集文本和其他数据用于训练大型语言模型（LLM）。这种活动可能因高请求量而使服务器不堪重负，降低合法用户的体验并增加托管成本。开放网络依赖于自愿访问，但激进的爬取破坏了这一模式。

**标签**: `#AI scraping`, `#web scraping`, `#LLM training data`, `#bot mitigation`, `#open web`

---

<a id="item-14"></a>
## [GitHub 为每个仓库分配了持久的所有者](https://github.blog/security/application-security/how-github-gave-every-repository-a-durable-owner/) ⭐️ 8.0/10

GitHub 在 45 天内为所有活跃仓库分配了经过验证的所有者，并归档了其余仓库。这解决了超过 14,000 个仓库中长期存在的所有权问题。 这在大规模上确保了仓库的安全性、可维护性和问责制，防止项目被遗弃或变得脆弱。同时，通过明确所有权，为未来的改进奠定了基础。 GitHub 拥有超过 14,000 个仓库，其中不到一半有明确的所有者。该流程包括验证活跃仓库的所有者并归档不活跃的仓库，使所有权成为后续工作的基础。

rss · GitHub Blog · Jul 9, 16:29

**背景**: 仓库所有权对安全性、可维护性和问责制至关重要，所有权不明确可能导致代码被遗弃或变得脆弱。许多大型组织在规模化时都面临此问题，因为所有者可能离开或失去兴趣。GitHub 的方法为此常见问题提供了系统性解决方案。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.blog/security/application-security/how-github-gave-every-repository-a-durable-owner/">How GitHub gave every repository a durable owner - The GitHub Blog</a></li>
<li><a href="https://news.ycombinator.com/item?id=48852151">How GitHub gave every repository a durable owner | Hacker News</a></li>

</ul>
</details>

**社区讨论**: Hacker News 的评论指出，当团队所有者离开时，项目会被随机重新分配，这并不理想。有人讨论需要更好的交换和转移机制。总体而言，该方法被视为一项实用的改进。

**标签**: `#repository management`, `#ownership`, `#GitHub`, `#large-scale systems`, `#security`

---

<a id="item-15"></a>
## [HubSpot 将语义搜索扩展至 200 亿向量](https://www.infoq.cn/article/eRl25z5ewrRHjReWhOUX?utm_source=rss&utm_medium=article) ⭐️ 8.0/10

HubSpot 发表了一篇详细文章，分享了其将语义搜索系统扩展至处理 200 亿个向量的工程实践。 随着企业越来越多地将语义搜索用于 AI 驱动的应用，HubSpot 的经验为构建和优化大规模向量搜索系统提供了宝贵参考，将影响搜索相关性和用户体验。 文章可能涵盖向量量化、分片、缓存以及近似最近邻（ANN）算法等技术，以实现此规模下的低延迟搜索。

rss · InfoQ 中文站 · Jul 10, 12:00

**背景**: 语义搜索使用向量嵌入来理解查询背后的含义，将文本转换为高维向量。向量数据库旨在使用余弦距离等相似度指标高效存储和搜索数十亿个这样的向量。扩展到 200 亿向量需要分布式系统、高级索引以及精细的资源管理。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://dbaplus.cn/news-160-5869-1.html">大模型崛起，向量数据库却凉透了？老码农这样看 - 更多 - dbaplus社群：围绕Data、Blockchain、AiOps的企业级专业社群。技术大咖、原创干货，每天精品原创文章推送，每周线上技术分享，每月线下技术沙龙。</a></li>
<li><a href="https://www.amazonaws.cn/en/knowledge/vector-database/">vector-database - 什么是向量数据库？ - 亚马逊云科技</a></li>

</ul>
</details>

**标签**: `#语义搜索`, `#向量数据库`, `#大规模系统`, `#HubSpot`, `#工程实践`

---

<a id="item-16"></a>
## [首个开源具身视频基础模型](https://www.infoq.cn/article/SCC8javdsA2zgBg0c2C1?utm_source=rss&utm_medium=article) ⭐️ 8.0/10

研究团队发布了 LingBot-Video，这是首个面向具身智能的开源大规模混合专家（MoE）视频生成模型，相关代码和模型已在 GitHub 和 Hugging Face 上公开。 该模型为机器人提供了基础视频理解和生成能力，可能使其能够预测物理交互并规划动作，这是迈向通用具身智能的关键一步。 该模型采用 MoE 架构，总参数量 300 亿，每个 token 激活 30 亿参数（30B-A3B），专注于机器人任务的视频预测和生成。模型在 Hugging Face 上以 robbyant/lingbot-video-moe-30b-a3b 发布。

rss · InfoQ 中文站 · Jul 9, 15:32

**背景**: 具身 AI 旨在让机器人等智能体具备在物理世界中感知和行动的能力。视频基础模型通过大规模视频数据学习理解运动、物理和物体交互。LingBot-Video 旨在通过生成合理的未来视频，让机器人预测动作结果，从而充当“机器人大脑的物理引擎”。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/robbyant/lingbot-video">GitHub - Robbyant/lingbot-video: Scaling Mixture-of-Experts Video Pretraining for Embodied Intelligence · GitHub</a></li>
<li><a href="https://huggingface.co/robbyant/lingbot-video-moe-30b-a3b">robbyant/lingbot-video-moe-30b-a3b · Hugging Face</a></li>

</ul>
</details>

**标签**: `#embodied AI`, `#robotics`, `#open source`, `#video foundation model`, `#physics engine`

---

<a id="item-17"></a>
## [Netflix 通过动态分区拆分大幅降低 Cassandra 读取延迟](https://www.infoq.cn/article/GRDxYebxA7ywxO4seBWy?utm_source=rss&utm_medium=article) ⭐️ 8.0/10

Netflix 工程师为 Apache Cassandra 部署了一种动态分区拆分机制，将大型时间序列分区的读取延迟从秒级降低到几十毫秒级。 这一突破提高了集群稳定性并减少了读取超时，使 Netflix 能够更高效地处理 PB 级时间序列数据。它展示了一种应对常见 Cassandra 性能瓶颈的新颖且透明的方法。 该技术按 TimeSeries ID 异步且透明地拆分宽分区，无需修改应用代码。它针对 Netflix 的 TimeSeries Abstraction 平台，将尾部延迟降至约 200 毫秒。

rss · InfoQ 中文站 · Jul 9, 15:00

**背景**: Apache Cassandra 是一种分布式 NoSQL 数据库，数据存储在分区中。当单个分区（如时间序列 ID）累积过多记录时，它会变得“宽”，导致高读取延迟。Netflix 的 TimeSeries Abstraction 存储 PB 级的时间事件数据，使宽分区成为一个关键性能问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.infoq.com/news/2026/07/netflix-cassandra-partition/">Netflix Cuts Cassandra Read Latency from Seconds to... - InfoQ</a></li>
<li><a href="https://www.vilbay.com/2026/07/06/netflix-tames-wide-cassandra-partitions-with-dynamic-splitting-slashing-read-latency/">Netflix Tames Wide Cassandra Partitions with Dynamic Splitting, Slashing Read Latency - Vilbay.com - Technology & programming news</a></li>

</ul>
</details>

**标签**: `#Cassandra`, `#Netflix`, `#database optimization`, `#latency`, `#distributed systems`

---

<a id="item-18"></a>
## [Scarf 在生产环境中使用 7 年后迁移出 Haskell](https://avi.press/posts/2026-07-10-after-7-years-in-production-scarf-has-reluctantly-moved-away-from-haskell.html) ⭐️ 8.0/10

在生产环境中使用 Haskell 七年后，Scarf 决定迁移出该语言，并列举了遇到的种种挑战。 此次迁移凸显了在利基函数式编程语言中维护大型系统的现实困难，为其他考虑将 Haskell 用于关键基础设施的团队提供了一个警示案例。 该文章详细回顾了 Scarf 多年来的 Haskell 部署历程，涵盖了最终导致他们不得不出此下策的技术和组织因素。

rss · Lobsters · Jul 10, 16:48

**背景**: Haskell 是一种纯函数式编程语言，以强静态类型和高可靠性著称，但与 Python 或 Java 等主流语言相比，其生态和人才储备较小。许多采用 Haskell 用于生产系统的公司最终都会面临可维护性和人员招聘方面的挑战。

**标签**: `#Haskell`, `#production`, `#programming languages`, `#migration`, `#lessons learned`

---

<a id="item-19"></a>
## [Cpp2Rust：自动将 C++翻译为安全 Rust 的工具发布](https://github.com/Cpp2Rust/cpp2rust) ⭐️ 8.0/10

Cpp2Rust 是一款新的开源工具，它利用 clang 的抽象语法树自动将 C++代码翻译成安全的 Rust 代码。该工具旨在帮助开发者将现有 C++代码库迁移到 Rust，同时保持安全性保证。 该工具解决了系统编程中的一个主要痛点：无需手动重写即可将大型 C++代码库迁移到 Rust，以提高内存安全性。它可能加速依赖遗留 C++代码的行业对 Rust 的采用。 工具不支持的构造包括联合体、volatile、goto、异常和位域，这些可能需要手动处理。该工具是语法驱动的，目前处于早期开发阶段。

rss · Lobsters · Jul 10, 03:24

**背景**: C++长期以来用于系统编程，但容易出现内存安全错误。Rust 在无需垃圾回收的情况下提供了内存安全性，使其成为一个有吸引力的替代方案。然而，手动翻译数百万行 C++代码是不切实际的，因此产生了对像 Cpp2Rust 这样的自动翻译工具的需求。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/Cpp2Rust/cpp2rust">Cpp2Rust: Automatic Translation of C++ to Safe Rust - GitHub</a></li>
<li><a href="https://news.ycombinator.com/item?id=48862086">Cpp2Rust: Translates C++ to safe Rust automatically - Hacker News</a></li>

</ul>
</details>

**标签**: `#cpp`, `#rust`, `#translation`, `#safe`, `#tool`

---

<a id="item-20"></a>
## [Rust 1.97.0 发布，新增 lint 和目标特性](https://blog.rust-lang.org/2026/07/09/Rust-1.97.0/) ⭐️ 8.0/10

Rust 1.97.0 于 2026 年 7 月 9 日发布，带来了多项语言改进、稳定版 API 和 Cargo 增强。主要新增包括一个 `dead_code_pub_in_binary` lint 以及 LoongArch 目标特性的稳定化。 此次发布延续了 Rust 稳步改进的节奏，通过更好的 lint 覆盖和平台支持提升了开发者体验。LoongArch 目标特性的稳定化对于 Rust 在该架构上的采用具有重要意义。 语言现在将 `Result<T, Uninhabited>` 视为等同于 `T` 以用于 must-use lint，减少了误报。Cargo 稳定了 `build.warnings` 配置以控制 CI 中的 lint 警告，并新增了 `-m` 作为 `--manifest-path` 的简写。

rss · Lobsters · Jul 9, 14:56

**背景**: Rust 中的不可创建类型（uninhabited type）是没有可能值的类型，如 `!`（never 类型）或没有变体的枚举。新的 lint 改进利用这一概念来避免当 `Result` 永远不可能是错误时的误报。LoongArch 是一种中国 CPU 架构；稳定其目标特性可以更好地在该平台上生成代码。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://releases.rs/docs/1.97.0/">1.97.0 | Rust Changelogs</a></li>
<li><a href="https://github.com/rust-lang/rust/pull/154510">Partially stabilize LoongArch target features by heiher · Pull Request #154510 · rust-lang/rust</a></li>
<li><a href="https://smallcultfollowing.com/babysteps/blog/2018/08/13/never-patterns-exhaustive-matching-and-uninhabited-types-oh-my/">Never patterns, exhaustive matching, and uninhabited types ...</a></li>

</ul>
</details>

**标签**: `#Rust`, `#programming language`, `#release`, `#community`

---

<a id="item-21"></a>
## [严重 KVM 逃逸漏洞'Januscape'允许虚拟机突破](https://hackaday.com/2026/07/10/this-week-in-security-escaping-linux-vms-vulnerable-solar-confusing-ai-again-and-confusing-npm-malware/) ⭐️ 8.0/10

发现了一个名为 Januscape（CVE-2026-53359）的严重漏洞，存在于 Linux 内核虚拟机（KVM）中，允许客户虚拟机破坏宿主机内存并突破隔离。该漏洞影响 Intel 和 AMD x86 系统，已存在 16 年。 该漏洞极其严重，因为它破坏了虚拟化的核心隔离保证，影响云提供商以及任何使用 KVM 的环境。成功利用可让攻击者从客户虚拟机逃逸并在宿主机上执行代码，从而危及整个基础设施。 该漏洞是 KVM 影子 MMU 模拟中的一个释放后使用（use-after-free）缺陷，需要客户机拥有 root 权限才能利用。研究人员已演示了完整的逃逸利用，但概念验证未公开。

rss · Hackaday · Jul 10, 14:00

**背景**: KVM（基于内核的虚拟机）是集成到 Linux 内核中的开源虚拟化模块，被 AWS、Google Cloud 和 Azure 等云提供商广泛使用。它允许多个虚拟机在单一物理主机上运行，并通过虚拟机监控程序强制隔离各虚拟机及宿主机。Januscape 漏洞利用了影子页表机制中的缺陷，该机制用于管理不支持硬件辅助虚拟化的虚拟机的内存。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://thehackernews.com/2026/07/16-year-old-linux-kvm-flaw-lets-guest.html">16-Year-Old Linux KVM Flaw Lets Guest VMs Escape to Host on Intel and AMD x86 Systems</a></li>
<li><a href="https://www.securityweek.com/linux-kernel-vulnerability-allows-vm-escape-on-intel-and-amd-systems/">Linux Kernel Vulnerability Allows VM Escape on Intel and AMD Systems - SecurityWeek</a></li>
<li><a href="https://cyso.cloud/blog/preventive-emergency-maintenance-januscape-cve-2026-53359">Januscape (CVE-2026-53359): How Cyso Protected Its Cloud</a></li>

</ul>
</details>

**标签**: `#security`, `#virtualization`, `#KVM`, `#vulnerability`, `#Linux`

---

<a id="item-22"></a>
## [开源射频传感器 QuadRF 可穿墙探测无人机和 WiFi 信号](https://www.jeffgeerling.com/blog/2026/quadrf-can-spot-drones-and-see-wifi-through-my-wall/) ⭐️ 7.0/10

QuadRF 是一款由树莓派 5 驱动的开源软件定义无线电（SDR）平台，能够以每秒 30 帧的速度实时穿墙探测无人机并可视化 WiFi 信号。 这使先进的射频传感技术大众化，让爱好者和研究人员能以低成本进行无人机探测和穿墙 WiFi 成像，而这些以往需要昂贵的专用设备。 QuadRF 采用 4x4 MIMO SDR 架构，具有四个相干通道和集成的树莓派 5，其软件栈以 GPLv2/GPLv3 开源，但生产级 RF 核心和 DSP 位流仍为专有。

hackernews · speckx · Jul 10, 15:59 · [社区讨论](https://news.ycombinator.com/item?id=48861717)

**背景**: 软件定义无线电（SDR）使用软件而非传统硬件处理射频信号，实现了灵活可编程的通信。多输入多输出（MIMO）利用多个天线提高信号质量和空间感知能力。QuadRF 将这些技术与树莓派 5 结合，创建了实时“射频相机”，将环境中的无线信号可视化。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.crowdsupply.com/scale-rf/quadrf">QuadRF | Crowd Supply</a></li>
<li><a href="https://lunar.computer/quadrf-turns-a-raspberry-pi-5-into-an-open-source-20260624">QuadRF Turns a Raspberry Pi 5 Into an Open Source RF Camera</a></li>
<li><a href="https://github.com/tardani95/quadrf-main">GitHub - tardani95/ quadrf -main · GitHub</a></li>

</ul>
</details>

**社区讨论**: 创作者 mrtnmcc 积极回应了反馈，承诺改进 UI。部分评论者质疑'穿墙看 WiFi'的说法，认为 WiFi 本身就能穿墙，而其他人则提出了声源定位、扫描隐藏设备的 RF 频段等潜在应用。

**标签**: `#RF sensing`, `#open source hardware`, `#drone detection`, `#WiFi`

---

<a id="item-23"></a>
## [《终结者 2》特效技术口述史](https://vfxblog.com/2017/08/23/the-tech-of-terminator-2-an-oral-history/) ⭐️ 7.0/10

一篇 2017 年的口述历史文章回顾了使《终结者 2》视觉效果具有开创性的技术创新，包括液态金属 T-1000 以及 Softimage 软件的使用。 这次回顾突显了为现代电影视觉效果和 CGI 奠定基础的开创性工作，影响了数代艺术家和工程师。 文章详细介绍了用于液态金属子弹撞击的定制炸药爆破，并指出 Softimage 是创建 T-1000 的主要 3D 软件。

hackernews · markus_zhang · Jul 10, 16:48 · [社区讨论](https://news.ycombinator.com/item?id=48862365)

**背景**: 1991 年，《终结者 2：审判日》通过将实际效果与计算机生成图像（CGI）相结合，突破了视觉效果的边界。液态金属 T-1000 是通过结合实用爆破、定格动画和早期的 3D 软件（如 Softimage）实现的，该软件后来被微软收购并广泛应用于电影制作。这篇口述历史捕捉了工业光魔（ILM）艺术家和工程师们面临的挑战和创新。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Softimage_(company)">Softimage (company) - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者对这些实际效果表示赞赏，特别是用于子弹撞击的定制爆破。他们还提到 4K 重制版重返影院、Softimage 的作用，并推荐了关于 Steve Williams 的纪录片《Jurassic Punk》。

**标签**: `#visual effects`, `#computer graphics`, `#film technology`, `#practical effects`, `#Softimage`

---

<a id="item-24"></a>
## [纽约市禁止欺骗性订阅行为](https://www.theguardian.com/us-news/2026/jul/10/new-york-city-deceptive-subscriptions-ban) ⭐️ 7.0/10

2026 年 7 月 10 日，纽约市长 Mamdani 宣布了一项具有里程碑意义的禁令，禁止欺骗性订阅行为，包括对所有周期性订阅强制实施“一键取消”要求。 这项规定在美国最大城市树立了强有力的消费者保护标准，可能影响其他地区，并迫使软件工程师和产品团队简化取消流程。 该禁令专门针对欺骗性订阅行为，包含“一键取消”要求，但目前尚不清楚是否也涵盖垃圾费用（如酒店度假费），评论者指出这些是常见投诉。

hackernews · randycupertino · Jul 10, 18:26 · [社区讨论](https://news.ycombinator.com/item?id=48863464)

**背景**: 2024 年 10 月，美国联邦贸易委员会（FTC）发布了全国性的“一键取消”规则，但于 2025 年 7 月被第八巡回上诉法院废除，留下了监管空白。“一键取消”要求卖方让消费者取消订阅的流程与注册时一样简单，从而结束需要电话或繁琐流程的做法。纽约市的这项法律似乎是在市政层面填补了这一空白，但具体执行机制尚未公布。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.ftc.gov/news-events/news/press-releases/2024/10/federal-trade-commission-announces-final-click-cancel-rule-making-it-easier-consumers-end-recurring">Federal Trade Commission Announces Final “Click-to-Cancel” Rule Making It Easier for Consumers to End Recurring Subscriptions and Memberships | Federal Trade Commission</a></li>
<li><a href="https://en.wikipedia.org/wiki/Click_to_Cancel">Click to Cancel</a></li>
<li><a href="https://www.consumerfinancemonitor.com/2025/07/23/eighth-circuit-voids-ftc-click-to-cancel-rule/">Eighth Circuit voids FTC ‘Click to Cancel’ rule | Consumer Finance Monitor</a></li>

</ul>
</details>

**社区讨论**: 评论者反应不一：有人欢迎此举是保护消费者的正当政府行为；也有人指出加州已有类似规定，并对纽约市法律的执行力度表示质疑，尤其是针对酒店垃圾费用。一位用户分享了 Evernote 在多次取消后仍继续收费的糟糕经历，凸显了此类监管的必要性。

**标签**: `#consumer protection`, `#regulation`, `#subscriptions`, `#tech policy`

---

<a id="item-25"></a>
## [Emacs 作为面向服务的平台](http://yummymelon.com/devnull/in-emacs-everything-looks-like-a-service.html) ⭐️ 7.0/10

一篇博文认为 Emacs 可以被视为面向服务的平台，其中的编辑、进程管理等一切功能都被当作服务，与 Lisp 机器和操作系统相类比。 这一视角将 Emacs 重新定义为不仅是一个编辑器，而是一个具有鼓励可扩展性和集成性的架构原则的平台，可能影响开发者对构建模块化软件的思考方式。 博文明确指出‘在 Emacs 中，一切看起来都像服务’，强调了 Emacs 的缓冲区、进程甚至外部工具如何通过类似服务的接口进行集成。

hackernews · kickingvegas · Jul 10, 08:21 · [社区讨论](https://news.ycombinator.com/item?id=48857230)

**背景**: Emacs 是一个基于 Lisp 解释器的可高度扩展的文本编辑器。面向服务架构（SOA）的概念是将软件设计为通过网络通信的松散耦合服务。Lisp 机器是专为高效运行 Lisp 而设计的专用计算机，其操作系统用 Lisp 编写。这一背景有助于理解将 Emacs 视为模糊编辑器与操作环境界限的平台的思想。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Lisp_machine">Lisp machine</a></li>
<li><a href="https://en.wikipedia.org/wiki/Service-oriented_architecture">Service-oriented architecture - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍认同 Emacs 是一个平台，但有人指出将其称为‘面向服务的平台’可能是在延伸术语。其他人则提到与 Lisp 机器的相似之处，并批评那些强制统一工具链的组织，认为这往往牺牲了基于平台的灵活性。

**标签**: `#emacs`, `#software architecture`, `#platform`, `#lisp`, `#services`

---

<a id="item-26"></a>
## [对闪卡的深情告白：Anki 与学习](https://lesleylai.info/en/flashcards/) ⭐️ 7.0/10

这篇文章是对闪卡和间隔重复软件 Anki 的个人反思，探讨了它们对于有效学习的益处与局限。 它引发了关于数字与手写闪卡之间权衡的讨论，以及 AI 在生成闪卡中的潜在作用，这对任何对优化学习技术感兴趣的人都具有相关性。 作者指出他们大部分卡片是手写的以适合他们自己的大脑，并批评无摩擦的数字替代品忽略了初始学习努力的意义。社区评论也强调，LLM 生成的卡片通常需要大量重写。

hackernews · surprisetalk · Jul 10, 15:30 · [社区讨论](https://news.ycombinator.com/item?id=48861319)

**背景**: 间隔重复是一种基于证据的学习技巧，新的和难的闪卡会频繁出现以利用间隔效应。Anki 是一款流行的开源间隔重复软件，可自动安排复习时间表。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Anki">Anki - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Spaced_repetition">Spaced repetition - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者分享了多样化的经验：有些人认为 Anki 是记忆的恩赐，而其他人则认为手写卡片更有利于深层编码。AI 生成闪卡的潜力受到争论，许多人认为其平庸且需要耗费时间优化。

**标签**: `#flashcards`, `#spaced repetition`, `#Anki`, `#learning`, `#memory`

---

<a id="item-27"></a>
## [AI 代理记忆选择的决策树方法](https://machinelearningmastery.com/choosing-the-right-ai-agent-memory-strategy-a-decision-tree-approach/) ⭐️ 7.0/10

该文章介绍了一个决策树框架，指导从业者根据具体用例为 AI 代理选择合适的记忆策略。 记忆是 AI 代理有效运作的基础，该决策树提供了一种清晰的系统化方法，减少了试错成本，有助于构建更可靠的代理。 该决策树可能涵盖短期记忆、情节记忆、语义记忆和程序记忆等类型，以及它们在成本、检索质量和失败模式方面的权衡。

rss · Machine Learning Mastery · Jul 10, 20:26

**背景**: AI 代理需要记忆来保留上下文、从交互中学习并执行复杂任务。不同的记忆策略——如短期记忆、情节记忆、语义记忆和程序记忆——服务于不同目的，并具有不同的成本性能特征。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://gravity.fast/blog/ai-agent-long-term-memory-strategies/">AI Agent Long-Term Memory Strategies , Explained | Gravity</a></li>
<li><a href="https://www.ibm.com/think/topics/ai-agent-memory">What Is AI Agent Memory? | IBM</a></li>

</ul>
</details>

**标签**: `#AI Agents`, `#Memory`, `#Decision Tree`, `#Machine Learning`

---

<a id="item-28"></a>
## [德国电信采用 OpenAI 转型为 AI 原生电信公司](https://openai.com/index/deutsche-telekom) ⭐️ 7.0/10

德国电信正在利用 OpenAI 的模型改造客户服务、员工工作流、网络运营和语音服务，旨在成为 AI 原生电信公司。 此次合作展示了 AI 在大型电信公司中的大规模实际部署，可能为行业树立先例，并展示 AI 如何从根本上重塑核心运营。 转型包括使用 OpenAI 模型实现实时翻译、智能通话辅助、自动摘要和网络优化。德国电信在其网络中服务超过 3 亿客户。

rss · OpenAI Blog · Jul 10, 07:00

**背景**: “AI 原生电信公司”将 AI 深度嵌入基础设施，实现自主和预测性运营。根据麦肯锡最近的一项调查，约 50%的电信运营商现在已从 AI 或生成式 AI 中获益，而一年前这一比例为 25%。OpenAI 最近推出了 GPT-Live 和 GPT-Realtime-2 等先进语音模型，支持更自然的全双工对话和实时翻译。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openai.com/index/deutsche-telekom/">How Deutsche Telekom is rewiring telecommunications with AI | OpenAI</a></li>
<li><a href="https://www.mckinsey.com/industries/technology-media-and-telecommunications/our-insights/scaling-the-ai-native-telco">Scaling the AI-native telco | McKinsey</a></li>
<li><a href="https://www.reuters.com/business/media-telecom/openai-unveils-three-audio-models-real-time-voice-tasks-2026-05-07/">OpenAI unveils three audio models for real-time voice tasks | Reuters</a></li>

</ul>
</details>

**标签**: `#AI`, `#telecommunications`, `#OpenAI`, `#digital transformation`, `#enterprise AI`

---

<a id="item-29"></a>
## [GPT 5.6 的 72 种配置详解](https://sebastianraschka.com/blog/2026/gpt-5-6-configurations.html) ⭐️ 7.0/10

GPT 5.6 拥有 72 种可能的配置，这些配置来自模型和努力（effort）选择的不同组合，并映射到训练时间和推理时间缩放。Sebastian Raschka 的说明阐明了这些配置如何从两个缩放维度产生。 理解这些配置有助于实践者选择合适的默认设置进行部署，平衡成本与性能。它也展示了缩放定律如何实际应用于现代大型语言模型。 这 72 种配置源自训练时间缩放（如模型大小、训练数据）和推理时间缩放（如用于推理的计算预算）的选择。虽然未提供具体分解，但映射突出了这两个缩放轴之间的相互作用。

rss · Sebastian Raschka · Jul 9, 22:33

**背景**: AI 中的缩放定律已从预训练缩放演变到包括后训练和测试时间（推理时间）缩放。训练时间缩放涉及在训练期间使用更多计算来提升模型性能，而推理时间缩放则在推理期间分配额外计算以增强推理能力，通常通过更长的思维链实现。GPT 5.6 的配置变化反映了这两个缩放维度。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://magazine.sebastianraschka.com/p/categories-of-inference-time-scaling">Categories of Inference-Time Scaling for Improved LLM Reasoning</a></li>
<li><a href="https://blogs.nvidia.com/blog/ai-scaling-laws/">How Scaling Laws Drive Smarter, More Powerful AI | NVIDIA Blog</a></li>

</ul>
</details>

**标签**: `#GPT-5.6`, `#scaling laws`, `#inference-time scaling`, `#training-time scaling`, `#configuration`

---

<a id="item-30"></a>
## [CodeQL 2.26.0 新增 Kotlin 2.4.0 支持和 AI 提示注入检测](https://github.blog/changelog/2026-07-10-codeql-2-26-0-adds-kotlin-2-4-0-support-and-ai-prompt-injection-detection) ⭐️ 7.0/10

GitHub 发布了 CodeQL 2.26.0，新增对 Kotlin 2.4.0 的支持，并引入 AI 提示注入漏洞的检测功能。 此次更新增强了使用 Kotlin 的应用的安全性，并针对 AI 系统中新兴的提示注入威胁提供了检测，帮助开发者更早发现此类漏洞。 对 Kotlin 2.4.0 的支持确保了与最新语言特性的兼容性，而 AI 提示注入检测查询可识别与大型语言模型交互的代码中潜在的注入点。

rss · GitHub Changelog · Jul 10, 20:40

**背景**: CodeQL 是 GitHub 开发的语义代码分析引擎，用于自动发现安全漏洞。AI 提示注入是一种通过恶意输入诱使 AI 模型执行非预期操作的技术，在基于大型语言模型的应用中构成重大风险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/CodeQL">CodeQL</a></li>
<li><a href="https://docs.github.com/code-security/code-scanning/introduction-to-code-scanning/about-code-scanning-with-codeql">Code scanning with CodeQL - GitHub Docs</a></li>
<li><a href="https://www.emergentmind.com/topics/prompt-injection-detection">Prompt Injection Detection Methods</a></li>

</ul>
</details>

**标签**: `#CodeQL`, `#static analysis`, `#security`, `#Kotlin`, `#AI prompt injection`

---

<a id="item-31"></a>
## [GitHub 用 Unix 工具改进 Copilot 代码审查](https://github.blog/ai-and-ml/github-copilot/better-tools-made-copilot-code-review-worse-heres-how-we-actually-improved-it/) ⭐️ 7.0/10

GitHub 通过迁移到共享的 Unix 风格代码探索工具来改进 Copilot 代码审查，通过围绕拉取请求证据重塑代理工作流，降低了审查成本。 这一优化表明，如果集成不当，更好的工具本身可能使 AI 代码审查变得更糟，而该解决方案为在软件工程中使用 AI 代理的团队提供了可操作的见解。 迁移涉及共享的 Unix 风格工具和自定义工具指令，内部基准测试使代理行为足够可见以便调优，从而减少了冗余和成本。

rss · GitHub Blog · Jul 10, 15:57

**背景**: GitHub Copilot 代码审查使用 AI 代理自动审查拉取请求。Unix 风格的工具如 grep、find 和 sed 在代码探索中很常见。以前，每个代理都有自己的工具栈，导致效率低下。通过共享一组通用工具，系统减少了开销并提高了一致性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.blog/ai-and-ml/github-copilot/better-tools-made-copilot-code-review-worse-heres-how-we-actually-improved-it/">Better tools made Copilot code review worse. - The GitHub Blog</a></li>
<li><a href="https://github.blog/changelog/2026-06-18-copilot-code-review-agents-md-support-and-ui-improvements/">Copilot code review: AGENTS.md support and UI improvements - GitHub Changelog</a></li>

</ul>
</details>

**标签**: `#GitHub Copilot`, `#code review`, `#AI`, `#software engineering`, `#Unix tools`

---

<a id="item-32"></a>
## [Airbnb 分享动态配置 Sidecar Sitar-agent 架构](https://www.infoq.cn/article/fO5byVPuZwwlBPosijBV?utm_source=rss&utm_medium=article) ⭐️ 7.0/10

Airbnb 发布了 Sitar-agent 的详细架构，这是一个用于 Kubernetes 的动态配置 sidecar，于 2024 年从 Ruby 重写为 Java。 该架构使工程师能够通过配置更改来修改应用程序行为，而无需重新部署服务，从而在大规模场景下显著提升运营效率。 Sitar-agent 通过共享文件系统和内存缓存，将配置数据本地提供给应用程序容器，与主应用运行在同一个 Kubernetes Pod 中。

rss · InfoQ 中文站 · Jul 11, 09:00

**背景**: Sidecar 模式是指在同一个 Pod 中运行辅助容器与应用主容器。动态配置系统允许运维人员在运行时更改应用行为而无需重启。Airbnb 的内部 Sitar 系统提供了这样的能力，而 Sitar-agent 是将配置传递给数千个 Pod 的 sidecar。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.infoq.com/news/2026/07/sitar-agent-sidecar-config/">Airbnb Shares Architecture behind Sitar-Agent Dynamic Configuration Sidecar for Kubernetes Services - InfoQ</a></li>
<li><a href="https://medium.com/airbnb-engineering/sitar-agent-building-a-reliable-dynamic-configuration-sidecar-at-scale-b7e00c152068">Sitar - agent : Building a reliable dynamic configuration sidecar... | Medium</a></li>

</ul>
</details>

**标签**: `#Kubernetes`, `#sidecar`, `#dynamic configuration`, `#Airbnb`, `#architecture`

---

<a id="item-33"></a>
## [蚂蚁集团发布 LingBot-VA 2.0 世界动作模型](https://www.infoq.cn/article/aU7GMFKF8qZRhT8VMWvY?utm_source=rss&utm_medium=article) ⭐️ 7.0/10

蚂蚁集团宣布推出 LingBot-VA 2.0，这是一个面向具身智能的预训练原生世界动作模型，现已在 GitHub 上开源。 该模型代表了具身 AI 的重大进步，使机器人能够实现零样本泛化和跨本体迁移，有望加速智能机器人在真实场景中的部署。 LingBot-VA 2.0 支持独立执行和服务器-客户端架构，将模型环境与模拟环境隔离以避免包冲突，并支持在 GPU 和集群上进行分布式推理。

rss · InfoQ 中文站 · Jul 10, 15:14

**背景**: 世界动作模型（WAM）是具身 AI 的一种新范式，它联合预测未来世界状态和机器人动作，将预测性世界建模与动作生成统一起来。与仅关注动作的传统模型不同，WAM 旨在建模未来状态和动作的联合分布，从而实现更鲁棒、更可泛化的机器人控制。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/robbyant/lingbot-va">GitHub - Robbyant/lingbot-va: [RSS 2026] Causal video-action world model for generalist robot control · GitHub</a></li>
<li><a href="https://github.com/robbyant/lingbot-vla-v2">GitHub - Robbyant/lingbot-vla-v2: From Foundation to Application · GitHub</a></li>
<li><a href="https://www.nvidia.com/en-us/glossary/world-action-model/">What Is a World Action Model (WAM)? | NVIDIA Glossary</a></li>

</ul>
</details>

**标签**: `#embodied AI`, `#robotics`, `#Ant Group`, `#foundation model`, `#world model`

---

<a id="item-34"></a>
## [AI 击穿 GitHub 旧模式，Cursor、GitLab、Zed 崛起](https://www.infoq.cn/article/7ZSdewTwDBz1mrx6wmat?utm_source=rss&utm_medium=article) ⭐️ 7.0/10

InfoQ 的一篇文章分析了人工智能如何从根本上颠覆像 GitHub 这样的传统软件开发平台，而 Cursor、GitLab 和 Zed 等新兴竞争对手各自采取了不同的 AI 驱动策略。 这一转变可能会重塑开发者工具生态系统，迫使传统平台快速创新，否则市场份额将被提供更智能代码辅助和自动化的 AI 原生替代品夺走。 Cursor 是一个 AI 编程代理，是 VS Code 的分支，到 2026 年初估值达到 293 亿美元，并被 SpaceX 收购；Zed 是一个高性能的多人在线代码编辑器；GitLab 则将 AI 集成到其 DevOps 流水线中。

rss · InfoQ 中文站 · Jul 10, 13:14

**背景**: GitHub 是微软旗下的平台，长期以来在版本控制和协作领域占据主导地位。然而，大型语言模型（LLM）的兴起使得新工具能够直接生成、审查和修复代码，挑战了 GitHub 的 Copilot 和仓库模式。竞争对手正在将 AI 深度嵌入编辑器和工作流中，以提供更无缝的开发体验。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Cursor_(code_editor)">Cursor (code editor)</a></li>
<li><a href="https://zed.dev/?ref=taaft">Zed — Your last next editor</a></li>
<li><a href="https://github.com/zed-industries/zed">GitHub - zed -industries/ zed : Code at the speed of thought – Zed is...</a></li>

</ul>
</details>

**标签**: `#AI`, `#version control`, `#software engineering`, `#GitHub`, `#dev tools`

---

<a id="item-35"></a>
## [vLLM 多模态推理优化实践在 AICon 深圳](https://www.infoq.cn/article/ItOOYNuWf6t9KtfgeH7F?utm_source=rss&utm_medium=article) ⭐️ 7.0/10

在 AICon 深圳会议上，一场演讲展示了使用 vLLM 对多模态模型进行推理优化的实践技巧，涵盖张量并行和前缀缓存等策略，以提高吞吐量并降低延迟。 随着多模态模型日益普及，高效的模型服务对于生产部署至关重要。vLLM 的优化实践有助于降低运营成本，并加速涉及文本、图像和视频的应用响应时间。 该演讲可能讨论了在模型层内跨 GPU 使用张量并行，以及利用前缀缓存为共享输入前缀重复计算，这些都是 vLLM 的标准优化技术。该演示在技术 AI 会议 AICon 深圳上进行。

rss · InfoQ 中文站 · Jul 10, 10:00

**背景**: vLLM 是一个开源库，用于高吞吐量和低延迟的大语言模型服务，支持张量并行和 PagedAttention 等多种优化技术。多模态模型能够处理来自多种模态（如文本、图像、音频）的输入。高效服务这类模型由于输入大小和模态的变化而面临额外挑战。该演讲旨在分享使用 vLLM 大规模部署多模态模型的实用解决方案。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://docs.vllm.ai/en/stable/configuration/optimization/">Optimization and Tuning - vLLM</a></li>
<li><a href="https://arxiv.org/abs/2502.00937">[2502.00937] ModServe: Modality- and Stage-Aware Resource Disaggregation for Scalable Multimodal Model Serving</a></li>

</ul>
</details>

**标签**: `#vLLM`, `#multimodal models`, `#inference optimization`, `#LLM serving`, `#AI conference`

---

<a id="item-36"></a>
## [Snowflake Cortex Sense：为未建模数据注入可信上下文](https://www.infoq.cn/article/E4kV7CPQGeWujNoVTEAU?utm_source=rss&utm_medium=article) ⭐️ 7.0/10

Snowflake 发布了 Cortex Sense，一个共享上下文基础层，为未建模数据注入可信上下文，使 CoWork 和 CoCo 等 AI 代理能够以更丰富的语义运行。 此版本解决了使未建模数据可供 AI 代理使用的关键挑战，显著提高了企业环境中的数据可信度和代理效率。 Cortex Sense 作为 Snowflake 代理 CoWork（个人工作代理）和 CoCo（编码代理）之下的上下文层，两者均于 2026 年 6 月 2 日在 Snowflake 峰会上发布。

rss · InfoQ 中文站 · Jul 9, 14:50

**背景**: 未建模数据指的是不符合预定义模式或模型的数据，常见于物联网传感器流中。传统的数据管道在没有明确模式定义的情况下难以从中提取含义。Cortex Sense 增加了一个可信上下文层，通过将未建模数据锚定到已知上下文，使 AI 系统能够更可靠地解释它。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://atlan.com/know/snowflake/snowflake-cortex-sense/">Snowflake Cortex Sense and the Enterprise Context Layer</a></li>
<li><a href="https://en.wikipedia.org/wiki/Unstructured_data">Unstructured data - Wikipedia</a></li>

</ul>
</details>

**标签**: `#data context`, `#trusted context`, `#product release`, `#technology trends`

---

<a id="item-37"></a>
## [Mitchell Hashimoto 访谈：聚焦 Ghostty、Zig 与开源](https://alexalejandre.com/programming/interview-with-mitchell-hashimoto/) ⭐️ 7.0/10

一篇对 Mitchell Hashimoto（Terraform 和 Vagrant 的创始人）的新采访中，他谈到了从 HashiCorp 创始人转型，用 Zig 构建 GPU 加速终端模拟器 Ghostty，以及 OAuth 代理 Vouch 的经历。 这篇采访提供了 DevOps 领域最具影响力人物之一的独到见解，说明了他为何选择构建现代终端模拟器以及对终端生态的愿景，这可能影响未来开发工具的走向。 Ghostty 是一个快速、功能丰富、跨平台的终端模拟器，使用平台原生 UI 和 GPU 加速，用 Zig 编写。Vouch 是一个 SSO 和 OAuth/OIDC 登录解决方案。Mitchell 强调终端应专注于基于文本的应用，而不是成为完整的应用平台。

rss · Lobsters · Jul 9, 15:41

**背景**: Mitchell Hashimoto 联合创办了 HashiCorp，并创建了 Terraform、Vagrant、Consul、Vault 等广泛使用的 DevOps 工具。Ghostty 是他的最新项目，使用 Zig 构建的终端模拟器，用于探索 GPU 编程和系统编程。Zig 是一种现代系统编程语言，旨在作为 C 语言的替代品，注重健壮性和性能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://ghostty.org/">Ghostty</a></li>
<li><a href="https://github.com/ghostty-org/ghostty">GitHub - ghostty-org/ghostty: 👻 Ghostty is a fast, feature-rich, and cross-platform terminal emulator that uses platform-native UI and GPU acceleration.</a></li>
<li><a href="https://en.wikipedia.org/wiki/Zig_(programming_language)">Zig (programming language)</a></li>

</ul>
</details>

**标签**: `#interview`, `#open source`, `#infrastructure`, `#zig`, `#terminals`

---

<a id="item-38"></a>
## [每位 Python 开发者都应了解的 CPython ABI 知识](https://labs.quansight.org/blog/python-abi-abi3t) ⭐️ 7.0/10

这篇文章介绍了 CPython 应用程序二进制接口（ABI）及其对 Python 开发者（尤其是编写 C 扩展的开发者）的影响，涵盖了稳定 ABI 和版本控制注意事项。 理解 CPython ABI 对于构建 C 扩展的开发者至关重要，以确保跨 Python 版本的二进制兼容性。掌握这些知识有助于避免运行时错误并减少维护负担。 CPython ABI 定义了编译后的 C 扩展如何与 Python 解释器交互，包括数据结构和调用约定。稳定 ABI（abi3）允许扩展无需重新编译即可兼容多个 Python 版本。

rss · Lobsters · Jul 10, 17:17

**背景**: 应用程序二进制接口（ABI）是编译代码模块之间的低级接口，指定了数据布局和函数调用约定等细节。在 CPython 中，ABI 比 API 更不稳定，即为一个次版本编译的 C 扩展可能无法在另一个版本上运行而不重新编译。Python 自 3.2 版起提供了“稳定 ABI”（受限 API），保证跨版本的兼容性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Application_binary_interface">Application binary interface - Wikipedia</a></li>
<li><a href="https://docs.python.org/3/c-api/apiabiversion.html">API and ABI Versioning — Python 3.14.6 documentation</a></li>

</ul>
</details>

**标签**: `#CPython`, `#Python ABI`, `#C extensions`, `#software engineering`

---

<a id="item-39"></a>
## [在浏览器代码运行器中加入 Go 支持](https://blog.lvmbdv.dev/posts/adding-go-to-a-browser-code-runner/) ⭐️ 7.0/10

一篇博客文章详细介绍了将 Go 语言支持添加到基于浏览器的代码运行器的过程，包括将 Go 编译为 WebAssembly 以及集成运行时。 这使得 Go 代码可以直接在浏览器中运行，扩展了在线代码编辑器和学习平台的多样性。它展示了实际的 WebAssembly 集成挑战和解决方案。 该集成涉及将 Go 程序编译为 WebAssembly 字节码并加载到浏览器环境中。文章可能解决了内存管理、函数导出以及 JavaScript 与 Go 之间的通信问题。

rss · Lobsters · Jul 10, 20:52

**背景**: WebAssembly (Wasm) 是一种二进制指令格式，可在 Web 浏览器和其他环境中实现高性能应用程序。它允许像 Go 这样的语言被编译为可移植的格式，以接近本机的速度运行。浏览器代码运行器是交互式工具，允许用户在浏览器内编写和执行代码片段，通常使用 WebAssembly 来支持多种编程语言。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/WebAssembly">WebAssembly</a></li>
<li><a href="https://htmlcoderunner.run/">Free Online HTML Editor & Code Runner - No Account Required</a></li>

</ul>
</details>

**标签**: `#Go`, `#WebAssembly`, `#browser`, `#code runner`, `#wasm`

---

<a id="item-40"></a>
## [一秒内运行 1000 个测试：性能优化技巧](https://marvinh.dev/blog/running-1000-test-in-1s/) ⭐️ 7.0/10

2022 年 Marvin Hagemeister 的一篇博客文章展示了在一秒内运行 1000 个测试的技术，重点在于减少开销和优化测试执行。 缓慢的测试套件是开发者的常见痛点；这篇文章提供了可实施的策略来大幅加快测试速度，提高开发效率和 CI 流水线效率。 这些技术包括使用最小化的测试运行器、避免不必要的 I/O、并行运行测试以及利用更快的断言库。该文章基于优化 JavaScript 测试套件的实际经验。

rss · Lobsters · Jul 10, 18:00

**背景**: 运行数千个测试可能需要几分钟或几小时，从而拖慢开发反馈循环。这篇文章通过分享低层次的优化技巧来解决这一挑战，这些技巧能显著减少每个测试的开销。

**标签**: `#testing`, `#performance`, `#optimization`, `#developer-tools`

---