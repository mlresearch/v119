---
title: Randomized Block-Diagonal Preconditioning for Parallel Learning
booktitle: Proceedings of the 37th International Conference on Machine Learning
year: '2020'
pdf: http://proceedings.mlr.press/v119/mendler-dunner20a/mendler-dunner20a.pdf
url: !binary |-
  aHR0cDovL3Byb2NlZWRpbmdzLm1sci5wcmVzcy92MTE5L21lbmRsZXJkw7xubmVyMjBhLmh0bWw=
abstract: We study preconditioned gradient-based optimization methods where the preconditioning
  matrix has block-diagonal form. Such a structural constraint comes with the advantage
  that the update computation can be parallelized across multiple independent tasks.
  Our main contribution is to demonstrate that the convergence of these methods can
  significantly be improved by a randomization technique which corresponds to repartitioning
  coordinates across tasks during the optimization procedure. We provide a theoretical
  analysis that accurately characterizes the expected convergence gains of repartitioning
  and validate our findings empirically on various traditional machine learning tasks.
  From an implementation perspective, block-separable models are well suited for parallelization
  and, when shared memory is available, randomization can be implemented on top of
  existing methods very efficiently to improve convergence.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: mendler-dunner20a
month: 0
tex_title: Randomized Block-Diagonal Preconditioning for Parallel Learning
firstpage: 6841
lastpage: 6851
page: 6841-6851
order: 6841
cycles: false
bibtex_author: Mendler-D{\"u}nner, Celestine and Lucchi, Aurelien
author:
- given: Celestine
  family: Mendler-Dünner
- given: Aurelien
  family: Lucchi
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
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v119/mendler-dunner20a/mendler-dunner20a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
