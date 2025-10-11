---
title: "수강 강의"
summary: "3학년 2학기까지 수강한 전공 과목들"
type: landing

cascade:
  - target:
      path: '{/courses/*/**}'
    type: course
    params:
      show_breadcrumb: true
      show_author: false

# 페이지 섹션 구성
sections:

  # 상단 소개 섹션
  - block: markdown
    id: intro
    content:
      title: "수강 강의"
      text: |
        김예은이 전북대학교 컴퓨터인공지능학부에 재학하면서 수강한 전공 과목들을 한눈에 볼 수 있습니다.
        학기별 강의 페이지에서 상세한 과목 정보를 확인할 수 있습니다.
    design:
      spacing:
        padding: [40, 0, 20, 0]

  # 강의 목록 섹션
  - block: collection
    id: all-courses
    content:
      title: "모든 강의 보기"
      subtitle: "1학년부터 3학년까지 수강한 과목"
      text: "각 카드를 클릭하면 학기별 상세 페이지로 이동합니다."
      page_type: course
      count: 0
      filters:
        author: ""
        category: ""
        tag: ""
      order: desc
    design:
      view: card
      columns: 2
      show_read_more: false
      show_date: false
      show_summary: true
      spacing:
        padding: [60, 0, 0, 0]
---
