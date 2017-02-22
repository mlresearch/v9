---
title: The Feature Selection Path in Kernel Methods
abstract: The problem of automatic feature selection/weighting in kernel methods is
  examined. We work on a formulation that optimizes both the weights of features and
  the parameters of the kernel model simultaneously, using L_1 regularization for
  feature selection. Under quite general choices of kernels, we prove that there exists
  a unique regularization path for this problem, that runs from 0 to a stationary
  point of the non-regularized problem. We propose an ODE-based homotopy method to
  follow this trajectory. By following the path, our algorithm is able to automatically
  discard irrelevant features and to automatically go back and forth to avoid local
  optima. Experiments on synthetic and real datasets show that the method achieves
  low prediction error and is efficient in separating relevant from irrelevant features.
pdf: "./li10a/li10a.pdf"
layout: inproceedings
key: li10a
month: 0
firstpage: 445
lastpage: 452
origpdf: http://jmlr.org/proceedings/papers/v9/li10a/li10a.pdf
sections: 
authors:
- given: Fuxin
  family: Li
- given: Cristian
  family: Sminchisescu
---
