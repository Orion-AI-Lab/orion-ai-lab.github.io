---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
show_date: false
type: landing

sections:
#   - block: hero
#     content:
#       title: OrionLab 
#       subtitle: Artificial Intelligence and Earth Observation 
#       text:  | 
#         ## Artificial Intelligence and Earth Observation for applications that matter
#         # 
        

#       cta:
#         label: GitHub Page
#         url: https://github.com/orion-ai-lab
#         icon: github
#         icon_pack: fab       

#       cta_alt:
#         label: Twitter
#         url: https://twitter.com/OrionLab_NOA
#         icon: twitter
#         icon_pack: fab  
      
#     #  cta_note:
#     #    label: Twitter
#     #    url: https://twitter.com/OrionLab_NOA
#     #    icon: twitter
#     #    icon_pack: fab  

#       image: 
#         filename: logo_text_white.png

      

    # design: 
    #   columns: '1'
    #   background:
    #     # gradient_end: '#1976d2'
    #     # gradient_start: '#004ba0'
    #     text_color_light: true
    #     image:
    #       # Name of image in `assets/media/`.
    #       filename: background.png
    #       # Apply image filters?
    #       filters:
    #         # Darken the image? Range 0-1 where 1 is transparent and 0 is opaque.
    #         brightness: 0.6
    #       #  Image fit. Options are `cover` (default), `contain`, or `actual` size.
    #       size: cover
    #       # Image focal point. Options include `left`, `center` (default), or `right`.
    #       position: center
    #       # Use a fun parallax-like fixed background effect on desktop? true/false
    #       parallax: true
    #       # Text color (true=light, false=dark, or remove for the dynamic theme color).
    #       # text_color_light: true

  - block: slider
    content:
      slides:
        - title: Who are we?
          content: |
            ## OrionLab is a research group established as a collaborative initiative involving both the *[National Observatory of Athens](https://www.noa.gr/en/)* and the *[National Technical University of Athens](https://www.ntua.gr/en)*. Organically, OrionLab belongs to the *[Remote Sensing Laboratory](https://www.survey.ntua.gr/en/departments/topo/topo-labs/rslab/rslab-pages)*. 
            
            ## In OrionLab, we like to play with big Earth Observation data and use Artificial Intelligence research to have a positive impact on the society and the environment. 

            # [{{< icon name="twitter" pack="fab" >}}](https://twitter.com/orionlab_noa) [{{< icon name="github" pack="fab" >}}](https://github.com/orion-ai-lab)

          align: left
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: slider/background.png
              filters:
                brightness: 0.7
            position: center
            color: '#666'
        - title: Our mission
          content: |
            ## We are committed to conducting cutting-edge research with the highest ethical standards, aiming to advance our understanding of fundamental Earth system processes and addressing key scientific questions in environmental science and the effective management of natural disasters. 
            
            ## We envision harnessing the power of artificial intelligence and Earth Observation to model and predict the impacts of climate change, fostering the development of resilient societies. 
          align: left
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: slider/5.png
              filters:
                brightness: 0.7
            position: center
            color: '#555'
          link:
            # icon: graduation-cap
            # icon_pack: fas
            text: Join Us
            url: ../contact/            
        - title: Our research focus 
          content: | 
            ## Developing foundation models for Earth Observation, applying deep learning for spatio-temporal forecasting, creating and utilizing datacubes and machine-learning ready datasets, as well as advancing knowledge retrieval and information extraction techniques from big satellite data. Additionally, we explore text-image alignment for satellite image captioning.              
          align: left
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: slider/4.png
              filters:
                brightness: 0.5
            position: center
            color: '#333'
          link:
            icon: graduation-cap
            icon_pack: fas
            text: Our Publications
            url: ../publication/    

          cta:
            label: GitHub Page
            url: https://github.com/orion-ai-lab
            icon: github
            icon_pack: fab 
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      # Make the slides full screen within the browser window?
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 4000

  # twitter timeline
  # - block: markdown
  #   content:
  #     title: Introduction
  #     subtitle: 
  #     text: |
  #       <a class="twitter-timeline" data-width="300" data-dnt="true" href="https://twitter.com/OrionLab_NOA?ref_src=twsrc%5Etfw">Tweets by OrionLab_NOA</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script> 
  #   design:
  #     columns: '1' 

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


---

