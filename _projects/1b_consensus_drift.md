---
layout: page
title: Consensus Drift
description: One well-phrased minority statement can flip an LLM's reading of the majority evidence.
importance: 1
category: research
related_publications: ram-etal-2026-consensus
---

When a language model aggregates verdicts from several "jurors", does it follow the majority? With plain YES/NO votes, yes: minority override is near zero across every model we tested. Once jurors attach short evidence statements, the picture changes.

**Findings**

- A semantically salient minority statement overrides a weak majority at high rates. A strong majority against a weak minority stays safe.
- Position matters, and authority cues on the minority statement shift the effect in some settings but do not beat evidence strength.
- The pattern holds across seeds, domains, and a phase-transition map over majority strength, minority strength, and position.
- Scaling does not remove it. Llama-3.3-70B-Instruct tracks the smaller-model baseline, while GPT-4.1 shows a substantially larger override magnitude.

We are careful to note that "strength" here is a synthetic manipulation, and that following a genuinely decisive minority can be the rational choice.

Joint work with Rashmi Elavazhagan and Anirudh Vasudevan. Published at EMNLP 2026. [Paper](https://aclanthology.org/2026.emnlp-main.1689/)
