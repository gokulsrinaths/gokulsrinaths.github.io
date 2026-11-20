---
layout: page
title: The Drift Kernel
description: Diffusion models change an image even when told not to. We measure how much, and why.
importance: 0
category: research
related_publications: ram-elavazhagan-2026-drift-kernel
github: https://github.com/gokulsrinaths/CVPR
---

Give an image-editing diffusion model a null instruction such as "make no changes" and it should return the input untouched. It does not. We call this **No-Op Drift** and show it is a structural property of the models, not a prompting artifact.

**What we did**

- Defined the **Drift Kernel**, the expected perceptual deviation of a model run at noise strength σ under a null instruction.
- Measured it on 120,000 baseline samples across Stable Diffusion 1.5, 2.1, SDXL, and InstructPix2Pix.
- Found that drift grows quadratically with noise strength, with an aggregate R² of 0.97, and that prompt wording barely moves it.
- Released **NoOp-Bench**, a 10,000-input benchmark, with full code.

Joint work with Rashmi Elavazhagan. Published at CVPR 2026. [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Ram_The_Drift_Kernel_Why_Diffusion_Models_Change_Even_When_Told_CVPR_2026_paper.html)
