---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: 
        content: ''
        align: center
        background:
          image:
            filename: Hello.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: 
        content: ''
        align: left
        background:
          image:
            filename: icon.png
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: 
        content: ''
        align: right
        background:
          image:
            filename: goodbye.png
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: contact
          url: ../en/contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '200px'
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000

  
  - block: collection
    content:
      title: Recent photos
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
  
#  - block: markdown
#    content:
#      title:
#      subtitle: ''
#      text:
#    design:
#      columns: '1'
#      background:
#        image: 
#          filename: coders.jpg
#          filters:
#            brightness: 1
#          parallax: false
#          position: center
#          size: cover
#          text_color_light: true
#      spacing:
#        padding: ['20px', '0', '20px', '0']
#      css_class: fullscreen

  - block: collection
    content:
      title: School of origin
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'school'
    design:
      view: citation
      columns: '1'
  



  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Introduce MySelf →" %}}
    design:
      columns: '1'
---
