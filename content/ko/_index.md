---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    id: bio
    content:
      username: admin
      text: ''
      button:
        text: 이력서 다운로드
        url: uploads/resume.pdf
      headings:
        about: '소개'
        education: '학위'
        interests: '관심 분야'
    design:
      css_class: hbx-bg-gradient
      avatar:
        size: medium
        shape: circle

  - block: markdown
    id: research
    content:
      title: "연구"
      text: |
        아래에서 금융 IT와 관련된
        **핵심 기술**과 **관련 강의**를 함께 확인하세요!

  - block: collection
    id: tech
    content:
      title: "금융 IT를 이끄는 핵심 기술"
      subtitle: "금융 산업의 디지털 혁신을 주도하는 5가지 핵심 기술 역량을 소개합니다."
      text: "각 카드를 클릭해 해당 기술의 세부 연구 내용을 확인하세요."
      filters:
        folders:
          - "tech"
      sort_by: "weight"
      sort_ascending: true
    design:
      view: article-grid
      columns: 3

  - block: collection
    id: related-courses
    content:
      title: "역량의 발판이 되는 핵심 전공 과목"
      subtitle: "금융 IT 기술의 근간이 되는 탄탄한 전공 지식을 소개합니다."
      text: "각 카드를 클릭해 해당 과목과 기술의 연결고리 설명을 확인하세요."
      filters:
        folders:
          - "related-courses"
      sort_by: "weight"
      sort_ascending: true
    design:
      view: article-grid
      columns: 3
---