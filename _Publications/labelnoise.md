---
title: "Don't Label Twice: Quantity Beats Quality when Comparing Binary Classifiers on a Budget"
collection: Publications
permalink: /Publication/labelnoise
excerpt: 'When building a test set for binary classification from noisy label, how many labels to collect per data point? Surprisingly under a simple budget constraint, the answer is a single label.'
date: 2024-02-03
venue: 'Workshop on Navigating and Addressing Data Problems for Foundation Models (at ICLR 2024)'
paperurl: 'https://arxiv.org/pdf/2402.02249.pdf'
citation: 'Dorner, Florian E., and Moritz Hardt. "Dont Label Twice: Quantity Beats Quality when Comparing Binary Classifiers on a Budget." arXiv preprint arXiv:2402.02249 (2024).'
authors: "<strong>Florian E. Dorner</strong>, Moritz Hardt"
---

We study how to best spend a budget of noisy labels to compare the accuracy of two binary classifiers. It's common practice to collect and aggregate multiple noisy labels for a given data point into a less noisy label via a majority vote. We prove a theorem that runs counter to conventional wisdom. If the goal is to identify the better of two classifiers, we show it's best to spend the budget on collecting a single label for more samples. Our result follows from a non-trivial application of Cramér's theorem, a staple in the theory of large deviations. We discuss the implications of our work for the design of machine learning benchmarks, where they overturn some time-honored recommendations. In addition, our results provide sample size bounds superior to what follows from Hoeffding's bound. 