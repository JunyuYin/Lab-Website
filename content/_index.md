---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title: LUMiNA Research Group
      subtitle: ''
      text: CUHKSZ
    design:
      columns: '1'
      background:
        image: 
          filename: homepage.jpg
          filters:
            brightness: 0.6
          parallax: true
          position: center
          size: cover
      spacing:
        padding: ['10px', '0', '10px', '0']
      css_class: fullscreen-hero

  - block: hero
    content:
      title: |
        LUMiNA
        Research Lab
      image:
        filename: homepage.jpg
        image_position: left
      text: |
        <br>
        <small>The LUMiNA Research Lab, established in 2025, focuses on advancing the understanding of mental disorders through the integration of machine learning, neuroimaging, and computational modeling. Our goal is to uncover the neural and behavioral mechanisms underlying psychopathology and to promote data-driven approaches in mental health research.</small>

  - block: hero
    content:
      image:
        filename: admin.jpg
        image_position: left
      text: |
        <br>
        <small>Dr. Mengxia Gao is an Assistant Professor at The Chinese University of Hong Kong, Shenzhen, with a joint appointment in the Division of Computational Social Science and Applied Psychology. Before joining CUHK Shenzhen, she worked as a Senior Research Fellow at Monash University.</small>
      design:
        columns: '1'
        css_class: "hero-image-left"
    
  - block: collection
    content:
      title: Featured Publications
      count: 5
      filters:
        folders:
          - publication
        featured_only: true
        publication_type: 'article-journal'
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      view: citation
      columns: '1'
  
  - block: slider
    content:
      slides:
      - title: 👋 Welcome to the group
        content: Take a look at what we're working on...
        align: center
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: Lunch & Learn ☕️
        content: 'Share your knowledge with the group and explore exciting new topics together!'
        align: left
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: World-Class Semiconductor Lab
        content: 'Just opened last month!'
        align: right
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: users
          icon_pack: fas
          text: Meet the Team
          url: ../people/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000
---
