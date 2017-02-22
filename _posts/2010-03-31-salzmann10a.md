---
title: Factorized Orthogonal Latent Spaces
abstract: Existing approaches to multi-view learning are particularly effective when
  the views are either independent (i.e, multi-kernel approaches) or fully dependent
  (i.e., shared latent spaces). However, in real scenarios, these assumptions are
  almost never truly satisfied. Recently, two methods have attempted to tackle this
  problem by factorizing the information and learn separate latent spaces for modeling
  the shared (i.e., correlated) and private (i.e., independent) parts of the data.
  However, these approaches are very sensitive to parameters setting or initialization.
  In this paper we propose a robust approach to factorizing the latent space into
  shared and private spaces by introducing orthogonality constraints, which penalize
  redundant latent representations. Furthermore, unlike previous approaches, we simultaneously
  learn the structure and dimensionality of the latent spaces by relying on a regularizer
  that encourages the latent space of each data stream to be low dimensional. To demonstrate
  the benefits of our approach, we apply it to two existing shared latent space models
  that assume full dependence of the views, the sGPLVM and the sKIE, and show that
  our constraints improve the performance of these models on the task of pose estimation
  from monocular images.
pdf: "./salzmann10a/salzmann10a.pdf"
layout: inproceedings
key: salzmann10a
month: 0
firstpage: 701
lastpage: 708
origpdf: http://jmlr.org/proceedings/papers/v9/salzmann10a/salzmann10a.pdf
sections: 
authors:
- given: Mathieu
  family: Salzmann
- given: Carl Henrik
  family: Ek
- given: Raquel
  family: Urtasun
- given: Trevor
  family: Darrell
---
