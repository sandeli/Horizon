---
layout: default
title: "Horizon Summary: 2026-11-12 (ZH)"
date: 2026-11-12
lang: zh
---

> 从 53 条内容中筛选出 4 条重要资讯。

---

**科技新闻**
1. [AWS 发布官方云服务本地模拟器](#item-tech-news-1) ⭐️ 8.0/10
2. [使用电压毛刺攻击解锁 NVIDIA 挖矿显卡](#item-tech-news-2) ⭐️ 8.0/10
3. [谷歌推出支持多模态输入的 Gemini Decisions API](#item-tech-news-3) ⭐️ 8.0/10

**财经新闻**
1. [中国国家安全部在英伟达 CEO 传闻中受到关注](#item-finance-news-1) ⭐️ 6.0/10

---

## 科技新闻

<a id="item-tech-news-1"></a>
### [AWS 发布官方云服务本地模拟器](https://github.com/aws/aws-emulator) ⭐️ 8.0/10

AWS 推出了用于本地测试云服务的官方模拟器，旨在解决开发人员在本地环境中测试云应用长期面临的痛点。该工具能够支持部分核心服务的本地运行，但在安全控制、IAM 策略以及跨账户和跨区域访问等方面的功能受到明确限制，不应用于这些场景的安全测试。

hackernews · super\_linear · 11月11日 18:21 · [社区讨论](https://news.ycombinator.com/item?id=50456631)

**「背景」** 长期以来，在本地测试环境中模拟 AWS 云服务一直是软件工程中的一个主要痛点，开发者通常依赖 LocalStack 等第三方开源工具来解决该问题。

**「社区讨论」** 社区工程师对该工具的实用性表示欢迎，但也对 AWS 是否会长期维护它表示怀疑。同时，有评论指出其安全文档明确排除了 IAM 策略和 KMS 等敏感权限的测试，且其实现可能得益于 AI 编码代理的应用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/phanlyhuynh/aws-local-emulator">GitHub - phanlyhuynh/ aws -local- emulator : Light, fluffy, and always...</a></li>

</ul>
</details>

**标签**: `#AWS`, `#Cloud Computing`, `#Software Testing`, `#Developer Tools`

---

<a id="item-tech-news-2"></a>
### [使用电压毛刺攻击解锁 NVIDIA 挖矿显卡](https://blog.kate.land/posts/using-voltage-glitching-to-unlock-the-a100/) ⭐️ 8.0/10

一位工程师成功利用电压毛刺攻击技术，解锁了 NVIDIA A100 系列特定挖矿显卡上被禁用的内存和功能。该硬件破解绕过了原本通过物理熔丝限制的配置，使受限型号能够访问更完整的硬件资源。这项技术展示了针对高端企业级 GPU 硬件限制的深度逆向工程与破解手段。

hackernews · lae · 11月11日 10:48 · [社区讨论](https://news.ycombinator.com/item?id=50451903)

**「背景」** NVIDIA 的部分企业级或衍生型号（如特定挖矿卡）常通过物理熔丝或软件禁用部分高带宽内存（HBM）与核心功能，以区分产品线或处理生产过程中的瑕疵芯片。电压毛刺攻击是一种通过对目标设备瞬间改变供电电压来破坏芯片内部逻辑状态、从而绕过安全检查或硬件锁定的硬件攻击手段。

**「影响」** 拥有同类受限硬件的极客和研究人员可能会尝试通过硬件改造来解锁完整显卡功能，但这种物理操作伴随着极高的硬件损坏风险。

**「社区讨论」** 评论者对该硬件破解的复杂性与风险表示惊叹，并讨论了部分显卡拥有大容量内存但大部分被禁用的历史情况。部分用户指出，这种限制可能是因为芯片制造缺陷所致，也有人探讨了使用独立电源或 PCIe 转接卡来优化此类实验流程的可能性。

**标签**: `#hardware`, `#reverse engineering`, `#GPUs`, `#security`

---

<a id="item-tech-news-3"></a>
### [谷歌推出支持多模态输入的 Gemini Decisions API](https://blog.google/innovation-and-ai/technology/developers-tools/gemini-decisions-api/) ⭐️ 8.0/10

谷歌推出了 Gemini Decisions API，为开发者提供支持多模态输入的结构化、具备概率感知的模型输出能力。该工具允许开发者获取模型输出的概率信息，并在决策场景中加以利用。虽然其定价高于同类决策模型，但它能够直接接受音频和视频作为输入。

hackernews · iamdelirium · 11月11日 18:32 · [社区讨论](https://news.ycombinator.com/item?id=50456791)

**「背景」** 在此之前，开发者主要通过 Gemini API 使用大语言模型进行通用文本生成、工具调用以及结构化输出，但缺乏专门针对多输入源进行高效率、批量化决策评估的专用接口。

**「社区讨论」** 评论者指出，相较于传统的语法约束输出，该 API 能够提供模型概率，这是一大优势。同时有用户认为其定价高于同类决策模型，但在处理音频和视频等特定多模态输入时非常实用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://ai.google.dev/gemini-api/docs/tools">Using tools with Gemini API | Google AI for Developers</a></li>

</ul>
</details>

**标签**: `#artificial intelligence`, `#machine learning`, `#developer tools`, `#APIs`, `#multimodal AI`

---

## 财经新闻

<a id="item-finance-news-1"></a>
### [中国国家安全部在英伟达 CEO 传闻中受到关注](https://www.cnbc.com/2026/11/12/china-ministry-state-security-nvidia-ceo.html) ⭐️ 6.0/10

媒体报道显示，在美国科技行业及英伟达首席执行官詹姆斯·黄相关涉谍传闻中，中国国家安全部受到的关注度日益上升。

rss · CNBC Finance · 11月12日 07:28

**「背景」** 中国国家安全部成立于 1983 年，随着北京自 2023 年起对国家安全重视程度的提高，该机构的政治影响力和公开活跃度均有所增加。

**标签**: `#Geopolitics`, `#National Security`, `#Technology`, `#China`, `#Intelligence`

---