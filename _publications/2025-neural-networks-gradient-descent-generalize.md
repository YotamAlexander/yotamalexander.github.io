---
title: "Do Neural Networks Need Gradient Descent to Generalize? A Theoretical Study"
collection: publications
category: conferences
permalink:
excerpt:
date: 2025-12-02
venue: 'Conference on Neural Information Processing Systems (NeurIPS)'
slidesurl:
paperurl: 'https://arxiv.org/abs/2506.03931'
citation:
---

Conventional wisdom attributes the mysterious generalization abilities of overparameterized neural networks to gradient descent (and its variants). The recent volume hypothesis challenges this view: it posits that these generalization abilities persist even when gradient descent is replaced by Guess & Check (G&C), i.e., by drawing weight settings until one that fits the training data is found. The validity of the volume hypothesis for wide and deep neural networks remains an open question. In this paper, we theoretically investigate this question for matrix factorization (with linear and non-linear activation)--a common testbed in neural network theory. We first prove that generalization under G&C deteriorates with increasing width, establishing what is, to our knowledge, the first case where G&C is provably inferior to gradient descent. Conversely, we prove that generalization under G&C improves with increasing depth, revealing a stark contrast between wide and deep networks, which we further validate empirically. These findings suggest that even in simple settings, there may not be a simple answer to the question of whether neural networks need gradient descent to generalize well.
