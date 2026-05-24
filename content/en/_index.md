---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

header:
  navbar:
    enable: true #false

sections:
  - block: about.biography
    id: about
    content:
      title: About Me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
    design:
      background:
        image:
          filename: bg-hue.svg
  - block: collection
    id: featured-pub
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    id: featured-talks
    content:
      title: Featured Talks
      filters:
        folders:
          - post
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: skills
    content:
      title: Skills & Lanuages
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'
  - block: accomplishments
    content:
      title: Fellowships and Awards
      date_format: Jan 2006
      items:
      - certificate_url: ''
        date_end: ''
        date_start: '2023-10-25'
        description: ''
        icon: award
        organization: Tsinghua University
        organization_url: ''
        title: Outstanding Student First-class Scholarship
        url: ''
      - certificate_url: ''
        date_end: ''
        date_start: '2022-10-25'
        description: ''
        icon: award
        organization: Tsinghua University
        organization_url: ''
        title: Outstanding Student First-class Scholarship
        url: ''
      - certificate_url: ''
        date_end: ''
        date_start: '2021-10-25'
        description: ''
        icon: award
        organization: Tsinghua University
        organization_url: ''
        title: Outstanding Student Second-class Scholarship
        url: ''
      - certificate_url: ''
        date_end: ''
        date_start: '2020-10-25'
        description: ''
        icon: award
        organization: Sun Yat-sen University
        organization_url: ''
        title: Outstanding Student First-class Scholarship
        url: ''
      - certificate_url: ''
        date_end: ''
        date_start: '2017-10-25'
        description: ''
        icon: award
        organization: Sun Yat-sen University
        organization_url: ''
        title: Outstanding Student Leader Award
        url: ''
      - certificate_url: ''
        date_end: ''
        date_start: '2017-10-25'
        description: ''
        icon: award
        organization: Sun Yat-sen University
        organization_url: ''
        title: Outstanding Volunteer Award
        url: ''

#sections:
#  - block: slider
#    content:
#      slides:
      #- title: 朱颜长似，头上花枝，岁岁年年！
      #  content: 一岁又一岁，快乐就万岁，生日快乐！
      #  align: left
      #  background:
      #    image:
      #      filename: hbd.jpg
      #      filters:
      #        brightness: 0.7
      #    position: left
      #  link:
      #    icon: figshare
      #    icon_pack: ai
      #    text: 由此，开启新的一岁 -->
      #    url: ./blog/
 #     - title: Welcome to my website!
 #       content: I am interested in energy and climate policy research.
 #       align: left
 #       background:
 #         image:
 #           filename: yurx_5.jpg
 #           filters:
 #             brightness: 0.7
 #         position: left
 #         color: '#666'
 #       link:
 #         text: About me
 #         url: ./bio/
 #     - title: Leakage or Benefit? Spillovers from a Forest Offset Program in China
 #       content: Latest talk at the EAERE conference 2024.
 #       align: left
 #       background:
 #         image:
 #           filename: eaere_2024.jpg
 #           filters:
 #             brightness: 0.7
 #         position: left
 #         color: '#555'
 #       link:
 #         text: Details
 #         url: ./post/
 #     - title: Machine Learning For Data Verification In Emissions Trading System
 #       content: Resources, Conservation and Recycling, 199, 107239.
 #       align: left
 #       background:
 #         image:
 #           filename: coal_emis.jpg
 #           filters:
 #             brightness: 0.7
 #         position: left
 #         color: '#555'
 #       link:
 #         text: Details
 #         url: ./publication/
 #   design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
 #     slide_height: ''
 #     is_fullscreen: true
      # Automatically transition through slides?
 #     loop: true
      # Duration of transition between slides (in ms)
#      interval: 5000
---
