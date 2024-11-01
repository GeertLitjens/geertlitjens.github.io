---
title: Using deep learning to segment breast and fibroglandular tissue in MRI volumes
authors:
- Mehmet Ufuk Dalmis
- Geert Litjens
- Katharina Holland
- Arnaud Setio
- Ritse Mann
- Nico Karssemeijer
- Albert Gubern-Mérida
date: '2017-02-01'
publishDate: '2024-09-11T12:09:38.345743Z'
publication_types:
- article-journal
publication: '*Med Phys*'
doi: 10.1002/mp.12079
abstract: "Automated segmentation of breast and fibroglandular tissue (FGT) is required
  for various computer-aided applications of breast MRI. Traditional image analysis
  and computer vision techniques, such atlas, template matching, or, edge and surface
  detection, have been applied to solve this task. However, applicability of these
  methods is usually limited by the characteristics of the images used in the study
  datasets, while breast MRI varies with respect to the different MRI protocols used,
  in addition to the variability in breast shapes. All this variability, in addition
  to various MRI artifacts, makes it a challenging task to develop a robust breast
  and FGT segmentation method using traditional approaches. Therefore, in this study,
  we investigated the use of a deep-learning approach known as \\\"U-net.\\\" We used
  a dataset of 66 breast MRI's randomly selected from our scientific archive, which
  includes five different MRI acquisition protocols and breasts from four breast density
  categories in a balanced distribution. To prepare reference segmentations, we manually
  segmented breast and FGT for all images using an in-house developed workstation.
  We experimented with the application of U-net in two different ways for breast and
  FGT segmentation. In the first method, following the same pipeline used in traditional
  approaches, we trained two consecutive (2C) U-nets: first for segmenting the breast
  in the whole MRI volume and the second for segmenting FGT inside the segmented breast.
  In the second method, we used a single 3-class (3C) U-net, which performs both tasks
  simultaneously by segmenting the volume into three regions: nonbreast, fat inside
  the breast, and FGT inside the breast. For comparison, we applied two existing and
  published methods to our dataset: an atlas-based method and a sheetness-based method.
  We used Dice Similarity Coefficient (DSC) to measure the performances of the automated
  methods, with respect to the manual segmentations. Additionally, we computed Pearson's
  correlation between the breast density values computed based on manual and automated
  segmentations. The average DSC values for breast segmentation were 0.933, 0.944,
  0.863, and 0.848 obtained from 3C U-net, 2C U-nets, atlas-based method, and sheetness-based
  method, respectively. The average DSC values for FGT segmentation obtained from
  3C U-net, 2C U-nets, and atlas-based methods were 0.850, 0.811, and 0.671, respectively.
  The correlation between breast density values based on 3C U-net and manual segmentations
  was 0.974. This value was significantly higher than 0.957 as obtained from 2C U-nets
  (P < 0.0001, Steiger's Z-test with Bonferoni correction) and 0.938 as obtained from
  atlas-based method (P = 0.0016). In conclusion, we applied a deep-learning method,
  U-net, for segmenting breast and FGT in MRI in a dataset that includes a variety
  of MRI protocols and breast densities. Our results showed that U-net-based methods
  significantly outperformed the existing algorithms and resulted in significantly
  more accurate breast density computation."
tags:
- MRI; breast segmentation; deep learning
---
