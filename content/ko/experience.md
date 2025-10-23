---
title: '경험'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: markdown
    id: courses-banner
    content:
      text: |
        <figure class="page-banner">
          <img src="/media/resume-banner.jpg" alt="Courses page banner" loading="lazy">
        </figure>
    design:
      spacing:
        padding: [0, 0, 0, 0]

  - block: resume-experience
    content:
      title: 경험
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false

  - block: resume-skills
    content:
      title: 기술 & 취미
      username: admin
    design:
      show_skill_percentage: false

  - block: resume-languages
    content:
      title: 언어
      username: admin
---
