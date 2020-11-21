---
title: Convolutional dictionary learning based auto-encoders for natural exponential-family
  distributions
booktitle: Proceedings of the 37th International Conference on Machine Learning
year: '2020'
pdf: http://proceedings.mlr.press/v119/tolooshams20a/tolooshams20a.pdf
url: http://proceedings.mlr.press/v119/tolooshams20a.html
abstract: We introduce a class of auto-encoder neural networks tailored to data from
  the natural exponential family (e.g., count data). The architectures are inspired
  by the problem of learning the filters in a convolutional generative model with
  sparsity constraints, often referred to as convolutional dictionary learning (CDL).
  Our work is the first to combine ideas from convolutional generative models and
  deep learning for data that are naturally modeled with a non-Gaussian distribution
  (e.g., binomial and Poisson). This perspective provides us with a scalable and flexible
  framework that can be re-purposed for a wide range of tasks and assumptions on the
  generative model. Specifically, the iterative optimization procedure for solving
  CDL, an unsupervised task, is mapped to an unfolded and constrained neural network,
  with iterative adjustments to the inputs to account for the generative distribution.
  We also show that the framework can easily be extended for discriminative training,
  appropriate for a supervised task. We 1) demonstrate that fitting the generative
  model to learn, in an unsupervised fashion, the latent stimulus that underlies neural
  spiking data leads to better goodness-of-fit compared to other baselines, 2) show
  competitive performance compared to state-of-the-art algorithms for supervised Poisson
  image denoising, with significantly fewer parameters, and 3) characterize the gradient
  dynamics of the shallow binomial auto-encoder.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: tolooshams20a
month: 0
tex_title: Convolutional dictionary learning based auto-encoders for natural exponential-family
  distributions
firstpage: 9493
lastpage: 9503
page: 9493-9503
order: 9493
cycles: false
bibtex_author: Tolooshams, Bahareh and Song, Andrew and Temereanca, Simona and Ba,
  Demba
author:
- given: Bahareh
  family: Tolooshams
- given: Andrew
  family: Song
- given: Simona
  family: Temereanca
- given: Demba
  family: Ba
date: 2020-11-21
address: 
container-title: Proceedings of the 37th International Conference on Machine Learning
volume: '119'
genre: inproceedings
issued:
  date-parts:
  - 2020
  - 11
  - 21
software: https://github.com/btolooshams/dea
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v119/tolooshams20a/tolooshams20a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
