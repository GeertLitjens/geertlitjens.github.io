---
title: Stain-Transforming Cycle-Consistent Generative Adversarial Networks for Improved
  Segmentation of Renal Histopathology
authors:
- Thomas de Bel
- Meyke Hermsen
- Jesper Kers
- Jeroen van der Laak
- Geert Litjens
date: '2019-01-01'
publishDate: '2024-09-11T12:09:38.793316Z'
publication_types:
- paper-conference
publication: '*Medical Imaging with Deep Learning*'
abstract: The performance of deep learning applications in digital histopathology
  can deteriorate significantly due to staining variations across centers. We employ
  cycle-consistent generative adversarial networks (cycleGANs) for unpaired image-to-image
  translation, facilitating between-center stain transformation. We find that modifications
  to the original cycleGAN architecture make it more suitable for stain transformation,
  creating artificially stained images of high quality. Specifically, changing the
  generator model to a smaller U-net-like architecture, adding an identity loss term,
  increasing the batch size and the learning all led to improved training stability
  and performance. Furthermore, we propose a method for dealing with tiling artifacts
  when applying the network on whole slide images (WSIs). We apply our stain transformation
  method on two datasets of PAS-stained (Periodic Acid-Schiff) renal tissue sections
  from different centers. We show that stain transformation is beneficial to the performance
  of cross-center segmentation, raising the Dice coefficient from 0.36 to 0.85 and
  from 0.45 to 0.73 on the two datasets.
links:
- name: URL
  url: https://openreview.net/forum?id=BkxJkgSlx4
---
