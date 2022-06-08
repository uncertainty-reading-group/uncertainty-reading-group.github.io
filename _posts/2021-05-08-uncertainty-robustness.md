---
layout: post
title: Evaluating Robustness of Predictive Uncertainty Estimation
subtitle: Are Dirichlet-based Models Reliable? - ICML 2021
cover-img: /assets/img/path.jpg
thumbnail-img: /assets/img/dbu-robustness.png
share-img: /assets/img/path.jpg
gh-repo: TUM-DAML/dbu-robustness
gh-badge: [star, fork, follow]
tags: [Uncertainty Estimation, Robustness]
comments: false
---

This page is about our paper

[**Evaluating Robustness of Predictive Uncertainty Estimation: Are Dirichlet-based Models Reliable?**](https://arxiv.org/pdf/2010.14986.pdf)

Anna-Kathrin Kopetzki*, Bertrand Charpentier*, Daniel Zügner, Sandhya Giri and Stephan Günnemann  
Published at the International Conference on Machine Learning (ICML) 2021

**Abstract**

Dirichlet-based uncertainty (DBU) models are a recent and promising class of uncertainty-awaremodels. DBU models predict the parameters of aDirichlet distribution to provide fast, high-quality uncertainty estimates alongside with class predictions. In this work, we present the first large-scale, in-depth study of the robustness of DBU models under adversarial attacks. Our results suggest that uncertainty estimates of DBU modelsare not robust w.r.t. three important tasks: (1) indicating correctly and wrongly classified samples; (2) detecting adversarial examples; and (3) distinguishing between in-distribution (ID) and out-of-distribution (OOD) data. Additionally, we explore the first approaches to make DBU mod-els more robust. While adversarial training has a minor effect, our median smoothing based approach significantly increases robustness of DBU models.

**Links**

[Paper](https://arxiv.org/pdf/2010.14986.pdf) | [Github](https://github.com/TUM-DAML/dbu-robustness)
