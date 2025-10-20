---
# Leave the homepage title empty to use the site title
title: '김예은'
date: 2025-10-11
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: markdown
    id: slider
    content:
      text: |
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css" />

        <div class="swiper mySwiper">
          <div class="swiper-wrapper">
            <div class="swiper-slide" style="background-image:url(/media/slider1.jpg)">
              <h3>김예은의 포트폴리오</h3>
              <p>WELCOME TO Yeeun-Kim's PORTFOLIO!</p>
            </div>
            <div class="swiper-slide" style="background-image:url(/media/slider2.jpg)">
              <h3>연구</h3>
              <p>핵심 기술 & 관련 과목을 확인하세요.</p>
            </div>
            <div class="swiper-slide" style="background-image:url(/media/slider3.jpg)">
              <h3>프로젝트</h3>
              <p>프로젝트와 github 링크를 함께 확인하세요.</p>
            </div>
          </div>
          <div class="swiper-pagination"></div>
          <div class="swiper-button-next"></div>
          <div class="swiper-button-prev"></div>
        </div>

        <script src="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js"></script>

        <script>
          var swiper = new Swiper(".mySwiper", {
            loop: true,
            speed: 1600,
            autoplay: {
              delay: 3000,
              disableOnInteraction: false,
            },
            effect: "fade", 
            fadeEffect: {
              crossFade: true,
            },
            pagination: {
              el: ".swiper-pagination",
              clickable: true,
            },
            navigation: {
              nextEl: ".swiper-button-next",
              prevEl: ".swiper-button-prev",
            },
          });

        </script>
    design:
      columns: '1'
      spacing:
        padding: ["0", "0", "0", "0"]

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
      css_class: 'custom-hero'
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
      view: myshowcase
      flip_alt_rows: true
      columns: '1'

  - block: collection
    id: related-courses
    content:
      title: "역량의 발판이 되는 핵심 전공 과목"
      subtitle: "금융 산업의 디지털 혁신을 주도하는 5가지 핵심 기술 역량을 소개합니다."
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