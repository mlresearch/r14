---
abstract: We consider \textit{anytime} linear prediction in the common machine learning
  setting wherefeatures are in groups that have costs. We achieve anytime or interruptible
  predictions by sequencing computation of feature groups andreporting results using
  the computed features at interruption. We extend Orthogonal Matching Pursuit (OMP)
  and Forward Regression (FR) to learn the sequencing greedily under this group setting
  with costs. We theoretically guarantee that our algorithms achieve near-optimal
  linear predictions at each budget when a feature group is chosen. With a novel analysis
  of OMP, we improve its theoretical bound to the same strength as that of FR. In
  addition, we develop a novel algorithm that consumes cost $4B$ to approximate the
  optimal performance of \textit{any} cost $B$, and prove that with cost less than
  $4B$, such an approximation is impossible. To our knowledge, these are the first
  anytime bounds at \textit{all} budgets. We experiment our algorithms on two real-world
  data-sets and evaluate them in terms of anytime linear prediction performance against
  cost-weighted Group Lasso, and alternative greedy algorithms.
title: Efficient Feature Group Sequencing for Anytime Linear Prediction
year: '2016'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: university16f
month: 0
tex_title: Efficient Feature Group Sequencing for Anytime Linear Prediction
firstpage: 246
lastpage: 255
page: 246-255
order: 246
cycles: false
bibtex_author: University, Hanzhang Hu Carnegie Mellon and Grubb, Alexander and Bagnell,
  J. Andrew and Hebert, Martial
author:
- given: Hanzhang Hu Carnegie Mellon
  family: University
- given: Alexander
  family: Grubb
- given: J. Andrew
  family: Bagnell
- given: Martial
  family: Hebert
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
pdf: https://raw.githubusercontent.com/mlresearch/r14/main/assets/university16f/university16f.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
