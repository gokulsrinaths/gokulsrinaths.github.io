---
layout: page
title: Zero-to-Forecast
description: Forecasting time series from a natural-language description, with no historical data.
importance: 3
category: research
related_publications: ram-2025-zerotoforecast
github: https://github.com/gokulsrinaths/zero-to-forecast
---

Can a model produce a sensible numeric forecast from a sentence like "foot traffic at a new coffee shop near a university over its first three months"? Zero-to-Forecast is a cross-modal framework that does exactly this.

**How it works**

- An LLM reasons about the description and the domain it belongs to.
- Domain- and pattern-specific predictors generate candidate sequences.
- Post-hoc calibration applies domain-aware smoothing and monotonic constraints so the output respects real-world structure.

**Benchmark**

I built **NL2TS-675**, a benchmark of natural-language-to-time-series tasks across six domains: finance, healthcare, weather, IoT, technology, and retail. The domain-optimized ensemble reaches an overall MAE of 16.06, with every domain under 25.

Code, artifacts, and a live interactive demo are released. Presented at the NeurIPS 2025 workshop on Recent Advances in Time Series Foundation Models. [Workshop page](https://neurips.cc/virtual/2025/loc/san-diego/130445)
