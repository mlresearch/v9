---
title: Efficient Learning of Deep Boltzmann Machines
abstract: We present a new approximate inference algorithm for Deep Boltzmann Machines
  (DBM’s), a generative model with many layers of hidden variables. The algorithm
  learns a separate “recognition” model that is used to quickly initialize, in a single
  bottom-up pass, the values of the latent variables in all hidden layers. We show
  that using such a recognition model, followed by a combined top-down and bottom-up
  pass, it is possible to efficiently learn a good generative model of high-dimensional
  highly-structured sensory input. We show that the additional computations required
  by incorporating a top-down feedback plays a critical role in the performance of
  a DBM, both as a generative and discriminative model. Moreover, inference is only
  at most three times slower compared to the approximate inference in a Deep Belief
  Network (DBN), making large-scale learning of DBM’s practical. Finally, we demonstrate
  that the DBM’s trained using the proposed approximate inference algorithm perform
  well compared to DBN’s and SVM’s on the MNIST handwritten digit, OCR English letters,
  and NORB visual object recognition tasks.
pdf: http://jmlr.org/proceedings/papers/v9/salakhutdinov10a/salakhutdinov10a.pdf
layout: inproceedings
id: salakhutdinov10a
month: 0
firstpage: 693
lastpage: 700
page: 693-700
sections: 
author:
- given: Ruslan
  family: Salakhutdinov
- given: Hugo
  family: Larochelle
reponame: v9
date: 2010-03-31
address: Chia Laguna Resort, Sardinia, Italy
publisher: PMLR
container-title: Proceedings of the Thirteenth International Conference on Artificial
  Intelligence and Statistics
volume: '9'
genre: inproceedings
issued:
  date-parts:
  - 2010
  - 3
  - 31
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
