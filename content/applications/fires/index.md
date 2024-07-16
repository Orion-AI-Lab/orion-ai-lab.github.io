---
date: 2024-07-16
show_date: false
show_author: false
# profile=True shows author
profile: false    
_build:
  # make render never if you don't want the page to open
  render: always
  list: always
title: Fire Hazard Forecasting (FireWatchGreece)
tags: 
  - wildfires
show_related: true
# links:
# - icon_pack: fa
#   icon: globe # code, file-pdf
#   name: Website
#   url: https://www.7shield.eu/
---

Orion Lab has developed deep learning methods for daily wildfire danger forecasting. We approach daily fire danger prediction as a machine learning task, using historical Earth observation data from the last decade to predict next-day’s fire danger. Our work aims at producing fire hazard forecasts at large scales and with better spatial resolution compared to other existing methods and operational tools.

<!--more-->

We implement a variety of Deep Learning (DL) models to capture the spatial, temporal or spatio-temporal context and compare them against a Random Forest (RF) baseline and the fire weather index

Our DL-based proof-of-concept provides national-scale daily fire danger maps at a much higher spatial resolution than existing operational solutions.

![](applications/fire_1.png)
Figure: Example of a DL-powered fire danger map.

We use *explainable Artificial Intelligence* methods on top of our DL models to gain more insights about the predictions. 
This allows us to answer important questions, for example: 
- which are the main drivers? 
- are there meaningful space/time patterns that increase fire risk? 
- are there ways to know how sure the model is about a prediction? 
- what is the impact of a change of a predictor on the fire risk?

Visit [**FireWatchGreece**](https://orion-watch.space.noa.gr/FireWatchGreece/ui/pages/map) to explore daily forecasts and explainability plots! 