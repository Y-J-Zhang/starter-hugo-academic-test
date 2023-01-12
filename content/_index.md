---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: experience
    content:
      title: Education Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Undergraduate
          company: Sichuan University
          company_url: 'https://www.scu.edu.cn/'
          company_logo: scu
          location: Chengdu, Sichuan
          date_start: '2018-09-01'
          date_end: '2022-06-31'
          description: Major in Water Science and Technology
       
        - title: Professor of Semiconductor Physics
          company: Tianjin University
          company_url: 'https://www.tju.edu.cn/'
          company_logo: tju
          location: Tianjin
          date_start: '2022-09-01'
          date_end: 'present'
          description: Major in Computer Science and Technology
    design:
      columns: '2'
  - block: collection
    id: featured
    content:
      title: Publications
      filters:
        folders:
          - publication
        featured_only: false
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
      email: yjzhang0720@gmail.com
      address:
        street: Yaguan Road No.135
        city: Tijian
        region: Jinnan
        postcode: '300354'
        country: China
        country_code: CHN
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
