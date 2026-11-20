---
layout: about
title: about
permalink: /
subtitle: M.S. Computer Science, <a href="https://www.cpp.edu/">Cal Poly Pomona</a>. Prospective PhD student in NLP and trustworthy AI.

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Department of Computer Science</p>
    <p>California State Polytechnic University, Pomona</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false
  scrollable: true
  limit: 5

latest_posts:
  enabled: false
  scrollable: true
  limit: 3
---

I am a computer science graduate student at California State Polytechnic University, Pomona, applying to PhD programs in natural language processing and trustworthy machine learning.

My research asks a simple question: **when do generative models look right while quietly being wrong?** I study drift: failures that standard checks miss. In [Consensus Drift](https://aclanthology.org/2026.emnlp-main.1689/) (EMNLP 2026) I showed that a single semantically salient minority statement can override majority evidence when LLMs aggregate conflicting jurors, while plain majority voting never does. In [The Drift Kernel](https://openaccess.thecvf.com/content/CVPR2026/html/Ram_The_Drift_Kernel_Why_Diffusion_Models_Change_Even_When_Told_CVPR_2026_paper.html) (CVPR 2026) I showed that diffusion models alter an image even under a null instruction, with drift growing quadratically in noise strength across 120,000 samples, and released NoOp-Bench. In [The Validity–Fidelity Gap](https://aclanthology.org/2026.findings-aacl.107/) (Findings of IJCNLP-AACL 2026) I showed that structured-extraction pipelines can keep perfect JSON validity while extraction fidelity collapses under redundant context. [Citation Drift](https://aclanthology.org/2025.wasp-main.20/) measures how references mutate or get fabricated across multi-turn conversations, and [Zero-to-Forecast](https://neurips.cc/virtual/2025/loc/san-diego/130445) (NeurIPS 2025 workshop) forecasts time series directly from natural-language descriptions.

Broader interests: LLM evaluation and reproducibility, interpretability, reasoning, multi-agent systems, and fairness in AI.

Outside of research I build things, usually at hackathons: a multi-agent chat simulator at the Nous RL Environments Hackathon, an autonomous AI engineering team for the Claude Code hackathon, and third-place finishes at the Caltech Longevity Hackathon, the Avanade Hackathon, and Cal Poly Pomona's AI for a Better Future hackathon. I also serve on the program committee of the HeaLing 2026 workshop at EACL.
