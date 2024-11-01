---
title: Automated robust registration of grossly misregistered whole-slide images with
  varying stains
authors:
- G. Litjens
- K. Safferling
- N. Grabe
date: '2016-01-01'
publishDate: '2024-09-11T12:09:38.549509Z'
publication_types:
- paper-conference
publication: '*Medical Imaging*'
doi: 10.1117/12.2216672
abstract: Cancer diagnosis and pharmaceutical research increasingly depend on the
  accurate quantification of cancer biomarkers. Identification of biomarkers is usually
  performed through immunohistochemical staining of cancer sections on glass slides.
  However, combination of multiple biomarkers from a wide variety of immunohistochemically
  stained slides is a tedious process in traditional histopathology due to the switching
  of glass slides and re-identification of regions of interest by pathologists. Digital
  pathology now allows us to apply image registration algorithms to digitized whole-slides
  to align the differing immunohistochemical stains automatically. However, registration
  algorithms need to be robust to changes in color due to differing stains and severe
  changes in tissue content between slides. In this work we developed a robust registration
  methodology to allow for fast coarse alignment of multiple immunohistochemical stains
  to the base hematyoxylin and eosin stained image. We applied HSD color model conversion
  to obtain a less stain color dependent representation of the whole-slide images.
  Subsequently, optical density thresholding and connected component analysis were
  used to identify the relevant regions for registration. Template matching using
  normalized mutual information was applied to provide initial translation and rotation
  parameters, after which a cost function-driven affine registration was performed.
  The algorithm was validated using 40 slides from 10 prostate cancer patients, with
  landmark registration error as a metric. Median landmark registration error was
  around 180 microns, which indicates performance is adequate for practical application.
  None of the registrations failed, indicating the robustness of the algorithm.
---
