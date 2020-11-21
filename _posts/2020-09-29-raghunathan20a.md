---
title: Understanding and Mitigating the Tradeoff between Robustness and Accuracy
booktitle: Proceedings of the 37th International Conference on Machine Learning
year: '2020'
pdf: http://proceedings.mlr.press/v119/raghunathan20a/raghunathan20a.pdf
url: http://proceedings.mlr.press/v119/raghunathan20a.html
abstract: Adversarial training augments the training set with perturbations to improve
  the robust error (over worst-case perturbations), but it often leads to an increase
  in the standard error (on unperturbed test inputs). Previous explanations for this
  tradeoff rely on the assumption that no predictor in the hypothesis class has low
  standard and robust error. In this work, we precisely characterize the effect of
  augmentation on the standard error in linear regression when the optimal linear
  predictor has zero standard and robust error. In particular, we show that the standard
  error could increase even when the augmented perturbations have noiseless observations
  from the optimal linear predictor. We then prove that the recently proposed robust
  self-training (RST) estimator improves robust error without sacrificing standard
  error for noiseless linear regression. Empirically, for neural networks, we find
  that RST with different adversarial training methods improves both standard and
  robust error for random and adversarial rotations and adversarial l_infty perturbations
  in CIFAR-10.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: raghunathan20a
month: 0
tex_title: Understanding and Mitigating the Tradeoff between Robustness and Accuracy
firstpage: 7909
lastpage: 7919
page: 7909-7919
order: 7909
cycles: false
bibtex_author: Raghunathan, Aditi and Xie, Sang Michael and Yang, Fanny and Duchi,
  John and Liang, Percy
author:
- given: Aditi
  family: Raghunathan
- given: Sang Michael
  family: Xie
- given: Fanny
  family: Yang
- given: John
  family: Duchi
- given: Percy
  family: Liang
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
software: https://github.com/p-lambda/robust_tradeoff
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v119/raghunathan20a/raghunathan20a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
