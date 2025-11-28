---
title: ''
date: 2022-10-24
type: landing

design:
  spacing: '4rem'

sections:

  # ABOUT
  - block: resume-biography-3
    id: about
    content:
      username: admin
      text: ""
      headings:
        about: "About"
        interests: ""
    design:
      css_class: hbx-bg-gradient
      avatar:
        size: medium
        shape: circle

  # EDUCATION
  - block: resume-experience
    id: education
    content:
      title: Education
      username: admin
      section: education   # MUST MATCH admin/_index.md key
    design:
      view: stacked

  # EXPERIENCE
  - block: resume-experience
    id: experience
    content:
      title: Experience
      username: admin
      section: work
    design:
      view: stacked

  # AWARDS
  - block: resume-experience
    id: awards
    content:
      title: Awards
      username: admin
      section: awards
    design:
      view: stacked

  # TALKS
  - block: collection
    id: talks
    content:
      title: Talks
      filters:
        folders:
          - events
    design:
      view: card

  # PAPERS
  - block: collection
    id: papers
    content:
      title: Papers
      filters:
        folders:
          - publications
    design:
      view: citation

  # PATENTS
  - block: collection
    id: patents
    content:
      title: Patents
      filters:
        folders:
          - patents
    design:
      view: article-grid
      columns: 1
---
