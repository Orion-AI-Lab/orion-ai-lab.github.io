---
date: 2019-12-01
show_date: false
show_author: false
# profile=True shows author
profile: false    
_build:
  # make render never if you don't want the page to open
  render: always
  list: always
title: Volcanic activity monitoring and early unrest detection
date: 2020-12-02
draft: false
# links:
# - name: Project Website
#   url: https://www.seasfire.hua.gr
# tags:
# - ESA
---

Orion Lab is developing a global volcanic activity alert service using Synthetic Aperture Radar (SAR) data and Deep Learning architectures that can automatically detect the presence of ground deformation associated with volcanic unrest.


<!--more-->

# Background

Volcanologists and seismologists monitor volcanic activity using several different techniques, including visual observations, seismic monitoring, gas monitoring, chemical analysis, topography monitoring with Digital Elevation Models, and ground deformation monitoring. Ground deformation measurements particularly, can provide an important indicator of volcanic unrest. 
As magma fills in the underground reservoir at depth, the ground surface of the volcano typically swells. Likewise, as magma leaves the underground reservoir during an eruption, the ground surface rapidly deflates. Volcanic ground deformation is highly linked with eruption events and is often considered as precursor for a potential eruption.

![](applications/volcano_1.jpg)

Interferometric Synthetic Aperture Radar (InSAR) can systematically provide ground deformation estimations over volcanic areas and complement the existing volcanic activity detection methods, especially for remote areas where the installation of in-situ measuring equipment is difficult or where hazardous conditions prevent or limit ground-based volcano monitoring. InSAR greatly extends the ability of scientists to monitor volcanoes, because unlike other techniques that rely on measurements at a few points, InSAR produces a map of ground deformation that covers a very large spatial area with centimeter-scale accuracy. Fringes detected in wrapped interferograms over volcanic areas indicate the onset of ground surface deformation, which can potentially be associated with magma chamber fill-in at depth.

![](applications/volcano_2.jpg)


Orion Lab is developing a volcanic unrest alert service based on the detection of ground deformation. The deformation alerts will be provided to volcano observatories as an early warning service, which could be of great importance for civil protection authorities, enhancing their response effectiveness and allowing for volcanologists to deploy critical in-situ monitoring equipment to assess more accurately volcanic hazard.

We are already monitoring several volcanoes globally, including Santorini, Fagradalsfjall, Mount Etna, Taal, Ale Bagu and Sierra Negra.

# Our Deep Learning method

![](applications/volcano_3.png)

We have introduced a self-supervised learning framework, which achieves higher accuracy with respect to the state-of-the-art methods. We have showcased the effectiveness of our approach for detecting the unrest episodes preceding the eruption of the Icelandic Fagradalsfjall volcano eruption in March 2021.

Our work has been published in IEEE Geoscience and Remote Sensing Letters. To access and download the publication visit https://ieeexplore.ieee.org/document/9517282

Cite the publication: 

N. I. Bountos, I. Papoutsis, D. Michail and N. Anantrasirichai, “Self-Supervised Contrastive Learning for Volcanic Unrest Detection,” in IEEE Geoscience and Remote Sensing Letters, doi: 10.1109/LGRS.2021.3104506