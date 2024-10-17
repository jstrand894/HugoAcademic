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
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - talks
        limit: 0
    design:
      view: article-grid
      columns: 3
# View.
view: citation

# Optional header image (relative to `static/media/` folder).
banner:
  caption: ''
  image: ''
---
