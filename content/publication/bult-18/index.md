+++
title = "Automated segmentation of epithelial tissue in prostatectomy slides using deep learning"
date = 2018-02-01
authors = ["W. Bulten", "C. Hulsbergen - van de Kaa", "J. van der Laak", "G. Litjens"]
publication_types = ["2"]
abstract = "Prostate cancer is generally graded by pathologists based on hematoxylin and eosin (H&E) stained slides. Because of the large size of the tumor areas in radical prostatectomies (RP), this task can be tedious and error prone with known high interobserver variability. Recent advancements in deep learning have enabled development of automated systems that may assist pathologists in prostate diagnostics. As prostate cancer originates from glandular tissue, an important prerequisite for development of such algorithms is the possibility to automatically differentiate between glandular tissue and other tissues. In this paper, we propose a method for automatically segmenting epithelial tissue in digitally scanned prostatectomy slides based on deep learning. We collected 30 single-center whole mount tissue sections, with reported Gleason growth patterns ranging from 3 to 5, from 27 patients that underwent RP. Two different network architectures, U-Net and regular fully convolutional networks with varying depths, were trained using a set of sparsely annotated slides. We evaluated the trained networks on exhaustively annotated regions from a separate test set. The test set contained both healthy and cancerous epithelium with different Gleason growth patterns. The results show the effectiveness of our approach given a pixel-based AUC score of 0.97. Our method contains no prior assumptions on glandular morphology, does not directly rely on the presence of lumina and all features are learned by the network itself. The generated segmentation can be used to highlight regions of interest for pathologists and to improve cancer annotations to further enhance an automatic cancer grading system."
featured = false
publication = "*in: Medical Imaging, volume 10581 of the Proceedings of the SPIE*"
doi = "10.1117/12.2292872"
projects = ["deeppca"]
+++

