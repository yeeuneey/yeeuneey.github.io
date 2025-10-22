---
title: "객체지향프로그래밍"
summary: ""
type: course
tags: ["2-1"]

image:
  filename: "uploads/media/object_oriented_programming.jpg"
  focal_point: "Center"
  preview_only: true
featured: true

goals:
  - "Goal 1️⃣ : 객체지향 프로그래밍의 개념을 이해하고 Java 언어를 기반으로 객체지향 프로그램을 설계할 수 있는 능력을 기른다."
  - "Goal 2️⃣ : 클래스, 객체, 상속, 다형성 등 객체지향의 핵심 개념을 학습한다."
  - "Goal 3️⃣ : 실습 중심의 학습을 통해 Java 기반 응용 프로그램을 개발할 수 있는 실무 능력을 배양한다."

instructor: "강동기 교수님"
department: "전북대학교 컴퓨터공학부 / IT정보공학과 / 컴퓨터인공지능학부"
room: "공대 7호관 204호"
language: "한국어"
credit: 3

textbook:
  title: "Do it! 자바 완전 정복"
  author: "김동형"
  publisher: "이지스퍼블리싱"
  year: "2021"
---

<!--more-->

## 📘 강의 개요

| 항목 | 내용 |
|------|------|
| **교과목명** | 객체지향프로그래밍 |
| **담당교수** | 강동기 교수님 |
| **소속** | 전북대학교 컴퓨터공학부 외 |
| **강의실** | 공대 7호관 204호 |
| **강의언어** | 한국어 |

---

## 🎯 강의 목표

1️⃣ 객체지향 프로그래밍의 개념을 이해하고 Java 언어를 기반으로 객체지향 프로그램을 설계할 수 있는 능력을 기른다.  
2️⃣ 클래스, 객체, 상속, 다형성 등 객체지향의 핵심 개념을 학습한다.  
3️⃣ 실습 중심의 학습을 통해 Java 기반 응용 프로그램을 개발할 수 있는 실무 능력을 배양한다.

---

## 📖 교재

> Do it! 자바 완전 정복
> 김동형 저 · 이지스퍼블리싱 (2021)

---

## 🧮 평가 비율

<canvas id="evaluationChart" width="400" height="400"></canvas>

<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<script>
const ctx = document.getElementById('evaluationChart');
new Chart(ctx, {
  type: 'pie',
  data: {
    labels: ['중간고사', '출석', '과제', '팀플'],
    datasets: [{
      data: [30, 10, 30, 30],
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
| 1주 | 자바 개발 환경 이해 | 자바 소개, 환경 구축, 이클립스 설치 |
| 2주 | 자바 기초 문법 학습Ⅰ | 변수, 자료형, 연산자 |
| 3주 | 자바 기초 문법 학습Ⅱ | 선택문, 반복문, 배열 |
| 4주 | 객체지향 개념 및 클래스 학습 | 클래스, 메소드, 오버로딩 |
| 5주 | 객체 생성 및 접근자 학습 | 생성자, 접근자·설정자, 내부 클래스 |
| 6주 | 상속과 다형성 이해 | 상속, 오버라이딩, 추상 클래스 |
| 7주 | GUI 프로그래밍 기초 | 자바 그래픽 컴포넌트 |
| 8주 | 중간고사 | 시험 |
| 9주 | 인터페이스와 람다식 | 인터페이스, 패키지, 람다식 |
| 10주 | 이벤트 처리 | 이벤트 기반 응용 개발 |
| 11주 | 그래픽 프로그래밍 | 이벤트 및 GUI 응용 |
| 12주 | 스윙 컴포넌트 활용 | 스윙을 이용한 응용 프로그램 개발 |
| 13주 | 예외 처리 학습 | try-catch 문, 디버깅 |
| 14주 | 팀 프로젝트 수행 | 자바 프로젝트 진행 |
| 15주 | 프로젝트 발표 및 평가 | 팀별 발표 및 결과물 평가 |
