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
  - block: skills
    content:
      title: Skills & Hobbies
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'
  - block: experience
    id: experience
    content:
      title: Professional Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Energy specialist
          company: Ministry of Finance of the People’s Republic of China
          company_url: ''
          location: Beijing
          date_start: '2024-02-02'
          date_end: '2024-04-02'
          description: special research on “Accelerating the Establishment of a Fiscal and Taxation System Corresponding to the Dual Carbon Goals”
        - title: Researcher
          company: Ministry of Ecology and Environment of the People’s Republic of China
          company_url: ''
          location: Beijing
          date_start: '2023-07-02'
          date_end: '2023-12-02'
          description: extensive research on the design of international carbon pricing initiates and assisting in related policy tracking and analysis
    design:
      columns: '2'
---
