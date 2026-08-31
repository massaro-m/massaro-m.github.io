---
title: Publications
cms_exclude: true
type: landing

cascade:
  - target:
      path: '{/publications/*/**}'
    type: docs
    params:
      show_breadcrumb: true

section:
  - block: collection
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
         - publications
        exclude_featured: false
    design:
      view: citation
# View.
#view: citation

# Optional header image (relative to `static/media/` folder).
#banner:
#  caption: ''
#  image: ''
---