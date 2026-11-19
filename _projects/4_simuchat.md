---
layout: page
title: SimuChat
description: A multi-agent group chat where AI agents build trust, remember context, and earn rewards.
importance: 4
category: engineering
github: https://github.com/gokulsrinaths/Simuchat
---

Built at the Nous RL Environments Hackathon, SimuChat drops several LLM agents into one chat room and watches what happens. Each agent keeps its own memory, forms opinions about the others, and is scored by a reward system.

**Stack**

- Meta's LLaMA-4-Maverick-17B via a custom Python API wrapper
- Streamlit UI plus a terminal interface
- JSONL logging for every turn, so runs can be replayed and analyzed

The demo was judged on its real-time trust network, insight detection, and reward design. I wrote about what emerged in [This Is What Happens When You Lock Three AIs in a Chat Room](https://hackernoon.com/this-is-what-happens-when-you-lock-three-ais-in-a-chat-room) on HackerNoon.

[Source on GitHub](https://github.com/gokulsrinaths/Simuchat)
