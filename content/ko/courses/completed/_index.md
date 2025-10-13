---
title: "수강 완료한 강의"
summary: "1학년 2학기부터 3학년 1학기까지 수강 완료한 강의 목록"
type: landing
layout: list

sections:

  # -----------------------------
  # 상단 소개 섹션
  # -----------------------------
  - block: markdown
    id: intro
    content:
      title: "수강 과목"
      text: |
        김예은이 전북대학교 컴퓨터인공지능학부에 재학하면서  
        3학년 2학기까지 수강한 모든 전공 과목들을 한눈에 볼 수 있습니다.  

        - <strong>[**수강 중인 강의로 이동**](/#current-courses)</strong>
        - 수강 완료한 강의 보기  
          <div style="margin-left: 24px; margin-top: 6px;">
            <p style="color:#666; font-size:0.8em; margin-bottom:6px;">
              각 카드를 클릭하면 과목의 상세 페이지로 이동합니다.
            </p>
            <ul style="margin: 0; padding-left: 20px; font-size:1.05em; font-weight: 500; color:#444;">
              <li><a href="#courses1-2"><strong>1-2</strong></a></li>
              <li><a href="#courses2-1"><strong>2-1</strong></a></li>
              <li><a href="#courses2-2"><strong>2-2</strong></a></li>
              <li><a href="#courses3-1"><strong>3-1</strong></a></li>
            </ul>
          </div>
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
      order: asc
    design:
      view: slider
      height: 420px
      interval: 3000
      buttons: true
      indicators: true
      show_image: true
      show_title: true
      show_read_more: false
      show_summary: false
      spacing:
        padding: [40, 0, 0, 0]

  - block: collection
    id: courses2-1
    content:
      title: "2학년 1학기"
      page_type: course
      filters:
        tag: "2-1"
      order: asc
    design:
      view: slider
      height: 420px
      interval: 3000
      buttons: true
      indicators: true
      show_image: true
      show_title: true
      show_read_more: false
      show_summary: false
      spacing:
        padding: [40, 0, 0, 0]

  - block: collection
    id: courses2-2
    content:
      title: "2학년 2학기"
      page_type: course
      filters:
        tag: "2-2"
      order: asc
    design:
      view: slider
      height: 420px
      interval: 3000
      buttons: true
      indicators: true
      show_image: true
      show_title: true
      show_read_more: false
      show_summary: false
      spacing:
        padding: [40, 0, 0, 0]

  - block: collection
    id: courses3-1
    content:
      title: "3학년 1학기"
      page_type: course
      filters:
        tag: "3-1"
      order: asc
    design:
      view: slider
      height: 420px
      interval: 3000
      buttons: true
      indicators: true
      show_image: true
      show_title: true
      show_read_more: false
      show_summary: false
      spacing:
        padding: [40, 0, 60, 0]
---