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
      text: |
        <br>
        The LUMiNA Research Lab, established in 2025, focuses on advancing the understanding of mental disorders through the integration of machine learning, neuroimaging, and computational modeling. Our goal is to uncover the neural and behavioral mechanisms underlying psychopathology and to promote data-driven approaches in mental health research.
    
  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
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
