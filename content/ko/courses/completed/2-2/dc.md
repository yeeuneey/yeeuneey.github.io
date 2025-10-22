---
title: "데이터통신"
summary: ""
type: course
tags: ["2-2"]

goals:
  - "Goal 1️⃣ : 서로 다른 컴퓨터 간 데이터 전송에 필요한 전송매체, 신호, 전송장비 등의 기술 요소를 학습한다."
  - "Goal 2️⃣ : 데이터의 손실 없는 전송을 위해 통신 과정과 네트워크 구성 원리를 이해한다."
  - "Goal 3️⃣ : 컴퓨터 네트워크의 기반 이론과 실무적 응용을 이해하고 분석할 수 있는 능력을 기른다."

instructor: "조기환 교수님"
department: "전북대학교 컴퓨터공학부 / IT정보공학과 / IT지능정보공학과 / 컴퓨터인공지능학부"
room: "공대 3호관 311호"
language: "한국어"
credit: 3

textbook:
  title: "Data & Computer Communications (10th Edition)"
  author: "William Stallings"
  publisher: "Prentice Hall"
  year: 2014
---

<!--more-->

## 📘 강의 개요

| 항목 | 내용 |
|------|------|
| **교과목명** | 데이터통신 |
| **담당교수** | 조기환 교수님 |
| **소속** | 전북대학교 컴퓨터공학부 외 |
| **강의실** | 공대 3호관 311호 |
| **강의언어** | 한국어 |

---

## 🎯 강의 목표

1️⃣ 서로 다른 컴퓨터 간 데이터 전송에 필요한 전송매체, 신호, 전송장비 등의 기술 요소를 학습한다.  
2️⃣ 데이터의 손실 없는 전송을 위해 통신 과정과 네트워크 구성 원리를 이해한다.  
3️⃣ 컴퓨터 네트워크의 기반 이론과 실무적 응용을 이해하고 분석할 수 있는 능력을 기른다.

---

## 📖 교재

> Data & Computer Communications (10th Edition)  
> William Stallings 저 · Prentice Hall (2014)

---

## 🧮 평가 비율

<canvas id="evaluationChart" width="400" height="400"></canvas>

<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<script>
const ctx = document.getElementById('evaluationChart');
new Chart(ctx, {
  type: 'pie',
  data: {
    labels: ['중간고사', '기말고사', '출석', '과제', '기타'],
    datasets: [{
      data: [35, 35, 10, 16, 4],
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
| 1주 | 데이터통신의 개요 이해 | 데이터 통신 개념, 컴퓨터통신과 네트워크 관계 |
| 2주 | 프로토콜 구조 이해 | OSI와 TCP/IP 프로토콜 비교, 역할 및 기능 |
| 3주 | 데이터 전송 기초 개념 이해 | 전송매체의 종류와 물리적 특성 |
| 4주 | 데이터 전송 매체 이해 | 유선/무선 매체의 특성 및 응용 *(퀴즈 1)* |
| 5주 | 신호 코딩 기법 이해Ⅰ | 아날로그·디지털 신호의 종류와 변환 |
| 6주 | 신호변환 및 에러 처리 이해 | PCM, 오류 검출·수정 기법 |
| 7주 | 데이터 링크 제어Ⅰ | 플로우 제어 개념, 슬라이딩 윈도우 알고리즘 |
| 8주 | 중간고사 | 시험 |
| 9주 | 데이터 링크 제어Ⅱ | HDLC 구조, 에러 종류 및 대응 방안 |
| 10주 | 멀티플렉싱 이해 | FDMA, TDMA, CDMA 방식의 특징 |
| 11주 | LAN의 기본 원리 이해Ⅰ | LAN 토폴로지와 프로토콜 구조 |
| 12주 | LAN의 기본 원리 이해Ⅱ | CSMA/CD 알고리즘과 허브, 스위치 개념 |
| 13주 | 고속 LAN 이해 | Ethernet의 구조와 동작 *(퀴즈 2)* |
| 14주 | 무선 LAN 이해 | Wi-Fi, CSMA/CA 알고리즘과 응용 |
| 15주 | 기말고사 | 시험 |
