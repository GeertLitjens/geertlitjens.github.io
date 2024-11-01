---
title: Pharmacokinetic modeling in breast cancer MRI
authors:
- Geert Litjens
date: '2009-01-01'
publishDate: '2024-09-11T12:09:38.917097Z'
publication_types:
- thesis
abstract: 'Breast cancer is a disease which impacts the lives of thousands of people.
  In the entire world over half a million people die due to breast cancer every year,
  mostly women. However, when breast cancer is detected in the early stages of disease
  ?ve-year-survival rate approaches 100%. So, it is very important to detect breast
  cancer as early as possible. That is why in most of modern Western society screening
  programs for breast cancer have been developed. Most of these screening programs
  focus on x-ray mammography. However, women who have an increased risk to get breast
  cancer these screening programs are not adequate. These women usually develop breast
  cancer at a younger age and x-ray mammography for those women has a low sensitivity.
  For these cases, and inconclusive ?ndings in x-ray mammography in other women, dynamic
  contrast enhance (DCE) MRI is used. In DCE MRI a contrast agent is used which takes
  advantage of the fact that tumor vasculature is leaky and sloppy, thus the contrast
  agent tends to accumulate in the tumor, leading to increased signal intensity in
  T1-weighted images. Due to the fact that we have a time range of images it is possible
  to look at kinetic behavior. However, as kinetic curves have a large inter and intra
  patient variability and variability depending on the imaging site the analysis of
  these curves is not straightforward. Pharmacokinetic modeling could be an answer
  to those problems as it can be used to obtain lesion-speci?c physiological parameters.
  To use pharmacokinetic modeling however we need high temporal resolution data, which
  is not readily available. The University of Chicago Medical Center obtained several
  high temporal resolution data sets for the initial part of the kinetic enhancement
  curve in addition to the regular low temporal clinical scans. These data sets were
  the basis for this research. When analyzing such data several factors play an important
  role. The ?rst of these being the extraction of the signal-vs.-time curves from
  the data sets. In this report we used a small graphical user interface to extract
  the data. The low and high temporal resolution images were obtained in different
  orientations, which was a problem we also needed to solve. The second step after
  extraction of the signal-vs.-time-curves was the conversion of the signal intensity
  to contrast agent concentration. In literature there were several methods that were
  used to accomplish this, but all were based on the use of a gradient recalled echo
  signal model. We ?rst investigated the assumption that we can neglect T2* effects,
  which we concluded was allowed. To estimate concentration the tissue T1 at time
  0 has to been known. As we had no additional T1 measurements, we used a reference
  tissue approach to estimate T1. We investigated if the simpli?cations often used
  in this method were allowed and we concluded that it was better to use the full
  model. The last part of the conversion to concentration is the estimation of uncertainty
  in the concentration curves, which in itself contains several uncertainties. We
  derived an algebraic expression for these uncertainties using a Taylor expansion
  of concentration uncertainty. On average the uncertainty levels are around 10% of
  the concentration. The third step was choosing a pharmacokinetic model, we inspected
  a total of four models, the standard and extended Tofts models, the shutter speed
  model and the Brix model. We ?rst assessed the ability of each model to ?nd correct
  minima using a forward-backward simulation approach. We then simulated data that
  has the same temporal and uncertainty characteristics as real clinical data and
  used the same forward-backward approach to estimate model performance. We concluded
  that for data with those speci?c characteristics only the standard Tofts model performed
  adequately. After that we started investigating the data requirements for all models
  and we could see that for all models except the standard Tofts model data requirements
  on especially temporal resolution are high. Lastly we did an investigation in the
  errors introduced by assuming that the underlying physiological processes are more
  simplistic, which is what we do when we use the standard Tofts model. The fourth
  step was ?nding the arterial input function, which is used as an input for the pharmacokinetic
  model. In literature there are several methods, we discussed three: the use of a
  standardized input function (population averaged or mathematical), the use of a
  single reference tissue approach and the use of a multiple refernce tissue approach.
  We found that errors caused by using a population averaged input function can be
  quite large as deviations from the true local input functions are seen directly
  in the pharmacokinetic parameters. The single reference tissue approach is another
  way to estimate the input function. We found that when we know the exact pharmacokinetic
  parameters of the reference tissue the errors are considerably lower than in the
  use of a standardized AIF. When pharmacokinetic parameters of the reference tissue
  are wrong however we can still induce large errors in parameter estimates. The third
  option was the use of a multiple reference tissue approach, which gave the best
  results. If multiple reference tissue are available within the data set this option
  should be used. The last step is to put together the pieces from the previous steps
  and use that to analyze the clinical data. We were able to use 14 patient data sets.
  Although a small number, we were able to see that there seems to be a relation between
  malignancy and Ktrans values. Benign tissues seemed to have lower Ktrans values
  when compared to malignant tissues. Another question was if we were able to cluster
  different cancer types according to pharmacokinetic parameters, but we have too
  little data to support that claim.'
---
