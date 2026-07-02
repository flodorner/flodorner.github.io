---
title: "Cutting LLM Evaluation Costs with SySRs: A Bandit Algorithm that Provably Exploits Model Similarity"
collection: Publications
permalink: /Publication/Sysrs
excerpt: 'How to efficiently identify the best model on a benchmark?'
date: 2026-06-05
venue: 'ICML 2026'
paperurl: 'https://arxiv.org/abs/2606.07726'
authors: "Zifan Lyu, Chahine Nejma, Tobias Wegel, Fanny Yang, <strong>Florian E. Dorner</strong>"
---

Large Language Models are typically benchmarked by evaluating every model on every test query. For practitioners seeking the best model to deploy, this is often wasteful: if a model clearly performs worse than others, there is no need to precisely estimate its performance. Best-arm identification algorithms can be naturally applied to drastically reduce costs by adaptively allocating evaluation budget. Further, language models often respond similarly to the same prompt-a property previous work has tried to leverage with mixed success. We propose Synchronized Successive Rejects (SySRs), augmenting the classical Successive Rejects algorithm with paired comparisons. Unlike prior attempts to leverage model similarity in best-model identification, our approach is hyperparameter-free and enjoys performance guarantees that improve with the degree of similarity between evaluated models. Empirically, our method outperforms all baselines in terms of average error rate across 15 standard benchmarks, and in terms of worst-case budget for reliably identifying the best model. 