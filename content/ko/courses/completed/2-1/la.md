---
title: "선형대수학"
summary: ""
type: course
tags: ["2-1"]

image:
  filename: "uploads/media/linear_algebra.jpg"
  focal_point: "Center"
  preview_only: true
featured: true

goals:
  - "Goal 1️⃣ : 선형대수학의 기본 요소인 벡터, 행렬, 선형 변환 등의 개념을 이해한다."
  - "Goal 2️⃣ : 관련 분야의 문제를 해결하는 방법을 학습하여 응용 능력을 기른다."
  - "Goal 3️⃣ : 실제 응용 문제를 해결할 수 있는 수학적 사고력과 문제 해결 능력을 함양한다."

instructor: "김지승 교수님"
department: "전북대학교 컴퓨터공학부 / IT정보공학과 / 컴퓨터인공지능학부"
room: "공대 6호관 B15호"
language: "한국어"
credit: 3

textbook:
  title: "Introduction to Linear Algebra (International Fourth Edition)"
  author: "Gilbert Strang"
  publisher: "Wellesley-Cambridge Press"
  year: 2009
---

<!--more-->

## 📘 강의 개요

| 항목 | 내용 |
|------|------|
| **교과목명** | 선형대수학 |
| **담당교수** | 김지승 교수님 |
| **소속** | 전북대학교 컴퓨터공학부 외 |
| **강의실** | 공대 6호관 B15호 |
| **강의언어** | 한국어 |

---

## 🎯 강의 목표

1️⃣ 선형대수학의 기본 요소인 벡터, 행렬, 선형 변환 등의 개념을 이해한다.  
2️⃣ 관련 분야의 문제를 해결하는 방법을 학습하여 응용 능력을 기른다.  
3️⃣ 실제 응용 문제를 해결할 수 있는 수학적 사고력과 문제 해결 능력을 함양한다.

---

## 📖 교재

> *Introduction to Linear Algebra (International Fourth Edition)*  
> Gilbert Strang 저 · Wellesley-Cambridge Press (2009)

---

## 🧮 평가 비율

<canvas id="evaluationChart" width="400" height="400"></canvas>

<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<script>
const ctx = document.getElementById('evaluationChart');
new Chart(ctx, {
  type: 'pie',
  data: {
    labels: ['중간고사', '기말고사', '과제', '출석'],
    datasets: [{
      data: [45, 45, 10, 0],
      backgroundColor: ['#9ad0f5', '#ffb7b2', '#b5ead7', '#ffdac1'],
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
| 1주 | 강의 소개 및 벡터 개념 이해 | Course Overview, Vectors and Linear Combinations |
| 2주 | 벡터의 내적 및 행렬 이해 | Lengths and Dot Products, Matrices |
| 3주 | 선형 방정식과 소거법 이해 | Vectors and Linear Equations, Elimination Using Matrices |
| 4주 | 행렬 연산 및 역행렬 학습 | Matrix Operations, Inverse Matrices, LU 분해 |
| 5주 | 전치행렬과 벡터공간 이해 | Transposes and Permutations, Spaces of Vectors |
| 6주 | 계수(rank)와 연립방정식 해법 | The Rank, Row Reduced Form, Ax=b의 해 |
| 7주 | 기저와 차원 개념 학습 | Independence, Basis, Dimension, Four Subspaces |
| 8주 | 중간고사 | 시험 |
| 9주 | 직교성 및 최소제곱법 | Orthogonality, Projections, Least Squares |
| 10주 | 행렬식 및 그 특성 | Determinants, Permutations, Cofactors |
| 11주 | 고유값과 대각화 이해 | Eigenvalues, Diagonalization |
| 12주 | 미분방정식 응용 및 대칭행렬 | Applications to Differential Equations, Symmetric Matrices |
| 13주 | 유사행렬과 SVD | Similar Matrices, Singular Value Decomposition |
| 14주 | 선형변환과 의사역행렬 | Matrix of a Linear Transformation, Pseudoinverse |
| 15주 | 기말고사 | 시험 |
