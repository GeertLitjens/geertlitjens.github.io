---
title: Automated detection of prostate cancer in digitized whole-slide images of H&E-stained
  biopsy specimens
authors:
- G. Litjens
- B. Ehteshami Bejnordi
- N. Timofeeva
- G. Swadi
- I. Kovacs
- C. A. Hulsbergen-van de Kaa
- J. A. W. M. van der Laak
date: '2015-01-01'
publishDate: '2024-09-11T12:09:38.466343Z'
publication_types:
- paper-conference
publication: '*Medical Imaging*'
doi: 10.1117/12.2081366
abstract: 'Automated detection of prostate cancer in digitized H and E whole-slide
  images is an important first step for computer-driven grading. Most automated grading
  algorithms work on preselected image patches as they are too computationally expensive
  to calculate on the multi-gigapixel whole-slide images. An automated multi-resolution
  cancer detection system could reduce the computational workload for subsequent grading
  and quantification in two ways: by excluding areas of definitely normal tissue within
  a single specimen or by excluding entire specimens which do not contain any cancer.
  In this work we present a multi-resolution cancer detection algorithm geared towards
  the latter. The algorithm methodology is as follows: at a coarse resolution the
  system uses superpixels, color histograms and local binary patterns in combination
  with a random forest classifier to assess the likelihood of cancer. The five most
  suspicious superpixels are identified and at a higher resolution more computationally
  expensive graph and gland features are added to refine classification for these
  superpixels. Our methods were evaluated in a data set of 204 digitized whole-slide
  H and E stained images of MR-guided biopsy specimens from 163 patients. A pathologist
  exhaustively annotated the specimens for areas containing cancer. The performance
  of our system was evaluated using ten-fold cross-validation, stratified according
  to patient. Image-based receiver operating characteristic (ROC) analysis was subsequently
  performed where a specimen containing cancer was considered positive and specimens
  without cancer negative. We obtained an area under the ROC curve of 0.96 and a 0.4
  specificity at a 1.0 sensitivity.'
---
