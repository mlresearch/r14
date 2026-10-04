---
abstract: Finding efficient and provable methods to solve nonconvex optimization problems
  is an outstanding challenge in machine learning and optimization theory. A popular
  approach used to tackle nonconvex problems is to use convex relaxation techniques
  to find a convex surrogate for the problem. Unfortunately, convex relaxations typically
  must be found on a problem-by-problem basis. Thus, providing a general-purpose strategy
  to estimate a convex relaxation would have a wide reaching impact. Here, we introduce
  Convex Relaxation Regression (CoRR), an approach for learning convex relaxations
  for a class of smooth functions. The idea behind our approach is to estimate the
  convex envelope of a function $f$ by evaluating $f$ at a set of $T$ random points
  and then fitting a convex function to these function evaluations. We prove that
  with probability greater than $1-\delta$, the solution of our algorithm converges
  to the global optimizer of $f$ with error $O \(\frac{\log(1/\delta) }{T} )^\alpha
  )$ for some $\alpha > 0$. Our approach enables the use of convex optimization tools
  to solve
title: 'Convex Relaxation Regression: Black-Box Optimization of Smooth Functions by
  Learning Their Convex Envelopes'
year: '2016'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: university16g
month: 0
tex_title: 'Convex Relaxation Regression: Black-Box Optimization of Smooth Functions
  by Learning Their Convex Envelopes'
firstpage: 266
lastpage: 275
page: 266-275
order: 266
cycles: false
bibtex_author: University, Mohamm Gheshlaghi Azar Northwestern and University, Eva
  Dyer Northwestern and University, Konrad Kording Northwestern
author:
- given: Mohamm Gheshlaghi Azar Northwestern
  family: University
- given: Eva Dyer Northwestern
  family: University
- given: Konrad Kording Northwestern
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
pdf: https://raw.githubusercontent.com/mlresearch/r14/main/assets/university16g/university16g.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
