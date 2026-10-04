---
abstract: Dantzig Selector (DS) is widely used in compressed sensing and sparse learning
  for feature selection and sparse signal recovery. Since the DS formulation is essentially
  a linear programming optimization, many existing linear programming solvers can
  be simply applied for scaling up. The DS formulation can be explained as a basis
  pursuit denoising problem, wherein the data matrix (or measurement matrix) is employed
  as the denoising matrix to eliminate the observation noise. However, we notice that
  the data matrix may not be the optimal denoising matrix, as shown by a simple counter-example.
  This motivates us to pursue a better denoising matrix for defining a general DS
  formulation. We first define the optimal denoising matrix through a minimax optimization,
  which turns out to be an NP-hard problem. To make the problem computationally tractable,
  we propose a novel algorithm, termed as “Optimal” Denoising Dantzig Selector (ODDS),
  to approximately estimate the optimal denoising matrix. Empirical experiments validate
  the proposed method. Finally, a novel sparse reinforcement learning algorithm is
  formulated by extending the proposed ODDS algorithm to temporal difference learning,
  and empirical experimental results demonstrate to outperform the conventional "vanilla"
  DS-TD algorithm.
title: Dantzig Selector with an Approximately Optimal Denoising Matrix and its Application
  in Sparse Reinforcement Learning
year: '2016'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: university16c
month: 0
tex_title: Dantzig Selector with an Approximately Optimal Denoising Matrix and its
  Application in Sparse Reinforcement Learning
firstpage: 78
lastpage: 87
page: 78-87
order: 78
cycles: false
bibtex_author: University, Bo Liu Auburn and Zhang, Luwan and Liu, Ji
author:
- given: Bo Liu Auburn
  family: University
- given: Luwan
  family: Zhang
- given: Ji
  family: Liu
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
pdf: https://raw.githubusercontent.com/mlresearch/r14/main/assets/university16c/university16c.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
