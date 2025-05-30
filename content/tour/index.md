---
title: Tour
date: 2022-10-24

type: landing

sections:
  - block: slider
    content:
      slides:
      - title: 👋 Welcome to the CVPD group
        content: From pixels to patterns — we blend vision, geometry, and AI
        align: left
        background:
          image:
            filename: code-vision.jpg
            filters:
              brightness: 0.5
          position: right
          color: '#666'
      - title: And beyond... ⚙️
        content: From embedding spaces to interactive systems — we keep exploring
        align: left
        background:
          image:
            filename: gpu-cluster.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#555'
      - title: Real-world impact 🌐
        content: From facial recognition to biomedical imaging — we turn theory into practice
        align: right
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./members/" cta_text="Meet the team →" %}}
    design:
      columns: '1'  
---
