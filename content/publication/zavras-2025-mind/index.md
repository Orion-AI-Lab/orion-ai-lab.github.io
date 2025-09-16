---
title: 'Mind the modality gap: Towards a remote sensing vision-language model via
  cross-modal alignment'
authors:
- Angelos Zavras
- Dimitrios Michail
- Begüm Demir
- Ioannis Papoutsis
date: '2025-01-01'
publishDate: '2025-09-16T13:44:27.895822Z'
publication_types:
- article-journal
publication: '*ISPRS Journal of Photogrammetry and Remote Sensing*'
doi: https://doi.org/10.1016/j.isprsjprs.2025.06.019
abstract: 'Deep Learning (DL) is undergoing a paradigm shift with the emergence of
  foundation models. In this work, we focus on Contrastive Language-Image Pre-training
  (CLIP), a Vision-Language foundation model that achieves high accuracy across various
  image classification tasks and often rivals fully supervised baselines, despite
  not being explicitly trained for those tasks. Nevertheless, there are still domains
  where zero-shot CLIP performance is far from optimal, such as Remote Sensing (RS)
  and medical imagery. These domains do not only exhibit fundamentally different distributions
  compared to natural images, but also commonly rely on complementary modalities,
  beyond RGB, to derive meaningful insights. To this end, we propose a methodology
  to align distinct RS image modalities with the visual and textual modalities of
  CLIP. Our two-stage procedure addresses the aforementioned distribution shift, extends
  the zero-shot capabilities of CLIP and enriches CLIP’s shared embedding space with
  domain-specific knowledge. Initially, we robustly fine-tune CLIP according to the
  PAINT (Ilharco et al., 2022) patching protocol, in order to deal with the distribution
  shift. Building upon this foundation, we facilitate the cross-modal alignment of
  a RS modality encoder by distilling knowledge from the CLIP visual and textual encoders.
  We empirically show that both patching and cross-modal alignment translate to significant
  performance gains, across several RS imagery classification and cross-modal retrieval
  benchmark datasets. Patching dramatically improves RS imagery (RGB) classification
  (BigEarthNet-5: +39.76% mAP, BigEarthNet-19: +56.86% mAP, BigEarthNet-43: +28.43%
  mAP, SEN12MS: +20.61% mAP, EuroSAT: +5.98% Acc), while it maintains performance
  on the representative supported task (ImageNet), and most critically it outperforms
  existing RS-specialized CLIP variants such as RemoteCLIP (Liu et al., 2023a) and
  SkyCLIP (Wang et al., 2024). Cross-modal alignment extends zero-shot capabilities
  to multi-spectral data, surpassing our patched CLIP classification performance and
  establishing strong cross-modal retrieval baselines. Linear probing further confirms
  the quality of learned representations of our aligned multi-spectral encoder, outperforming
  existing RS foundation models such as SatMAE (Cong et al., 2022). Notably, these
  enhancements are achieved without the reliance on textual descriptions, without
  introducing any task-specific parameters, without training from scratch and without
  catastrophic forgetting. Our work highlights the potential of leveraging existing
  VLMs’ large-scale pre-training and extending their zero-shot capabilities to specialized
  fields, paving the way for resource efficient establishment of in-domain multi-modal
  foundation models in RS and beyond. We make our code implementation and weights
  for all experiments publicly available on our project’s GitHub repository https://github.com/Orion-AI-Lab/MindTheModalityGap.'
tags:
- Vision-language model
- Foundation model
- Multi-modal learning
- Cross-modal alignment
- Cross-modal retrieval
- Cross-modal distillation
- Satellite representation learning
- Remote sensing

categories: ['Code']
featured: false
url_code: 'https://github.com/Orion-AI-Lab/MindTheModalityGap'

links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S092427162500245X
---
