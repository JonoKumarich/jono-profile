---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      username: jono_kumarich
      text:
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      items:
        - title: Data Scientist
          company: Woolworths NZ
          company_url: ''
          company_logo: woolworths-logo
          location: Auckland, New Zealand
          date_start: '2021-08-01'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Analysing
              * Modelling
              * Deploying
        - title: Statistical Researcher
          company: Ministry of Education
          company_url: ''
          company_logo: ministry-of-education-logo
          location: Wellington, New Zealand
          date_start: '2020-11-01'
          date_end: '2021-08-01'
          description: Taught electronic engineering and researched semiconductor physics.
        - title: Project Analyst
          company: Smart Environmental Ltd
          company_url: ''
          company_logo: smart-environmental-logo
          location: Auckland, New Zealand
          date_start: '2018-09-01'
          date_end: '2020-11-01'
          description: Taught electronic engineering and researched semiconductor physics.
        - title: Professional Athelete
          company: Rowing New Zealand
          company_url: ''
          company_logo: silver-fern
          location: Cambridge, New Zealand
          date_start: '2017-03-01'
          date_end: '2019-08-01'
          description: Taught electronic engineering and researched semiconductor physics.
    design:
      columns: '2'
  - block: features
    content:
      title: Skills
      items:
        - name: Python
          description: 90%
          icon: python
          icon_pack: fab
        - name: dbt
          description: 100%
          icon: chart-line
          icon_pack: fas
        - name: GCP
          description: 10%
          icon: camera-retro
          icon_pack: fas
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
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: jonathankumarich@gmail.com
      phone: "+6421 024 65665"
      contact_links:
        - icon: linkedin
          icon_pack: fab
          name: Reach out on LinkedIn
          link: 'https://twitter.com/Twitter'
        - icon: medium
          icon_pack: fab
          name: Follow me on Medium
          link: 'https://medium.com/@jkakld'
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
