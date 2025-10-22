---
title: "컴퓨터구조"
summary: ""
type: course
tags: ["2-2"]

goals:
  - "Goal 1️⃣ : 컴퓨터 시스템의 내부 구성 요소와 동작 원리를 이해한다."
  - "Goal 2️⃣ : 명령어의 해석 과정과 프로세서 설계 원리를 학습한다."
  - "Goal 3️⃣ : 파이프라인과 메모리 계층 구조를 이해하고 컴퓨터 성능 향상 원리를 습득한다."

instructor: "윤수경 교수님"
department: "전북대학교 컴퓨터공학부 / IT정보공학과 / IT지능정보공학과 / 컴퓨터인공지능학부"
room: "공대 7호관 534호"
language: "한국어"
credit: 3

textbook:
  title: "Computer Organization and Design RISC-V Edition: The Hardware/Software Interface"
  author: "David A. Patterson, John L. Hennessy"
  publisher: "Morgan Kaufmann"
  year: 2017
---

<!--more-->

## 📘 강의 개요

| 항목 | 내용 |
|------|------|
| **교과목명** | 컴퓨터구조 |
| **담당교수** | 윤수경 교수님 |
| **소속** | 전북대학교 컴퓨터공학부 외 |
| **강의실** | 공대 7호관 534호 |
| **강의언어** | 한국어 |

---

## 🎯 강의 목표

1️⃣ 컴퓨터 시스템의 내부 구성 요소와 동작 원리를 이해한다.  
2️⃣ 명령어의 해석 과정과 프로세서 설계 원리를 학습한다.  
3️⃣ 파이프라인과 메모리 계층 구조를 이해하고 컴퓨터 성능 향상 원리를 습득한다.

---

## 📖 교재

> Computer Organization and Design RISC-V Edition: The Hardware/Software Interface  
> David A. Patterson, John L. Hennessy 저 · Morgan Kaufmann (2017)

---

## 🧮 평가 비율

<canvas id="evaluationChart" width="400" height="400"></canvas>

<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<script>
const ctx = document.getElementById('evaluationChart');
new Chart(ctx, {
  type: 'pie',
  data: {
    labels: ['중간고사', '기말고사', '출석', '과제'],
    datasets: [{
      data: [45, 45, 10, 0],
      backgroundColor: ['#9ad0f5', '#ffb7b2', '#ffdac1', '#b5ead7'],
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
| 1주 | 강의 소개 및 컴퓨터구조 개요 이해 | Introduction to Computer Architecture |
| 2주 | 컴퓨터의 추상화 계층 이해 | Computer Abstractions and Technology |
| 3주 | 명령어 구조 및 성능 이해Ⅰ | Instruction Set: RISC-V, Number Representation |
| 4주 | 명령어 구조 및 성능 이해Ⅱ | RISC Addressing Mode, Translating and Starting a Program |
| 5주 | 명령어 구조 및 성능 이해Ⅲ | RISC-V 명령어 세트 심화 |
| 6주 | 명령어 구조 및 성능 이해Ⅳ | 프로그램 번역 및 실행 과정 |
| 7주 | 컴퓨터 연산 구조 이해Ⅰ | Arithmetic for Computers: 정수 및 실수 연산 |
| 8주 | 중간고사 | 시험 |
| 9주 | 컴퓨터 연산 구조 이해Ⅱ | 부동소수점 연산, 산술 연산 심화 |
| 10주 | 컴퓨터 연산 구조 이해Ⅲ | 연산기 설계 및 성능 평가 |
| 11주 | 프로세서 구조 이해Ⅰ | Datapath, Control, Pipelining, Hazard |
| 12주 | 프로세서 구조 이해Ⅱ | 파이프라인 및 제어 흐름 구조 |
| 13주 | 메모리 계층 구조 이해Ⅰ | Cache, Memory Technologies |
| 14주 | 메모리 계층 구조 이해Ⅱ | Virtual Memory, Cache Performance |
| 15주 | 기말고사 | 시험 |
