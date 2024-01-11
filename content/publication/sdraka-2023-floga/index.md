---
title: 'FLOGA: A machine learning ready dataset, a benchmark and a novel deep learning
  model for burnt area mapping with Sentinel-2'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Maria Sdraka
- Alkinoos Dimakos
- Alexandros Malounis
- Zisoula Ntasiou
- Konstantinos Karantzalos
- Dimitrios Michail
- Ioannis Papoutsis

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2023-11-06'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2023-11-06T09:59:46.276676Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*arXiv preprint arXiv:2311.03339*'
publication_short: ''

doi: ''

abstract: "Over the last decade there has been an increasing frequency and intensity of wildfires across the globe, posing significant threats to human and animal lives, ecosystems, and socio-economic stability. Therefore urgent action is required to mitigate their devastating impact and safeguard Earth's natural resources. Robust Machine Learning methods combined with the abundance of high-resolution satellite imagery can provide accurate and timely mappings of the affected area in order to assess the scale of the event, identify the impacted assets and prioritize and allocate resources effectively for the proper restoration of the damaged region. In this work, we create and introduce a machine-learning ready dataset we name FLOGA (Forest wiLdfire Observations for the Greek Area). This dataset is unique as it comprises of satellite imagery acquired before and after a wildfire event, it contains information from Sentinel-2 and MODIS modalities with variable spatial and spectral resolution, and contains a large number of events where the corresponding burnt area ground truth has been annotated by domain experts. FLOGA covers the wider region of Greece, which is characterized by a Mediterranean landscape and climatic conditions. We use FLOGA to provide a thorough comparison of multiple Machine Learning and Deep Learning algorithms for the automatic extraction of burnt areas, approached as a change detection task. We also compare the results to those obtained using standard specialized spectral indices for burnt area mapping. Finally, we propose a novel Deep Learning model, namely BAM-CD. Our benchmark results demonstrate the efficacy of the proposed technique in the automatic extraction of burnt areas, outperforming all other methods in terms of accuracy and robustness."

# Summary. An optional shortened abstract.
summary: ''

tags: [wildfires, deep learning, dataset, change detection, disaster monitoring]

categories: ['Datasets']

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: ''
url_code: 'https://github.com/Orion-AI-Lab/FLOGA'
url_dataset: 'https://github.com/Orion-AI-Lab/FLOGA'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
---
