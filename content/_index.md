---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
show_date: false
type: landing

sections:
  - block: hero
    content:
      title: Orion Lab
      subtitle: Artificial Intelligence for Earth Observation 
      text: We like to play with big Earth Observation data and use artificial intelligence research to have a positive impact on the society and the environment. Orion Lab is a research group that belongs to the [Institute for Astronomy, Astrophysics, Space Applications and Remote Sensing](https://www.astro.noa.gr/en/) of the [National Observatory of Athens](https://www.noa.gr/en/). 
      image: 
        filename: icon.png

    design: 
      columns: '1'
      background:
        gradient_end: '#1976d2'
        gradient_start: '#004ba0'
        text_color_light: true
  - block: collection
    content:
      title: Latest Publications
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: publication
    design:
      view: compact
      columns: '1' 
      flip_alt_rows: true


  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
      # Choose an optional background color, gradient, image, or video

---

