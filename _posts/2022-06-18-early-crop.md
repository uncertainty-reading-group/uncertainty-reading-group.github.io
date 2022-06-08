---
layout: post
title: Winning the Lottery Ahead of Time: Efficient Early Network Pruning
subtitle: ICML 2022
cover-img: /assets/img/path.jpg
thumbnail-img: /assets/img/early-crop.png
share-img: /assets/img/path.jpg
gh-repo: 
gh-badge: [star, fork, follow]
tags: [Hierarchical Inference]
comment: false
---

This page is about our paper

[**Winning the Lottery Ahead of Time: Efficient Early Network Pruning**]()

by John Rachwan, Daniel Zügner, Bertrand Charpentier, Simon Geisler, Morgane Ayle and Stephan Günnemann
Published at the International Conference on Machine Learning (ICML), 2022

**Abstract**

Pruning, the task of sparsifying deep neural networks, received increasing attention recently. Although state-of-the-art pruning methods extract highly sparse models, they neglect two main challenges: (1) the process of finding these sparse models is often very expensive; (2) unstructured pruning does not provide benefits in terms of GPU memory, training time, or carbon emissions. We propose Early Compression via Gradient Flow Preservation (EarlyCroP), which efficiently extracts state-of-the-art sparse models before or early in training addressing challenge (1), and can be applied in a structured manner addressing challenge (2). This enables us to train sparse networks on commodity GPUs whose dense versions would be too large, thereby saving costs and reducing hardware requirements. We empirically compare EarlyCroP against a rich set of baselines and cover classification as well as regression for benchmarks of computer vision, natural language processing, and reinforcement learning, where our method leads to accuracy comparable to dense training while outperforming pruning baselines.

**Links**

[Paper]() | [Github]()
