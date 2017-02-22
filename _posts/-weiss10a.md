---
title: Structured Prediction Cascades
abstract: 'Structured prediction tasks pose a fundamental trade-off between the need
  for model complexity to increase predictive power and the limited computational
  resources for inference in the exponentially-sized output spaces such models require.
  We formulate and develop structured prediction cascades: a sequence of increasingly
  complex models that progressively filter the space of possible outputs. We represent
  an exponentially large set of filtered outputs using max marginals and propose a
  novel convex loss function that balances filtering error with filtering efficiency.
  We provide generalization bounds for these loss functions and evaluate our approach
  on handwriting recognition and part-of-speech tagging. We find that the learned
  cascades are capable of reducing the complexity of inference by up to five orders
  of magnitude, enabling the use of models which incorporate higher order features
  and yield higher accuracy.'
pdf: "./weiss10a/weiss10a.pdf"
layout: inproceedings
key: weiss10a
month: 0
firstpage: 916
lastpage: 923
origpdf: http://jmlr.org/proceedings/papers/v9/weiss10a/weiss10a.pdf
sections: 
authors:
- given: David
  family: Weiss
- given: Benjamin
  family: Taskar
---
