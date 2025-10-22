---
title: "인공지능"
summary: ""
type: course
tags: ["3-1"]

goals:
  - "Goal 1️⃣ : 인공지능의 전반적인 개념과 주요 원리를 이해한다."
  - "Goal 2️⃣ : 탐색, 지식표현, 논리추론, 확률 기반 추론 등 인공지능의 핵심 기법을 학습한다."
  - "Goal 3️⃣ : 최신 인공지능 응용 분야를 이해하고 실제 문제 해결에 적용할 수 있는 능력을 기른다."

instructor: "송현제 교수님"
department: "전북대학교 컴퓨터공학부 / IT정보공학과 / 컴퓨터공학부(컴퓨터) / 컴퓨터인공지능학부"
room: "공대 7호관 534호"
language: "한국어"
credit: 3

textbook:
  title: "Artificial Intelligence: A Modern Approach"
  author: "Stuart Russell, Peter Norvig"
  publisher: "Pearson"
  year: 2016
---

<!--more-->

## 📘 강의 개요

| 항목 | 내용 |
|------|------|
| **교과목명** | 인공지능 |
| **담당교수** | 송현제 교수님 |
| **소속** | 전북대학교 컴퓨터공학부 외 |
| **강의실** | 공대 7호관 534호 |
| **강의언어** | 한국어 |

---

## 🎯 강의 목표

1️⃣ 인공지능의 전반적인 개념과 주요 원리를 이해한다.  
2️⃣ 탐색, 지식표현, 논리추론, 확률 기반 추론 등 인공지능의 핵심 기법을 학습한다.  
3️⃣ 최신 인공지능 응용 분야를 이해하고 실제 문제 해결에 적용할 수 있는 능력을 기른다.

---

## 📖 교재

> Artificial Intelligence: A Modern Approach  
> Stuart Russell, Peter Norvig 저 · Pearson (2016)

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
      data: [30, 35, 5, 30],
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
| 1주 | 인공지능의 개요 이해 | Introduction to AI |
| 2주 | 지능형 에이전트의 개념 학습 | Intelligent Agents |
| 3주 | 탐색 기반 문제 해결 방법 이해 | Solving Problems by Searching |
| 4주 | 경쟁적 탐색 및 제약 충족 문제 학습 | Adversarial Search / Constraint Satisfaction Problems |
| 5주 | 논리 기반 지식표현 학습 | Logical Agents / First-Order Logic |
| 6주 | 계획(Planning) 개념 이해 | Planning |
| 7주 | 지식표현 심화 | Knowledge Representation |
| 8주 | 중간고사 | 시험 |
| 9주 | 마르코프 의사결정 과정 학습 | Markov Decision Process |
| 10주 | 강화학습Ⅰ 이해 | Reinforcement Learning 1 |
| 11주 | 강화학습Ⅱ 이해 | Reinforcement Learning 2 |
| 12주 | 베이지안 네트워크 기초 이해 | Introduction & Representation of Bayesian Networks |
| 13주 | 베이지안 네트워크 추론 학습 | Inference and Sampling |
| 14주 | 기계학습 및 딥러닝 개요 | Introduction to Machine Learning and Deep Learning |
| 15주 | 기말고사 | 시험 |
