---
title: ''
date: 2022-10-24
type: landing

design:
  spacing: '6rem'

sections:

  # BIO SECTION
  - block: resume-biography-3
    id: bio
    content:
      username: admin
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      css_class: hbx-bg-gradient
      avatar:
        size: medium
        shape: circle

  # RESEARCH SECTION
  - block: markdown
    id: research
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        Replace this text with your actual research summary.
    design:
      columns: '1'

  # FEATURED PAPERS
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2

  # RECENT PAPERS
  - block: collection
    id: papers-all
    content:
      title: Recent Publications
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation

  # TALKS
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - events
    design:
      view: card

  # EXPERIENCE SECTION — ADDED NEW BLOCK HERE
  - block: resume-experience
    id: experience
    content:
      title: Experience
      username: admin
    design:
      view: stacked

---
