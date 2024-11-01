---
title: Computerized characterization of central gland lesions using texture and relaxation
  features from T2-weighted prostate MRI
authors:
- G. Litjens
- J. O. Barentsz
- N. Karssemeijer
- H. J. Huisman
date: '2012-01-01'
publishDate: '2024-09-11T12:09:38.451011Z'
publication_types:
- paper-conference
publication: '*RSNA*'
abstract: 'Purpose: The recent PI-RADS standard considers T2-weighted (T2W) MR the
  best imaging modality to characterize central gland (CG) lesions. In this study
  we assessed whether computer-aided diagnosis using T2 texture and relaxation features
  can separate benign and malignant CG lesions. Materials and Methods: MR scans of
  101 patients were included in this study. The reference standard was MR-guided MR
  biopsy. Of these patients 36 had benign disease (e.g. benign prostatic hyperplasia)
  and 65 had prostate cancer. Lesions were annotated on the T2W sequence using a contouring
  tool. A quantitative T2 relaxation map was computed using an estimator that combines
  the T2W and proton density images with a turbo-spin-echo signal model and a gain
  factor. The latter was estimated using an automatically selected muscle reference
  region. Several texture voxel features were computed on the resulting T2-map: co-occurrenc
  matrix based homogeneity, neighboring gray-level dependence matrix based texture
  strength, and multi-scale Gaussian derivative features. For the latter 5 scales
  between 2 and 12 mm and derivatives up to the second order were calculated. For
  the matrix based features we calculated several histogram bin sizes (8, 16 and 32)
  and kernel sizes (4, 8 and 12 mm). The total number of texture features was 42.
  A linear discriminant classifier with feature selection was trained to compute the
  cancer likelihood for each voxel in the lesion. A feature selection was performed
  in a nested cross-validation loop using 10 folds. Cross-validation was performed
  in a leave-one-patient-out manner. For each annotated region a summary lesion likelihood
  was computed using the 75th percentile of the voxel likelihoods. The diagnostic
  accuracy of the lesion cancer likelihood was evaluated using receiver-operating
  characteristic (ROC) analysis and bootstrapping. Results: An area under the ROC
  curve of 0.76 (95% bootstrap confidence interval 0.64 Ã¯Â¿Â½ 0.87) was obtained
  for determining cancer likelihood using texture features, which is similar to radiologist
  performance reported in the literature when they only have T2W images available,
  like in this study. Conclusion: A novel method for characterizing lesions in T2-weighted
  MRI using texture descriptors was developed. The performance is in the range of
  values reported in the literature for radiologists. Clinical relevance: A CAD system
  for classification of CG lesions could improve the characterization of these lesions,
  which might result in better treatment planning.'
---
