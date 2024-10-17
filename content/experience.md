---
title: ''
date: 2024-10-17
type: landing

design:
  spacing: '3rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: tetons_cover.svg
          filters:
            brightness: 0.25
          size: cover
          position: center
          parallax: true
  - block: resume-experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: true
  # - block: resume-skills
  #   content:
  #     title: Skills & Hobbies
  #     username: admin
  #   design:
  #     show_skill_percentage: false
  - block: resume-awards
    content:
      title: Awards
      username: admin
  # - block: resume-languages
  #   content:
  #     title: Languages
  #     username: admin
  - block: 'github.jstrand894.testblock'
    id: talks
    content:
      title: Paper Presentations
      filters:
        folders:
          - talks
        featured_only: false
      custom_count: 60
    design:
      view: article-grid
      columns: 4
---

