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
