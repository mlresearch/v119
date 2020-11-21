---
title: 'Radioactive data: tracing through training'
booktitle: Proceedings of the 37th International Conference on Machine Learning
year: '2020'
pdf: http://proceedings.mlr.press/v119/sablayrolles20a/sablayrolles20a.pdf
url: http://proceedings.mlr.press/v119/sablayrolles20a.html
abstract: Data tracing determines whether particular data samples have been used to
  train a model. We propose a new technique, radioactive data, that makes imperceptible
  changes to these samples such that any model trained on them will bear an identifiable
  mark. Given a trained model, our technique detects the use of radioactive data and
  provides a level of confidence (p-value). Experiments on large-scale benchmarks
  (Imagenet), with standard architectures (Resnet-18, VGG-16, Densenet-121) and training
  procedures, show that we detect radioactive data with high confidence (p<0.0001)
  when only 1% of the data used to train a model is radioactive. Our radioactive mark
  is resilient to strong data augmentations and variations of the model architecture.
  As a result, it offers a much higher signal-to-noise ratio than data poisoning and
  backdoor methods.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: sablayrolles20a
month: 0
tex_title: 'Radioactive data: tracing through training'
firstpage: 8326
lastpage: 8335
page: 8326-8335
order: 8326
cycles: false
bibtex_author: Sablayrolles, Alexandre and Douze, Matthijs and Schmid, Cordelia and
  Jegou, Herve
author:
- given: Alexandre
  family: Sablayrolles
- given: Matthijs
  family: Douze
- given: Cordelia
  family: Schmid
- given: Herve
  family: Jegou
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
software: http://github.com/facebookresearch/radioactive_data
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v119/sablayrolles20a/sablayrolles20a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
