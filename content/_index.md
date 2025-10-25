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

  - block: markdown
    content:
      title: |
        GAO Mengxia
      text: |
        <div class="row align-items-center">
          <div class="col-md-6">
            <img src="homepage.jpg" alt="GAO Mengxia" class="w-100">
          </div>
          <div class="col-md-6">
            <small>Dr. Mengxia Gao is an Assistant Professor at The Chinese University of Hong Kong, Shenzhen, with a joint appointment in the Division of Computational Social Science and Applied Psychology. Before joining CUHK Shenzhen, she worked as a Senior Research Fellow at Monash University.</small>
          </div>
        </div>
    design:
      columns: '1'
    
  - block: collection
    content:
      title: Featured Publications
      text: |
        <br>
        {{% cta cta_link="./publication/" cta_text="See More Publications →" %}}
      count: 5
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
