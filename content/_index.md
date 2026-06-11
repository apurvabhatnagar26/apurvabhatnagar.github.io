---
title: Apurva Bhatnagar
type: landing

# Page sections (Hugo Blox blocks)
# Each `block:` corresponds to a folder under `blox/` in the Hugo Blox kit.
sections:
  - block: resume-biography
    content:
      username: me

  - block: resume-experience
    id: experience
    content:
      title: Experience
      username: me
      # Show only the IDinsight role on the home page; full timeline lives on /experience/
      count: 1
    design:
      date_format: 'January 2006'
      is_education_first: false

  - block: content-collection
    id: papers
    content:
      title: Reports and Publications
      text: Selected publications and reports. Full list available on request.
      filters:
        folders:
          - publication
      count: 20
      sort_by: 'Date'
      sort_order: 'desc'
    design:
      view: citation

  - block: content-collection
    id: news
    content:
      title: Blogs and Briefs
      filters:
        folders:
          - publication
        tags:
          - brief
      count: 10
      sort_by: 'Date'
      sort_order: 'desc'
    design:
      view: citation

  - block: resume-awards
    id: certifications
    content:
      title: Certifications
      username: me

  - block: cta-card
    content:
      title: Let's connect
      text: |
        I'm always open to conversations about impact evaluation, government
        advisory in South and Southeast Asia, or AI safety and policy.
      button:
        text: Email me
        url: mailto:apurvabhatnagar26@gmail.com
---
