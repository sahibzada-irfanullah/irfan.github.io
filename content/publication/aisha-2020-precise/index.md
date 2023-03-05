---
abstract: "Deep learning (DL) logarithms have shown an impressive performance
in various tasks. Among them, Single-stage object detectors (SSD) mainly depends on
classification network to extract features, multiple feature maps to predict, and classification
confidence to guide the filtration of the overlapping prediction boxes. However, there are
still two problems causing some inaccurate results: (1) In the process of feature extraction,
with the layer-by-layer acquisition of semantic information, local information is gradually lost,
resulting into less representative feature maps; (2) During the Non-Maximum Suppression
(NMS) algorithm due to inconsistency in classification and regression tasks, the classification
confidence and predicted detection position cannot accurately indicate the position of the
prediction boxes. Methods: In order to address these aforementioned issues, we propose a
new architecture, a modified version of Single Shot Multibox Detector (SSD), named Precise
Single Stage Detector (PSSD). Firstly, we improve the features by adding extra layers to
SSD. Secondly, we construct a simple and effective feature enhancement module to expand
the receptive field step by step for each layer and enhance its local and semantic information.
Finally, we design a more efficient loss function to predict the IOU between the prediction boxes
and ground truth boxes, and the threshold IOU guides classification training and attenuates
the scores, which are used by the NMS algorithm. Main Results: Benefiting from the above
optimization, the proposed model PSSD achieves exciting performance in real-time. Specifically,
with the hardware of Titan Xp and the input size of 320 pix, PSSD achieves 33.8 mAP at 45
FPS speed on MS COCO benchmark and 81.28 mAP at 66 FPS speed on Pascal VOC 2007
outperforming state-of-the-art object detection models. Besides, the proposed model performs
significantly well with larger input size. Under 512 pix, PSSD can obtain 37.2 mAP with 27
FPS on MS COCO and 82.82 mAP with 40 FPS on Pascal VOC 2007. The experiment results
prove that the proposed model has a better trade-off between speed and accuracy."
author_notes:
- 
- 
-
- "ORCID: 0000-0003-1659-6040"
- 
-
authors:
- Aisha Chandio
- Gong Gui†
- Teerath Kumar
- admin
- Ramin Ranjbarzadeh
- Arunabha M. Roy
- Akhtar Hussain
- and Yao Shen
date: "2022-10-09T00:00:00Z"
doi: ""
featured: false
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#  focal_point: ""
#  preview_only: false
#links:
#- name: Custom Link
#  url: http://example.org
#projects:
#- internal-project
publication: ""
publication_short: ""
publication_types:
- "3"
publishDate: "2022-10-09T00:00:00Z"
#slides: example
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus
#  ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.
tags:
- Objection Detection(OD)
- Precise Single Stage Detector (PSSD)
- Deep-Convolutional Neural Networks (D-CNNs)
- Deep Learning (DL)
- Machine Learning (ML)
title: "Precise Single-stage Detector"
#url_code: https://github.com/wowchemy/wowchemy-hugo-themes
#url_dataset: '#'
url_pdf: https://arxiv.org/pdf/2210.04252.pdf
#url_poster: '#'
#url_project: ""
#url_slides: ""
#url_source: '#'
#url_video: '#'
---

{{% callout note %}}
Click the *Cite* button above to download the Bibtex citation of the paper.
{{% /callout %}}

{{% callout note %}}
Click the *PDF* button above to download the paper.
{{% /callout %}}


