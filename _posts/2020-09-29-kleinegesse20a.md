---
title: Bayesian Experimental Design for Implicit Models by Mutual Information Neural
  Estimation
booktitle: Proceedings of the 37th International Conference on Machine Learning
year: '2020'
pdf: http://proceedings.mlr.press/v119/kleinegesse20a/kleinegesse20a.pdf
url: http://proceedings.mlr.press/v119/kleinegesse20a.html
abstract: Implicit stochastic models, where the data-generation distribution is intractable
  but sampling is possible, are ubiquitous in the natural sciences. The models typically
  have free parameters that need to be inferred from data collected in scientific
  experiments. A fundamental question is how to design the experiments so that the
  collected data are most useful. The field of Bayesian experimental design advocates
  that, ideally, we should choose designs that maximise the mutual information (MI)
  between the data and the parameters. For implicit models, however, this approach
  is severely hampered by the high computational cost of computing posteriors and
  maximising MI, in particular when we have more than a handful of design variables
  to optimise. In this paper, we propose a new approach to Bayesian experimental design
  for implicit models that leverages recent advances in neural MI estimation to deal
  with these issues. We show that training a neural network to maximise a lower bound
  on MI allows us to jointly determine the optimal design and the posterior. Simulation
  studies illustrate that this gracefully extends Bayesian experimental design for
  implicit models to higher design dimensions.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: kleinegesse20a
month: 0
tex_title: "{B}ayesian Experimental Design for Implicit Models by Mutual Information
  Neural Estimation"
firstpage: 5316
lastpage: 5326
page: 5316-5326
order: 5316
cycles: false
bibtex_author: Kleinegesse, Steven and Gutmann, Michael U.
author:
- given: Steven
  family: Kleinegesse
- given: Michael U.
  family: Gutmann
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
software: https://github.com/stevenkleinegesse/minebed
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v119/kleinegesse20a/kleinegesse20a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
