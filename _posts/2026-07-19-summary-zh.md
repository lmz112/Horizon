---
layout: default
title: "Horizon Summary: 2026-07-19 (ZH)"
date: 2026-07-19
lang: zh
---

> 从 39 条内容中筛选出 4 条重要资讯。

---

1. [Kimi K3：中国前沿模型挑战美国主导地位](#item-1) ⭐️ 9.0/10
2. [阿里千问 3.8-Max 预览版上线，即将开源](#item-2) ⭐️ 9.0/10
3. [OpenAI Codex 重置与 5 小时限制取消](#item-3) ⭐️ 8.0/10
4. [商汤科技发布 SenseNova U1 Pro 多模态智能体](#item-4) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Kimi K3：中国前沿模型挑战美国主导地位](https://stephen.bochinski.dev/blog/2026/07/18/the-kimi-k3-moment/) ⭐️ 9.0/10

中国 AI 公司月之暗面发布了 Kimi K3，一个拥有 2.8 万亿参数、100 万 token 上下文窗口的开源权重模型，其前沿性能可与美国顶级模型媲美。 这标志着中国模型达到与美国前沿模型同等水平的重要里程碑，加剧了 AI 竞争，并引发了关于蒸馏、开源权重和国家安全等议题的辩论。 Kimi K3 采用了名为 Kimi Delta Attention \(KDA\)的混合线性注意力机制和注意力残差，专为软件工程、知识工作和深度推理而设计。

hackernews · sbochins · 7月18日 17:32 · [社区讨论](https://news.ycombinator.com/item?id=48960218)

**背景**: 知识蒸馏是一种让较小的“学生”模型从较大的“教师”模型输出中学习的技术。开源权重模型允许任何人访问和微调模型权重。Kimi K3 是 2025 年 7 月发布的 Kimi K2 的继任者。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Kimi_%28chatbot%29">Kimi (chatbot) - Wikipedia</a></li>
<li><a href="https://platform.kimi.ai/docs/guide/kimi-k3-quickstart">Kimi K3 - Kimi API Platform</a></li>
<li><a href="https://en.wikipedia.org/wiki/Knowledge_distillation">Knowledge distillation - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者就 Kimi K3 的性能是源于蒸馏还是独立创新展开辩论，有人对美国政府的监管和国家安全影响表示担忧。用户 SwellJoe 报告称，在相同任务上，Kimi K3 比 OpenAI 的模型消耗了更多时间和使用额度。

**标签**: `#Kimi K3`, `#frontier model`, `#distillation`, `#AI competition`, `#open-weight`

---

<a id="item-2"></a>
## [阿里千问 3.8-Max 预览版上线，即将开源](https://36kr.com/newsflashes/3902296634050437?f=rss) ⭐️ 9.0/10

2025 年 7 月 19 日，阿里发布了千问 3.8-Max 的预览版，已在阿里云 Token Plan、Qoder 及 QoderWork 上线。正式版预计近期开源。 千问 3.8-Max 是阿里最新、最强的大语言模型，在编程和智能体能力上达到领先水平。其即将开源将为 AI 开发者和整个开源社区带来直接价值。 Qwen3.8-Max-Instruct 预览版目前在 Text Arena 排行榜上排名第三，超越了 GPT-5-Chat。正式版将进一步增强编程和智能体能力。

rss · 36氪 · 7月19日 08:43

**背景**: 千问是阿里系列大语言模型，以强大的多语言和多模态能力著称。千问 3.8-Max 是千问 3 系列中最大的模型，旨在推动推理、编程和智能体任务的性能边界。该模型原生支持 32,768 个 token 的上下文长度，通过 YaRN 扩展可达 131,072 个 token。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://qwen.ai/blog?id=qwen3-max">Qwen3-Max: Just Scale it</a></li>
<li><a href="https://huggingface.co/Qwen/Qwen3-8B">Qwen/Qwen3-8B · Hugging Face</a></li>
<li><a href="https://arxiv.org/pdf/2505.09388">Qwen3 Technical Report - arXiv.org</a></li>

</ul>
</details>

**标签**: `#模型发布`, `#开源`, `#Qwen`, `#阿里`

---

<a id="item-3"></a>
## [OpenAI Codex 重置与 5 小时限制取消](https://codex-resets.com/) ⭐️ 8.0/10

OpenAI Codex 近期频繁重置使用额度，并暂时取消了 5 小时使用限制，用户现在可以累积未使用的重置次数以备后用。 这一变化消除了开发者对使用额度的精打细算，深刻改变了智能体开发工作流，但也引发了对重置依赖性和长期成本可持续性的担忧。 取消 5 小时限制是事故响应的一部分，预计问题解决后将恢复；用户现在会看到“您有 4 次使用额度重置可用”的提示。

hackernews · denysvitali · 7月18日 23:24 · [社区讨论](https://news.ycombinator.com/item?id=48963465)

**背景**: OpenAI Codex 是一款帮助开发者编写代码的 AI 编程助手。使用额度是 OpenAI 为管理服务器负载和确保公平访问而设置的配额。5 小时限制此前限制了用户在滚动 5 小时窗口内的连续使用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://codex-resets.com/">Codex Resets — Usage Limit Reset Tracker</a></li>
<li><a href="https://community.openai.com/t/clarification-on-the-temporary-removal-of-the-codex-five-hour-limit/1386911">Clarification on the temporary removal of the Codex five-hour ...</a></li>
<li><a href="https://www.explainx.ai/blog/chatgpt-codex-5-hour-limit-removed-weekly-reset-july-2026">ChatGPT 5-Hour Limit Removed — July 2026 | explainx.ai Blog</a></li>

</ul>
</details>

**社区讨论**: 开发者反映频繁重置正在将他们锚定到更高的使用基线，有人已在 API 替代方案上花费超过 1 万美元。其他人指出，Claude Code 和 Grok Build 等竞品重置频率较低，而 Google Antigravity 几乎从不重置。

**标签**: `#OpenAI Codex`, `#Agent Workflow`, `#Usage Limits`, `#Cost Analysis`, `#Developer Experience`

---

<a id="item-4"></a>
## [商汤科技发布 SenseNova U1 Pro 多模态智能体](https://36kr.com/newsflashes/3902187700766593?f=rss) ⭐️ 7.0/10

2026 年 7 月 18 日，商汤科技在世界人工智能大会（WAIC）上正式发布旗舰级多模态智能体基座 SenseNova U1 Pro。该模型定位为面向长程任务的交付级原生多模态智能体基座，实现了理解、生成和行动的深度统一。 SenseNova U1 Pro 标志着从单点内容生成向系统级任务交付的转变，解决了多模态模型‘反复抽卡’的瓶颈。它为开发者构建复杂长程智能体应用提供了实用的基础。 该模型采用原生统一架构（NEO-unify 内核），实现语言与视觉的联合表征，从而无缝集成理解、生成和行动。预览版已开启邀测，正式版及 API 服务预计于 2026 年 8 月上线。

rss · 36氪 · 7月19日 06:30

**背景**: 多模态 AI 模型能够处理和生成多种类型的数据，如文本和图像。传统的多模态模型在处理需要多步骤和一致输出的长程任务时常常遇到困难，导致‘反复抽卡’问题——每次生成都是独立的。SenseNova U1 Pro 旨在通过在一个原生统一架构中融合理解、生成和行动，实现端到端的任务完成。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.163.com/dy/article/L2576SI705118O92.html">商汤发布旗舰级SenseNova U1 Pro，多模态智能体实现长程任务闭环|工作流|大语言模型|sensenova_网易订阅</a></li>
<li><a href="https://www.nbd.com.cn/articles/2026-07-18/4476806.html">大模型范式里程碑！商汤科技旗舰级SenseNova U1 Pro正式发布：从“内容生成”走向“系统级交付” | 每经网</a></li>
<li><a href="https://www.tmtpost.com/8070465.html">商汤发布旗舰级SenseNova U1 Pro，多模态智能体实现长程任务闭环</a></li>

</ul>
</details>

**标签**: `#多模态智能体`, `#商汤科技`, `#SenseNova`, `#Agent基座`, `#模型发布`

---