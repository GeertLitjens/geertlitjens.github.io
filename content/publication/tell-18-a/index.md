---
title: H&E stain augmentation improves generalization of convolutional networks for
  histopathological mitosis detection
authors:
- D. Tellez
- M. Balkenhol
- N. Karssemeijer
- G. Litjens
- J. van der Laak
- F. Ciompi
date: '2018-02-01'
publishDate: '2024-09-11T12:09:38.664822Z'
publication_types:
- paper-conference
publication: '*Medical Imaging*'
doi: 10.1117/12.2293048
abstract: The number of mitotic figures per tumor area observed in hematoxylin and
  eosin (H and E) histological tissue sections under light microscopy is an important
  biomarker for breast cancer prognosis. Whole-slide imaging and computational pathology
  have enabled the development of automatic mitosis detection algorithms based on
  convolutional neural networks (CNNs). These models can suffer from high generalization
  error, i.e. trained networks often underperform on datasets originating from pathology
  laboratories different than the one that provided the training data, mainly due
  to the presence of inter-laboratory stain variations. We propose a novel data augmentation
  strategy that exploits the properties of the H and E color space to simulate a broad
  range of realistic H and E stain variations. To our best knowledge, this is the
  first time that data augmentation is performed directly in the H and E color space,
  instead of RGB. The proposed technique uses color deconvolution to transform RGB
  images into the H and E color space, modifies the H and E color channels stochastically,
  and projects them back to RGB space. We trained a CNN-based mitosis detector on
  homogeneous data from a single institution, and tested its performance on an external,
  multicenter cohort that contained a wide range of unseen H and E stain variations.
  We compared CNNs trained with and without the proposed augmentation strategy and
  observed a significant improvement in performance and robustness to unseen stain
  variations when the new color augmentation technique was included. In essence, we
  have shown that CNNs can be made robust to inter-lab stain variation by incorporating
  extensive stain augmentation techniques.
---
