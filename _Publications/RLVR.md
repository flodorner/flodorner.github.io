---
title: "Delay, Plateau, or Collapse: Evaluating the Impact of Systematic Verification Error on RLVR"
collection: Publications
permalink: /Publication/RLVR
excerpt: 'How do systematic verification errors affect reinforcement learning with verifiable rewards?'
date: 2026-04-06
venue: 'arxiv preprint'
paperurl: 'https://arxiv.org/abs/2605.02909'
authors: " Kazuki Egashira, Mark Vero, Jasper Dekoninck,  <strong>Florian E. Dorner</strong>, Robin Staab, Martin Vechev"
---

Reinforcement Learning with Verifiable Rewards (RLVR) has become a powerful approach for improving the reasoning capabilities of large language models (LLMs). While RLVR is designed for tasks with verifiable ground-truth answers, real-world verifiers (e.g., static code checkers) can introduce errors into the reward signal. Prior analyses have largely treated such errors as random and independent across samples, concluding that errors merely slow training with limited effect on final performance. However, practical verifiers tend to exhibit systematic errors. This introduces a risk of models learning unwanted consistent behavior from a structurally incorrect reward signal. In this work, we study the impact of such systematic verification errors on RLVR. Through controlled experiments on arithmetic tasks, we show that systematic false negatives lead to similar effects as random noise. On the other hand, systematic false positives can cause a wide range of behaviors from sub-optimal plateaus to performance collapse. Crucially, these outcomes are not determined by the overall error rate but by the specific pattern of introduced errors, making pre-hoc mitigation difficult. Our results show that, in contrast to prior conclusions, realistic verification errors can critically shape RLVR outcomes and that verifier quality has to be understood beyond its sample-level error rate. 
