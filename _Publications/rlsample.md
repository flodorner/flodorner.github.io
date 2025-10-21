---
title: "Measuring Progress in Deep Reinforcement Learning Sample Efficiency"
collection: Publications
permalink: /Publication/rlsample
excerpt: 'How has sample efficiency in deep reinforcement learning improved over time?'
date: 2021-02-09
venue: 'arxiv preprint'
paperurl: 'https://arxiv.org/pdf/2102.04881.pdf'
authors: "<strong>Florian E. Dorner</strong>"
---

Sampled environment transitions are a critical input to deep reinforcement learning (DRL) algorithms. Current DRL benchmarks often allow for the cheap and easy generation of large amounts of samples such that perceived progress in DRL does not necessarily correspond to improved sample efficiency. As simulating real world processes is often prohibitively hard and collecting real world experience is costly, sample efficiency is an important indicator for economically relevant applications of DRL. We investigate progress in sample efficiency on Atari games and continuous control tasks by comparing the number of samples that a variety of algorithms need to reach a given performance level according to training curves in the corresponding publications. We find exponential progress in sample efficiency with estimated doubling times of around 10 to 18 months on Atari, 5 to 24 months on state-based continuous control and of around 4 to 9 months on pixel-based continuous control depending on the specific task and performance level.