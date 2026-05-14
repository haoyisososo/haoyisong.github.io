---
title: "Inv-Entropy: A Fully Probabilistic Framework for Uncertainty Quantification in Language Models"
collection: publications
category: manuscripts
permalink: /publication/2025-inv-entropy
excerpt: 'Uncertainty quantification (UQ) in LLMs has largely relied on heuristic measures all of which struggle with confidently wrong predictions. These methods overlook a key issue: replication alone fails to reveal hidden brittleness, as semantically identical prompts often yield identical but incorrect outputs. This paper begins by providing a theoretical proof demonstrating why input perturbations are essential for exposing model uncertainty. Building on this insight, it introduces a fully probabilistic framework that models perturbed inputs and outputs through dual random walks, enabling an inverse view of uncertainty based on the diversity of input configurations that correspond to a given output. Within this framework, the paper proposes Inv-Entropy, a principled uncertainty measure, and GAAP, a genetic-algorithm–based perturbation method that enhances semantic coverage. Extensive experiments show that this approach significantly outperforms existing UQ techniques.'
date: 2025-12-01
venue: 'NeurIPS 2025'
paperurl: 'https://arxiv.org/abs/2506.09684'
citation: 'Haoyi Song, Ruihan Ji, Naichen Shi, Fan Lai, Raed Kontar. &quot;Inv-Entropy: A Fully Probabilistic Framework for Uncertainty Quantification in Language Models.&quot; <i>NeurIPS</i>. 2025.'
---

**Authors:** Haoyi Song, Ruihan Ji, Naichen Shi, Fan Lai, Raed Al Kontar

**Venue:** NeurIPS 2025

\[[Paper](https://arxiv.org/abs/2506.09684)\] \ [[Code](https://github.com/UMDataScienceLab/Uncertainty-Quantification-for-LLMs)\] \ [[Youtube Video](https://www.youtube.com/watch?v=aYxIvemy68M&t=520s)\]

![Inv-Entropy Framework](/images/inv.jpg)

Uncertainty quantification (UQ) in LLMs has largely relied on heuristic measures all of which struggle with confidently wrong predictions. These methods overlook a key issue: replication alone fails to reveal hidden brittleness, as semantically identical prompts often yield identical but incorrect outputs. This paper begins by providing a theoretical proof demonstrating why input perturbations are essential for exposing model uncertainty. Building on this insight, it introduces a fully probabilistic framework that models perturbed inputs and outputs through dual random walks, enabling an inverse view of uncertainty based on the diversity of input configurations that correspond to a given output. Within this framework, the paper proposes Inv-Entropy, a principled uncertainty measure, and GAAP, a genetic-algorithm–based perturbation method that enhances semantic coverage. Extensive experiments show that this approach significantly outperforms existing UQ techniques.