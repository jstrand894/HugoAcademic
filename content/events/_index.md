---
title: Events
cms_exclude: true
type: landing


cascade:
  - _target:
      kind: page
    params:
      show_breadcrumb: true

sections:
  - block: 'github.jstrand894.testblock'
    id: events
    content:
      title: Events
      filters:
        folders:
          - events
    design:
      view: article-grid
      columns: 2
# View.
view: citation

# Optional header image (relative to `static/media/` folder).
banner:
  caption: ''
  image: ''
---
