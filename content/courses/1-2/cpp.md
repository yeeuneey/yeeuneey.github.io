---
title: "C++ 프로그래밍"
summary: ""
type: course
tags: ["1-2"]

image:
  filename: "uploads/media/cpp.jpg"
  focal_point: "Center"
  preview_only: true
featured: true

goals:
  - "Goal 1️⃣ : 언어기초를 공부한 학생을 대상으로 C++ 언어의 프로그래밍 문법을 학습한다."
  - "Goal 2️⃣ : 객체지향프로그래밍(OOP)의 개념을 이해하고, C++ 언어를 이용하여 OOP 프로그램을 설계 및 구현하는 능력을 기른다."
  - "Goal 3️⃣ : 다양한 문제에 대한 프로그래밍 실습을 통해 각 주제를 실질적으로 이해하고, C++ 프로그래밍 응용 능력을 향상시킨다."

instructor: "🧑‍🏫 이세호 교수님 🧑‍🏫"
department: "전북대학교 컴퓨터인공지능학부"
room: "공대 7호관 204호"
language: "한국어"
credit: 3

textbook:
  title: "📖 열혈 C++ 프로그래밍 📖"
  author: "윤성우"
  publisher: "오렌지미디어"
  year: 2010
---

<!--more-->

## 📘 강의 개요

| 항목 | 내용 |
|------|------|
| **강의명** | C++ 프로그래밍 |
| **담당교수** | 🧑‍🏫 이세호 교수님 |
| **소속** | 전북대학교 컴퓨터인공지능학부 |
| **강의실** | 공대 7호관 204호 |
| **강의언어** | 한국어 |
| **학점** | 3학점 |

---

## 🎯 강의 목표

1️⃣ 언어기초를 공부한 학생을 대상으로 C++ 언어의 프로그래밍 문법을 학습한다.  
2️⃣ 객체지향프로그래밍(OOP)의 개념을 이해하고, C++ 언어를 이용하여 OOP 프로그램을 설계 및 구현하는 능력을 기른다.  
3️⃣ 다양한 문제에 대한 프로그래밍 실습을 통해 각 주제를 실질적으로 이해하고, C++ 프로그래밍 응용 능력을 향상시킨다.

---

## 📖 교재 정보

> 열혈 C++ 프로그래밍
> 윤성우 저 · 오렌지미디어 (2010)

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
      data: [40, 40, 10, 10],
      backgroundColor: ['#ff9aa2', '#9ad0f5', '#b5ead7', '#ffdac1'],
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

## 📆 주별 강의 내용

| 주별 | 수업목표 | 수업내용 |
|------|-----------|-----------|-----------|
| 1주 | 강의소개 및 C++ 개요 | 강의소개 및 C++ 개요 |
| 2주 | C++ 기초 Part I | C++ 입출력, 이름공간(namespace) |
| 3주 | C++ 기초 Part II | 함수, 동적할당(new & delete) |
| 4주 | 클래스 Part I | 클래스와 객체, 객체지향 프로그래밍 이해 |
| 5주 | 클래스 Part II | 생성자, 복사생성자 |
| 6주 | 복사 생성자/special keywords | 복사 생성자, friend/static/const |
| 7주 | 중간평가 | 중간고사 |
| 8주 | 상속과 다형성 Part I | 상속의 기본개념, 상속과 클래스의 응용 |
| 9주 | 상속과 다형성 Part II | 객체 포인터와 참조, 가상 함수와 다중 상속 |
| 10주 | 연산자 오버로딩 Part I | 단항/이항 연산자 오버로딩, 타입 변환 연산자 |
| 11주 | 연산자 오버로딩 Part II | 비트 연산자 오버로딩, 기타 연산자 |
| 12주 | 템플릿 Part I | 함수/클래스 템플릿 이해 |
| 13주 | 템플릿 Part II | 표준 템플릿 라이브러리(STL) |
| 14주 | 예외처리 | 예외처리 메커니즘, 예외 클래스 설계 |
| 15주 | 기말평가 | 기말고사 |