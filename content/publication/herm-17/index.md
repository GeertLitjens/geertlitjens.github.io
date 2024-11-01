---
title: Automatic segmentation of histopathological slides from renal allograft biopsies
  using artificial intelligence
authors:
- Meyke Hermsen
- Thomas de Bel
- Milly van de Warenburg
- Jimmy Knuiman
- Eric Steenbergen
- Geert Litjens
- Bart Smeets
- Luuk Hilbrands
- Jeroen van der Laak
date: '2017-01-01'
publishDate: '2024-09-11T12:09:38.902566Z'
publication_types:
- paper-conference
publication: '*Dutch Federation of Nephrology (NfN) Fall Symposium*'
abstract: 'Objective: Histopathological analysis of renal biopsies depends on the
  identification and assessment of specific histological structures. Both in research
  and routine diagnostics, this analysis can be time-consuming and suffer from observer
  variability. Recently, it has been shown that the combination of high resolution
  whole slide imaging (WSI) and artificial intelligence yields powerful new avenues
  for tissue section analysis. This study aims to develop an algorithm based on a
  specific type of artificial intelligence (a convolutional neural network; CNN) to
  fully automatically segment structures in cortical fragments of renal allograft
  biopsies. Automated segmentation of renal tissue allows an unbiased, reproducible
  computation of morphological characteristics of important structures. This in turn
  can be used as support in diagnostic quantitative measure-based decisions as for
  instance is employed in the Banff-classification. Methods: The neural network was
  trained using a set of Periodic acid-Schiff (PAS) stained slides (n=26) of renal
  allograft biopsies. WSIs were produced using a 3DHISTECH Pannoramic 250 Flash II
  digital slide scanner with a 20x objective lens. We used a U-net architecture CNN,
  which has been proven to be specifically useful in biomedical image segmentation
  tasks. Training was based on exhaustive annotations in one to two randomly selected
  rectangular areas per WSI (size approximately 3000 x 4000 pixels; comparable to
  one 200x microscopic field of view). A total of nine classes were annotated: Glomeruli,
  Sclerotic glomeruli, Proximal tubuli, Distal tubuli, Atrophic tubuli, Undefined
  tubuli, Arteries, Capsule and Interstitium. All annotations were revised by a pathology
  resident (JK), under consultation of an experienced nephropathologist (ES). Our
  CNN was evaluated using the Dice coefficient for each individual class. This coefficient
  expresses the quality of the segmentation on a scale ranging from 0-1, taking into
  account both recall and precision. Because of the limited amount of annotations
  for certain classes, cross-validation was applied. Results: We found the following
  Dice coefficients for the different histological segments: Glomeruli: 0.89, Sclerotic
  glomeruli: 0.43, Proximal tubuli: 0.88, Distal tubuli: 0.77, Atrophic tubuli: 0.32,
  Undefined tubuli: 0.11, Arteries: 0.71, Capsule: 0.47 and Interstitium: 0.85. Conclusion:
  This study shows that segmentation of WSIs of PAS-stained renal allograft biopsies
  using a CNN is feasible. Segmentation of several important classes (Glomeruli, Interstitium,
  Arteries, Proximal-, and Distal tubuli) was highly accurate. CNNs learn from being
  exposed to many example images. The most probable reason for the lower performance
  for the other classes are the relatively low number of annotated regions for these
  classes, combined with a high level of variability inherently present in these tissue
  structures. To our knowledge, this is the first time artificial intelligence is
  being deployed in a nine-class segmentation task in the field of kidney transplant
  histopathology. Results of this study show the promising potential of CNNs in obtaining
  quantitative, spatial and morphometric information from renal tissue in an objective,
  reproducible, high-scale fashion supporting diagnostic decisions based on quantitative
  measures.'
---
