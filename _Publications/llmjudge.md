---
title: "Limits to scalable evaluation at the frontier: LLM as Judge won't beat twice the data"
collection: Publications
permalink: /Publication/llmjudge
excerpt: 'Model evaluations based on LLM judgements are often biased. After debiasing, the gains achievable from access to an LLM are limited.'
date: 2024-10-17
venue: 'ICLR 2025 (Oral)'
paperurl: 'https://arxiv.org/abs/2410.13341.pdf'
citation: 'Dorner, Florian E., Vivian Y. Nastl, and Moritz Hardt. "Limits to scalable evaluation at the frontier: LLM as Judge wont beat twice the data." arXiv preprint arXiv:2410.13341 (2024).'
authors: "<strong>Florian E. Dorner</strong>, Vivian Y. Nastl, and Moritz Hardt"
---

High quality annotations are increasingly a bottleneck in the explosively growing machine learning ecosystem. Scalable evaluation methods that avoid costly annotation have therefore become an important research ambition. Many hope to use strong existing models in lieu of costly labels to provide cheap model evaluations. Unfortunately, this method of using models as judges introduces biases, such as self-preferencing, that can distort model comparisons. An emerging family of debiasing tools promises to fix these issues by using a few high quality labels to debias a large number of model judgments. In this paper, we study how far such debiasing methods, in principle, can go. Our main result shows that when the judge is no more accurate than the evaluated model, no debiasing method can decrease the required amount of ground truth labels by more than half. Our result speaks to the severe limitations of the LLM-as-a-judge paradigm at the evaluation frontier where the goal is to assess newly released models that are possibly better than the judge. Through an empirical evaluation, we demonstrate that the sample size savings achievable in practice are even more modest than what our theoretical limit suggests. Along the way, our work provides new observations about debiasing methods for model evaluation, and points out promising avenues for future work. 