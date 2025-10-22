---
# Leave the homepage title empty to use the site title
title: ''
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
              <h3>Ye-eun Kim's Portfolio</h3>
              <p>WELCOME TO Ye-eun Kim's PORTFOLIO!</p>
            </div>
            <div class="swiper-slide" style="background-image:url(/media/slider2.jpg)">
              <h3>Research</h3>
              <p>Explore core technologies and related courses.</p>
            </div>
            <div class="swiper-slide" style="background-image:url(/media/slider3.jpg)">
              <h3>Projects</h3>
              <p>Discover projects alongside their GitHub links.</p>
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
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: 'About Me'
        education: 'Education'
        experience: 'Experience'
        interests: 'Interests'
        skills: 'Skills'
        hobbies: 'Hobbies'
        languages: 'Languages'
        awards: 'Awards'
    design:
      css_class: 'custom-hero'
      avatar:
        size: medium
        shape: circle

  - block: collection
    id: tech
    content:
      title: "Core Technologies Driving Financial IT"
      subtitle: "Meet the six key technical competencies powering digital innovation in finance."
      text: "Select each item to explore detailed insights on the technology."
      count: 0
      filters:
        folders:
          - "tech"
      sort_by: "weight"
      sort_ascending: true
    design:
      view: showcase
      columns: 3

  - block: collection
    id: related-courses
    content:
      title: "Essential Courses Behind My Expertise"
      subtitle: "Discover the six major courses underpinning my finance-focused skill set."
      text: "Open card to learn how the course connects to the highlighted technology."
      count: 0
      filters:
        folders:
          - "related-courses"
      sort_by: "weight"
      sort_ascending: true
    design:
      view: showcase
      columns: 3
---
