---
title: Reducing Label Complexity by Learning From Bags
abstract: We consider a supervised learning setting in which the main cost of learning
  is the number of training labels and one can obtain a single label for a bag of
  examples, indicating only if a positive example exists in the bag, as in Multi-Instance
  Learning. We thus propose to create a training sample of bags, and to use the obtained
  labels to learn to classify individual examples. We provide a theoretical analysis
  showing how to select the bag size as a function of the problem parameters, and
  prove that if the original labels are distributed unevenly, the number of required
  labels drops considerably when learning from bags. We demonstrate that finding a
  low-error separating hyperplane from bags is feasible in this setting using a simple
  iterative procedure similar to latent SVM. Experiments on synthetic and real data
  sets demonstrate the success of the approach.
pdf: "./sabato10a/sabato10a.pdf"
layout: inproceedings
key: sabato10a
month: 0
firstpage: 685
lastpage: 692
origpdf: http://jmlr.org/proceedings/papers/v9/sabato10a/sabato10a.pdf
sections: 
authors:
- given: Sivan
  family: Sabato
- given: Nathan
  family: Srebro
- given: Naftali
  family: Tishby
---
