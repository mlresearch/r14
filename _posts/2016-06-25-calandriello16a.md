---
abstract: Large-scale kernel ridge regression (KRR) is limited by the need to store
  a large kernel matrix Kt. To avoid storing the entire matrix Kt, Nystro?m methods
  subsample a subset of columns of the kernel matrix, and efficiently find an approximate
  KRR solution on the reconstructed Kt . The chosen subsampling distribution in turn
  affects the statistical and computational tradeoffs. For KRR problems, [15, 1] show
  that a sampling distribution proportional to the ridge leverage scores (RLSs) provides
  strong reconstruction guarantees for Kt. While exact RLSs are as difficult to compute
  as a KRR solution, we may be able to approximate them well enough. In this paper,
  we study KRR problems in a sequential setting and introduce the INK-ESTIMATE algorithm,
  that incrementally computes the RLSs estimates. INK-ESTIMATE maintains a small sketch
  of Kt, that at each step is used to compute an intermediate estimate of the RLSs.
  First, our sketch update does not require access to previously seen columns, and
  therefore a single pass over the kernel matrix is sufficient. Second, the algorithm
  requires a fixed, small space budget to run dependent only on the effective dimension
  of the kernel matrix. Finally, our sketch provides strong approximation guarantees
  on the distance ?Kt?Kt?2 , and on the statistical risk of the approximate KRR solution
  at any time, because all our guarantees hold at any intermediate step.
title: Analysis of Nyström method with sequential ridge leverage scores
year: '2016'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: calandriello16a
month: 0
tex_title: Analysis of Nystr{ö}m method with sequential ridge leverage scores
firstpage: 712
lastpage: 721
page: 712-721
order: 712
cycles: false
bibtex_author: Calandriello, Daniele and Lazaric, Alessandro and Valko, Michal
author:
- given: Daniele
  family: Calandriello
- given: Alessandro
  family: Lazaric
- given: Michal
  family: Valko
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
pdf: https://raw.githubusercontent.com/mlresearch/r14/main/assets/calandriello16a/calandriello16a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
