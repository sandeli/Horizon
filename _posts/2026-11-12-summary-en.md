---
layout: default
title: "Horizon Summary: 2026-11-12 (EN)"
date: 2026-11-12
lang: en
---

> From 53 items, 4 important content pieces were selected

---

**Technology News**
1. [AWS Releases Emulator for Local Cloud Service Testing](#item-tech-news-1) ⭐️ 8.0/10
2. [Unlocking an NVIDIA A100-based mining card via voltage glitching](#item-tech-news-2) ⭐️ 8.0/10
3. [Google Introduces Gemini Decisions API for Structured Multimodal Outputs](#item-tech-news-3) ⭐️ 8.0/10

**Financial News**
1. [China&\#x27;s Intelligence Agency Gains Prominence Amid Tech Sector Scrutiny](#item-finance-news-1) ⭐️ 6.0/10

---

## Technology News

<a id="item-tech-news-1"></a>
### [AWS Releases Emulator for Local Cloud Service Testing](https://github.com/aws/aws-emulator) ⭐️ 8.0/10

AWS has released an official emulator via GitHub to facilitate local testing environments for its cloud services. The tool addresses a long-standing challenge in cloud software engineering by enabling developers to run and test AWS services locally. However, official documentation notes significant security limitations, warning that the emulator should not be used to test IAM policies, resource-based bucket policies, KMS key policies, or cross-account and cross-region access controls.

hackernews · super\_linear · Nov 11, 18:21 · [Discussion](https://news.ycombinator.com/item?id=50456631)

**「Background」** Engineers have long relied on third-party tools like LocalStack or container-based setups to test AWS deployments locally, because AWS previously lacked an official native local emulation environment.

**「Impact」** Developers adopting the AWS emulator must avoid relying on it for validating security permissions or access control policies, as its behavior with IAM and keys differs from actual AWS cloud environments.

**「Community Discussion」** Commenters expressed excitement over finally having an official local testing environment while remaining skeptical about its long-term support and maintenance from AWS. Others noted that existing alternatives like LocalStack or Floci with Testcontainers already provide similar multi-cloud capabilities.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/phanlyhuynh/aws-local-emulator">GitHub - phanlyhuynh/ aws -local- emulator : Light, fluffy, and always...</a></li>

</ul>
</details>

**Tags**: `#AWS`, `#Cloud Computing`, `#Software Testing`, `#Developer Tools`

---

<a id="item-tech-news-2"></a>
### [Unlocking an NVIDIA A100-based mining card via voltage glitching](https://blog.kate.land/posts/using-voltage-glitching-to-unlock-the-a100/) ⭐️ 8.0/10

An engineer successfully used hardware voltage glitching to bypass fused restrictions and unlock disabled memory and features on an NVIDIA A100-derived mining card. The technique targets enterprise GPUs where manufacturers deliberately disable hardware capacities due to binning or product segmentation. This hardware modification approach provides an alternative to purely software-based methods for accessing restricted resources.

hackernews · lae · Nov 11, 10:48 · [Discussion](https://news.ycombinator.com/item?id=50451903)

**「Background」** Hardware manufacturers often physically disable functional components on silicon dies using electronic fuses to create lower-tier products or repurpose defective chips for specialized markets like cryptocurrency mining. Voltage glitching involves intentionally manipulating the power supply of a chip for brief moments to cause transient faults that can bypass security checks or instruction execution flows.

**「Impact」** Hardware enthusiasts and researchers attempting similar modifications face high physical risks of permanent component damage due to the precise timing and voltage control required to manipulate blown fuses.

**「Community Discussion」** Commenters debated whether the disabled memory on these mining cards resulted from artificial market segmentation or necessary binning for chips with manufacturing defects. Others discussed the risks of physical voltage glitching compared to safer software-based unlocking attempts.

**Tags**: `#hardware`, `#reverse engineering`, `#GPUs`, `#security`

---

<a id="item-tech-news-3"></a>
### [Google Introduces Gemini Decisions API for Structured Multimodal Outputs](https://blog.google/innovation-and-ai/technology/developers-tools/gemini-decisions-api/) ⭐️ 8.0/10

Google has launched the Gemini Decisions API, giving developers tools for structured and probability-aware model outputs that include multimodal input support. The API enables constrained outputs while exposing underlying model probabilities, accommodating audio and video inputs alongside text. According to community feedback, the service is priced higher than competing decision models in the same category, though commenters noted its multimodal capabilities remain uniquely useful for specific workloads.

hackernews · iamdelirium · Nov 11, 18:32 · [Discussion](https://news.ycombinator.com/item?id=50456791)

**「Background」** The Gemini API allows developers to integrate Google&\#x27;s multimodal models into applications, previously supporting text, image, audio, and video inputs alongside tool use capabilities like function calling and search grounding.

**「Community Discussion」** Commenters discussed how the API bridges a gap by providing explicit probability data rather than just grammar-constrained text structures. Participants observed that while the API carries a higher cost than alternatives, its ability to ingest audio and video inputs makes it valuable for specialized multimodal decision tasks.

<details><summary>References</summary>
<ul>
<li><a href="https://ai.google.dev/gemini-api/docs/tools">Using tools with Gemini API | Google AI for Developers</a></li>

</ul>
</details>

**Tags**: `#artificial intelligence`, `#machine learning`, `#developer tools`, `#APIs`, `#multimodal AI`

---

## Financial News

<a id="item-finance-news-1"></a>
### [China&\#x27;s Intelligence Agency Gains Prominence Amid Tech Sector Scrutiny](https://www.cnbc.com/2026/11/12/china-ministry-state-security-nvidia-ceo.html) ⭐️ 6.0/10

Media reports and intelligence sources indicate that China&\#x27;s Ministry of State Security has gained increased prominence amid allegations involving espionage and intelligence gathering in the U.S. technology sector, including a personal affair connected to Nvidia CEO Jensen Huang.

rss · CNBC Finance · Nov 12, 07:28

**「Background」** Established in 1983, the Ministry of State Security is China&\#x27;s primary civilian intelligence and security agency, which has expanded its political influence and public profile under Chinese President Xi Jinping&\#x27;s national security initiatives.

**Tags**: `#Geopolitics`, `#National Security`, `#Technology`, `#China`, `#Intelligence`

---