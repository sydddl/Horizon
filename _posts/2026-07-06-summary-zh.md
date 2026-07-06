---
layout: default
title: "Horizon Summary: 2026-07-06 (ZH)"
date: 2026-07-06
lang: zh
---

> From 79 items, 19 important content pieces were selected

---

1. [Karpathy 发布 nanochat，只需 100 美元的 ChatGPT 克隆版](#item-1) ⭐️ 8.0/10
2. [数字游戏所有权争论焦点是控制权而非格式](#item-2) ⭐️ 8.0/10
3. [免费在线编译器构建书籍](#item-3) ⭐️ 8.0/10
4. [七个稳定内核修复关键 IPv6 容器逃逸漏洞](#item-4) ⭐️ 8.0/10
5. [Azure Functions 在 Build 2026 发布 Serverless 智能体运行时](#item-5) ⭐️ 8.0/10
6. [新 Claude 模型因强化学习过拟合导致工具调用退化](#item-6) ⭐️ 8.0/10
7. [使用 Prolly 树实现数据库版本控制](#item-7) ⭐️ 8.0/10
8. [PEP 814：为 Python 添加内置 frozendict 类型](#item-8) ⭐️ 8.0/10
9. [Rust 1.96.1 补丁修复 Cargo 安全问题和 rustc 误编译](#item-9) ⭐️ 7.0/10
10. [Organic Maps 争议催生 CoMaps 分叉](#item-10) ⭐️ 7.0/10
11. [电脑明星：电影中的计算机目录](#item-11) ⭐️ 7.0/10
12. [sqlite-utils 4.0rc2：借助 Claude Fable 的 AI 辅助开发](#item-12) ⭐️ 7.0/10
13. [光象科技获数亿元融资，自研物理原生基座模型](#item-13) ⭐️ 7.0/10
14. [苹果首次将私有云计算平台扩展至谷歌云](#item-14) ⭐️ 7.0/10
15. [Rayfish：基于 Iroh 的 P2P VPN](#item-15) ⭐️ 7.0/10
16. [使用 Zig 编写 10 万行游戏代码后的三年回顾](#item-16) ⭐️ 7.0/10
17. [Blender 模拟测试波浪墙的用砖效率](#item-17) ⭐️ 7.0/10
18. [Immich v3.0.0 发布](#item-18) ⭐️ 7.0/10
19. [Bench Press：利用 CSS 泄露文本节点的技术](#item-19) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Karpathy 发布 nanochat，只需 100 美元的 ChatGPT 克隆版](https://github.com/karpathy/nanochat) ⭐️ 8.0/10

Andrej Karpathy 开源了 nanochat，这是一个极简且低成本的 ChatGPT 风格对话 AI 实现，训练成本约 100 美元。该项目涵盖了从分词器训练到 Web 界面的完整流程。 该项目通过大幅降低成本和复杂性，使个人和小团队能够开发大型语言模型，可能加速对话 AI 领域的创新。它证明在预算有限的情况下也能构建出有能力的模型，挑战了只有大公司才能负担此类工程的传统观念。 nanochat 设计为轻依赖，包含完整流程：数据准备、分词器训练、语言模型训练（重点在于快速达到 GPT-2 级别的性能），以及用于交互的 Web 界面。主要性能指标是在 8XH100 GPU 节点上的“达到 GPT-2 的时间”。

github · karpathy · Jul 4, 03:44

**背景**: 像 ChatGPT 这样的大型语言模型训练通常非常昂贵，成本高达数百万美元。Karpathy 的 nanochat 旨在以极低的成本复制核心功能，采用高效的训练技术和紧凑的架构。该项目是开源的，任何人都可以查看、修改和部署自己的聊天机器人。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/karpathy/nanochat">GitHub - karpathy / nanochat : The best ChatGPT that $100 can buy.</a></li>
<li><a href="https://www.linkedin.com/posts/marktechpost_andrej-karpathy-releases-nanochat-a-minimal-activity-7384110979908784128-cVDO">Andrej Karpathy releases nanochat , a ChatGPT-style... | LinkedIn</a></li>
<li><a href="https://medium.com/@mieitza/build-a-full-stack-llm-in-an-afternoon-with-karpathys-nanochat-step-by-step-with-code-041b434ec066">Build a Full-Stack LLM in an Afternoon with Karpathy ’s nanochat ...</a></li>

</ul>
</details>

**标签**: `#AI`, `#ChatGPT`, `#machine learning`, `#open source`

---

<a id="item-2"></a>
## [数字游戏所有权争论焦点是控制权而非格式](https://popcar.bearblog.dev/its-about-ownership/) ⭐️ 8.0/10

一篇热门博客文章认为，数字游戏的核心问题是所有权的丧失，而非数字与实体格式之争，在 Hacker News 上引发了广泛讨论。 这场辩论凸显了消费者对数字所有权日益增长的担忧，可能影响游戏行业乃至更广泛领域的未来监管和商业模式。 文章区分了便利性与所有权，指出 Steam 等平台允许离线游玩且无 DRM，但 Game Pass 等订阅服务加剧了控制权的丧失。

hackernews · popcar2 · Jul 5, 14:56 · [社区讨论](https://news.ycombinator.com/item?id=48794750)

**背景**: 过去十年中，游戏行业从实体光盘转向数字下载和订阅服务。这一变化引发了关于消费者是否真正拥有所购游戏的疑问，因为数字许可可能被撤销或与持续订阅绑定。

**社区讨论**: 评论者普遍认为所有权是核心问题，一些人支持监管以确保数字购买的可转让性和永久性。另一些人则指责消费者接受了订阅模式，并将 Game Pass 视为负面影响。

**标签**: `#digital rights`, `#game ownership`, `#subscription models`, `#consumer protection`, `#DRM`

---

<a id="item-3"></a>
## [免费在线编译器构建书籍](https://dthain.github.io/books/compiler/) ⭐️ 8.0/10

一本名为《Introduction to Compilers and Language Design (2021)》的高质量免费在线书籍现已发布，提供了关于编译器构建和语言设计的实用入门介绍。 这本书受到学生和从业者的好评，使编译器教育更易于广泛受众获取，无需传统教科书的高昂成本。 该书结构清晰且实用，基于一门大学课程，学生逐步构建一个可工作的 C 风格编译器；内容涵盖理论和实践实现。

hackernews · AlexeyBrin · Jul 5, 11:54 · [社区讨论](https://news.ycombinator.com/item?id=48793454)

**背景**: 编译器是将高级编程语言编写的源代码转换为机器代码或其他低级语言的程序。语言设计涉及为新编程语言创建语法和语义。本书面向希望通过动手实践理解这两个主题的初学者。

**社区讨论**: 一位前学生强烈推荐这本书及其相关的课程项目，称其为极好的学习体验。另一位评论者建议，像 C4 这样的小型自编译 C 子集编译器可以作为进一步学习的有益补充。

**标签**: `#compilers`, `#programming languages`, `#education`, `#computer science`

---

<a id="item-4"></a>
## [七个稳定内核修复关键 IPv6 容器逃逸漏洞](https://lwn.net/Articles/1081230/) ⭐️ 8.0/10

Greg Kroah-Hartman 于周六发布了七个稳定版 Linux 内核（7.1.3、6.18.38、6.12.95、6.6.144、6.1.177、5.15.211、5.10.260），其中包含针对关键 IPv6 漏洞（CVE-2026-53362）和 KVM 中释放后使用漏洞（CVE-2026-53359）的安全修复。 此次发布意义重大，因为 IPv6 漏洞（CVE-2026-53362）允许攻击者逃逸容器并在宿主机上获得 root 权限，对云和容器化环境构成严重风险。系统管理员和安全团队应尽快升级以保护系统。 IPv6 漏洞从内核版本 6.0 开始引入，影响 6.0 及更高版本；KVM 的释放后使用漏洞可追溯到内核 2.6.36。这七个稳定内核覆盖了从 5.10 到 7.1 的广泛版本，确保用户得到广泛覆盖。

rss · LWN.net · Jul 4, 16:46

**背景**: 容器逃逸漏洞允许攻击者突破容器的隔离边界，访问宿主机操作系统或其他容器。IPv6 漏洞（CVE-2026-53362）专门利用 IPv6 处理中的缺陷实现逃逸，可能导致宿主机完全沦陷。稳定内核是长期支持版本，接收关键安全修复，对生产环境至关重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.wiz.io/academy/container-security/container-escape">What is Container Escape: Detection & Prevention | Wiz</a></li>

</ul>
</details>

**标签**: `#linux-kernel`, `#security`, `#CVE-2026-53362`, `#container-escape`, `#stable-release`

---

<a id="item-5"></a>
## [Azure Functions 在 Build 2026 发布 Serverless 智能体运行时](https://www.infoq.cn/article/kGHZu2K5V8IrwYvo6Cm3?utm_source=rss&utm_medium=article) ⭐️ 8.0/10

Azure Functions 在 Build 2026 上发布了 Serverless 智能体运行时（公开预览版）。开发者可通过.agent.md 文件定义智能体，支持 YAML 触发器、MCP 服务器访问以及超过 1400 个连接器。 这标志着 AI 智能体与 Serverless 计算整合的重要一步，让开发者无需管理基础设施即可构建事件驱动的智能体。它将降低在 Azure 上构建和部署智能体应用的门槛。 智能体通过.agent.md Markdown 文件定义，包含 YAML 触发器，运行时自动处理智能体发现、触发器注册、工具组装和会话历史。Flex Consumption 计划支持缩到零、按秒计费、托管标识和虚拟网络集成。

rss · InfoQ 中文站 · Jul 6, 09:19

**背景**: Serverless 计算允许开发者无需配置或管理服务器即可运行代码，自动伸缩并按执行次数付费。Azure Functions 是流行的 Serverless 平台。智能体是能够感知环境、推理并采取行动的自主程序，通常使用 AI 模型。新运行时将两者结合，让智能体以 Serverless 方式运行。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://techcommunity.microsoft.com/blog/appsonazureblog/introducing-the-azure-functions-serverless-agents-runtime-preview/4523804">Introducing the Azure Functions serverless agents runtime (preview) | Microsoft Community Hub</a></li>
<li><a href="https://learn.microsoft.com/en-us//azure/Azure-functions/functions-serverless-agents-runtime">Serverless agents runtime in Azure Functions | Microsoft Learn</a></li>
<li><a href="https://www.infoq.com/news/2026/06/azure-functions-serverless-agent/">Azure Functions Ships Serverless Agents Runtime at Build 2026 - InfoQ</a></li>

</ul>
</details>

**标签**: `#Azure`, `#serverless`, `#AI agents`, `#runtime`, `#cloud computing`

---

<a id="item-6"></a>
## [新 Claude 模型因强化学习过拟合导致工具调用退化](https://lucumr.pocoo.org/2026/7/4/better-models-worse-tools/) ⭐️ 8.0/10

Armin Ronacher 的博客文章指出，较新的 Anthropic 模型（Opus 4.8、Sonnet 5）在工具调用时比旧模型表现更差，经常在参数中发明额外的键，原因是强化学习导致其过度拟合到 Claude Code 的闭源 harness 上。 这种退化对依赖于工具调用的第三方编码 harness 开发者至关重要，因为它破坏了与新模型的兼容性，迫使工具制造商要么采用 Claude Code 的精确模式，要么处理格式错误的调用。 问题影响编辑工具：像 Opus 4.8 这样的模型在嵌套的 `edits[]` 数组中添加虚构字段，导致 Pi 拒绝调用。编辑内容本身通常是正确的，但模式不匹配迫使重试。

rss · Lobsters · Jul 4, 21:51

**背景**: 工具调用是 LLM 智能体的核心能力，允许模型通过函数调用与外部工具交互。最近，Anthropic 使用强化学习在 Claude Code 自己的编辑工具模式上训练了较新模型。这种 RL 微调可能导致过拟合，即模型期望完全相同的工具模式，当遇到略有不同但兼容的模式时表现不佳。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://code.claude.com/docs/en/how-claude-code-works">How Claude Code works - Claude Code Docs</a></li>
<li><a href="https://arxiv.org/abs/2410.19920">[2410.19920] Reinforcement Learning for Aligning Large Language Models ...</a></li>

</ul>
</details>

**标签**: `#AI models`, `#tool calling`, `#regression`, `#Anthropic`, `#Claude Code`

---

<a id="item-7"></a>
## [使用 Prolly 树实现数据库版本控制](https://lwn.net/Articles/1068864/) ⭐️ 8.0/10

LWN.net 上的一篇详尽文章探讨了如何使用 Prolly 树（概率性 B 树）来实现数据库的版本控制，支持类似 Git 的高效分支和合并操作。 这种方法为数据库带来了强大的版本控制能力，可能改变开发者管理 schema 和数据变更的方式，并支持数据密集型应用中的协作工作流。 Prolly 树结合了 B 树和 Merkle 树的特性，提供确定性节点边界和高效的差异比较，适合版本化存储。像 Dolt 这样的实现已经使用 Prolly 树构建版本控制的 SQL 数据库。

rss · Lobsters · Jul 5, 19:28

**背景**: 数据库的版本控制具有挑战性，因为传统系统缺乏高效跟踪和合并变更的方法。Prolly 树（概率性 B 树）是一种数据结构，可以高效地存储、检索和验证有序数据，支持分支、合并和时间旅行查询等功能。它通过基于哈希的结构来验证完整性并快速计算差异。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.dolthub.com/blog/2024-03-03-prolly-trees/">Prolly Trees | DoltHub Blog</a></li>
<li><a href="https://github.com/cfkaran2/prolly">GitHub - cfkaran2/prolly: An implementation of the prolly tree data structure</a></li>
<li><a href="https://github.com/zhangfengcdt/prollytree">GitHub - zhangfengcdt/prollytree: A prolly tree (probabilistic tree) is a data structure designed to provide efficient storage, retrieval, and modification of ordered data with integrity guarantees.</a></li>

</ul>
</details>

**标签**: `#databases`, `#version control`, `#data structures`, `#Prolly trees`

---

<a id="item-8"></a>
## [PEP 814：为 Python 添加内置 frozendict 类型](https://vstinner.github.io/pep-814-add-frozendict-builtin-type.html) ⭐️ 8.0/10

PEP 814 提议为 Python 添加一个内置的 frozendict 类型，在标准库中提供不可变字典。 如果被接受，Python 开发者将拥有原生的不可变映射类型，从而编写更安全的代码，并可能为可哈希字典带来性能优化。 该 PEP 最初旨在支持 Python 沙箱，但该动机已被放弃；目前，types.MappingProxyType 提供了只读视图，但并非完整的不可变字典。

rss · Lobsters · Jul 5, 06:52

**背景**: Python 目前缺少内置的不可变字典类型。frozendict 概念已讨论多年，第三方库如 frozendict PyPI 包提供了实现。内置版本将确保生态系统的一致性和性能优势。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://peps.python.org/pep-0814/">PEP 814 – Add frozendict built-in type | peps. python .org</a></li>
<li><a href="https://pypi.org/project/frozendict/">frozendict · PyPI</a></li>

</ul>
</details>

**标签**: `#Python`, `#PEP`, `#language design`, `#immutable`, `#dict`

---

<a id="item-9"></a>
## [Rust 1.96.1 补丁修复 Cargo 安全问题和 rustc 误编译](https://github.com/rust-lang/rust/releases/tag/1.96.1) ⭐️ 7.0/10

Rust 1.96.1 是一个补丁版本，修复了 Cargo 所捆绑的 libssh2 库中的三个 CVE 漏洞，以及 rustc 在 MIR 优化阶段的一个误编译问题。 此版本对 Rust 开发者至关重要，因为它修复了可能影响使用 Cargo 通过 SSH 获取依赖的项目的安全漏洞，以及一个可能导致优化构建产生错误代码的误编译问题。 libssh2 中修复的三个 CVE 分别为 CVE-2025-15661、CVE-2026-55199 和 CVE-2026-55200。误编译修复针对的是 MIR 优化阶段中可能导致错误结果的问题。

github · rustbot · Jul 5, 23:50

**背景**: Cargo 是 Rust 的包管理器，它可以利用 SSH 访问私有仓库。libssh2 是 Cargo 用于 SSH 连接的库。MIR（中级中间表示）是 Rust 用于优化的内部表示；MIR 优化中的误编译可能导致生成错误的机器码。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://libssh2.org/">libssh2</a></li>
<li><a href="https://github.com/libssh2/libssh2">GitHub - libssh2/libssh2: the SSH library · GitHub</a></li>
<li><a href="https://rustc-dev-guide.rust-lang.org/mir/optimizations.html">MIR optimizations - Rust Compiler Development Guide</a></li>

</ul>
</details>

**标签**: `#Rust`, `#security`, `#compiler`, `#software-update`

---

<a id="item-10"></a>
## [Organic Maps 争议催生 CoMaps 分叉](https://organicmaps.app/) ⭐️ 7.0/10

免费开源导航应用 Organic Maps 因治理和开源许可证合规问题遭到社区反对，导致衍生出名为 CoMaps 的分支。 这一争议凸显了透明治理和真正开源合规在 FOSS 社区中的重要性，可能影响用户信任以及注重隐私的地图应用的采用。 社区成员指责 Organic Maps 包含非开源组件、添加广告以及滥用捐款，而分支 CoMaps 正在添加如 CarPlay 仪表盘支持等新功能。

hackernews · tosh · Jul 5, 14:14 · [社区讨论](https://news.ycombinator.com/item?id=48794446)

**背景**: 开源项目依赖清晰的治理模式和许可证合规来确保社区信任与合作。治理模型定义了角色、决策过程和参与规则，而许可证合规确保所有组件遵守开源许可证。当这些原则被认为受到侵犯时，经常会出现分叉（衍生项目）。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://guidebook.theopensourceway.org/growing-contributors/project-and-community-governance">Project and Community Governance | The Open Source Way</a></li>
<li><a href="https://opensource.org/blog/what-is-open-governance-drafting-a-charter-for-an-open-source-project">What Is Open Governance? Drafting a charter for an Open Source project</a></li>
<li><a href="https://www.mend.io/open-source-license-compliance/">Automate Open Source License Compliance</a></li>

</ul>
</details>

**社区讨论**: 社区意见分歧：一些用户强烈批评 Organic Maps 所谓的恶意行为，并推荐使用 CoMaps；另一些用户则认可该应用的实用性及其正在进行的开发工作。此外，还有关于 F-Droid 上指出的 Organic Maps 中非开源组件的讨论。

**标签**: `#open-source`, `#maps`, `#navigation`, `#privacy`, `#controversy`

---

<a id="item-11"></a>
## [电脑明星：电影中的计算机目录](https://www.starringthecomputer.com/computers.html) ⭐️ 7.0/10

一个名为“电脑明星”的网站整理了在电影和电视节目中出现的计算机，收录了 400 多个条目，并由用户贡献内容。 这一资源连接了科技与流行文化，让爱好者能够识别媒体中的复古硬件，并了解计算机在历史上的呈现方式。 该网站由社区驱动，用户添加目击信息并讨论细节，例如许多电影中使用的 IBM AN/FSQ-7 面板。它还包含关于道具真实性的幕后说明。

hackernews · gitowiec · Jul 5, 17:33 · [社区讨论](https://news.ycombinator.com/item?id=48796093)

**背景**: 电影和电视节目经常使用计算机作为道具，往往使用过时或重新利用的硬件。该网站是一个全面的数据库，帮助爱好者识别特定机型并观察道具使用的模式。

**社区讨论**: 社区评论强调了具体的硬件出现，如 IBM AN/FSQ-7 面板，并讨论了屏幕上显示代码的真实性。一些用户将其与汽车数据库 IMCDB 相比较，其他人则分享了像《皇后区之王》中使用假道具的有趣事实。

**标签**: `#computers`, `#movies`, `#retro hardware`, `#pop culture`, `#history`

---

<a id="item-12"></a>
## [sqlite-utils 4.0rc2：借助 Claude Fable 的 AI 辅助开发](https://simonwillison.net/2026/Jul/5/sqlite-utils-fable/#atom-everything) ⭐️ 7.0/10

Simon Willison 发布了 sqlite-utils 4.0rc2 候选版本，该版本主要借助 Anthropic 的 Claude Fable AI 助手开发，AI 发现了包括 delete_where()中数据丢失 bug 在内的关键问题。 此版本展示了 AI 辅助开发对成熟开源工具的实用价值，表明 AI 能在稳定版发布前捕获严重 bug，从而避免潜在的数据丢失并节省大量调试时间。 通过 37 个提示和 34 次提交，AI 帮助修复了 5 个阻碍发布的 bug，并在 30 个文件中进行了代码变更（+1,321 -190 行）。最严重的 bug 是 delete_where()未能提交并污染连接，导致数据丢失。

rss · Simon Willison · Jul 5, 01:00

**背景**: sqlite-utils 是一个用于操作 SQLite 数据库的 Python 库和命令行工具。项目遵循语义化版本控制（SemVer），以避免主要版本中的破坏性变更。Claude Fable 是 Anthropic 最强大的 AI 模型，专门用于大型编码项目，支持多天自主会话。作者最初在 iPhone 上使用 Claude Code 进行审查，后来切换到笔记本电脑。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/simonw/sqlite-utils">GitHub - simonw/sqlite-utils: Python CLI utility and library for manipulating SQLite databases · GitHub</a></li>
<li><a href="https://simonwillison.net/2026/Jun/21/sqlite-utils-40rc1/">sqlite-utils 4.0rc1 adds migrations and nested transactions</a></li>
<li><a href="https://www.anthropic.com/claude/fable">Claude Fable \ Anthropic</a></li>

</ul>
</details>

**标签**: `#sqlite`, `#AI-assisted development`, `#open source`, `#semver`, `#software maintenance`

---

<a id="item-13"></a>
## [光象科技获数亿元融资，自研物理原生基座模型](https://www.infoq.cn/article/m4QJlWAyRq7Fp4yQImp9?utm_source=rss&utm_medium=article) ⭐️ 7.0/10

光象科技获得数亿元融资，用于其自主研发的物理原生基座模型，该模型跳出了当前主流的 VLA（视觉-语言-动作）模型和世界模型技术路线。 这笔融资及其独特的技术路线可能挑战主流的 VLA 和世界模型范式，为 AI 理解和交互物理世界提供更高效的方案，对机器人、自动驾驶等领域产生重要影响。 物理原生基座模型旨在让模型自然地涌现出对物理的理解，而非显式编写物理规律；该模型面向移动物理 AI 应用。公司声称其方法在根本上不同于 VLA 和世界模型路线。

rss · InfoQ 中文站 · Jul 6, 10:06

**背景**: 主流机器人 AI 常采用视觉-语言-动作（VLA）模型，融合视觉、语言和动作模态，或使用世界模型模拟环境进行规划。物理 AI 旨在构建能与真实世界交互的模型，但当前多数方法依赖大规模数据和显式物理建模。物理原生基座模型试图从数据中以更基础的方式学习物理，可能减少对海量数据的依赖并提升泛化能力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://k.sina.com.cn/article_7205918816_1ad819860001014lc4.html">智驾龙头鏖战 物 理 AI， 基 座 模 型 成了“银子弹” | 新浪网</a></li>
<li><a href="https://www.tmtpost.com/7998296.html">22岁的北大青年学者，想做真正 理 解 物 理 的通用世界 基 座 模 型 ｜AI...</a></li>
<li><a href="https://zhuanlan.zhihu.com/p/1934608134745338050">【世界模型】一文读懂世界模型：从核心原理到前沿争议 - 知乎</a></li>

</ul>
</details>

**标签**: `#AI`, `#robotics`, `#funding`, `#foundation model`, `#startup`

---

<a id="item-14"></a>
## [苹果首次将私有云计算平台扩展至谷歌云](https://www.infoq.cn/article/UoJtxVXj0d1QT1ftyjtd?utm_source=rss&utm_medium=article) ⭐️ 7.0/10

苹果首次将其私有云计算（Private Cloud Compute，PCC）平台扩展到谷歌云基础设施上运行，该平台用于在保障隐私的前提下处理 Apple Intelligence 请求。 此举标志着苹果对其最注重隐私的人工智能工作负载采用了多云战略，可能为其他公司树立先例。同时也引发了关于苹果在依赖第三方云提供商时如何维持其隐私承诺的讨论。 私有云计算平台之前使用苹果自家数据中心的 Apple Silicon 服务器处理 AI 请求，不存储数据且苹果员工无法访问。扩展到谷歌云可能涉及在谷歌数据中心内部署类似硬件或安全区域。

rss · InfoQ 中文站 · Jul 4, 09:00

**背景**: 苹果推出私有云计算平台作为 Apple Intelligence 的一部分，以在保证端到端隐私的同时处理复杂的 AI 请求。此前，苹果仅使用自有云基础设施。此次扩展到谷歌云表明苹果需要额外容量、地理冗余或更快的部署能力来支持其 AI 服务。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.theverge.com/2018/2/26/17053496/apple-google-cloud-platform-icloud-confirmation">Apple confirms it now uses Google Cloud for iCloud... | The Verge</a></li>
<li><a href="https://www.linkedin.com/posts/marcmanzano_apples-introduction-of-private-cloud-compute-activity-7211352555103129600-mums">Apple ’s introduction of Private Cloud Compute (PCC) is a brave...</a></li>
<li><a href="https://beebom.com/apple-private-cloud-compute-processed-ai-data-safe-privacy/">Apple Private Cloud Compute : What It Means for Your... | Beebom</a></li>

</ul>
</details>

**标签**: `#cloud computing`, `#Apple`, `#Google Cloud`, `#private cloud`

---

<a id="item-15"></a>
## [Rayfish：基于 Iroh 的 P2P VPN](https://rayfish.xyz/blog/01-introducing-rayfish) ⭐️ 7.0/10

Rayfish 是一个基于 Iroh 网络库构建的点对点 VPN 项目。它利用 Iroh 的 QUIC 连接和 NAT 穿透技术，在节点之间建立直接加密隧道。 该方案为传统 VPN 提供了一种去中心化的替代方案，通过消除中央服务器可能提升隐私性和抗干扰能力。对 Rust 生态而言，它展示了 Iroh 在简单文件共享之外驱动实际应用的能力。 Rayfish 使用 Iroh 的拨号键（dial keys）而非 IP 地址来标识节点，并通过 QUIC 协议及自动 NAT 穿透进行连接。该项目仍处于早期阶段，初始博客文章仅概述了其概念和架构。

rss · Lobsters · Jul 5, 18:39

**背景**: Iroh 是一个用 Rust 编写的模块化、生产级网络库，为点对点应用提供基础组件。它使用 QUIC 作为传输协议，并包含 NAT 穿透机制，即使在防火墙后也能建立直接连接。传统 VPN 依赖中心化服务器转发流量，而 P2P VPN 让节点直接连接，从而降低延迟并消除单点故障。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.iroh.computer/">Iroh</a></li>
<li><a href="https://github.com/n0-computer/iroh">GitHub - n0-computer/iroh: IP addresses break, dial keys instead. A ...</a></li>
<li><a href="https://docs.iroh.computer/what-is-iroh">What is iroh? - iroh</a></li>

</ul>
</details>

**标签**: `#VPN`, `#P2P`, `#Rust`, `#Iroh`, `#networking`

---

<a id="item-16"></a>
## [使用 Zig 编写 10 万行游戏代码后的三年回顾](https://www.youtube.com/watch?v=HXpUShkr2VQ) ⭐️ 7.0/10

一位开发者分享了使用 Zig 编程语言进行游戏开发的经验报告，在三年内累计了 10 万行代码。 这份回顾为 Zig 在实际大规模项目中的优缺点提供了实用见解，让游戏开发和系统编程社区了解其可行性。 该报告基于三年使用 Zig 进行游戏开发的实践经验，涵盖了规模化开发中遇到的正面体验和痛点。

rss · Lobsters · Jul 5, 09:49

**背景**: Zig 是由 Andrew Kelley 于 2016 年创建的通用系统编程语言，旨在改进 C 语言，具有编译时泛型、无隐藏控制流和手动内存管理等特性。它因其对鲁棒性和性能的关注而受到关注，使得它在需要控制力和效率的游戏开发中具有吸引力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Zig_(programming_language)">Zig (programming language)</a></li>

</ul>
</details>

**标签**: `#Zig`, `#game development`, `#programming languages`, `#experience report`

---

<a id="item-17"></a>
## [Blender 模拟测试波浪墙的用砖效率](https://blog.tymscar.com/posts/crinklecranklewalls/) ⭐️ 7.0/10

一位作者使用 Blender 模拟来测试波浪状（crinkle crankle）墙是否比直墙使用更少的砖块，通过 3D 建模探索了一个长期存在的工程说法。 这一分析为传统砌体技术提供了现代计算验证，提供了对材料效率的见解，可能影响建筑设计和修复。 该模拟可能比较了具有相同结构强度的墙体的用砖数量，考虑了直墙需要扶壁的额外材料。波浪设计因其蛇形曲线提供侧向稳定性，可用单砖厚度建造。

rss · Lobsters · Jul 4, 15:20

**背景**: Crinkle crankle 墙，也称为蛇形墙或波浪墙，是以正弦曲线形状建造的花园墙。其曲线提供侧向力稳定性，使得它们可以比同样强度的直墙更薄，而直墙需要扶壁。这种结构效率通常导致总用砖量减少，尽管路径更长。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Crinkle_crankle_wall">Crinkle crankle wall - Wikipedia</a></li>
<li><a href="https://usefulbs.com/blog/why-do-some-historic-brick-garden-walls-follow-a-wavy-serpentine-shape-instead-of-a-straight-line">Why do some historic brick garden walls follow a wavy serpentine shape ...</a></li>

</ul>
</details>

**标签**: `#simulation`, `#engineering`, `#blender`, `#masonry`, `#physics`

---

<a id="item-18"></a>
## [Immich v3.0.0 发布](https://immich.app/blog/v3.0.0-release) ⭐️ 7.0/10

开源自托管照片管理应用 Immich 发布了 3.0.0 版本，引入了重要的新功能和改进。 此次主要版本发布标志着该流行隐私优先替代方案（如 Google Photos）的一个里程碑，有益于自托管社区和寻求数据控制的用户。 v3.0.0 的具体变更详见官方发布说明，但主要版本号暗示可能包含破坏性变更或重大升级。

rss · Lobsters · Jul 4, 18:25

**背景**: Immich 是一款开源、自托管的照片和视频管理器，让用户完全掌控个人媒体，作为 Google Photos 等云服务的私有替代方案。因其功能齐备和积极开发，它在注重隐私的用户和自托管社区中广受欢迎。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://medium.com/@Emily_OnChain/immich-an-open-source-devrel-case-study-57747bb5e5d2">Immich — An Open Source DevRel Case Study | by Emily... | Medium</a></li>

</ul>
</details>

**标签**: `#self-hosted`, `#photo management`, `#open-source`, `#software release`

---

<a id="item-19"></a>
## [Bench Press：利用 CSS 泄露文本节点的技术](https://blog.pspaul.de/posts/bench-press-leaking-text-nodes-with-css/) ⭐️ 7.0/10

一种名为 Bench Press 的新技术被展示，通过操控 CSS 属性并观察渲染行为，能够从网页中泄露文本节点。 该技术揭示了绕过传统安全措施的数据窃取新途径，对网络用户隐私和数据机密性构成威胁。 该方法利用 CSS 与布局之间的相互作用来推断文本节点中的字符，可能使攻击者无需直接脚本访问即可提取敏感信息。

rss · Lobsters · Jul 5, 18:40

**背景**: 通过 CSS 进行数据窃取是一种高级技术，利用 CSS 选择器和渲染行为从网页向外发送数据。传统的窃取方法通常依赖带有外部 URL 的属性选择器，而 Bench Press 将此扩展到文本节点，这是以前较难泄露的。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://modernorange.io/item/48798317">Bench Press : Leaking Text Nodes with CSS (2024) | Modern Orange</a></li>
<li><a href="https://vue-hackernews-ssr-5cavbdjcta-ew.a.run.app/item/48798317">Vue HN 2.0 | Bench Press : Leaking Text Nodes with CSS (2024)</a></li>

</ul>
</details>

**标签**: `#css`, `#security`, `#web`, `#exfiltration`

---