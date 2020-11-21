---
title: Enhancing Simple Models by Exploiting What They Already Know
booktitle: Proceedings of the 37th International Conference on Machine Learning
year: '2020'
pdf: http://proceedings.mlr.press/v119/dhurandhar20a/dhurandhar20a.pdf
url: http://proceedings.mlr.press/v119/dhurandhar20a.html
abstract: There has been recent interest in improving performance of simple models
  for multiple reasons such as interpretability, robust learning from small data,
  deployment in memory constrained settings as well as environmental considerations.
  In this paper, we propose a novel method SRatio that can utilize information from
  high performing complex models (viz. deep neural networks, boosted trees, random
  forests) to reweight a training dataset for a potentially low performing simple
  model of much lower complexity such as a decision tree or a shallow network enhancing
  its performance. Our method also leverages the per sample hardness estimate of the
  simple model which is not the case with the prior works which primarily consider
  the complex model’s confidences/predictions and is thus conceptually novel. Moreover,
  we generalize and formalize the concept of attaching probes to intermediate layers
  of a neural network to other commonly used classifiers and incorporate this into
  our method. The benefit of these contributions is witnessed in the experiments where
  on 6 UCI datasets and CIFAR-10 we outperform competitors in a majority (16 out of
  27) of the cases and tie for best performance in the remaining cases. In fact, in
  a couple of cases, we even approach the complex model’s performance. We also conduct
  further experiments to validate assertions and intuitively understand why our method
  works. Theoretically, we motivate our approach by showing that the weighted loss
  minimized by simple models using our weighting upper bounds the loss of the complex
  model.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: dhurandhar20a
month: 0
tex_title: Enhancing Simple Models by Exploiting What They Already Know
firstpage: 2525
lastpage: 2534
page: 2525-2534
order: 2525
cycles: false
bibtex_author: Dhurandhar, Amit and Shanmugam, Karthikeyan and Luss, Ronny
author:
- given: Amit
  family: Dhurandhar
- given: Karthikeyan
  family: Shanmugam
- given: Ronny
  family: Luss
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
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v119/dhurandhar20a/dhurandhar20a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
