---
abstract: 
authors:
- Valeria Vitelli
- admin
- Marta Crispino
- Arnoldo Frigessi
- Elja Arjas
date: "2018-04-01T00:00:00Z"
doi: ""
featured: false
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false
projects: []
publication: 'Journal of Machine Learning Research'
publication_short: ""
publication_types:
- "2"
publishDate: "2017-01-01T00:00:00Z"
tags:
- Mallows' rank model
title: Probabilistic preference learning with the Mallows rank model
---

Ranking and comparing items is crucial for collecting information about preferences in many areas, from marketing to politics. The Mallows rank model is among the most successful approaches to analyze rank data, but its computational complexity has limited its use to a particular form based on Kendall distance. We develop new computationally tractable methods for Bayesian inference in Mallows models that work with any right-invariant distance. Our method performs inference on the consensus ranking of the items, also when based on partial rankings, such as top-k items or pairwise comparisons. We prove that items that none of the assessors has ranked do not influence the maximum a posteriori consensus ranking, and can therefore be ignored. When assessors are many or heterogeneous, we propose a mixture model for clustering them in homogeneous subgroups, with clusterspecific consensus rankings. We develop approximate stochastic algorithms that allow a fully probabilistic analysis, leading to coherent quantifications of uncertainties. We make probabilistic predictions on the class membership of assessors based on their ranking of just some items, and predict missing individual preferences, as needed in recommendation systems. We test our approach using several experimental and benchmark data sets.
Valeria Vitelli and Øystein Sørensen are joint first authors. [Full text link.](https://jmlr.org/beta/papers/v18/15-481.html)