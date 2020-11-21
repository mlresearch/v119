---
title: Decoupled Greedy Learning of CNNs
booktitle: Proceedings of the 37th International Conference on Machine Learning
year: '2020'
pdf: http://proceedings.mlr.press/v119/belilovsky20a/belilovsky20a.pdf
url: http://proceedings.mlr.press/v119/belilovsky20a.html
abstract: 'A commonly cited inefficiency of neural network training by back-propagation
  is the update locking problem: each layer must wait for the signal to propagate
  through the network before updating. In recent years multiple authors have considered
  alternatives that can alleviate this issue. In this context, we consider a simpler,
  but more effective, substitute that uses minimal feedback, which we call Decoupled
  Greedy Learning (DGL). It is based on a greedy relaxation of the joint training
  objective, recently shown to be effective in the context of Convolutional Neural
  Networks (CNNs) on large-scale image classification. We consider an optimization
  of this objective that permits us to decouple the layer training, allowing for layers
  or modules in networks to be trained with a potentially linear parallelization in
  layers. We show theoretically and empirically that this approach converges. Then,
  we empirically find that it can lead to better generalization than sequential greedy
  optimization and sometimes end-to-end back-propagation. We show an extension of
  this approach to asynchronous settings, where modules can operate with large communication
  delays, is possible with the use of a replay buffer. We demonstrate the effectiveness
  of DGL on the CIFAR-10 dataset against alternatives and on the large-scale ImageNet
  dataset.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: belilovsky20a
month: 0
tex_title: Decoupled Greedy Learning of {CNN}s
firstpage: 736
lastpage: 745
page: 736-745
order: 736
cycles: false
bibtex_author: Belilovsky, Eugene and Eickenberg, Michael and Oyallon, Edouard
author:
- given: Eugene
  family: Belilovsky
- given: Michael
  family: Eickenberg
- given: Edouard
  family: Oyallon
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
software: https://github.com/eugenium/DGL
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v119/belilovsky20a/belilovsky20a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
