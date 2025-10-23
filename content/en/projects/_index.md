---
title: 'Projects'
date: 2025-10-11
type: landing
image:
  filename: "media/projects-banner.jpg"
  focal_point: "center"
  perview_only: false

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: markdown
    id: projects-banner
    content:
      text: |
        <figure class="page-banner">
          <img src="/media/projects-banner.jpg" alt="Projects page banner" loading="lazy">
        </figure>
    design:
      spacing:
        padding: [0, 0, 0, 0]
  - block: collection
    content:
      title: Projects
      text: Select any project card to view more details.
      filters:
        folders:
          - projects
      sort_by: date
      sort_order: desc
    design:
      view: article-grid
      fill_image: false
      columns: 2
      show_date: false
      show_read_time: false
      show_read_more: false
---
