---
title: Burnt area mapping with MODIS data
date: 2023-11-06
show_date: false
show_related: true
profile: false
tags: ['wildfires', 'change detection', 'remote sensing']
---

Orion Lab has assembled a novel benchmark dataset, namely FLOGA [1], for the mapping of burnt areas in the Greek region. The dataset comprises bitemporal image acquisitions from Sentinel-2 and MODIS satellites and the ground truth labels are photointerpretation mappings produced by Hellenic Fire Brigade experts. A total of 326 wildfire events all over Greece for the period 2017-2021 are covered. We have also designed a state-of-the-art Deep Learning architecture, BAM-CD, for automatic burn scar mapping using FLOGA (trained only on Sentinel-2 data).

Since BAM-CD is only trained on Sentinel-2 data, it is able to produce high-resolution burn scar mappings but can only be used when clear images are provided both for the pre- and the post-fire status. The Sentinel-2 satellites have a temporal resolution of ~5 days, i.e. a new image of a specific region is captured every 5 days, rendering our method incapable of rapid, near real-time damage assessment. Therefore, the aim of this thesis is to train Machine Learning or Deep Learning models only on MODIS data, which have a temporal resolution of 1 day. Such a model will be able to provide a quicker evaluation of the burnt area and allow local authorities and forest scientists to formulate effective response and recovery strategies for the affected ecosystem and communities.

Supervisor: Maria Sdraka

[1] https://arxiv.org/abs/2311.03339