---
title: Improving generalization by controlling label-noise information in neural network
  weights
booktitle: Proceedings of the 37th International Conference on Machine Learning
year: '2020'
pdf: http://proceedings.mlr.press/v119/harutyunyan20a/harutyunyan20a.pdf
url: http://proceedings.mlr.press/v119/harutyunyan20a.html
abstract: In the presence of noisy or incorrect labels, neural networks have the undesirable
  tendency to memorize information about the noise. Standard regularization techniques
  such as dropout, weight decay or data augmentation sometimes help, but do not prevent
  this behavior. If one considers neural network weights as random variables that
  depend on the data and stochasticity of training, the amount of memorized information
  can be quantified with the Shannon mutual information between weights and the vector
  of all training labels given inputs, $I(w; \mathbf{y} \mid \mathbf{x})$. We show
  that for any training algorithm, low values of this term correspond to reduction
  in memorization of label-noise and better generalization bounds. To obtain these
  low values, we propose training algorithms that employ an auxiliary network that
  predicts gradients in the final layers of a classifier without accessing labels.
  We illustrate the effectiveness of our approach on versions of MNIST, CIFAR-10,
  and CIFAR-100 corrupted with various noise models, and on a large-scale dataset
  Clothing1M that has noisy labels.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: harutyunyan20a
month: 0
tex_title: Improving generalization by controlling label-noise information in neural
  network weights
firstpage: 4071
lastpage: 4081
page: 4071-4081
order: 4071
cycles: false
bibtex_author: Harutyunyan, Hrayr and Reing, Kyle and Steeg, Greg Ver and Galstyan,
  Aram
author:
- given: Hrayr
  family: Harutyunyan
- given: Kyle
  family: Reing
- given: Greg Ver
  family: Steeg
- given: Aram
  family: Galstyan
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
  link: http://proceedings.mlr.press/v119/harutyunyan20a/harutyunyan20a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
