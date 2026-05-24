---
# Leave the homepage title empty to use the site title
title:
date: 2026-05-24
type: landing

header:
  navbar:
    enable: true

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
  - block: collection
    id: featured-talks
    content:
      title: 代表性报告
      filters:
        folders:
          - post
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
  - block: accomplishments
    content:
      title: 荣誉与奖项
      date_format: 2006年1月
      items:
      - certificate_url: ''
        date_end: ''
        date_start: '2023-10-25'
        description: ''
        icon: award
        organization: 清华大学
        organization_url: ''
        title: 优秀学生一等奖学金
        url: ''
      - certificate_url: ''
        date_end: ''
        date_start: '2022-10-25'
        description: ''
        icon: award
        organization: 清华大学
        organization_url: ''
        title: 优秀学生一等奖学金
        url: ''
      - certificate_url: ''
        date_end: ''
        date_start: '2021-10-25'
        description: ''
        icon: award
        organization: 清华大学
        organization_url: ''
        title: 优秀学生二等奖学金
        url: ''
      - certificate_url: ''
        date_end: ''
        date_start: '2020-10-25'
        description: ''
        icon: award
        organization: 中山大学
        organization_url: ''
        title: 优秀学生一等奖学金
        url: ''
      - certificate_url: ''
        date_end: ''
        date_start: '2017-10-25'
        description: ''
        icon: award
        organization: 中山大学
        organization_url: ''
        title: 优秀学生干部
        url: ''
      - certificate_url: ''
        date_end: ''
        date_start: '2017-10-25'
        description: ''
        icon: award
        organization: 中山大学
        organization_url: ''
        title: 优秀志愿者
        url: ''
---
