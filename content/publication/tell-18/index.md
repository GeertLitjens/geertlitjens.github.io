---
title: Whole-Slide Mitosis Detection in H&E Breast Histology Using PHH3 as a Reference
  to Train Distilled Stain-Invariant Convolutional Networks
authors:
- David Tellez
- Maschenka Balkenhol
- Irene Otte-Holler
- Rob van de Loo
- Rob Vogels
- Peter Bult
- Carla Wauters
- Willem Vreuls
- Suzanne Mol
- Nico Karssemeijer
- Geert Litjens
- Jeroen van der Laak
- Francesco Ciompi
date: '2018-03-01'
publishDate: '2024-09-11T12:09:38.672056Z'
publication_types:
- article-journal
publication: '*IEEE Trans Med Imaging*'
doi: 10.1109/TMI.2018.2820199
abstract: 'Manual counting of mitotic tumor cells in tissue sections constitutes one
  of the strongest prognostic markers for breast cancer. This procedure, however,
  is time-consuming and error-prone. We developed a method to automatically detect
  mitotic figures in breast cancer tissue sections based on convolutional neural networks
  (CNNs). Application of CNNs to hematoxylin and eosin (H&E) stained histological
  tissue sections is hampered by: (1) noisy and expensive reference standards established
  by pathologists, (2) lack of generalization due to staining variation across laboratories,
  and (3) high computational requirements needed to process gigapixel whole-slide
  images (WSIs). In this paper, we present a method to train and evaluate CNNs to
  specifically solve these issues in the context of mitosis detection in breast cancer
  WSIs. First, by combining image analysis of mitotic activity in phosphohistone-H3
  (PHH3) restained slides and registration, we built a reference standard for mitosis
  detection in entire H&E WSIs requiring minimal manual annotation effort. Second,
  we designed a data augmentation strategy that creates diverse and realistic H&E
  stain variations by modifying the hematoxylin and eosin color channels directly.
  Using it during training combined with network ensembling resulted in a stain invariant
  mitosis detector. Third, we applied knowledge distillation to reduce the computational
  requirements of the mitosis detection ensemble with a negligible loss of performance.
  The system was trained in a single-center cohort and evaluated in an independent
  multicenter cohort from The Cancer Genome Atlas on the three tasks of the Tumor
  Proliferation Assessment Challenge (TUPAC). We obtained a performance within the
  top-3 best methods for most of the tasks of the challenge.'
---
