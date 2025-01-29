---
layout: page
permalink: /research/
title: Research
description: 
nav: true
nav_order: 5
---

## Neural Network Robustness & Out-of-Distribution (OOD) Generalization

In our exploration of **neural network robustness**, we've uncovered a fascinating phenomenon: neural networks exhibit a rich interplay of mechanisms, a concept also discussed by Zhang et al. (2021). This interplay influences how models generalize, especially under distribution shifts.

### Mechanisms in Neural Networks

To illustrate, consider a digit recognition task in two distinct datasets:  
- **Colored MNIST**, where digit labels are correlated with colors.  
- **SVHN**, a real-world dataset of street-view house numbers.  

When training a Multi-Layer Perceptron (MLP) on Colored MNIST, the model learns both **digit recognition** and **color recognition** mechanisms. If these mechanisms could be **isolated**, the model could:  

- Disregard **color cues** when the distribution shifts, improving robustness.  
- Transfer learned **digit recognition** mechanisms to SVHN or other similar tasks.  
- Facilitate **counterfactual generations** by separating generative model components (e.g., background, object, color).  

While **modular generative modeling** approaches (e.g., Sauer et al., 2021) tackle similar challenges, they typically rely on **strict supervision**. Our research aims to achieve this **in an unsupervised manner**.

### Research Objectives

Our primary goal is to **disentangle and extract diverse mechanisms** embedded in neural networks. Specifically, we aim to:  

- Investigate how **Generalized Cross Entropy (GCE)** loss can help isolate the most easily learnable mechanism.  
- Develop **unsupervised methods** for extracting independent mechanisms from data.  
- Address **bias in multi-bias settings**, such as the "Whack-a-Mole Dilemma" (Li et al., 2023).  
- Improve **continual learning** by enhancing knowledge transfer across distribution shifts.  

### Potential Approaches

To achieve these objectives, we explore multiple strategies, including:  

1. **Mode Connectivity**: Functionally similar networks often reside in a single **low-loss basin**. By leveraging this property, we can decompose a model into independent mechanisms.  
2. **Architectural Constraints**: Structuring models to capture different mechanisms in **distinct network components**.  
3. **Training Dynamics**: Utilizing **learning trajectories** to isolate and understand different mechanisms.  

### Applications

These insights have significant implications in:  

- **Continual Learning**: Enabling **long-term knowledge retention** and adaptation.  
- **Compositional Generalization**: Enhancing generative models to extrapolate from limited data.  
- **Bias Mitigation**: Addressing multi-bias problems by disentangling **spurious correlations**.  

By leveraging these techniques, we aim to advance the understanding of neural network robustness and its role in **compositional generalization**.
