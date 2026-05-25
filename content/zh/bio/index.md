---
# Leave the homepage title empty to use the site title
title: ''
date: 2026-05-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: 个人简介
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
    design:
      background:
        image:
          filename: bg-hue.svg
  - block: collection
    id: featured-pub
    content:
      title: 代表性论文
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: skills
    content:
      title: 技能与语言
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'
---
