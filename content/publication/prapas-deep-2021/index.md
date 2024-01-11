---
title: Deep Learning Methods for Daily Wildfire Danger Forecasting

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Ioannis Prapas
- Spyros Kondylatos
- Ioannis Papoutsis
- Gustau Camps-Valls
- Michele Ronco
- Miguel-Ángel Fernández-Torres
- Maria Piles Guillem
- Nuno Carvalhais

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: ['Equal Contribution','Equal Contribution']

date: '2021-11-04'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2023-11-06T10:26:25.783758Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- manuscript

# Publication name and optional abbreviated publication name.
publication: '*arXiv*'
publication_short: ''

doi: ''

abstract: Wildfire forecasting is of paramount importance for disaster risk reduction
  and environmental sustainability. We approach daily fire danger prediction as a
  machine learning task, using historical Earth observation data from the last decade
  to predict next-day's fire danger. To that end, we collect, pre-process and harmonize
  an open-access datacube, featuring a set of covariates that jointly affect the fire
  occurrence and spread, such as weather conditions, satellite-derived products, topography
  features and variables related to human activity. We implement a variety of Deep
  Learning (DL) models to capture the spatial, temporal or spatio-temporal context
  and compare them against a Random Forest (RF) baseline. We find that either spatial
  or temporal context is enough to surpass the RF, while a ConvLSTM that exploits
  the spatio-temporal context performs best with a test Area Under the Receiver Operating
  Characteristic of 0.926. Our DL-based proof-of-concept provides national-scale daily
  fire danger maps at a much higher spatial resolution than existing operational solutions.

# Summary. An optional shortened abstract.
summary: ''

tags: [wildfires]

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: ''
url_code: 'https://github.com/Orion-AI-Lab/wildfire_forecasting'
url_dataset: 'https://zenodo.org/records/6475592'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

categories: ['Code']

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
links:
- name: URL
  url: http://arxiv.org/abs/2111.02736
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
