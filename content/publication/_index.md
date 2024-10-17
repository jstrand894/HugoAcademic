---
title: Publications
cms_exclude: true
type: landing


cascade:
  - _target:
      kind: page
    params:
      show_breadcrumb: true

sections:
  - block: collection
    id: publication
    content:
      title: Publications
      filters:
        folders:
          - publication
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
