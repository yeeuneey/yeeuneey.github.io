---
title: "초급프로젝트"
summary: ""
type: course
tags: ["3-2"]

image:
  filename: "uploads/media/intro_project.jpg"
  focal_point: "Center"
  preview_only: true
featured: true

goals:
  - "Goal 1️⃣ : 최신 개발 기술(TS, Vue/React, Git, Firebase, API 등)의 기본을 이해한다."
  - "Goal 2️⃣ : Git·GitHub 기반 협업과 디자인 패턴 적용을 통해 구조적 프로그래밍 역량을 강화한다."
  - "Goal 3️⃣ : 개인/2인 프로젝트 수행으로 실제 웹·앱 서비스 개발 경험과 문제해결·협업 능력을 배양한다."

instructor: "이경수 교수님"
department: "전북대학교 컴퓨터공학부 / IT정보공학과 / 컴퓨터인공지능학부"
room: "공대 7호관 301호"
language: "한국어"
credit: 3

textbook:
  title: "모두의 깃&깃허브"
  author: "강민철"
  publisher: "길벗"
  year: 2022
---

<!--more-->

## 📘 강의 개요

| 항목 | 내용 |
|------|------|
| **교과목명** | 초급프로젝트 |
| **담당교수** | 이경수 교수님 |
| **소속** | 전북대학교 컴퓨터공학부 외 |
| **강의실** | 공대 7호관 301호 |
| **강의언어** | 한국어 |

---

## 🎯 강의 목표

1️⃣ 최신 개발 기술(TS, Vue/React, Git, Firebase, API 등)의 기본을 이해한다.  
2️⃣ Git·GitHub 기반 협업과 디자인 패턴 적용을 통해 구조적 프로그래밍 역량을 강화한다.  
3️⃣ 개인/2인 프로젝트 수행으로 실제 웹·앱 서비스 개발 경험과 문제해결·협업 능력을 배양한다.

---

## 📖 교재

> 모두의 깃&깃허브  
> 강민철 저 · 길벗 (2022)

---

## 🧮 평가 비율

<canvas id="chart-introproj" width="400" height="400"></canvas>
<script>
const cIP = document.getElementById('chart-introproj');
new Chart(cIP, {
  type: 'pie',
  data: {
    labels: ['중간고사', '기말고사', '출석', '과제', '발표/토론', '수업태도', '기타'],
    datasets: [{ data: [20, 40, 10, 20, 10, 0, 0], backgroundColor: ['#9ad0f5','#ffb7b2','#ffdac1','#b5ead7','#c7ceea','#f6a5c0','#cfd8dc'], borderColor:'#222', borderWidth:2 }]
  },
  options: { plugins:{ legend:{ position:'bottom' } } }
});
</script>

---

## 📆 주차별 강의 내용

| 주차 | 수업목표 | 수업내용 |
|------|-----------|-----------|
| 1주 | OT 및 환경세팅 | 강의 소개, 실습 환경 세팅 |
| 2주 | TypeScript 기초 | 타입 이해, 문법 기초, 클래스/객체 |
| 3주 | 프론트엔드 기초 | TS+Vue 환경, 기초 문법·바인딩·컴포넌트 |
| 4주 | Git 기본 | Commit/PR, 브랜치, 원격 저장소 |
| 5주 | GitHub Actions/Pages | 워크플로/배포 자동화, 정적 페이지 배포 |
| 6주 | 디자인 패턴 I | 생성·구조 패턴 실습(TS+Vue) |
| 7주 | 디자인 패턴 II | 행위 패턴 실습 |
| 8주 | 중간 발표 & Firebase 소개 | 프로젝트 제안 발표, Firebase 기초 |
| 9주 | API & Firebase, AI/Streamlit | REST API, Firebase, 미니 프로젝트 |
| 10주 | 웹 개발 기초 I | React/Vue 기본, 데이터 바인딩 |
| 11주 | 웹 개발 기초 II | 상태관리·API 연동·DB 연동 |
| 12주 | 모바일 개발 I | React Native/Flutter 기초 |
| 13주 | 모바일 개발 II | 상태관리·API/DB 연동 |
| 14주 | 모바일 개발 III | 심화·소셜 로그인 연동 |
| 15주 | 최종 발표 | 최종 프로젝트 발표 및 제출 |
