---
title: "수강 강의"
summary: "3학년 2학기까지 수강한 전공 과목들"
type: landing
layout: list

# cascade:
#   - target:
#       path: '{/courses/*/**}'
#     type: course
#     params:
#       show_breadcrumb: true
#       show_author: false

sections:

  # 상단 소개 섹션
  - block: markdown
    id: intro
    content:
      title: "수강 강의"
      text: |
        김예은이 전북대학교 컴퓨터인공지능학부에 재학하면서 3학년 2학기까지 수강한 모든 전공 과목들을 한눈에 볼 수 있습니다. 
        또한, 학기별 강의 페이지에서 상세한 과목 정보를 확인할 수 있습니다.
    design:
      spacing:
        padding: [40, 0, 20, 0]

  # 강의 목록 섹션
  - block: markdown
    id: all-courses-intro
    content:
      title: "모든 강의 보기"
      subtitle: "1학년부터 3학년까지 수강한 전공 과목"
      text: "각 카드를 클릭하면 학기별 상세 페이지로 이동합니다."
    design:
      spacing:
        padding: [40, 0, 20, 0]

  # -----------------------------
  # 학기별 강의 슬라이드
  # -----------------------------

  - block: collection
    id: courses1-2
    content:
      title: "1학년 2학기"
      page_type: course
      filters:
        tag: "1-2"
      count: 0
      order: asc
    design:
      view: carousel
      columns: 2
      show_read_more: false
      show_date: false
      show_summary: true
      spacing:
        padding: [40, 0, 0, 0]


  - block: collection
    id: courses2-1
    content:
      title: "2학년 1학기"
      page_type: course
      filters:
        tag: "2-1"
      count: 0
      order: asc
    design:
      view: carousel
      columns: 2
      show_read_more: false
      show_date: false
      show_summary: true
      spacing:
        padding: [40, 0, 0, 0]


  - block: collection
    id: courses2-2
    content:
      title: "2학년 2학기"
      page_type: course
      filters:
        tag: "2-2"
      count: 0
      order: asc
    design:
      view: carousel
      columns: 2
      show_read_more: false
      show_date: false
      show_summary: true
      spacing:
        padding: [40, 0, 0, 0]


  - block: collection
    id: courses3-1
    content:
      title: "3학년 1학기"
      page_type: course
      filters:
        tag: "3-1"
      count: 0
      order: asc
    design:
      view: carousel
      columns: 2
      show_read_more: false
      show_date: false
      show_summary: true
      spacing:
        padding: [40, 0, 0, 0]


  - block: collection
    id: courses3-2
    content:
      title: "3학년 2학기"
      page_type: course
      filters:
        tag: "3-2"
      count: 0
      order: asc
    design:
      view: carousel
      columns: 2
      show_read_more: false
      show_date: false
      show_summary: true
      spacing:
        padding: [40, 0, 60, 0]
---
