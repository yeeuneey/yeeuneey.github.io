---
title: "컴퓨터네트워크"
summary: ""
type: course
tags: ["3-1"]

image:
  filename: "uploads/media/computer_network.jpg"
  focal_point: "Center"
  preview_only: true
featured: true

goals:
  - "Goal 1️⃣ : 컴퓨터 네트워크의 구조와 동작 원리를 이해한다."
  - "Goal 2️⃣ : 네트워크 계층(IP), 전송 계층(TCP/UDP), 응용 계층(HTTP, SMTP 등)의 역할을 학습한다."
  - "Goal 3️⃣ : 네트워크 프로토콜과 보안 기술의 개념을 이해하고 이를 응용할 수 있는 능력을 기른다."

instructor: "편기현 교수님"
department: "전북대학교 컴퓨터공학부 / IT정보공학과 / 컴퓨터인공지능학부"
room: "공대 3호관 311호"
language: "한국어"
credit: 3

textbook:
  title: "Data Communications and Networking"
  author: "Behrouz A. Forouzan"
  publisher: "McGraw-Hill"
  year: "3rd/4th Edition"
---

<!--more-->

## 📘 강의 개요

| 항목 | 내용 |
|------|------|
| **교과목명** | 컴퓨터네트워크 |
| **담당교수** | 편기현 교수님 |
| **소속** | 전북대학교 컴퓨터공학부 외 |
| **강의실** | 공대 3호관 311호 |
| **강의언어** | 한국어 |

---

## 🎯 강의 목표

1️⃣ 컴퓨터 네트워크의 구조와 동작 원리를 이해한다.  
2️⃣ 네트워크 계층(IP), 전송 계층(TCP/UDP), 응용 계층(HTTP, SMTP 등)의 역할을 학습한다.  
3️⃣ 네트워크 프로토콜과 보안 기술의 개념을 이해하고 이를 응용할 수 있는 능력을 기른다.

---

## 📖 교재

> Data Communications and Networking  
> Behrouz A. Forouzan 저 · McGraw-Hill

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
      data: [47.5, 47.5, 5, 0],
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
| 1주 | 네트워크 개요 이해 | Introduction |
| 2주 | 호스트 간 데이터 전달 학습 | Host-to-Host Delivery |
| 3주 | 네트워크 계층 이해 | Network Layer Protocols |
| 4주 | 라우팅 기법 이해 | Unicast and Multicast Routing Protocols |
| 5주 | 프로세스 간 통신 학습 | Process-to-Process Delivery |
| 6주 | 혼잡 제어 기법 이해 | Congestion Control |
| 7주 | 서비스 품질 이해 | Quality of Service |
| 8주 | 중간고사 | 시험 |
| 9주 | 클라이언트-서버 모델 학습 | Client-Server Model |
| 10주 | 도메인 이름 시스템 이해 | Domain Name System |
| 11주 | 이메일 및 파일 전송 프로토콜 | SMTP, FTP |
| 12주 | 웹 프로토콜 학습 | HTTP, WWW |
| 13주 | 멀티미디어 네트워크 | Multimedia |
| 14주 | 암호화와 보안 | Cryptography |
| 15주 | 기말고사 | 시험 |
