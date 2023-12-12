---
title: Data curation and model finetuning for burnt area mapping
date: 2023-11-06
show_date: false
show_related: true
profile: false
tags: ['wildfires', 'change detection', 'remote sensing']
---

Orion Lab has assembled a novel benchmark dataset, namely FLOGA [1], for the mapping of burnt areas in the Greek region. The dataset comprises bitemporal image acquisitions from Sentinel-2 and MODIS satellites and the ground truth labels are photointerpretation mappings produced by Hellenic Fire Brigade experts. A total of 326 wildfire events all over Greece for the period 2017-2021 are covered. We have also designed a state-of-the-art Deep Learning architecture, BAM-CD, for automatic burn scar mapping using FLOGA (trained only on Sentinel-2 data).

The aim of this thesis is to extend the FLOGA dataset with several other wildfire events worldwide. Several other datasets for this task have been proposed in the literature covering a variety of countries and can serve as possible sources. For example, BARD [2], CaBuAr [3], NIFC GeoMAC Historic Perimeters [4] [5], Satellite Burnt Area Dataset [6], MultiEarth 2023 [7], HLS Burn Scar Scenes [8], etc.

Subsequently, the BAM-CD model will be finetuned on the new data and its performance will be assessed.

Supervisor: Maria Sdraka

[1] https://arxiv.org/abs/2311.03339 <br>
[2] https://edatos.consorciomadrono.es/dataset.xhtml?persistentId=doi:10.21950/BBQQU7  <br>
[3] https://ieeexplore.ieee.org/abstract/document/10261881 <br>
[4] https://data-nifc.opendata.arcgis.com/datasets/nifc::historic-perimeters-combined-2000-2018-geomac/about <br>
[5] https://data-nifc.opendata.arcgis.com/maps/nifc::historic-perimeters-2019 <br>
[6] https://dl.acm.org/doi/abs/10.1145/3511808.3557528  <br>
[7] https://arxiv.org/abs/2306.04738 <br>
[8] https://huggingface.co/datasets/ibm-nasa-geospatial/hls_burn_scars <br>
