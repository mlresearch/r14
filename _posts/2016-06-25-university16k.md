---
abstract: Probabilistic mixture models are among the most important clustering methods.
  These models assume that the feature vectors of the samples can be described by
  a mixture of several components. Each of these components follows a distribution
  of a certain form. In recent years, there has been an increasing amount of interest
  and work in similarity-matrix-based methods. Rather than considering the feature
  vectors, these methods learn patterns by observing the similarity matrix that describes
  the pairwise relative similarity between each pair of samples. However, there are
  limited works in probabilistic mixture model for clustering with input data in the
  form of a similarity matrix. Observing this, we propose a generative model for clustering
  that finds the block-diagonal structure of the similarity matrix to ensure that
  the samples within the same cluster (diagonal block) are similar while the samples
  from different clusters (off-diagonal block) are less similar. In this model, we
  assume the elements in the similarity matrix follow one of beta distributions, depending
  on whether the element belongs to one of the diagonal blocks or to off-diagonal
  blocks. The assignment of the element to a block is determined by the cluster indicators
  that follow categorical distributions. Experiments on both synthetic and real data
  show that the performance of the proposed method is comparable to the state-of-the-art
  methods.
title: A Generative Block-Diagonal Model for Clustering
year: '2016'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: university16k
month: 0
tex_title: A Generative Block-Diagonal Model for Clustering
firstpage: 415
lastpage: 424
page: 415-424
order: 415
cycles: false
bibtex_author: University, Junxiang Chen Northeastern and Dy, Jennifer
author:
- given: Junxiang Chen Northeastern
  family: University
- given: Jennifer
  family: Dy
date: 2016-06-25
note: Reissued by PMLR on 04 October 2026.
address:
container-title: Proceedings of the 32nd Conference on Uncertainty in Artificial Intelligence
volume: R14
genre: inproceedings
issued:
  date-parts:
  - 2016
  - 6
  - 25
pdf: https://raw.githubusercontent.com/mlresearch/r14/main/assets/university16k/university16k.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
