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
  - block: skills
    content:
      title: Skills & Hobbies
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'
  - block: experience
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
        - title: Intern
          company: China International Capital Corporation
          company_url: ''
          location: Beijing
          date_start: '2021-01-02'
          date_end: '2021-04-02'
          description: assisting in drafting regional carbon neutrality reports, China-US climate cooperation reports, and daily data collection
    design:
      columns: '2'
  - block: experience
    content:
      title: Research Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Investigator
          company: Ministry of Ecology and Environment of the People’s Republic of China
          company_url: ''
          location: Beijing
          date_start: '2024-02-02'
          date_end: ''
          description: “Letter Requesting Assistance in Research on the Key Issues on the Construction of the National Carbon Market”
        - title: Investigator
          company: Beijing Municipal Commission of Transport
          company_url: ''
          location: Beijing
          date_start: '2023-07-02'
          date_end: '2024-07-02'
          description: “Research on the Theory of Carbon Inclusion Mechanism and the Additionality of Corresponding Generated Carbon Credits”
    design:
      columns: '2'
  - block: languages
    content:
      title: Languages
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'
---
