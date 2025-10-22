---
title: "기계학습"
summary: ""
type: course
tags: ["3-2"]

goals:
  - "Goal 1️⃣ : 기계학습의 정의와 한계를 포함한 기본 개념과 이론을 이해한다."
  - "Goal 2️⃣ : 의사결정나무, 최근접, 퍼셉트론, 선형·확률모형, SVM, 앙상블, GMM 등 핵심 알고리즘을 학습한다."
  - "Goal 3️⃣ : 신경망, 커널 방법, 학습이론, 비지도학습 등을 통해 실제 데이터 문제에 기계학습을 적용하는 능력을 기른다."

instructor: "송현제 교수님"
department: "전북대학교 컴퓨터공학부 / IT정보공학과 / 컴퓨터인공지능학부"
room: "공대 7호관 534호"
language: "한국어"
credit: 3

textbook:
  title: "A Course in Machine Learning"
  author: "Hal Daumé III"
  publisher: "ciml.info"
  year: 2015
---

<!--more-->

## 📘 강의 개요

| 항목 | 내용 |
|------|------|
| **교과목명** | 기계학습 |
| **담당교수** | 송현제 교수님 |
| **소속** | 전북대학교 컴퓨터공학부 외 |
| **강의실** | 공대 7호관 534호 |
| **강의언어** | 한국어 |

---

## 🎯 강의 목표

1️⃣ 기계학습의 정의와 한계를 포함한 기본 개념과 이론을 이해한다.  
2️⃣ 의사결정나무, 최근접, 퍼셉트론, 선형·확률모형, SVM, 앙상블, GMM 등 핵심 알고리즘을 학습한다.  
3️⃣ 신경망, 커널 방법, 학습이론, 비지도학습 등을 통해 실제 데이터 문제에 기계학습을 적용하는 능력을 기른다.

---

## 📖 교재

> A Course in Machine Learning  
> Hal Daumé III 저 · (2015)

---

## 🧮 평가 비율

<canvas id="chart-ml" width="400" height="400"></canvas>
<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<script>
const cML = document.getElementById('chart-ml');
new Chart(cML, {
  type: 'pie',
  data: {
    labels: ['중간고사', '기말고사', '출석', '과제'],
    datasets: [{ data: [30, 30, 10, 30], backgroundColor: ['#9ad0f5','#ffb7b2','#ffdac1','#b5ead7'], borderColor:'#222', borderWidth:2 }]
  },
  options: { plugins:{ legend:{ position:'bottom' } } }
});
</script>

---

## 📆 주차별 강의 내용

| 주차 | 수업목표 | 수업내용 |
|------|-----------|-----------|
| 1주 | 과목 소개 및 ML 개요 | Introduction to Machine Learning |
| 2주 | 결정트리·학습 한계 이해 | Decision Trees, Limits of Learning |
| 3주 | 기하와 최근접 | Geometry and Nearest Neighbors |
| 4주 | 퍼셉트론 | The Perceptron |
| 5주 | 다중분류로 확장 | Beyond Binary Classification |
| 6주 | 선형모형 | Linear Models |
| 7주 | 확률모형 | Probabilistic Modeling |
| 8주 | 중간고사 | 시험 |
| 9주 | 신경망 | Neural Networks |
| 10주 | 커널 방법 | Kernel Methods |
| 11주 | 학습이론 | Learning Theory |
| 12주 | 앙상블 | Ensemble Methods |
| 13주 | 비지도학습 | Unsupervised Learning (Clustering, PCA) |
| 14주 | 구조적 예측 | Structured Prediction |
| 15주 | 기말고사 | 시험 |
