---
title: 'GAIA: A Global, Multi-modal, Multi-scale Vision-Language Dataset for Remote Sensing Image Analysis'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Angelos Zavras
- Dimitrios Michail 
- Xiao Xiang Zhu
- Begüm Demir
- Ioannis Papoutsis


# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2025-02-13'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-02-13T18:52:14.000000Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- manuscript

# Publication name and optional abbreviated publication name.
publication: '*arXiv*'
publication_short: ''

doi: ''

abstract: "The continuous operation of Earth-orbiting satellites generates vast and ever-growing archives of Remote Sensing (RS) images. Natural language presents an intuitive interface for accessing, querying, and interpreting the data from such archives. However, existing Vision-Language Models (VLMs) are predominantly trained on web-scraped, noisy image-text data, exhibiting limited exposure to the specialized domain of RS. This deficiency results in poor performance on RS-specific tasks, as commonly used datasets often lack detailed, scientifically accurate textual descriptions and instead emphasize solely on attributes like date and location. To bridge this critical gap, we introduce GAIA, a novel dataset designed for multi-scale, multi-sensor, and multi-modal RS image analysis. GAIA comprises of 205,150 meticulously curated RS image-text pairs, representing a diverse range of RS modalities associated to different spatial resolutions. Unlike existing vision-language datasets in RS, GAIA specifically focuses on capturing a diverse range of RS applications, providing unique information about environmental changes, natural disasters, and various other dynamic phenomena. The dataset provides a spatially and temporally balanced distribution, spanning across the globe, covering the last 25 years with a balanced temporal distribution of observations. GAIA's construction involved a two-stage process: (1) targeted web-scraping of images and accompanying text from reputable RS-related sources, and (2) generation of five high-quality, scientifically grounded synthetic captions for each image using carefully crafted prompts that leverage the advanced vision-language capabilities of GPT-4o. We also release an automated processing framework developed for this purpose, enabling the broader research community to generate captions for RS images using the web-crawled image-text data. Our extensive experiments, including fine-tuning of CLIP and BLIP2 models, demonstrate that GAIA significantly improves performance on RS image classification, cross-modal retrieval and image captioning tasks, proving its value as a crucial resource for advancing the field."

# Summary. An optional shortened abstract.
summary: ''

tags: ['vision-language dataset', 'vision-language model', 'representation learning', 'remote sensing']

categories: ['Code', 'Datasets']

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: 'https://arxiv.org/pdf/2502.09598'
url_code: 'https://github.com/Orion-AI-Lab/GAIA'
url_dataset: 'https://huggingface.co/datasets/azavras/GAIA'
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
links:
- name: URL
  url: https://arxiv.org/abs/2502.09598
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
