---
title: "웹서비스설계"
summary: ""
type: course
tags: ["3-2"]

image:
  filename: "uploads/media/web_service_design.jpg"
  focal_point: "Center"
  preview_only: true
featured: true

goals:
  - "Goal 1️⃣ : 현대 웹서비스의 구조와 백엔드 설계·REST API 설계 원리를 이해한다."
  - "Goal 2️⃣ : Node.js/Express, Spring Boot, FastAPI/Flask 등 주요 백엔드 프레임워크를 실습한다."
  - "Goal 3️⃣ : 인증·보안, DB/ORM, CI/CD, Docker·Kubernetes 등 배포·인프라 환경을 이해하고 적용한다."

instructor: "이경수 교수님"
department: "전북대학교 컴퓨터공학부 / IT정보공학과 / 컴퓨터인공지능학부"
room: "공대 3호관 311호"
language: "한국어"
credit: 3

textbook:
  title: "Node.js 백엔드 개발자 되기"
  author: "박승규"
  publisher: "lulu.com"
  year: 2009
---

<!--more-->

## 📘 강의 개요

| 항목 | 내용 |
|------|------|
| **교과목명** | 웹서비스설계 |
| **담당교수** | 이경수 교수님 |
| **소속** | 전북대학교 컴퓨터공학부 외 |
| **강의실** | 공대 3호관 311호 |
| **강의언어** | 한국어 |

---

## 🎯 강의 목표

1️⃣ 현대 웹서비스의 구조와 백엔드 설계·REST API 설계 원리를 이해한다.  
2️⃣ Node.js/Express, Spring Boot, FastAPI/Flask 등 주요 백엔드 프레임워크를 실습한다.  
3️⃣ 인증·보안, DB/ORM, CI/CD, Docker·Kubernetes 등 배포·인프라 환경을 이해하고 적용한다.

---

## 📖 교재

> Node.js 백엔드 개발자 되기  
> 박승규 저 · lulu.com (2009)

---

## 🧮 평가 비율

<canvas id="chart-web" width="400" height="400"></canvas>
<script>
const cWEB = document.getElementById('chart-web');
new Chart(cWEB, {
  type: 'pie',
  data: {
    labels: ['중간고사', '기말고사', '출석', '과제', '발표/토론', '수업태도', '기타'],
    datasets: [{ data: [0, 0, 5, 80, 5, 0, 10], backgroundColor: ['#9ad0f5','#ffb7b2','#ffdac1','#b5ead7','#c7ceea','#f6a5c0','#cfd8dc'], borderColor:'#222', borderWidth:2 }]
  },
  options: { plugins:{ legend:{ position:'bottom' } } }
});
</script>

---

## 📆 주차별 강의 내용

| 주차 | 수업목표 | 수업내용 |
|------|-----------|-----------|
| 1주 | 웹서비스 구조 이해 | OT, 개발자 로드맵 |
| 2주 | 웹서비스 구조 심화 | 서버 종류와 구조 |
| 3주 | 백엔드 구조 이해 | 백엔드 서버 구조, 아키텍처 디자인 |
| 4주 | 프레임워크·HTTP | Node.js & Express, HTTP, REST API |
| 5주 | 인증·문서화 | JWT, Swagger, Postman |
| 6주 | 프레임워크 실습 I | Express/Spring Boot 기초 |
| 7주 | 프레임워크 실습 II | Spring Boot 심화, Flask/FastAPI |
| 8주 | Term Project I 마감 | 중간기간 보완 |
| 9주 | DB/ORM | RDB·NoSQL, JPA/MyBatis/Prisma/SQLAlchemy |
| 10주 | OAuth/소셜 로그인 | Google/카카오, Firebase 연동 |
| 11주 | 통신 프로토콜 | WebSocket, MQTT 등 |
| 12주 | 유지보수·테스트 | 로깅·테스트·문서화 |
| 13주 | CI/CD | 자동화·GitHub Actions |
| 14주 | 컨테이너/오케스트레이션 | Docker, Kubernetes |
| 15주 | Term Project III 마감 | 서버 배포 제출 |
