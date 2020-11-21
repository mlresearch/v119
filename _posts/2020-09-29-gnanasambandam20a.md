---
title: 'One Size Fits All: Can We Train One Denoiser for All Noise Levels?'
booktitle: Proceedings of the 37th International Conference on Machine Learning
year: '2020'
pdf: http://proceedings.mlr.press/v119/gnanasambandam20a/gnanasambandam20a.pdf
url: http://proceedings.mlr.press/v119/gnanasambandam20a.html
abstract: When training an estimator such as a neural network for tasks like image
  denoising, it is often preferred to train one estimator and apply it to all noise
  levels. The de facto training protocol to achieve this goal is to train the estimator
  with noisy samples whose noise levels are uniformly distributed across the range
  of interest. However, why should we allocate the samples uniformly? Can we have
  more training samples that are less noisy, and fewer samples that are more noisy?
  What is the optimal distribution? How do we obtain such a distribution? The goal
  of this paper is to address this training sample distribution problem from a minimax
  risk optimization perspective. We derive a dual ascent algorithm to determine the
  optimal sampling distribution of which the convergence is guaranteed as long as
  the set of admissible estimators is closed and convex. For estimators with non-convex
  admissible sets such as deep neural networks, our dual formulation converges to
  a solution of the convex relaxation. We discuss how the algorithm can be implemented
  in practice. We evaluate the algorithm on linear estimators and deep networks.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: gnanasambandam20a
month: 0
tex_title: 'One Size Fits All: Can We Train One Denoiser for All Noise Levels?'
firstpage: 3576
lastpage: 3586
page: 3576-3586
order: 3576
cycles: false
bibtex_author: Gnanasambandam, Abhiram and Chan, Stanley
author:
- given: Abhiram
  family: Gnanasambandam
- given: Stanley
  family: Chan
date: 2020-09-29
address: 
container-title: Proceedings of the 37th International Conference on Machine Learning
volume: '119'
genre: inproceedings
issued:
  date-parts:
  - 2020
  - 9
  - 29
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
