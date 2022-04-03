---
# Documentation: https://wowchemy.com/docs/managing-content/

title: A low-parametric rhombic microstructure family for irregular lattices
subtitle: ''
summary: ''
authors:
- Davi Colli Tozoni
- Jérémie Dumas
- Zhongshi Jiang
- Julian Panetta
- Daniele Panozzo
- Denis Zorin
tags:
- additive fabrication
- deformable objects
- homogenization
- microstructures
- shape optimization
categories: []
date: '2020-07-01'
lastmod: 2022-04-03T12:44:50-04:00
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
publishDate: '2022-04-03T16:44:50.552931Z'
publication_types:
- '2'
abstract: New fabrication technologies have significantly decreased the cost of fabrication
  of shapes with highly complex geometric structure. One important application of
  complex fine-scale geometric structures is to create variable effective elastic
  material properties in shapes manufactured from a single material. Modification
  of material properties has a variety of uses, from aerospace applications to soft
  robotics and prosthetic devices. Due to its scalability and effectiveness, an increasingly
  common approach to creating spatially varying materials is to partition a shape
  into cells and use a parametric family of small-scale geometric structures with
  known effective properties to fill the cells. We propose a new approach to solving
  this problem for extruded, planar microstructures. Differently from existing methods
  for two-scale optimization based on regular grids with square periodic cells, which
  cannot conform to an arbitrary boundary, we introduce cell decompositions consisting
  of (nearly) rhombic cells. These meshes have far greater flexibility than those
  with square cells in terms of approximating arbitrary shapes, and, at the same time,
  have a number of properties simplifying small-scale structure construction. Our
  main contributions include a new family of 2D cell geometry structures, explicitly
  parameterized by their effective Young's moduli E, Poisson's ratios v, and rhombic
  angle α with the geometry parameters expressed directly as smooth spline functions
  of E, v, and α. This family leads to smooth transitions between the tiles and can
  handle a broad range of rhombic cell shapes. We introduce a complete material design
  pipeline based on this microstructure family, composed of an algorithm to generate
  rhombic tessellation from quadrilateral meshes and an algorithm to synthesize the
  microstructure geometry. We fabricated a number of models and experimentally demonstrated
  how our method, in combination with material optimization, can be used to achieve
  the desired deformation behavior.
publication: '*ACM Transactions on Graphics*'
doi: 10.1145/3386569.3392451
links:
- name: URL
  url: https://doi.org/10.1145/3386569.3392451
---
