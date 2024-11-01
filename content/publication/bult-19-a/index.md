---
title: Automated Gleason Grading of Prostate Biopsies Using Deep Learning
authors:
- Wouter Bulten
- Hans Pinckaers
- Christina Hulsbergen-van de Kaa
- Geert Litjens
date: '2019-01-01'
publishDate: '2024-09-11T12:09:38.735055Z'
publication_types:
- paper-conference
publication: '*United States and Canadian Academy of Pathology (USCAP) 108th Annual
  Meeting*'
abstract: Grading prostate cancer is a time-consuming process and suffers from high
  inter- and intra-observer variability. Advances in computer-aided diagnosis have
  shown promise in improving histopathological diagnosis. We trained a deep learning
  system using data retrieved from the patients records to grade digitized prostate
  biopsies. Our system is the first that can automatically classify background, benign
  epithelium, Gleason 3, 4, and 5 on a gland-by-gland level in prostate biopsies.
  532 glass slides containing 2162 prostate biopsies, evaluated by an experienced
  urogenital pathologist were collected and scanned. 596 biopsies were kept separate
  for evaluation, the remaining 1576 were used to train the deep learning algorithm
  (see table for Gleason grade distribution). A single label denoting the Gleason
  score (e.g. 3+4=7) was available for each biopsy, without information on tumor location
  or volume. To generate detailed annotations for training we used two previously
  trained deep learning networks to first segment the epithelium and, subsequently,
  to detect cancer. The Gleason grade from the patient record was assigned to the
  cancerous epithelium. These generated weakly annotated regions of tumor were then
  used to train a Gleason grading system. To evaluate, the system was applied to the
  biopsies in the test set. We used the total predicted surface area of each growth
  pattern to determine the Gleason score of the biopsy. Predicted tumor areas smaller
  than 15% of total epithelial tissue were considered unreliable (e.g. incomplete
  glands at the edges of the biopsy) and ignored for slide level classification. For
  predicted grades only areas larger than 5% of all epithelial tissue were considered,
  which is also common in clinical practice. Predicting whether a biopsy contains
  tumor resulted in an accuracy of 86% (linear weighted kappa (k) of 0.73, area under
  the ROC curve of 0.96). We compared the predicted primary Gleason grade to the one
  from the pathologists’ report. Our system achieved an accuracy of 75% (k 0.64).
  On predicting the Grade Group (using primary and secondary pattern), our system
  achieved an accuracy of 67% (k 0.57). Misclassifications of more than one grade
  are rare. Our deep learning system automatically identifies Gleason patterns and
  benign tissue on a gland-by-gland basis. This can be used to determine the biopsy-level
  Grade Group and Gleason score, and show which parts of the tissue contribute to
  this prediction. Improvements need to be made to decrease misclassifications, for
  example in areas with inflammation.
---
