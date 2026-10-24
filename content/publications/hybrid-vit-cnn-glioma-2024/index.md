---
title: "Explainable hybrid vision transformers and convolutional network for multimodal glioma segmentation in brain MRI"
authors:
  - "admin"
  - "M. E. Karar"
  - "Ziad Elshaer"
  - "J. Coburger"
  - "C. Wirtz"
  - "Oliver Burgert"
  - "Franziska Mathis-Ullrich"
date: '2024-02-14'
publishDate: '2024-02-14'
publication_types: ["article-journal"]
publication: "*Scientific Reports*, 14"
abstract: "Accurate localization of gliomas, the most common malignant primary brain cancer, and its different sub-region from multimodal magnetic resonance imaging (MRI) volumes are highly important for interventional procedures. Recently, deep learning models have been applied widely to assist automatic lesion segmentation tasks for neurosurgical interventions. However, these models are often complex and represented as “black box” models which limit their applicability in clinical practice. This article introduces new hybrid vision Transformers and convolutional neural networks for accurate and robust glioma segmentation in Brain MRI scans. Our proposed method, TransXAI, provides surgeon-understandable heatmaps to make the neural networks transparent. TransXAI employs a post-hoc explanation technique that provides visual interpretation after the brain tumor localization is made without any network architecture modifications or accuracy tradeoffs. Our experimental findings showed that TransXAI achieves competitive performance in extracting both local and global contexts in addition to generating explainable saliency maps to help understand the prediction of the deep network. Further, visualization maps are obtained to realize the flow of information in the internal layers of the encoder-decoder network and understand the contribution of MRI modalities in the final prediction. The explainability process could provide medical professionals with additional information about the tumor segmentation results and therefore aid in understanding how the deep learning model is capable of processing MRI data successfully. Thus, it enables the physicians’ trust in such deep learning systems towards applying them clinically. To facilitate TransXAI model development and results reproducibility, we will share the source code and the pre-trained models after acceptance at https://github.com/razeineldin/TransXAI."
featured: true
hugoblox:
  ids:
    doi: "10.1038/s41598-024-54186-7"
links:
  - type: pdf
    url: "https://www.nature.com/articles/s41598-024-54186-7.pdf"
  - type: code
    url: "https://github.com/razeineldin/TransXAI"
---
