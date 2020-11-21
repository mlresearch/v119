---
title: Combining Differentiable PDE Solvers and Graph Neural Networks for Fluid Flow
  Prediction
booktitle: Proceedings of the 37th International Conference on Machine Learning
year: '2020'
pdf: http://proceedings.mlr.press/v119/de-avila-belbute-peres20a/de-avila-belbute-peres20a.pdf
url: http://proceedings.mlr.press/v119/deavilabelbuteperes20a.html
abstract: Solving large complex partial differential equations (PDEs), such as those
  that arise in computational fluid dynamics (CFD), is a computationally expensive
  process. This has motivated the use of deep learning approaches to approximate the
  PDE solutions, yet the simulation results predicted from these approaches typically
  do not generalize well to truly novel scenarios. In this work, we develop a hybrid
  (graph) neural network that combines a traditional graph convolutional network with
  an embedded differentiable fluid dynamics simulator inside the network itself. By
  combining an actual CFD simulator (run on a much coarser resolution representation
  of the problem) with the graph network, we show that we can both generalize well
  to new situations and benefit from the substantial speedup of neural network CFD
  predictions, while also substantially outperforming the coarse CFD simulation alone.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: de-avila-belbute-peres20a
month: 0
tex_title: Combining Differentiable {PDE} Solvers and Graph Neural Networks for Fluid
  Flow Prediction
firstpage: 2402
lastpage: 2411
page: 2402-2411
order: 2402
cycles: false
bibtex_author: De Avila Belbute-Peres, Filipe and Economon, Thomas and Kolter, Zico
author:
- given: Filipe
  family: De Avila Belbute-Peres
- given: Thomas
  family: Economon
- given: Zico
  family: Kolter
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
software: https://github.com/locuslab/cfd-gcn
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v119/de-avila-belbute-peres20a/de-avila-belbute-peres20a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
