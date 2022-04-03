---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Algorithm 966: A Practical Iterative Algorithm for the Art Gallery Problem
  Using Integer Linear Programming'
subtitle: ''
summary: ''
authors:
- Davi C. Tozoni
- Pedro J. De Rezende
- Cid C. De Souza
tags:
- Art gallery problem
- combinatorial optimization
- computational geometry
- exact algorithm
categories: []
date: '2016-08-01'
lastmod: 2022-04-03T12:49:08-04:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-04-03T16:49:08.470043Z'
publication_types:
- '2'
abstract: In the last few decades, the search for exact algorithms for known NP-hard
  geometric problems has intensified. Many of these solutions use Integer Linear Programming
  (ILP) modeling and rely on state-of-the- art solvers to be able to find optimal
  solutions for large instances in a matter of minutes. In this work, we discuss an
  ILP-based algorithm that solves to optimality the Art Gallery Problem (AGP), one
  of the most studied problems in computational geometry. The basic idea of our method
  is to iteratively generate upper and lower bounds for the problem through the resolution
  of discretized versions of the AGP, which are reduced to instances of the Set Cover
  Problem. Our algorithm was implemented and tested on almost 3,000 instances and
  attained optimal solutions for the vast majority of them, greatly increasing the
  set of instances for which exact solutions are known. To the best of our knowledge,
  in spite of the extensive study of the AGP in the last four decades, no other algorithm
  has shown the ability to solve the AGP as effectively and efficiently as the one
  described here. Evidence of its robustness is presented through tests done on a
  number of classes of polygons of various sizes with and without holes. A software
  package implementing the algorithm is made available.
publication: '*ACM Transactions on Mathematical Software*'
doi: 10.1145/2890491
links:
- name: URL
  url: http://doi.acm.org/10.1145/2890491
---
