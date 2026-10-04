---
abstract: 'Matrix-parametrized models (MPMs) are widely used in machine learning (ML)
  applications. In large-scale ML problems, the parameter matrix of a MPM can grow
  at an unexpected rate, resulting in high communication and parameter synchronization
  costs. To address this issue, we offer two contributions: first, we develop a computation
  model for a large family of MPMs, which share the following property: the parameter
  update computed on each data sample is a rank-1 matrix, \ie the outer product of
  two “sufficient factors" (SFs). Second, we implement a decentralized, peer-to-peer
  system, Sufficient Factor Broadcasting (SFB), which broadcasts the SFs among worker
  machines, and reconstructs the update matrices locally at each worker. SFB takes
  advantage of small rank-1 matrix updates and efficient partial broadcasting strategies
  to dramatically improve communication efficiency. We propose a graph optimization
  based partial broadcasting scheme, which minimizes the delay of information dissemination
  under the constraint that each machine only communicates with a subset rather than
  all of machines. Furthermore, we provide theoretical analysis to show that SFB guarantees
  convergence of algorithms (under full broadcasting) without requiring a centralized
  synchronization mechanism. Experiments corroborate SFB’s efficiency on four MPMs.'
title: Lighter-Communication Distributed Machine Learning via Sufficient Factor Broadcasting
year: '2016'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: university16a
month: 0
tex_title: Lighter-Communication Distributed Machine Learning via Sufficient Factor
  Broadcasting
firstpage: 28
lastpage: 37
page: 28-37
order: 28
cycles: false
bibtex_author: University, Pengtao Xie Carnegie Mellon and University, Jin Kyu Kim
  Carnegie Mellon and University, Yi Zhou Syracuse and Ho, Qirong and Inc., Abhimanu
  Kumar Groupon and Yu, Yaoliang and University, Eric Xing Carnegie Mellon
author:
- given: Pengtao Xie Carnegie Mellon
  family: University
- given: Jin Kyu Kim Carnegie Mellon
  family: University
- given: Yi Zhou Syracuse
  family: University
- given: Qirong
  family: Ho
- given: Abhimanu Kumar Groupon
  family: Inc.
- given: Yaoliang
  family: Yu
- given: Eric Xing Carnegie Mellon
  family: University
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
pdf: https://raw.githubusercontent.com/mlresearch/r14/main/assets/university16a/university16a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
