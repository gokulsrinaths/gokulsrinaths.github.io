---
layout: page
title: The Validity–Fidelity Gap
description: When structured extraction stays valid JSON but silently stops being correct.
importance: 2
category: research
related_publications: ram-etal-2026-validity
github: https://github.com/gokulsrinaths/validity-fidelity-gap
---

Production pipelines that use LLMs to pull structured data out of documents are usually monitored one way: does the output parse as JSON, and does it have the expected keys? This project shows that check can be perfect while the extracted content quietly falls apart.

**Key findings**

- We name the failure **representation drift**: the model still finds the entity, but writes it in a different shape, such as a nested object where a plain string was expected. Validators pass, but downstream consumers score it as both a miss and a false positive.
- With synthetic clinical notes repeated 1x to 32x, LLaMA-3.1-8B-Instruct drops from 0.499 to 0.259 micro-F1 while JSON validity stays at 1.00.
- We introduce the **Differential Redundancy Effect**, the extra F1 loss under repeated content versus a length-matched unrelated-filler control. It is large at 8B and near zero at 70B and Qwen2.5-72B.
- We provide a zero-ground-truth drift check that teams can run in production without labels.

Joint work with Anirudh Vasudevan and Rashmi Elavazhagan. Published in Findings of IJCNLP-AACL 2026. [Paper](https://aclanthology.org/2026.findings-aacl.107/)
