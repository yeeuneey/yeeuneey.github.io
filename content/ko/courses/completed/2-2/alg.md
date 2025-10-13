---
title: "알고리즘"
summary: ""
type: course
tags: ["2-2"]

image:
  filename: "uploads/media/algorithm.jpg"
  focal_point: "Center"
  preview_only: true
featured: true

goals:
  - "Goal 1️⃣ : 문제 해결을 위한 알고리즘을 설계하고 구현하는 능력을 기른다."
  - "Goal 2️⃣ : 알고리즘의 효율성을 분석하고 다양한 문제 유형에 적합한 알고리즘을 선택할 수 있는 능력을 배양한다."
  - "Goal 3️⃣ : 실제 문제를 해결하기 위해 알고리즘을 응용하고 창의적으로 활용할 수 있는 사고력을 기른다."

instructor: "장재우 교수님"
department: "전북대학교 컴퓨터공학부 / IT정보공학과 / IT지능정보공학과 / 컴퓨터인공지능학부"
room: "공대 6호관 B15호"
language: "한국어"
credit: 3

textbook:
  title: "쉽게 배우는 알고리즘 - 관계중심의 사고법"
  author: "문병로"
  publisher: "한빛미디어"
  year: 2014
---

<!--more-->

## 📘 강의 개요

| 항목 | 내용 |
|------|------|
| **교과목명** | 알고리즘 |
| **담당교수** | 장재우 교수님 |
| **소속** | 전북대학교 컴퓨터공학부 외 |
| **강의실** | 공대 6호관 B15호 |
| **강의언어** | 한국어 |

---

## 🎯 강의 목표

1️⃣ 문제 해결을 위한 알고리즘을 설계하고 구현하는 능력을 기른다.  
2️⃣ 알고리즘의 효율성을 분석하고 다양한 문제 유형에 적합한 알고리즘을 선택할 수 있는 능력을 배양한다.  
3️⃣ 실제 문제를 해결하기 위해 알고리즘을 응용하고 창의적으로 활용할 수 있는 사고력을 기른다.

---

## 📖 교재

> 쉽게 배우는 알고리즘 - 관계중심의 사고법  
> 문병로 저 · 한빛미디어 (2014)

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
      data: [35, 35, 10, 20],
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
| 1주 | 강의 소개 | 강의 개요 및 오리엔테이션 |
| 2주 | 알고리즘 설계와 분석의 기초 | 알고리즘 설계 원리 |
| 3주 | 점화식과 복잡도 분석 | 점근적 복잡도 분석, 효율성 평가 |
| 4주 | 기초 정렬 알고리즘 | 선택 정렬, 삽입 정렬, 버블 정렬 |
| 5주 | 고급 정렬 알고리즘 | 퀵 정렬, 병합 정렬, 힙 정렬 |
| 6주 | 프로젝트 제안 발표 | 알고리즘 설계 및 발표 |
| 7주 | 검색트리 | 이진 탐색 트리 등 검색 알고리즘 |
| 8주 | 중간고사 | 시험 |
| 9주 | 해시 테이블 | 해싱 기법 및 충돌 해결 |
| 10주 | 동적 프로그래밍 | 최적화 문제와 점화식 활용 |
| 11주 | 기초 그래프 알고리즘 | 그래프 탐색(DFS, BFS) |
| 12주 | 심화 그래프 알고리즘 | 최소 비용 신장 트리, 최단 경로 알고리즘 |
| 13주 | 문자열 매칭 | 문자열 검색 알고리즘 |
| 14주 | 프로젝트 결과 발표 | 알고리즘 구현 결과 발표 |
| 15주 | 기말고사 | 시험 |
