---
title: Resolution-agnostic tissue segmentation in whole-slide histopathology images
  with convolutional neural networks
authors:
- P. Bándi
- Maschenka Balkenhol
- Bram van Ginneken
- Jeroen van der Laak
- Geert Litjens
date: '2019-01-01'
publishDate: '2024-09-11T12:09:38.831261Z'
publication_types:
- article-journal
publication: '*PeerJ*'
doi: https://doi.org/10.7717/peerj.8242
abstract: Modern pathology diagnostics is being driven toward large scale digitization
  of microscopic tissue sections. A prerequisite for its safe implementation is the
  guarantee that all tissue present on a glass slide can also be found back in the
  digital image. Whole-slide scanners perform a tissue segmentation in a low resolution
  overview image to prevent inefficient high-resolution scanning of empty background
  areas. However, currently applied algorithms can fail in detecting all tissue regions.
  In this study, we developed convolutional neural networks to distinguish tissue
  from background. We collected 100 whole-slide images of 10 tissue samples--staining
  categories from five medical centers for development and testing. Additionally,
  eight more images of eight unfamiliar categories were collected for testing only.
  We compared our fully-convolutional neural networks to three traditional methods
  on a range of resolution levels using Dice score and sensitivity. We also tested
  whether a single neural network can perform equivalently to multiple networks, each
  specialized in a single resolution. Overall, our solutions outperformed the traditional
  methods on all the tested resolutions. The resolution-agnostic network achieved
  average Dice scores between 0.97 and 0.98 across the tested resolution levels, only
  0.0069 less than the resolution-specific networks. Finally, its excellent generalization
  performance was demonstrated by achieving averages of 0.98 Dice score and 0.97 sensitivity
  on the eight unfamiliar images. A future study should test this network prospectively.
links:
- name: URL
  url: https://peerj.com/articles/8242/
---
