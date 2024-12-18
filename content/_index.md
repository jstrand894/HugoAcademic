---
# Leave the homepage title empty to use the site title
title: ""
date: 2024-11-01
type: landing

design:
  # Default section spacing
  spacing: "3rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/JRS_CV_11-1-24.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: tetons.svg
          filters:
            brightness: 0.25
          size: cover
          position: center
          parallax: false
  # - block: markdown
  #   content:
  #     title: 'My Research'
  #     subtitle: ''
  #     text: |-
  #       I am currently a research associate at Montana State University, starting my PhD in January 2025. 

  #       I am interested in understanding how insects can help solve problems and using them to promote ecological sustainability and preserving our environment. 
  #   design:
  #     columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 3
  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: ""
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: false
  #   design:
  #     view: citation
  - block: 'github.jstrand894.testblock'
    id: talks
    content:
      title: '<a href="/talks">Recent & Upcoming Talks</a>'
      filters:
        folders:
          - talks
        featured_only: true
      custom_count: 4
    design:
      view: article-grid
      columns: 3
  - block: collection
    id: events
    content:
      title: Events
      filters:
        folders:
          - events
        featured_only: false
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: date-title-summary
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
---
