---
title: 'Transformers are RNNs: Fast Autoregressive Transformers with Linear Attention'
booktitle: Proceedings of the 37th International Conference on Machine Learning
year: '2020'
pdf: http://proceedings.mlr.press/v119/katharopoulos20a/katharopoulos20a.pdf
url: http://proceedings.mlr.press/v119/katharopoulos20a.html
abstract: Transformers achieve remarkable performance in several tasks but due to
  their quadratic complexity, with respect to the input’s length, they are prohibitively
  slow for very long sequences. To address this limitation, we express the self-attention
  as a linear dot-product of kernel feature maps and make use of the associativity
  property of matrix products to reduce the complexity from $\bigO{N^2}$ to $\bigO{N}$,
  where $N$ is the sequence length. We show that this formulation permits an iterative
  implementation that dramatically accelerates autoregressive transformers and reveals
  their relationship to recurrent neural networks. Our \emph{Linear Transformers}
  achieve similar performance to vanilla Transformers and they are up to 4000x faster
  on autoregressive prediction of very long sequences.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: katharopoulos20a
month: 0
tex_title: 'Transformers are {RNN}s: Fast Autoregressive Transformers with Linear
  Attention'
firstpage: 5156
lastpage: 5165
page: 5156-5165
order: 5156
cycles: false
bibtex_author: Katharopoulos, Angelos and Vyas, Apoorv and Pappas, Nikolaos and Fleuret,
  Fran{\c{c}}ois
author:
- given: Angelos
  family: Katharopoulos
- given: Apoorv
  family: Vyas
- given: Nikolaos
  family: Pappas
- given: François
  family: Fleuret
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
software: https://github.com/idiap/fast-transformers
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v119/katharopoulos20a/katharopoulos20a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
