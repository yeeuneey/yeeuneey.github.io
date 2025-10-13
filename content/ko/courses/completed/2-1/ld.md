---
title: "논리설계"
summary: ""
type: course
tags: ["2-1"]

image:
  filename: "uploads/media/logic_design.jpg"
  focal_point: "Center"
  preview_only: true
featured: true

goals:
  - "Goal 1️⃣ : 디지털 시스템의 기본 개념과 동작 원리를 이해하여 디지털 시스템 설계에 대한 폭넓은 시각을 기른다."
  - "Goal 2️⃣ : 논리회로를 구성하는 기본 소자와 조합회로 및 순차회로의 설계 이론을 학습한다."
  - "Goal 3️⃣ : 논리회로 설계 능력을 바탕으로 디지털 시스템의 구조를 이해하고 응용할 수 있는 능력을 기른다."

instructor: "윤수경 교수님"
department: "전북대학교 컴퓨터공학부 / IT정보공학과 / IT지능정보공학과 / 컴퓨터인공지능학부"
room: "공대 7호관 534호"
language: "한국어"
credit: 3

textbook:
  title: "처음 만나는 디지털 논리회로"
  author: "임석구, 홍경호"
  publisher: "한빛아카데미"
  year: 2016
---

<!--more-->

## 📘 강의 개요

| 항목 | 내용 |
|------|------|
| **교과목명** | 논리설계 |
| **담당교수** | 윤수경 교수님 |
| **소속** | 전북대학교 컴퓨터공학부 외 |
| **강의실** | 공대 7호관 534호 |
| **강의언어** | 한국어 |

---

## 🎯 강의 목표

1️⃣ 디지털 시스템의 기본 개념과 동작 원리를 이해하여 디지털 시스템 설계에 대한 폭넓은 시각을 기른다.  
2️⃣ 논리회로를 구성하는 기본 소자와 조합회로 및 순차회로의 설계 이론을 학습한다.  
3️⃣ 논리회로 설계 능력을 바탕으로 디지털 시스템의 구조를 이해하고 응용할 수 있는 능력을 기른다.

---

## 📖 교재

> 처음 만나는 디지털 논리회로  
> 임석구, 홍경호 저 · 한빛아카데미 (2016)

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
      data: [40, 40, 10, 10],
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
| 1주 | 디지털 시스템의 개념 이해 | 디지털 시스템 소개, Course Overview |
| 2주 | 수의 체계 이해 | 디지털 시스템에서 사용하는 수의 체계 |
| 3주 | 논리 게이트 이해 | NOT, AND, OR, NAND, NOR 게이트 등 |
| 4주 | 부울대수 이해 Ⅰ | 부울 대수 기초, 기본 논리식 표현, 부울 대수 법칙 |
| 5주 | 부울대수 이해 Ⅱ 및 논리식 간소화 Ⅰ | 논리회로식 변환, 카르노맵 |
| 6주 | 논리식 간소화 Ⅱ | 카르노맵 *(과제 1)* |
| 7주 | 조합논리회로 이해 Ⅰ | 조합논리회로 설계 |
| 8주 | 중간고사 | 시험 |
| 9주 | 조합논리회로 이해 Ⅱ | 조합논리회로 심화 |
| 10주 | 플립플롭 이해 Ⅰ | SR, D, JK 플립플롭 기본 동작 |
| 11주 | 플립플롭 이해 Ⅱ | 플립플롭 응용 |
| 12주 | 순서논리회로 이해 | 순서논리회로 개요 및 설계 |
| 13주 | 카운터·레지스터 이해 Ⅰ | 비동기식/동기식 카운터, 레지스터 *(과제 2)* |
| 14주 | 카운터·레지스터 이해 Ⅱ | 비동기식/동기식 카운터, 레지스터 심화 |
| 15주 | 기말고사 | 시험 |
