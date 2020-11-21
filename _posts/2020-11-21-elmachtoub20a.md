---
title: Decision Trees for Decision-Making under the Predict-then-Optimize Framework
booktitle: Proceedings of the 37th International Conference on Machine Learning
year: '2020'
pdf: http://proceedings.mlr.press/v119/elmachtoub20a/elmachtoub20a.pdf
url: http://proceedings.mlr.press/v119/elmachtoub20a.html
abstract: We consider the use of decision trees for decision-making problems under
  the predict-then-optimize framework. That is, we would like to first use a decision
  tree to predict unknown input parameters of an optimization problem, and then make
  decisions by solving the optimization problem using the predicted parameters. A
  natural loss function in this framework is to measure the suboptimality of the decisions
  induced by the predicted input parameters, as opposed to measuring loss using input
  parameter prediction error. This natural loss function is known in the literature
  as the Smart Predict-then-Optimize (SPO) loss, and we propose a tractable methodology
  called SPO Trees (SPOTs) for training decision trees under this loss. SPOTs benefit
  from the interpretability of decision trees, providing an interpretable segmentation
  of contextual features into groups with distinct optimal solutions to the optimization
  problem of interest. We conduct several numerical experiments on synthetic and real
  data including the prediction of travel times for shortest path problems and predicting
  click probabilities for news article recommendation. We demonstrate on these datasets
  that SPOTs simultaneously provide higher quality decisions and significantly lower
  model complexity than other machine learning approaches (e.g., CART) trained to
  minimize prediction error.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: elmachtoub20a
month: 0
tex_title: Decision Trees for Decision-Making under the Predict-then-Optimize Framework
firstpage: 2858
lastpage: 2867
page: 2858-2867
order: 2858
cycles: false
bibtex_author: Elmachtoub, Adam and Liang, Jason Cheuk Nam and Mcnellis, Ryan
author:
- given: Adam
  family: Elmachtoub
- given: Jason Cheuk Nam
  family: Liang
- given: Ryan
  family: Mcnellis
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
software: https://github.com/rtm2130/SPOTree
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v119/elmachtoub20a/elmachtoub20a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
