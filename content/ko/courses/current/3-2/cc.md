---
title: "클라우드컴퓨팅"
summary: ""
type: course
tags: ["3-2"]

goals:
  - "Goal 1️⃣ : 가상화 기술 및 클라우드 서비스의 기본 개념을 이해한다."
  - "Goal 2️⃣ : AWS 기반의 가상 서버, 네트워크, 스토리지 등 주요 클라우드 인프라 서비스를 학습한다."
  - "Goal 3️⃣ : 클라우드 환경에서 응용 서비스를 설계·구현·배포할 수 있는 능력을 기른다."

instructor: "강동기 교수님"
department: "전북대학교 컴퓨터공학부 / IT정보공학과 / 컴퓨터인공지능학부"
room: "공대 7호관 204호"
language: "한국어"
credit: 3

textbook:
  title: "아마존 웹 서비스 AWS Discovery Book"
  author: "권영한"
  publisher: "정보문화사"
  year: 2020
---

<!--more-->

## 📘 강의 개요

| 항목 | 내용 |
|------|------|
| **교과목명** | 클라우드컴퓨팅 |
| **담당교수** | 강동기 교수님 |
| **소속** | 전북대학교 컴퓨터공학부 외 |
| **강의실** | 공대 7호관 204호 |
| **강의언어** | 한국어 |

---

## 🎯 강의 목표

1️⃣ 가상화 기술 및 클라우드 서비스의 기본 개념을 이해한다.  
2️⃣ AWS 기반의 가상 서버, 네트워크, 스토리지 등 주요 클라우드 인프라 서비스를 학습한다.  
3️⃣ 클라우드 환경에서 응용 서비스를 설계·구현·배포할 수 있는 능력을 기른다.

---

## 📖 교재

> 아마존 웹 서비스 AWS Discovery Book  
> 권영한 저 · 정보문화사 (2020)

---

## 🧮 평가 비율

<canvas id="chart-cloud" width="400" height="400"></canvas>
<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<script>
const ctxC = document.getElementById('chart-cloud');
new Chart(ctxC, {
  type: 'pie',
  data: {
    labels: ['중간고사', '출석', '과제', '팀플'],
    datasets: [{
      data: [30, 10, 30, 30],
      backgroundColor: ['#9ad0f5', '#ffdac1', '#b5ead7', '#ffb7b2'],
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
| 1주 | 수업 소개 | 강의 운영 및 평가 안내 |
| 2주 | 클라우드 기본 개념 학습 | 클라우드 개념, 가상 자원 이해 |
| 3주 | AWS 가상 서버 이해 | EC2 및 Lambda 실습 |
| 4주 | AWS 스토리지 활용 | S3, Glacier 등 스토리지 서비스 실습 |
| 5주 | AWS VPC 구성Ⅰ | 가상 네트워크 기초 실습 |
| 6주 | AWS VPC 구성Ⅱ | 보안 그룹 및 라우팅 실습 |
| 7주 | AWS 데이터베이스 서비스 학습 | RDS 활용 |
| 8주 | 중간고사 | 시험 |
| 9주 | 로드밸런싱 이해 | 트래픽 분산 실습 |
| 10주 | 오토스케일링 학습 | 서버 확장 및 자원 관리 실습 |
| 11주 | 가용성 보장 방법 학습 | 모니터링 및 복구 실습 |
| 12주 | AWS Lambda 실습 | 서버리스 컴퓨팅 구현 |
| 13주 | 팀 프로젝트Ⅰ | 프로젝트 설계 및 구현 |
| 14주 | 팀 프로젝트Ⅱ | 구현 및 테스트 |
| 15주 | 팀 프로젝트 발표 | 발표 및 피드백 |
