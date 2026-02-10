---
title: "Outcome-Based RL Provably Leads Transformers to Reason, but Only With the Right Data"
collection: publications
category: preprints
permalink:
excerpt:
date: 2026-01-21
venue: 'arXiv preprint (submitted to International Conference on Machine Learning (ICML))'
slidesurl:
paperurl: 'https://arxiv.org/abs/2601.15158'
citation:
---

Transformers trained via Reinforcement Learning (RL) with outcome-based supervision can spontaneously develop the ability to generate intermediate reasoning steps (Chain-of-Thought). Yet the mechanism by which sparse rewards drive gradient descent to discover such systematic reasoning remains poorly understood. We address this by analyzing the gradient flow dynamics of single-layer Transformers on a synthetic graph traversal task that cannot be solved without Chain-of-Thought (CoT) but admits a simple iterative solution. We prove that despite training solely on final-answer correctness, gradient flow drives the model to converge to a structured, interpretable algorithm that iteratively traverses the graph vertex-by-vertex. We characterize the distributional properties required for this emergence, identifying the critical role of "simple examples": instances requiring fewer reasoning steps. When the training distribution places sufficient mass on these simpler instances, the model learns a generalizable traversal strategy that extrapolates to longer chains; when this mass vanishes, gradient-based learning becomes infeasible. We corroborate our theoretical results through experiments on synthetic data and with real-world language models on mathematical reasoning tasks, validating that our theoretical findings carry over to practical settings.
