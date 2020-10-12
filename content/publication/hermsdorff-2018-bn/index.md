---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Quantifying Humans' Priors Over Graphical Representations of Tasks
subtitle: ''
summary: ''
authors:
- Gecia Bravo Hermsdorff
- Talmo Pereira
- Yael Niv
tags: []
categories: []
date: '2018-07-01'
lastmod: 2020-10-12T13:11:40-04:00
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
publishDate: '2020-10-12T17:11:40.098707Z'
publication_types:
- '1'
abstract: Some new tasks are trivial to learn while others are almost impossible;
  what determines how easy it is to learn an arbitrary task? Similar to how our prior
  beliefs about new visual scenes colors our perception of new stimuli, our priors
  about the structure of new tasks shapes our learning and generalization abilities
  [2]. While quantifying visual priors has led to major insights on how our visual
  system works [5, 10, 11], quantifying priors over tasks remains a formidable goal,
  as it is not even clear how to define a task [4]. Here, we focus on tasks that have
  a natural mapping to graphs. We develop a method to quantify humans' priors over
  these "task graphs", combining new modeling approaches with Markov chain Monte
  Carlo with people, MCMCP (a process whereby an agent learns from data generated
  by another agent, recursively [9]). We show that our method recovers priors more
  accurately than a standard MCMC sampling approach. Additionally, we propose a novel
  low-dimensional "smooth" (In the sense that graphs that differ by fewer edges
  are given similar probabilities.) parametrization of probability distributions over
  graphs that allows for more accurate recovery of the prior and better generalization.
  We have also created an online experiment platform that gamifies our MCMCP algorithm
  and allows subjects to interactively draw the task graphs. We use this platform
  to collect human data on several navigation and social interactions tasks. We show
  that priors over these tasks have non-trivial structure, deviating significantly
  from null models that are insensitive to the graphical information. The priors also
  notably differ between the navigation and social domains, showing fewer differences
  between cover stories within the same domain. Finally, we extend our framework to
  the more general case of quantifying priors over exchangeable random structures.
publication: '*International Conference on Complex Systems*'

links:
- name: Journal
  url: http://dx.doi.org/10.1007/978-3-319-96661-8_30
---
