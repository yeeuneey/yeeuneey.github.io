---
title: "데이터베이스"
summary: ""
type: course
tags: ["3-1"]

goals:
  - "Goal 1️⃣ : 데이터베이스의 기본 개념과 DBMS 구조를 이해한다."
  - "Goal 2️⃣ : ER 다이어그램과 SQL을 활용해 실제 데이터베이스를 설계하고 구축할 수 있다."
  - "Goal 3️⃣ : 데이터 보안, 트랜잭션, 정규화 등의 관리 기법을 학습한다."

instructor: "김아미 교수님"
department: "전북대학교 컴퓨터공학부 / IT정보공학과 / 컴퓨터인공지능학부"
room: "공대 7호관 204호"
language: "한국어"
credit: 3

textbook:
  title: "데이터베이스 기초와 SQL"
  author: "오세종"
  publisher: "생능출판"
  year: 2023
---

<!--more-->

## 📘 강의 개요

| 항목 | 내용 |
|------|------|
| **교과목명** | 데이터베이스 |
| **담당교수** | 김아미 교수님 |
| **소속** | 전북대학교 컴퓨터공학부 외 |
| **강의실** | 공대 7호관 204호 |
| **강의언어** | 한국어 |

---

## 🎯 강의 목표

1️⃣ 데이터베이스의 기본 개념과 DBMS 구조를 이해한다.  
2️⃣ ER 다이어그램과 SQL을 활용해 실제 데이터베이스를 설계하고 구축할 수 있다.  
3️⃣ 데이터 보안, 트랜잭션, 정규화 등의 관리 기법을 학습한다.

---

## 📖 교재

> 데이터베이스 기초와 SQL  
> 오세종 저 · 생능출판 (2023)

---

## 🧮 평가 비율

<canvas id="evaluationChart2" width="400" height="400"></canvas>
<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<script>
const ctx2 = document.getElementById('evaluationChart2');
new Chart(ctx2, {
  type: 'pie',
  data: {
    labels: ['중간고사', '기말고사', '출석', '과제'],
    datasets: [{
      data: [35, 35, 10, 20],
      backgroundColor: ['#9ad0f5', '#ffb7b2', '#ffdac1', '#b5ead7'],
      borderColor: '#222',
      borderWidth: 2
    }]
  },
  options: { plugins: { legend: { position: 'bottom' } } }
});
</script>

---

## 📆 주차별 강의 내용

| 주차 | 수업목표 | 수업내용 |
|------|-----------|-----------|
| 1주 | 데이터베이스 개요 | 데이터베이스 소개 |
| 2주 | DBMS 구조 이해 | 데이터베이스와 사용자, 시스템 |
| 3주 | 관계형 모델 학습 | 관계 연산 및 무결성 규칙 |
| 4주 | 관계대수 이해 | 관계 연산자와 SQL Developer |
| 5주 | SQL Ⅰ | SELECT, 함수, 정렬, 그룹 |
| 6주 | SQL Ⅱ | 키, 조인, 집합연산 |
| 7주 | SQL Ⅲ | CREATE, INSERT, UPDATE, DELETE |
| 8주 | 중간고사 | 시험 |
| 9주 | 뷰와 인덱스 | View 생성, Index |
| 10주 | DB 설계 Ⅰ | ERD, 물리적 모델링 |
| 11주 | DB 설계 Ⅱ | 함수적 종속성, 정규화 |
| 12주 | DB 관리 및 보안 | 계정, 권한 관리 |
| 13주 | 트랜잭션 | 병행 제어, 회복 관리 |
| 14주 | DB 기반 앱 개발 | GUI 연동 실습 |
| 15주 | 기말고사 | 시험 |
