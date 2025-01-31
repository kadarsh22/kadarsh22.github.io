---
layout: page
permalink: /research/
title: Research
description: 
nav: true
nav_order: 5
---

# Robustness at Scale for Neural Networks

Machine learning algorithms are designed under the assumption that data points are independently and identically distributed (IID). However, in real-world applications, models often encounter samples that deviate from the training distribution. This deviation can lead to unreliable predictions with potentially severe consequences, especially in high-stakes domains like autonomous driving and healthcare.

To address this issue, large-scale models are typically trained on vast amounts of data. While this approach has shown some success, particularly in large language models, it comes with substantial computational and financial costs. Moreover, for high-dimensional data like images, the volume of data required can be prohibitively large or even unattainable. This highlights the need for machine learning algorithms that are inherently robust to distribution shifts and capable of generalizing beyond the training data.

## Research Focus

This study focuses on the design and evaluation of machine learning algorithms that can handle distribution shifts as well as compositional generalise to unseen scenarios. The goal is to improve the adaptability and reliability of models in diverse and dynamic environments.

### Initial Work: Resilience to Spurious Correlations

My initial work centers on developing models that are robust to one of the most commonly encountered distribution shifts: spurious correlations. I propose a novel, data-centric method that builds models resilient to such shifts while ensuring scalability to real-world, in-the-wild scenarios.

### Future Research: Compositional Generalization

Building upon this foundation, my subsequent research aims to create models capable of compositional generalization across various tasks by discovering modular networks in an unsupervised manner. The objective is to minimize data and computational requirements while preserving performance levels comparable to current foundation models, thereby enhancing efficiency.

### Vision Models for Robust Generalization

Future research will extend these approaches to vision models capable of robust compositional generalization, further advancing model adaptability in complex environments.

---
