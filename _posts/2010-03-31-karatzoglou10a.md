---
title: Collaborative Filtering on a Budget
abstract: Matrix factorization is a successful technique for building   collaborative
  filtering systems. While it works well on a large   range of problems, it is also
  known for requiring significant   amounts of storage for each user or item to be
  added to the   database.  This is a problem whenever the collaborative filtering   task
  is larger than the medium-sized Netflix Prize data.    In this paper, we propose
  a new model for representing and   compressing matrix factors via hashing.  This
  allows for   essentially unbounded storage (at a graceful storage / performance   trade-off)
  for users and items to be represented in a pre-defined   memory footprint.  It allows
  us to scale recommender systems to very   large numbers of users or conversely,
  obtain very good performance   even for tiny models (e.g. 400kB of data suffice
  for a   representation of the EachMovie problem).    We provide both experimental
  results and approximation bounds for   our compressed representation and we show
  how this approach can be   extended to multipartite problems.
pdf: http://proceedings.mlr.press/v9/karatzoglou10a/karatzoglou10a.pdf
layout: inproceedings
id: karatzoglou10a
month: 0
firstpage: 389
lastpage: 396
page: 389-396
sections: 
author:
- given: Alexandros
  family: Karatzoglou
- given: Alex
  family: Smola
- given: Markus
  family: Weimer
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
