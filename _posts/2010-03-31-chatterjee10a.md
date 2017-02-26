---
title: Why are DBNs sparse?
abstract: Real stochastic processes operate in continuous time and can be modeled
  by sets of stochastic differential equations.  On the other hand, several popular
  model families, including hidden Markov models and dynamic Bayesian networks (DBNs),
  use discrete time steps.  This paper explores methods for converting DBNs with infinitesimal
  time steps into DBNs with finite time steps, to enable efficient simulation and
  filtering over long periods.  An exact conversion—summing out all intervening time
  slices between two steps—results in a completely connected DBN, yet nearly all human-constructed
  DBNs are sparse.  We show how this sparsity arises from well-founded approximations
  resulting from differences among the natural time scales of the variables in the
  DBN. We define an automated procedure for constructing a provably accurate, approximate
  DBN model for any desired time step. We illustrate the method by generating a series
  of approximations to a simple pH model for the human body, demonstrating speedups
  of several orders of magnitude compared to the original model.
pdf: http://proceedings.mlr.press/v9/chatterjee10a/chatterjee10a.pdf
layout: inproceedings
series: Proceedings of Machine Learning Research
id: chatterjee10a
month: 0
tex_title: Why are DBNs sparse?
firstpage: 81
lastpage: 88
page: 81-88
order: 81
cycles: false
author:
- given: Shaunak
  family: Chatterjee
- given: Stuart
  family: Russell
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
