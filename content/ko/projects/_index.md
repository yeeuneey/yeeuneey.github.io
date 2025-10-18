---
title: '프로젝트'
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
  - block: collection
    content:
      title: 프로젝트
      text: 각 프로젝트 카드를 누르면 상세 페이지로 이동합니다.
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