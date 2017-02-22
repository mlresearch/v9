---
title: Sequential Monte Carlo Samplers for Dirichlet Process Mixtures
abstract: In this paper, we develop a novel online algorithm based on the Sequential
  Monte Carlo(SMC) samplers framework for posterior inference in Dirichlet Process
  Mixtures (DPM). Our method generalizes  many sequential importance sampling approaches.
  It provides a computationally efficient improvement to particle filtering that is
  less prone to getting stuck in isolated modes. The proposed method is a particular
  SMC sampler that enables us to design sophisticated clustering update schemes, such
  as updating past trajectories of the particles in light of recent observations,
  and still ensures convergence to the true DPM target distribution asymptotically.  Performance
  has been evaluated in a Bayesian Infinite Gaussian mixture density estimation problem
  and it is shown that the proposed algorithm outperforms conventional Monte Carlo
  approaches in terms of estimation variance and average log-marginal likelihood.
pdf: "./ulker10a/ulker10a.pdf"
layout: inproceedings
key: ulker10a
month: 0
firstpage: 876
lastpage: 883
origpdf: http://jmlr.org/proceedings/papers/v9/ulker10a/ulker10a.pdf
sections: 
authors:
- given: Yener
  family: Ulker
- given: Bilge
  family: Günsel
- given: Taylan
  family: Cemgil
---
