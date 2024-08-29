---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

header:
  navbar:
    enable: false

sections:
  - block: slider
    content:
      slides:
      - title: Welcome to my site!
        content: I am interested in energy and climate policy research.
        align: left
        background:
          image:
            filename: yurx_5.jpg
            filters:
              brightness: 0.7
          position: left
          color: '#666'
        link:
          icon: figshare
          icon_pack: fas
          text: About me
          url: ./bio/
      - title: Leakage or Benefit? Spillovers from a Forest Offset Program in China
        content: Latest talk at the EAERE conference 2024.
        align: left
        background:
          image:
            filename: eaere_2024.jpg
            filters:
              brightness: 0.7
          position: left
          color: '#555'
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 4500
---
