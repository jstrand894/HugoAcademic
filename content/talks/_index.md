---
title: Recent & Upcoming Talks
cms_exclude: true
type: landing


cascade:
  - _target:
      kind: page
    params:
      show_breadcrumb: true

sections:
  - block: 'github.jstrand894.testblock'
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - talks
      custom_count: 30
    design:
      view: article-grid
      columns: 4
# View.
view: citation

# Optional header image (relative to `static/media/` folder).
banner:
  caption: ''
  image: ''
---
