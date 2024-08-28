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
      - title: Happy birthday!
        content: Take a look at what we're working on...
        align: center
        background:
          image:
            filename: yurx_5.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000
---
