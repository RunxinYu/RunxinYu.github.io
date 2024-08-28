---
# Leave the homepage title empty to use the site title
title: ''
date: 2024-5-24
type: landing

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
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: skills
    content:
      title: Skills & Hobbies
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
  - block: languages
    content:
      title: 语言
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'
---
