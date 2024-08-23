---
title: Data curation and burnt area mapping with SAR
date: 2023-11-06
show_date: false
show_related: true
profile: false
tags: ['wildfires', 'change detection', 'mapping']
---

Orion Lab has assembled a novel benchmark dataset, namely FLOGA [1], for the mapping of burnt areas in the Greek region. The dataset comprises bitemporal image acquisitions from Sentinel-2 and MODIS satellites and the ground truth labels are photointerpretation mappings produced by Hellenic Fire Brigade experts. A total of 326 wildfire events all over Greece for the period 2017-2021 are covered. We have also designed a state-of-the-art Deep Learning architecture, BAM-CD, for automatic burn scar mapping using FLOGA (trained only on Sentinel-2 data).

Rapid assessment of the damage inflicted by a wildfire is of paramount importance since it allows local authorities and forest scientists to formulate effective response and recovery strategies for the affected ecosystem and communities. Therefore automatic mapping methods, such as Machine Learning and Deep Learning algorithms, combined with satellite data can provide an invaluable tool for a quick and robust damage monitoring without the need for field inspection or human annotation. In particular, multispectral data offer a rich source of information for the extraction of the burn scar signature, but require the absence of clouds, cloud shadows and smoke. On the other hand, SAR sensors are not affected by atmospheric conditions and can possibly offer an alternative input source to a robust Machine Learning model.

The aim of this thesis is to extend the FLOGA dataset with SAR data. For each event in the dataset, the corresponding Sentinel-1 images should be downloaded and processed into an analysis-ready state.

Subsequently, the BAM-CD model or any other model of the student’s choice will be trained on the new SAR data and its performance will be assessed.

Prerequisites: Strong Python skills

Supervisor: Maria Sdraka

[1] https://arxiv.org/abs/2311.03339