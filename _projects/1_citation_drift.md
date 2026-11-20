---
layout: page
title: Citation Drift
description: Measuring whether LLMs keep their references straight across multi-turn conversations.
importance: 1
category: research
related_publications: ram-2025-citation, ram-2026-reproduce
github: https://github.com/gokulsrinaths/citationdrift16k
---

Large language models are increasingly used as research assistants, yet nobody had measured whether the references they give stay stable as a conversation goes on. This project introduces **citation drift**: references that mutate, disappear, or are fabricated over multi-turn interactions.

**What I did**

- Ran 240 multi-turn conversations across four LLaMA models, grounded in 36 real scientific papers from six domains.
- Defined five metrics: citation stability, fabrication rate, drift rate, drift entropy, and willingness-to-cite.
- Found that stability varies sharply by model. LLaMA-4-Maverick was the most stable, while LLaMA-4-Scout fabricated up to 85.6% of citations.
- Released a model-agnostic, reproducible benchmark so others can test their own systems.

The follow-up paper, presented at the AAAI 2026 workshop on responsible synthetic data, frames citation drift as a reproducibility failure for scientific LLMs.

Published at the Third Workshop for AI for Scientific Publications (WASP), co-located with IJCNLP-AACL 2025. [Paper](https://aclanthology.org/2025.wasp-main.20/)
