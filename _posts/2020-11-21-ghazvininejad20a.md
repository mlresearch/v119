---
title: Aligned Cross Entropy for Non-Autoregressive Machine Translation
booktitle: Proceedings of the 37th International Conference on Machine Learning
year: '2020'
pdf: http://proceedings.mlr.press/v119/ghazvininejad20a/ghazvininejad20a.pdf
url: http://proceedings.mlr.press/v119/ghazvininejad20a.html
abstract: Non-autoregressive machine translation models significantly speed up decoding
  by allowing for parallel prediction of the entire target sequence. However, modeling
  word order is more challenging due to the lack of autoregressive factors in the
  model. This difficultly is compounded during training with cross entropy loss, which
  can highly penalize small shifts in word order. In this paper, we propose aligned
  cross entropy (AXE) as an alternative loss function for training of non-autoregressive
  models. AXE uses a differentiable dynamic program to assign loss based on the best
  possible monotonic alignment between target tokens and model predictions. AXE-based
  training of conditional masked language models (CMLMs) substantially improves performance
  on major WMT benchmarks, while setting a new state of the art for non-autoregressive
  models.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: ghazvininejad20a
month: 0
tex_title: Aligned Cross Entropy for Non-Autoregressive Machine Translation
firstpage: 3515
lastpage: 3523
page: 3515-3523
order: 3515
cycles: false
bibtex_author: Ghazvininejad, Marjan and Karpukhin, Vladimir and Zettlemoyer, Luke
  and Levy, Omer
author:
- given: Marjan
  family: Ghazvininejad
- given: Vladimir
  family: Karpukhin
- given: Luke
  family: Zettlemoyer
- given: Omer
  family: Levy
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
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
