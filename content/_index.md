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
      subtitle: Artificial Intelligence and Earth Observation 
      text:  Artificial Intelligence and Earth Observation for applications that matter

        

      cta:
        label: GitHub Page
        url: https://github.com/orion-ai-lab
        icon: github
        icon_pack: fab       
      
      cta:
        label: Twitter
        url: https://twitter.com/OrionLab_NOA
        icon: twitter
        icon_pack: fab  
      
      image: 
        filename: logo_text_white.png

      

    design: 
      columns: '1'
      background:
        # gradient_end: '#1976d2'
        # gradient_start: '#004ba0'
        text_color_light: true
        image:
          # Name of image in `assets/media/`.
          filename: background.png
          # Apply image filters?
          filters:
            # Darken the image? Range 0-1 where 1 is transparent and 0 is opaque.
            brightness: 0.6
          #  Image fit. Options are `cover` (default), `contain`, or `actual` size.
          size: cover
          # Image focal point. Options include `left`, `center` (default), or `right`.
          position: center
          # Use a fun parallax-like fixed background effect on desktop? true/false
          parallax: true
          # Text color (true=light, false=dark, or remove for the dynamic theme color).
          # text_color_light: true

  # - block: slider
  #   content:
  #     slides:
  #       - title: 👋 Welcome to the group
  #         content: Take a look at what we're working on...
  #         align: center
  #         background:
  #           image:
  #             # Specify an image from `assets/media/`
  #             # or delete the image section to remove it
  #             filename: background.png
  #             filters:
  #               brightness: 0.7
  #           position: right
  #           color: '#666'
  #       - title: Lunch & Learn ☕️
  #         content: 'Share your knowledge with the group and explore exciting new topics together!'
  #         align: left
  #         background:
  #           image:
  #             # Specify an image from `assets/media/`
  #             # or delete the image section to remove it
  #             filename: background.png
  #             filters:
  #               brightness: 0.7
  #           position: center
  #           color: '#555'
  #       - title: World-Class Semiconductor Lab
  #         content: 'Just opened last month!'
  #         align: right
  #         background:
  #           image:
  #             # Specify an image from `assets/media/`
  #             # or delete the image section to remove it
  #             filename: welcome.jpg
  #             filters:
  #               brightness: 0.5
  #           position: center
  #           color: '#333'
  #         link:
  #           icon: graduation-cap
  #           icon_pack: fas
  #           text: Join Us
  #           url: ../contact/
  #   design:
  #     # Slide height is automatic unless you force a specific height (e.g. '400px')
  #     slide_height: ''
  #     # Make the slides full screen within the browser window?
  #     is_fullscreen: true
  #     # Automatically transition through slides?
  #     loop: false
  #     # Duration of transition between slides (in ms)
  #     interval: 2000

 
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

