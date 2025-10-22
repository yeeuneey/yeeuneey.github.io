---
title: "소프트웨어공학"
summary: ""
type: course
tags: ["2-2"]

goals:
  - "Goal 1️⃣ : 소프트웨어 개발 주기와 공학적 접근 방법을 이해하고, 요구사항 분석부터 유지보수까지의 전 과정을 학습한다."
  - "Goal 2️⃣ : 요구사항 관리, 소프트웨어 설계, 테스트, 프로젝트 관리 등 핵심 기술을 습득한다."
  - "Goal 3️⃣ : 팀 프로젝트를 통해 실제 소프트웨어 개발 경험을 쌓고 협업 및 문제 해결 능력을 향상시킨다."

instructor: "정종욱 교수님"
department: "전북대학교 컴퓨터공학부 / IT정보공학과 / IT지능정보공학과 / 컴퓨터인공지능학부"
room: "공대 7호관 534호"
language: "한국어"
credit: 3

textbook:
  title: "Software Engineering"
  author: "Ian Sommerville"
  publisher: "Pearson"
  year: 2015
---

<!--more-->

## 📘 강의 개요

| 항목 | 내용 |
|------|------|
| **교과목명** | 소프트웨어공학 |
| **담당교수** | 정종욱 교수님 |
| **소속** | 전북대학교 컴퓨터공학부 외 |
| **강의실** | 공대 7호관 534호 |
| **강의언어** | 한국어 |

---

## 🎯 강의 목표

1️⃣ 소프트웨어 개발 주기와 공학적 접근 방법을 이해하고, 요구사항 분석부터 유지보수까지의 전 과정을 학습한다.  
2️⃣ 요구사항 관리, 소프트웨어 설계, 테스트, 프로젝트 관리 등 핵심 기술을 습득한다.  
3️⃣ 팀 프로젝트를 통해 실제 소프트웨어 개발 경험을 쌓고 협업 및 문제 해결 능력을 향상시킨다.

---

## 📖 교재

> Software Engineering  
> Ian Sommerville 저 · Pearson (2015)

---

## 🧮 평가 비율

<canvas id="evaluationChart" width="400" height="400"></canvas>

<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<script>
const ctx = document.getElementById('evaluationChart');
new Chart(ctx, {
  type: 'pie',
  data: {
    labels: ['중간고사', '기말고사', '출석', '과제', '팀플'],
    datasets: [{
      data: [25, 25, 10, 10, 30],
      backgroundColor: ['#9ad0f5', '#ffb7b2', '#ffdac1', '#b5ead7', '#c7ceea'],
      borderColor: '#222',
      borderWidth: 2
    }]
  },
  options: {
    plugins: {
      legend: {
        position: 'bottom',
        labels: { color: '#ddd', font: { size: 14 } }
      }
    }
  }
});
</script>

---

## 📆 주차별 강의 내용

| 주차 | 수업목표 | 수업내용 |
|------|-----------|-----------|
| 1주 | 소프트웨어공학 개요 이해 | Introduction to Software Engineering |
| 2주 | 소프트웨어 개발 프로세스Ⅰ | Software Process |
| 3주 | 소프트웨어 개발 프로세스Ⅱ | Agile, Lean, CMMI |
| 4주 | 요구사항 분석 | Requirement Engineering *(요구사항 실습)* |
| 5주 | 시스템 모델링 이해 | System Modeling |
| 6주 | 소프트웨어 아키텍처 학습 | Architecture, View, Architecture Pattern |
| 7주 | UML 및 디자인 패턴 학습 | UML, Design Pattern |
| 8주 | 중간고사 | 시험 |
| 9주 | 소프트웨어 테스트 및 TDD | Testing & Test-Driven Development |
| 10주 | 신뢰성과 품질 관리 | Dependability, Reliability |
| 11주 | 재사용 소프트웨어 개념 이해 | Software Reuse, Product Line |
| 12주 | 컴포넌트 기반 시스템 | Component-based System, Distributed System |
| 13주 | 프로젝트 계획 및 비용 관리 | Project Planning, Estimation, Inspection |
| 14주 | 팀 프로젝트 발표 | Term Project Presentation |
| 15주 | 기말고사 | 시험 |
