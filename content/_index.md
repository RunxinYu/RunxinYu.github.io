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
        align: left
        background:
          video:
            filename: hbd.mp4
            flip: false
      - title: Happy birthday!
        content: Take a look at what we're working on...
        align: left
        background:
          image:
            filename: yurx_5.jpg
            filters:
              brightness: 0.7
          position: left
          color: '#666'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: About me
          url: ./bio/
      - title: Enjoy Life ☕️
        content: 'Share your knowledge with the group and explore exciting new topics together!'
        align: left
        background:
          image:
            filename: yurx_1.jpg
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
