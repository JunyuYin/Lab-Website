---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

---
title: My Page
type: landing

sections:
  - block: hero
    content:
      title: |
        LUMiNA Lab
      image:
        filename: homepage.jpg
      text: |
        <br>
        The **LUMiNA Lab** has been a center of excellence for Artificial Intelligence research, teaching, and practice since its founding in 2016.
    design:
      css_class: "min-h-screen flex items-center justify-center text-center"
      background:
        image:
          filename: homepage.jpg
          size: cover          
          position: center    
          filters:
            brightness: 0.5   
          parallax: true       
        text_color_light: true   
  
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
