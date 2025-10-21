---
title: "Incentivizing Honesty among Competitors in Collaborative Learning and Optimization"
collection: Publications
permalink: /Publication/federated
excerpt: 'We show how to use peer-prediction mechanisms to prevent rational clients from adversarially manipulating updates in federated learning.'
date: 2023-10-12
venue: 'NeurIPS 2023'
paperurl: 'https://proceedings.neurips.cc/paper_files/paper/2023/file/182b39a4458fb4a9a8d6871a6671ff3e-Paper-Conference.pdf'
authors: "<strong>Florian E. Dorner</strong>, Nikola Konstantinov, Georgi Pashaliev, Martin Vechev"
---

Collaborative learning techniques have the potential to enable training machine learning models that are superior to models trained on a single entity’s data. However, in many cases, potential participants in such collaborative schemes are competitors on a downstream task, such as firms that each aim to attract customers by providing the best recommendations. This can incentivize dishonest updates that damage other participants' models, potentially undermining the benefits of collaboration. In this work, we formulate a game that models such interactions and study two learning tasks within this framework: single-round mean estimation and multi-round SGD on strongly-convex objectives. For a natural class of player actions, we show that rational clients are incentivized to strongly manipulate their updates, preventing learning. We then propose mechanisms that incentivize honest communication and ensure learning quality comparable to full cooperation. Lastly, we empirically demonstrate the effectiveness of our incentive scheme on a standard non-convex federated learning benchmark. Our work shows that explicitly modeling the incentives and actions of dishonest clients, rather than assuming them malicious, can enable strong robustness guarantees for collaborative learning.

