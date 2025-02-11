---
title: "Training on the Test Task Confounds Evaluation and Emergence"
collection: Publications
permalink: /Publication/TTT
excerpt: 'Recent improvements in LLM performance that go beyond compute scaling appear to be fully explained by training on benchmark-specific data'
date: 2024-07-10
venue: 'ICLR 2025 (Oral)'
paperurl: 'https://arxiv.org/pdf/2407.07890'
citation: 'Dominguez-Olmedo, Ricardo, Florian E. Dorner, and Moritz Hardt. "Training on the Test Task Confounds Evaluation and Emergence." arXiv preprint arXiv:2407.07890 (2024).'
authors: "Ricardo Dominguez-Olmedo, <strong>Florian E. Dorner</strong>, and Moritz Hardt"
---

We study a fundamental problem in the evaluation of large language models that we call training on the test task. Unlike wrongful practices like training on the test data, leakage, or data contamination, training on the test task is not a malpractice. Rather, the term describes a growing set of techniques to include task-relevant data in the pretraining stage of a language model. We demonstrate that training on the test task confounds both relative model evaluations and claims about emergent capabilities. We argue that the seeming superiority of one model family over another may be explained by a different degree of training on the test task. To this end, we propose an effective method to adjust for training on the test task by fine-tuning each model under comparison on the same task-relevant data before evaluation. We then show that instances of emergent behavior largely vanish once we adjust for training on the test task. This also applies to reported instances of emergent behavior that cannot be explained by the choice of evaluation metric. Our work promotes a new perspective on the evaluation of large language models with broad implications for benchmarking and the study of emergent capabilities.