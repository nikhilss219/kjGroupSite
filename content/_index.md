---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title: Materials Modeling group @NCL
      columns: '1'
  - block: slider
    content:
      slides:
      - title: 👋 Welcome to the group
        content: Take a look at what we're working on...
        align: center
        background:
          image:
            filename: CO2-MgCu.png
            # filters:
            #   brightness: 0.7
          position: right
          color: '#666'
      - title: Lunch & Learn ☕️
        content: 'Share your knowledge with the group and explore exciting new topics together!'
        align: left
        background:
          image:
            filename: Shweta_Mehta_abstract_image.png
            # filters:
            #   brightness: 0.7
          position: center
          color: '#555'
      - title: World-Class Semiconductor Lab
        content: 'Just opened last month!'
        align: right
        background:
          image:
            filename: shweta_viva.jpg
            # filters:
            #   brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '400px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 500
  # - block: hero
  #   content:
  #     title: |
  #       Materials Modeling group @NCL
        
      
  #     text: |
  #       <br>
        
  #       Research in our group is driven by a quest to understand the underlying electronic structure of materials and how it affects their properties. We work with DFT based codes and develop machine learning models to predict material properties.

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
  #             filename: coders.jpg
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
  #             filename: contact.jpg
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
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
