---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:

  - block: slider
    content:
      slides:
      - title: 👋 Welcome to the Biophotonics Lab!
        content:
        align: center
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: 3D Lab Tour
        content: 'Explore a LiDAR-based representation of our lab space.'
        align: left
        background:
          image:
            filename: lab1.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
        link:
          icon: cube
          icon_pack: fas
          text: Open 3D tour
          url: ../labtour/

      - title: Cool images we are proud of!
        content: 'Take a look!'
        align: right
        background:
          image:
            filename: chamber1.jpeg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Go to Gallery
          url: ../gallery/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000   

  - block: hero
    content:
      title: |
        Piazza
        Research Group
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The **Piazza Research Group** has been a center of excellence for biophotonics, teaching, and practice since its founding in 2014.
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 9
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
      view: compact
      columns: '3'
  
  - block: collection
    content:
      title: Publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article-journal'
    design:
      view: citation
      columns: '1'
      
---
