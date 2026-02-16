---
title: "On Evaluating Methods vs. Evaluating Models"
collection: Publications
permalink: /Publication/methods-vs-models
excerpt: 'Should benchmarks evaluate LLMs, or the methods used to train them?'
date: 2025-09-24
venue: 'Evaluating the Evolving LLM Lifecycle Workshop at NeurIPS 2025 (Oral, Best Paper Award)'
paperurl: 'https://openreview.net/forum?id=8yg3XadfIZ'
authors: "Olawale Elijah Salaudeen, <strong>Florian E. Dorner</strong>, and Peter Hase"
---

We distinguish between two often-conflated uses of datasets: evaluating methods, which compares algorithms under controlled conditions, and evaluating models, which assesses the capabilities of a fixed model. Method evaluation emphasizes relative rankings and is robust to model-independent distortions, while model evaluation requires valid absolute scores but can be biased by contamination or task mismatch. Using simple formulations and synthetic experiments, we demonstrate how this conflation can reverse method rankings and misrepresent model capabilities, leading to misleading leaderboards and a flawed understanding of a models' true capabilities. We conclude with recommendations for designing and interpreting state-of-the-art evaluations, grounded in the critical distinction between methods and models.