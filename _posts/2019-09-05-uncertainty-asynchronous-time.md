---
layout: post
title: Uncertainty on Asynchronous Time Event Prediction
subtitle: ICLR 2022
cover-img: /assets/img/path.jpg
thumbnail-img: /assets/img/asynchronous-uncertainty-2.png
share-img: /assets/img/path.jpg
gh-repo: sharpenb/Uncertainty-Event-Prediction
gh-badge: [star, fork, follow]
tags: [Uncertainty Estimation, Sequential Data]
comments: false
---

This page is about our paper

[**Uncertainty on Asynchronous Time Event Prediction**](https://papers.nips.cc/paper/2019/file/78efce208a5242729d222e7e6e3e565e-Paper.pdf)

by Marin Bilos\*, Bertrand Charpentier\* and Stephan Günnemann  
Published at the Neural Information Processing Systems (Neurips) 2019, (Spotlight)

**Abstract**

Asynchronous event sequences are the basis of many applications throughout different industries. In this work, we tackle the task of predicting the next event (given a history), and how this prediction changes with the passage of time. Since at some time points (e.g. predictions far into the future) we might not be able to predict anything with confidence, capturing uncertainty in the predictions is crucial. We present two new architectures, WGP-LN and FD-Dir, modelling the evolution of the distribution on the probability simplex with time-dependent logistic normal and Dirichlet distributions. In both cases, the combination of RNNs with either Gaussian process or function decomposition allows to express rich temporal evolution of the distribution parameters, and naturally captures uncertainty. Experiments on class prediction, time prediction and anomaly detection demonstrate the high performances of our models on various datasets compared to other approaches.

**Links**

[Paper](https://papers.nips.cc/paper/2019/file/78efce208a5242729d222e7e6e3e565e-Paper.pdf) | [Video](https://www.youtube.com/watch?v=qMtpK0ECD8c) | [Github](https://github.com/sharpenb/Uncertainty-Event-Prediction)
