---
title: Detection of prostate cancer in whole-slide images through end-to-end training
  with image-level labels.
authors:
- Hans Pinckaers
- Wouter Bulten
- Jeroen Van der Laak
- Geert Litjens
date: '2021-03-01'
publishDate: '2024-09-11T12:09:38.954429Z'
publication_types:
- article-journal
publication: '*IEEE Trans Med Imaging*'
doi: 10.1109/TMI.2021.3066295
abstract: Prostate cancer is the most prevalent cancer among men in Western countries,
  with 1.1 million new diagnoses every year. The gold standard for the diagnosis of
  prostate cancer is a pathologists' evaluation of prostate tissue. To potentially
  assist pathologists deep-learning-based cancer detection systems have been developed.
  Many of the state-of-the-art models are patch-based convolutional neural networks,
  as the use of entire scanned slides is hampered by memory limitations on accelerator
  cards. Patch-based systems typically require detailed, pixel-level annotations for
  effective training. However, such annotations are seldom readily available, in contrast
  to the clinical reports of pathologists, which contain slide-level labels. As such,
  developing algorithms which do not require manual pixel-wise annotations, but can
  learn using only the clinical report would be a significant advancement for the
  field. In this paper, we propose to use a streaming implementation of convolutional
  layers, to train a modern CNN (ResNet-34) with 21 million parameters end-to-end
  on 4712 prostate biopsies. The method enables the use of entire biopsy images at
  high-resolution directly by reducing the GPU memory requirements by 2.4 TB. We show
  that modern CNNs, trained using our streaming approach, can extract meaningful features
  from high-resolution images without additional heuristics, reaching similar performance
  as state-of-the-art patch-based and multiple-instance learning methods. By circumventing
  the need for manual annotations, this approach can function as a blueprint for other
  tasks in histopathological diagnosis. The source code to reproduce the streaming
  models is available at https://github.com/DIAGNijmegen/pathology-streaming-pipeline.
---
