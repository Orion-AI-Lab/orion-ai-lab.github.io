---
title: 'Kuro Siwo: 12.1 billion $m^2$ under the water. A global multi-temporal satellite
  dataset for rapid flood mapping'
authors:
- Nikolaos Ioannis Bountos
- Maria Sdraka
- Angelos Zavras
- Ilektra Karasante
- Andreas Karavias
- Themistocles Herekakis
- Angeliki Thanasou
- Dimitrios Michail
- Ioannis Papoutsis

author_notes: ['Equal Contribution', 'Equal Contribution']




url_code: 'https://github.com/Orion-AI-Lab/KuroSiwo'
url_dataset: 'https://github.com/Orion-AI-Lab/KuroSiwo'
url_pdf: 'https://arxiv.org/pdf/2311.12056.pdf'


abstract: '<span style="font-size: 80%;">Global floods, exacerbated by climate change, pose severe threats to human life, infrastructure, and the environment. This urgency is highlighted by recent catastrophic events in Pakistan and New Zealand, underlining the critical need for precise flood mapping for guiding restoration
efforts, understanding vulnerabilities, and preparing for future events. While Synthetic Aperture Radar (SAR) offers day-and-night, all-weather imaging capabilities, harnessing it for deep learning is hindered by the absence of a large annotated dataset. To bridge this gap, we introduce Kuro Siwo, a meticulously curated multi-temporal dataset, spanning 32 flood events globally. Our dataset maps more than 63 billion {{< math >}}$m^2${{< /math >}} of land, with 12.1 billion of them being either a flooded area or a permanent water body. Kuro Siwo stands out for its unparalleled annotation quality to
facilitate rapid flood mapping.</span>'

summary: ''


tags: [floods, deep learning, computer vision, remote sensing, SAR, synthetic aperture radar]

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
date: '2023-11-18'
publishDate: '2023-11-27T15:58:12.211007Z'
image:
  caption: 'Spatial distribution of Kuro Siwo'
  focal_point: ''
  preview_only: false


---

## Comparison of Kuro Siwo annotations with pre-existing Copernicus Emergency Service (CEMS) flood mapping
<figure>
    <img src="example.png"
    <figcaption>
      <span style="font-size: 80%;">
      (left) Mosaic depicting Kuro Siwo samples for both VV and VH polarizations. (right) Copernicus Emergency Management
      Service (CEMS) annotations for a 2020 flood event in an agricultural area in France vis `a vis Kuro Siwo photointerpretation. <span style="color: #00B9F2;"> Cyan </span> denotes permanent water bodies while <span style="color: rgb(220,79,117);">purple</span> indicates flooded areas. Notably, errors in CEMS annotations are apparent, particularly in the
      Permanent Waters class, suggesting the possibility that the CEMS annotator solely used VH polarization for annotation in this particular
      example.</span>
</figcaption>


## Qualitative evaluation of a model trained on Kuro Siwo
![qualitative](qualitative.png)
<span style="font-size: 80%;">
Qualitative evaluation of a transformer based model in Honduras and Malawi. Flood is marked in <span style="color: rgb(220,79,117);">purple</span>, permanent waters in <span style="color: #00B9F2;">cyan</span> and
non-water areas in **black**.</span>
