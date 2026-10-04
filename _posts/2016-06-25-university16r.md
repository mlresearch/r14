---
abstract: Lossy compression fundamentally involves a decision about what is relevant
  and what is not. The information bottleneck (IB) by Tishby, Pereira, and Bialek
  formalized this notion as an information-theoretic optimization problem and proposed
  an optimal tradeoff between throwing away as many bits as possible, and selectively
  keeping those that are most important. Here, we introduce an alternative formulation,
  the deterministic information bottleneck (DIB), that we argue better captures this
  notion of compression. As suggested by its name, the solution to the DIB problem
  is a deterministic encoder, as opposed to the stochastic encoder that is optimal
  under the IB. We then compare the IB and DIB on synthetic data, showing that the
  IB and DIB perform similarly in terms of the IB cost function, but that the DIB
  vastly outperforms the IB in terms of the DIB cost function. Moreover, the DIB offered
  a 1-2 order of magnitude speedup over the IB in our experiments. Our derivation
  of the DIB also offers a method for continuously interpolating between the soft
  clustering of the IB and the hard clustering of the DIB.
title: The Deterministic Information Bottleneck
year: '2016'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: university16r
month: 0
tex_title: The Deterministic Information Bottleneck
firstpage: 841
lastpage: 850
page: 841-850
order: 841
cycles: false
bibtex_author: University, DJ Strouse Princeton and University, david Schwab Northwestern
author:
- given: DJ Strouse Princeton
  family: University
- given: david Schwab Northwestern
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
pdf: https://raw.githubusercontent.com/mlresearch/r14/main/assets/university16r/university16r.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
