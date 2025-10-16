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
        experience: '경험'
        interests: '관심 분야'
        skills: '기술'
        hobbies: '취미'
        languages: '언어'
        awards: '수상'
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
        아래에서 제 관심 연구 분야인 금융 IT와 관련된
        **핵심 기술**과 **관련 과목**을 함께 확인하세요!

  - block: collection
    id: tech
    content:
      title: "금융 IT를 이끄는 핵심 기술"
      subtitle: "금융 산업의 디지털 혁신을 주도하는 5가지 핵심 기술 역량을 소개합니다."
      text: "각 항목을 클릭해 해당 기술의 세부 연구 내용을 확인하세요."
      filters:
        folders:
          - "tech"
      sort_by: "weight"
      sort_ascending: true
    design:
      view: article-grid
      columns: 1

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
      
  - block: markdown
    content:
      text: |
        <style>
        #tech .article-item {
          display: flex !important; 
          flex-direction: row !important;
          align-items: center !important;
          max-width: 100% !important;
          margin-bottom: 3.5rem !important;
          background: none !important;
          border: none !important;
          box-shadow: none !important;
          padding: 0 !important;
        }

        #tech .article-item .card-image {
          flex: 0 0 40%;
          margin: 0 !important;
        }

        #tech .article-item .card-body {
          flex: 1 1 auto;
          padding: 0 0 0 2.5rem !important; 
        }

        #tech .article-item:nth-child(even) {
          flex-direction: row-reverse !important;
        }
        
        #tech .article-item:nth-child(even) .card-body {
          padding: 0 2.5rem 0 0 !important;
        }

        #tech .article-item .card-body .article-title,
        #tech .article-item .card-body .article-style,
        #tech .article-item .card-body .article-metadata {
            text-align: left !important;
        }
        #tech .article-item .article-metadata {
            justify-content: flex-start !important;
        }
        </style>
---