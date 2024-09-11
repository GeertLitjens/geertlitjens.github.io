+++
title = "Automatic Computer Aided Detection of Abnormalities in Multi-Parametric Prostate MRI"
date = 2011-03-01
authors = ["G. Litjens", "P. Vos", "J. Barentsz", "N. Karssemeijer", "H. Huisman"]
publication_types = ["2"]
abstract = "Development of CAD systems for detection of prostate cancer has been a recent topic of research. A multi-stage computer aided detection scheme is proposed to help reduce perception and oversight errors in multi-parametric prostate cancer screening MRI. In addition, important features for development of computer aided detection systems for prostate cancer screening MRI are identified. A fast, robust prostate segmentation routine is used to segment the prostate, based on coupled appearance and anatomy models. Subsequently a voxel classification is performed using a support vector machine to compute an abnormality likelihood map of the prostate. This classification step is based on quantitative voxel features like the apparent diffusion coefficient (ADC) and pharmacokinetic parameters. Local maxima in the likelihood map are found using a local maxima detector, after which regions around the local maxima are segmented. Region features are computed to represent statistical properties of the voxel features within the regions. Region classification is performed using these features, which results in a likelihood of abnormality per region. Performance was validated using a 188 patient dataset in a leave-one-patient-out manner. Ground truth was annotated by two expert radiologists. The results were evaluated using FROC analysis. The FROC curves show that inclusion of ADC and pharmacokinetic parameter features increases the performance of an automatic detection system. In addition it shows the potential of such an automated system in aiding radiologists diagnosing prostate MR, obtaining a sensitivity of respectively 74.7% and 83.4% at 7 and 9 false positives per patient."
featured = false
publication = "*in: Medical Imaging, volume 7963 of the Proceedings of the SPIE*"
doi = "10.1117/12.877844"
projects = ["mpmri-pca"]
+++

