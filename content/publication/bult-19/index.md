---
title: Epithelium segmentation using deep learning in H&E-stained prostate specimens
  with immunohistochemistry as reference standard
authors:
- Wouter Bulten
- Péter Bándi
- Jeffrey Hoven
- Rob van de Loo
- Johannes Lotz
- Nick Weiss
- Jeroen van der Laak
- Bram van Ginneken
- Christina Hulsbergen-van de Kaa
- Geert Litjens
date: '2019-01-29'
publishDate: '2024-09-11T12:09:38.758873Z'
publication_types:
- article-journal
publication: '*Nat Sci Rep*'
doi: 10.1038/s41598-018-37257-4
abstract: Given the importance of gland morphology in grading prostate cancer (PCa),
  automatically differentiating between epithelium and other tissues is an important
  prerequisite for the development of automated methods for detecting PCa. We propose
  a new deep learning method to segment epithelial tissue in digitised hematoxylin
  and eosin (H&E) stained prostatectomy slides using immunohistochemistry (IHC) as
  reference standard. We used IHC to create a precise and objective ground truth compared
  to manual outlining on H&E slides, especially in areas with high-grade PCa. 102
  tissue sections were stained with H&E and subsequently restained with P63 and CK8/18
  IHC markers to highlight epithelial structures. Afterwards each pair was co-registered.
  First, we trained a U-Net to segment epithelial structures in IHC using a subset
  of the IHC slides that were preprocessed with color deconvolution. Second, this
  network was applied to the remaining slides to create the reference standard used
  to train a second U-Net on H&E. Our system accurately segmented both intact glands
  and individual tumour epithelial cells. The generalisation capacity of our system
  is shown using an independent external dataset from a different centre. We envision
  this segmentation as the first part of a fully automated prostate cancer grading
  pipeline.
links:
- name: URL
  url: https://arxiv.org/abs/1808.05883
---
