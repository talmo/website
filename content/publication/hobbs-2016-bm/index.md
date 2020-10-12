---
# Documentation: https://wowchemy.com/docs/managing-content/

title: A Bayesian inference method for the analysis of transcriptional regulatory
  networks in metagenomic data
subtitle: ''
summary: ''
authors:
- Elizabeth T Hobbs
- Talmo Pereira
- Patrick K O'Neill
- Ivan Erill
tags:
- '"Bayesian inference; Copper homeostasis; CsoR; Metagenomics; Metal resistance;
  Regulatory network; Regulon; Stress response; Transcription factor"'
categories: []
date: '2016-07-01'
lastmod: 2020-10-12T13:11:37-04:00
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
publishDate: '2020-10-12T17:11:36.551703Z'
publication_types:
- '2'
abstract: 'BACKGROUND: Metagenomics enables the analysis of bacterial population composition
  and the study of emergent population features, such as shared metabolic pathways.
  Recently, we have shown that metagenomics datasets can be leveraged to characterize
  population-wide transcriptional regulatory networks, or meta-regulons, providing
  insights into how bacterial populations respond collectively to specific triggers.
  Here we formalize a Bayesian inference framework to analyze the composition of transcriptional
  regulatory networks in metagenomes by determining the probability of regulation
  of orthologous gene sequences. We assess the performance of this approach on synthetic
  datasets and we validate it by analyzing the copper-homeostasis network of Firmicutes
  species in the human gut microbiome. RESULTS: Assessment on synthetic datasets shows
  that our method provides a robust and interpretable metric for assessing putative
  regulation by a transcription factor on sets of promoter sequences mapping to an
  orthologous gene cluster. The inference framework integrates the regulatory contribution
  of secondary sites and can discern false positives arising from multiple instances
  of a clonal sequence. Posterior probabilities for orthologous gene clusters decline
  sharply when less than 20 % of mapped promoters have binding sites, but we introduce
  a sensitivity adjustment procedure to speed up computation that enhances regulation
  assessment in heterogeneous ortholog clusters. Analysis of the copper-homeostasis
  regulon governed by CsoR in the human gut microbiome Firmicutes reveals that CsoR
  controls itself and copper-translocating P-type ATPases, but not CopZ-type copper
  chaperones. Our analysis also indicates that CsoR frequently targets promoters with
  dual CsoR-binding sites, suggesting that it exploits higher-order binding conformations
  to fine-tune its activity. CONCLUSIONS: We introduce and validate a method for the
  analysis of transcriptional regulatory networks from metagenomic data that enables
  inference of meta-regulons in a systematic and interpretable way. Validation of
  this method on the CsoR meta-regulon of gut microbiome Firmicutes illustrates the
  usefulness of the approach, revealing novel properties of the copper-homeostasis
  network in poorly characterized bacterial species and putting forward evidence of
  new mechanisms of DNA binding for this transcriptional regulator. Our approach will
  enable the comparative analysis of regulatory networks across metagenomes, yielding
  novel insights into the evolution of transcriptional regulatory networks.'
publication: '*Algorithms Mol. Biol.*'
---
