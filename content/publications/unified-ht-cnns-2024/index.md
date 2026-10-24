---
title: "Unified HT-CNNs Architecture: Transfer Learning for Segmenting Diverse Brain Tumors in MRI from Gliomas to Pediatric Tumors"
authors:
  - "admin"
  - "Franziska Mathis-Ullrich"
date: '2024-12-11'
publishDate: '2024-12-11'
publication_types: ["article"]
publication: "*arXiv preprint* arXiv:2412.08240"
abstract: "Accurate segmentation of brain tumors from 3D multimodal MRI is vital for diagnosis and treatment planning across diverse brain tumors. This paper addresses the challenges posed by the BraTS 2023, presenting a unified transfer learning approach that applies to a broader spectrum of brain tumors. We introduce HT-CNNs, an ensemble of Hybrid Transformers and Convolutional Neural Networks optimized through transfer learning for varied brain tumor segmentation. This method captures spatial and contextual details from MRI data, fine-tuned on diverse datasets representing common tumor types. Through transfer learning, HT-CNNs utilize the learned representations from one task to improve generalization in another, harnessing the power of pre-trained models on large datasets and fine-tuning them on specific tumor types. We preprocess diverse datasets from multiple international distributions, ensuring representativeness for the most common brain tumors. Our rigorous evaluation employs standardized quantitative metrics across all tumor types, ensuring robustness and generalizability. The proposed ensemble model achieves superior segmentation results across the BraTS validation datasets over the previous winning methods. Comprehensive quantitative evaluations using the DSC and HD95 demonstrate the effectiveness of our approach. Qualitative segmentation predictions further validate the high-quality outputs produced by our model. Our findings underscore the potential of transfer learning and ensemble approaches in medical image segmentation, indicating a substantial enhancement in clinical decision-making and patient care. Despite facing challenges related to post-processing and domain gaps, our study sets a new precedent for future research for brain tumor segmentation. The docker image for the code and models has been made publicly available, https://hub.docker.com/r/razeineldin/ht-cnns."
featured: false
hugoblox:
  ids:
    arxiv: "2412.08240"
links:
  - type: pdf
    url: "https://arxiv.org/pdf/2412.08240"
---
