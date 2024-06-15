---
title: 'Projects'
# date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: collection
    content:
      title: Open Source Projects
      text: 
      filters:
        folders:
          - repos
    design:
      view: article-grid # card # article-grid
      fill_image: false
      columns: 2
  - block: collection
    content:
      title: Funded Projects
      text: 
      filters:
        folders:
          - grants
    design:
      view: article-grid # card # article-grid
      fill_image: false
      columns: 3
---
