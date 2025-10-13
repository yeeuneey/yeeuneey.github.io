---
title: "리눅스프로그래밍"
summary: ""
type: course
tags: ["2-1"]

image:
  filename: "uploads/media/linux_programming.jpg"
  focal_point: "Center"
  preview_only: true
featured: true

goals:
  - "Goal 1️⃣ : 리눅스 환경에서 CLI(Command Line Interface) 사용 능력을 배양한다."
  - "Goal 2️⃣ : 리눅스 운영체제의 사용 능력과 시스템 구조를 이해한다."
  - "Goal 3️⃣ : 리눅스 환경에서 네트워크 서비스 관리 및 시스템 프로그래밍 능력을 기른다."

instructor: "김아미 교수님"
department: "전북대학교 컴퓨터공학부 / IT정보공학과 / 컴퓨터인공지능학부"
room: "공대 7호관 204호"
language: "한국어"
credit: 3

textbook:
  title: "리눅스 프로그래밍 원리와 실제"
  author: "창병모"
  publisher: "생능출판"
  year: "2022"
---

<!--more-->

## 📘 강의 개요

| 항목 | 내용 |
|------|------|
| **교과목명** | 리눅스프로그래밍 |
| **담당교수** | 김아미 교수님 |
| **소속** | 전북대학교 컴퓨터공학부 외 |
| **강의실** | 공대 7호관 204호 |
| **강의언어** | 한국어 |

---

## 🎯 강의 목표

1️⃣ 리눅스 환경에서 CLI(Command Line Interface) 사용 능력을 배양한다.  
2️⃣ 리눅스 운영체제의 사용 능력과 시스템 구조를 이해한다.  
3️⃣ 리눅스 환경에서 네트워크 서비스 관리 및 시스템 프로그래밍 능력을 기른다.

---

## 📖 교재

> 리눅스 프로그래밍 원리와 실제 
> 창병모 저 · 생능출판 (2022)

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
| 1주 | 리눅스 개요 및 설치 이해 | 리눅스 개요 및 설치 |
| 2주 | 리눅스 시스템과 명령어 이해 | 리눅스 시스템 구축, 기본 명령어 *(실습과제 1)* |
| 3주 | 디렉토리와 파일 관리 | CLI 환경에서 디렉토리·파일 관리 *(실습과제 2)* |
| 4주 | 사용자와 권한 관리 | 시스템 권한 개념, 사용자 관리 *(실습과제 3)* |
| 5주 | 프로세스와 입출력 재지정 | 프로세스 개념, redirection *(실습과제 4)* |
| 6주 | 기타 명령어 학습 | 검색, 압축 등 자주 사용하는 명령어 *(실습과제 5)* |
| 7주 | C언어 기반 프로그래밍 실습 | 리눅스 환경에서의 C 프로그램 개발 |
| 8주 | 중간고사 | 시험 |
| 9주 | 시스템콜 및 파일 입출력Ⅰ | 시스템콜 개념, 파일 입출력 (Low-Level) *(실습과제 6)* |
| 10주 | 파일 입출력Ⅱ | 파일 입출력 (High-Level) *(실습과제 7)* |
| 11주 | 메모리·프로세스 관리 | 동적 메모리 활용, 프로세스 생성·실행·종료 *(실습과제 8)* |
| 12주 | IPC – 시그널, 공유메모리 | 프로세스 간 통신 *(실습과제 9)* |
| 13주 | IPC – 소켓·스레드 | 네트워크 소켓, 스레드 프로그래밍 *(실습과제 10)* |
| 14주 | 병렬 프로그래밍 이해 | 병렬 프로그래밍 및 스레드 활용 |
| 15주 | 기말고사 | 시험 |
