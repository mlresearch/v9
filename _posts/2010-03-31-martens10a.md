---
title: Parallelizable Sampling of Markov Random Fields
abstract: Markov Random Fields (MRFs) are an important class of probabilistic models
  which are used for density estimation, classification, denoising, and for constructing
  Deep Belief Networks.  Every application of an MRF requires addressing its inference
  problem, which can be done using deterministic inference methods or using stochastic
  Markov Chain Monte Carlo methods.  In this paper we introduce a new Markov Chain
  transition operator that updates all the variables of a pairwise MRF in parallel
  by using auxiliary Gaussian variables. The proposed MCMC operator is extremely simple
  to implement and to parallelize. This is achieved by a formal equivalence result
  between arbitrary pairwise MRFs and a particular type of Restricted Boltzmann Machine.  This
  result also implies that the later can be learned in place of the former without
  any loss of modeling power, a possibility we explore in experiments.
pdf: "./martens10a/martens10a.pdf"
layout: inproceedings
key: martens10a
month: 0
firstpage: 517
lastpage: 524
origpdf: http://jmlr.org/proceedings/papers/v9/martens10a/martens10a.pdf
sections: 
authors:
- given: James
  family: Martens
- given: Ilya
  family: Sutskever
---
