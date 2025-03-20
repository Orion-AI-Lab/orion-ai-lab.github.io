---
title: 'Mind the modality gap: Towards a remote sensing vision-language model via cross-modal alignment'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Angelos Zavras
- Dimitrios Michail
- Begüm Demir
- Ioannis Papoutsis


# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-02-15'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-02-15T09:31:07.000000Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- manuscript

# Publication name and optional abbreviated publication name.
publication: '*arXiv*'
publication_short: ''

doi: ''

abstract: 'Deep Learning (DL) is undergoing a paradigm shift with the emergence of foundation models. In this work, we focus on Contrastive Language-Image Pre-training (CLIP), a Vision-Language foundation model that achieves high accuracy across various image classification tasks and often rivals fully supervised baselines, despite not being explicitly trained for those tasks. Nevertheless, there are still domains where zero-shot CLIP performance is far from optimal, such as Remote Sensing (RS) and medical imagery. These domains do not only exhibit fundamentally different distributions compared to natural images, but also commonly rely on complementary modalities, beyond RGB, to derive meaningful insights. To this end, we propose a methodology to align distinct RS image modalities with the visual and textual modalities of CLIP. Our two-stage procedure addresses the distribution shift and enhances CLIP zero-shot capabilities. Initially, we robustly fine-tune CLIP according to the PAINT patching protocol, in order to deal with the aforementioned distribution shift. Building upon this foundation, we facilitate the cross-modal alignment of a RS modality encoder by distilling knowledge from the CLIP visual and textual encoders. This process extends the zero-shot capabilities of CLIP and enriches CLIP shared embedding space with domain-specific knowledge. We ultimately demonstrate our method on the tasks of RS imagery classification and cross-modal retrieval. We empirically show that both robust fine-tuning and cross-modal alignment translate to significant performance gains, across several RS benchmark datasets. Notably, these enhancements are achieved without the reliance on textual descriptions, without introducing any task-specific parameters, without training from scratch and without catastrophic forgetting. Our work highlights the potential of leveraging existing VLMs large-scale pre-training and extending their zero-shot capabilities to specialized fields, paving the way for resource efficient establishment of in-domain multi-modal foundation models in RS and beyond.'

# Summary. An optional shortened abstract.
summary: ''

tags: ['vision-language model', 'foundation model', 'multi-modal learning', 'cross-modal alignment', 'cross-modal retrieval', 'cross-modal distillation', 'satellite representation learning', 'remote sensing']

categories: ['Code']

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: 'https://arxiv.org/pdf/2402.09816'
url_code: 'https://github.com/Orion-AI-Lab/MindTheModalityGap'
url_dataset: ''
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
  url: https://arxiv.org/abs/2402.09816
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
