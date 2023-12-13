---
title: Self-supervised learning on datacubes for wildfire forecasting
date: 2023-12-13
show_date: false
show_related: true
profile: false
tags: ['SSL', 'wildfires', 'forecasting', 'deep learning']
---

Our lab has created large-scale datasets for wildfire forecasting ([Greek Datacube](https://zenodo.org/records/6475592), [Mesogeos](https://orion-ai-lab.github.io/mesogeos/), [SeasFire Datacube](https://arxiv.org/abs/2312.07199)). The potential of these datasets remains untapped and could potentially be harvested with Self-Supervised Learning (SSL) methods. 

<!--more-->

Wildfires are a spatiotemporally rare phenomenon. Even in the day with the most burned areas in Europe, only a small percentage of the cells in the Mesogeos cube will be affected. Our previous work ([1](https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/2022GL099368), [2](https://orion-ai-lab.github.io/mesogeos/), [3](https://arxiv.org/abs/2306.10940)) has focused on samples of affected pixels, ignoring most of the datacube, i.e. learning from variable interactions, non-burned pixels etc. SSL methods offer a way to learn good representations of our data and the apply those to the downstream task of wildfire prediction. This thesis will explore latest SSL methods and seek to advance wildfire danger forecasting. Starting points for SSL methods: [SimCLR](https://arxiv.org/abs/2002.05709), [MoCo](https://arxiv.org/abs/2003.04297v1), [Dino](https://arxiv.org/abs/2104.14294), [Dino V2](https://arxiv.org/abs/2304.07193), [Masked Autoencoders](https://arxiv.org/abs/2111.06377)


**Supervisors**: [Ioannis Prapas](/author/ioannis-prapas/), [Spyros Kondylatos](/author/spyros-kondylatos/), [Ioannis Papoutsis](/author/ioannis-papoutsis)

**Relevant skills**: Python, Deep Learning basics, Deep Learning library (pytorch, jax, tensorflow), Remote Sensing basics