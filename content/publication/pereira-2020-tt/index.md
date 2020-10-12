---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'SLEAP: Multi-animal pose tracking'
subtitle: ''
summary: ''
authors:
- Talmo D Pereira
- Nathaniel Tabris
- Junyu Li
- Shruthi Ravindranath
- Eleni S Papadoyannis
- Z Yan Wang
- David M Turner
- Grace McKenzie-Smith
- Sarah D Kocher
- Annegret Lea Falkner
- Joshua W Shaevitz
- Mala Murthy
tags: []
categories: []
date: '2020-09-01'
lastmod: 2020-10-12T13:11:44-04:00
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
publishDate: '2020-10-12T17:11:43.706219Z'
publication_types:
- '2'
abstract: 'The desire to understand how the brain generates and patterns behavior
  has driven rapid methodological innovation to quantify and model natural animal
  behavior. This has led to important advances in deep learning-based markerless pose
  estimation that have been enabled in part by the success of deep learning for computer
  vision applications. Here we present SLEAP (Social LEAP Estimates Animal Poses),
  a framework for multi-animal pose tracking via deep learning. This system is capable
  of simultaneously tracking any number of animals during social interactions and
  across a variety of experimental conditions. SLEAP implements several complementary
  approaches for dealing with the problems inherent in moving from single- to multi-animal
  pose tracking, including configurable neural network architectures, inference techniques,
  and tracking algorithms, enabling easy specialization and tuning for particular
  experimental conditions or performance requirements. We report results on multiple
  datasets of socially interacting animals (flies, bees, and mice) and describe how
  dataset-specific properties can be leveraged to determine the best configuration
  of SLEAP models. Using a high accuracy model (<2.8 px error on 95% of points), we
  were able to track two animals from full size 1024 x 1024 pixel frames at up to
  320 FPS. The SLEAP framework comes with a sophisticated graphical user interface,
  multi-platform support, Colab-based GPU-free training and inference, and complete
  tutorials available, in addition to the datasets, at sleap.ai. ### Competing Interest
  Statement The authors have declared no competing interest.'
publication: '*bioRxiv*'
---
