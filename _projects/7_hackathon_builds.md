---
layout: page
title: Hackathon builds
description: AI Medical Analyst (Caltech Longevity), Installama (LlamaCon 2025), and Silence as Music.
importance: 7
category: engineering
---

**AI Medical Analyst**, Caltech Longevity Hackathon, October 2025. Upload a medical PDF or image, and the app extracts the text with pdf-parse and Tesseract OCR, then runs a structured LLaMA prompt that returns a summary, keywords, categories, abnormal-value flags, and related PubMed titles. Next.js and Tailwind on the front end, Supabase storage, Postgres, and an edge function on the back end. Third place. [Write-up](https://hackernoon.com/we-built-an-ai-medical-analyst-in-a-weekend-at-the-caltech-longevity-hackathon)

**Installama**, LlamaCon 2025. Meta's first official hackathon for the LLaMA API, run with Cerebral Valley. Triple-tap an Instagram-style post and a conversational window opens that answers *as the post*, using the caption, tags, and a Gemini Vision description of the image. LLaMA-4-Maverick via the Meta API, Express with server-sent-event streaming, Next.js, Supabase. I led engineering; Rashmi Elavazhagan handled design and UX. [Write-up](https://hackernoon.com/this-hackathon-app-lets-instagram-posts-talk-back-using-ai) · [Demo](https://www.youtube.com/shorts/CUXM1DGofo0)

**Silence as Music.** A controllable, interpretable system that places musical rests. Candidate rest patterns come from phrase boundaries, melodic tension, rhythm heuristics, and cultural presets, and a quality function picks the mask that best balances rhythmic entropy, groove, and structure. Released with an API, demos, and audio examples. Published in PMLR 303 at the Emerging AI Technologies for Music workshop, January 2026. [Paper](https://proceedings.mlr.press/v303/ram26a.html)
