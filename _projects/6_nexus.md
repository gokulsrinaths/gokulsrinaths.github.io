---
layout: page
title: Nexus
description: An autonomous AI engineering team that turns one instruction into verified code patches.
importance: 6
category: engineering
github: https://github.com/rashmi-star/claude-hackathon
---

Built for the "Built with Opus 4.6" Claude Code hackathon with Rashmi Elavazhagan. Nexus takes a single instruction and runs it through six Claude Opus 4.6 agents, each a separate step:

- **Router** decides where to focus.
- **Frontend** and **Backend** agents scan the codebase with domain expertise.
- **Manager** prioritizes like a product manager.
- **Detect** reviews code, **Plan** turns findings into tasks, and **Patch** emits unified diffs that are applied with git and verified with a real build.

A **Reflector** writes what it learned to persistent memory, and the system can also learn from external articles. The demo runs scan mode, instruction mode with auto-apply and build verification, and continuous learning from the web against a real Next.js codebase.

[Hackathon gallery entry](https://cerebralvalley.ai/e/claude-code-hackathon/hackathon/gallery/50) · [Source](https://github.com/rashmi-star/claude-hackathon)
