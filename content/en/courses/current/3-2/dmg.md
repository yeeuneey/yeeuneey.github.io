---
title: "데이터마이닝"
summary: ""
type: course
tags: ["3-2"]

image:
  filename: "uploads/media/data_mining.jpg"
  focal_point: "Center"
  preview_only: true
featured: true

goals:
  - "Goal 1️⃣ : 대규모 데이터로부터 유용한 정보를 추출하는 원리와 기법을 학습한다."
  - "Goal 2️⃣ : Python을 활용해 데이터마이닝 알고리즘을 구현하고 분석한다."
  - "Goal 3️⃣ : 실제 산업 데이터를 기반으로 데이터마이닝의 응용을 이해한다."

instructor: "송현제 교수님"
department: "전북대학교 컴퓨터공학부 / IT정보공학과 / 컴퓨터인공지능학부"
room: "공대 7호관 534호"
language: "한국어"
credit: 3

textbook:
  title: "Mining of Massive Datasets (3rd Edition)"
  author: "Jure Leskovec, Anand Rajaraman, Jeff Ullman"
  publisher: "Cambridge University Press"
  year: 2020
---

<!--more-->

## 📘 강의 개요

| 항목 | 내용 |
|------|------|
| **교과목명** | 데이터마이닝 |
| **담당교수** | 송현제 교수님 |
| **소속** | 전북대학교 컴퓨터공학부 외 |
| **강의실** | 공대 7호관 534호 |
| **강의언어** | 한국어 |

---

## 🎯 강의 목표

1️⃣ 대규모 데이터로부터 유용한 정보를 추출하는 원리와 기법을 학습한다.  
2️⃣ Python을 활용해 데이터마이닝 알고리즘을 구현하고 분석한다.  
3️⃣ 실제 산업 데이터를 기반으로 데이터마이닝의 응용을 이해한다.

---

## 📖 교재

> Mining of Massive Datasets (3rd Edition)  
> Jure Leskovec, Anand Rajaraman, Jeff Ullman 저 · Cambridge University Press (2020)

---

## 🧮 평가 비율

<canvas id="chart-dm" width="400" height="400"></canvas>
<script>
const ctxD = document.getElementById('chart-dm');
new Chart(ctxD, {
  type: 'pie',
  data: {
    labels: ['중간고사', '기말고사', '출석', '과제'],
    datasets: [{
      data: [35, 35, 5, 25],
      backgroundColor: ['#9ad0f5', '#ffb7b2', '#ffdac1', '#b5ead7'],
      borderColor: '#222', borderWidth: 2
    }]
  },
  options: { plugins: { legend: { position: 'bottom' } } }
});
</script>

---

## 📆 주차별 강의 내용

| 주차 | 수업목표 | 수업내용 |
|------|-----------|-----------|
| 1주 | 데이터마이닝 개요 | Introduction |
| 2주 | Frequent ItemsetsⅠ | Frequent Itemsets |
| 3주 | Frequent ItemsetsⅡ | Frequent Itemsets 심화 |
| 4주 | Similar ItemsⅠ | Finding Similar Items I |
| 5주 | Similar ItemsⅡ | Finding Similar Items II |
| 6주 | 군집화 알고리즘 학습 | Clustering |
| 7주 | 그래프 기반 커뮤니티 탐지 | Community Detection in Graphs |
| 8주 | 중간고사 | 시험 |
| 9주 | 차원 축소 기법 이해 | Dimensionality Reduction |
| 10주 | PageRank 알고리즘 | PageRank |
| 11주 | 추천 시스템Ⅰ | Recommender Systems - 1 |
| 12주 | 추천 시스템Ⅱ | Recommender Systems - 2 |
| 13주 | 데이터 스트림 마이닝Ⅰ | Mining Data Stream I |
| 14주 | MapReduce 및 Spark 학습 | MapReduce and Spark |
| 15주 | 기말고사 | 시험 |
