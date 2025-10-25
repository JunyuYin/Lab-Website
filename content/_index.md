---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        LUMiNA
        Research Lab
      image:
        filename: homepage.jpg
      text: |
        <br>
        
        The **LUMiNA Research Group** has been a center of excellence for Artificial Intelligence research, teaching, and practice since its founding in 2016.
    design:
      css_class: fullscreen
  - block: markdown
    content:
      title: LUMiNA Research Group
      subtitle: ''
      text: CUHKSZ
    design:
      columns: '2'
      background:
        image: 
          filename: homepage.jpg
          filters:
            brightness: 0.5
          parallax: true
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: "min-h-screen flex flex-col items-center justify-center text-center text-white"

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
