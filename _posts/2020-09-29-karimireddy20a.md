---
title: 'SCAFFOLD: Stochastic Controlled Averaging for Federated Learning'
booktitle: Proceedings of the 37th International Conference on Machine Learning
year: '2020'
pdf: http://proceedings.mlr.press/v119/karimireddy20a/karimireddy20a.pdf
url: http://proceedings.mlr.press/v119/karimireddy20a.html
abstract: Federated learning is a key scenario in modern large-scale machine learning
  where the data remains distributed over a large number of clients and the task is
  to learn a centralized model without transmitting the client data. The standard
  optimization algorithm used in this setting is Federated Averaging (FedAvg) due
  to its low communication cost. We obtain a tight characterization of the convergence
  of FedAvg and prove that heterogeneity (non-iid-ness) in the client’s data results
  in a ‘drift’ in the local updates resulting in poor performance. As a solution,
  we propose a new algorithm (SCAFFOLD) which uses control variates (variance reduction)
  to correct for the ‘client drift’. We prove that SCAFFOLD requires significantly
  fewer communication rounds and is not affected by data heterogeneity or client sampling.
  Further, we show that (for quadratics) SCAFFOLD can take advantage of similarity
  in the client’s data yielding even faster convergence. The latter is the first result
  to quantify the usefulness of local-steps in distributed optimization.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: karimireddy20a
month: 0
tex_title: "{SCAFFOLD}: Stochastic Controlled Averaging for Federated Learning"
firstpage: 5132
lastpage: 5143
page: 5132-5143
order: 5132
cycles: false
bibtex_author: Karimireddy, Sai Praneeth and Kale, Satyen and Mohri, Mehryar and Reddi,
  Sashank and Stich, Sebastian and Suresh, Ananda Theertha
author:
- given: Sai Praneeth
  family: Karimireddy
- given: Satyen
  family: Kale
- given: Mehryar
  family: Mohri
- given: Sashank
  family: Reddi
- given: Sebastian
  family: Stich
- given: Ananda Theertha
  family: Suresh
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
  link: http://proceedings.mlr.press/v119/karimireddy20a/karimireddy20a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
