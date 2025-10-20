---
title: database
date: 2025-06-21
links:
  - name: 도서관 예약 관리 시스템 github link
    url: https://github.com/yeeuneey/db_project.git
    icon: link
tags:
  - DataBase
  - SQL
---

<br>

sql을 이용한 도서관 예약 관리 시스템을 구현하는 프로젝트.

<!--more-->

<div style="text-align: center; margin: 28px 0;">
  <a href="/uploads/db-report.pdf" download class="hb-btn">
    <svg xmlns="http://www.w3.org/2000/svg" fill="none"
         viewBox="0 0 24 24" stroke="currentColor">
      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
            d="M4 16v2a2 2 0 002 2h12a2 2 0 002-2v-2M7 10l5 5 5-5M12 15V3" />
    </svg>
    보고서 PDF 다운로드
  </a>
</div>

도서관 좌석 예약 관리 시스템은 시험 기간 중 좌석을 선점만 하고 사용하지 않는 문제를 해결하고자 시작되었습니다. 많은 학생이 자리를 비효율적으로 사용하여 다른 학생들이 피해를 보는 상황을 개선하기 위해, 사용자 정보, 좌석 현황, 예약 및 이용 이력을 체계적으로 관리하는 시스템을 구상했습니다. 핵심 기능으로 민원 시스템을 도입하여, 장시간 자리를 비우는 등의 문제를 신고하고 경고를 누적시켜, 규칙을 위반한 사용자에게는 이용 제한 패널티를 부여함으로써 공정한 이용 환경을 조성하고자 했습니다. 

요구사항 분석부터 시작하여 학생, 좌석, 예약, 민원, 이용 제한 등 핵심 개체를 정의하고, ER 다이어그램을 통해 관계를 명확히 하는 개념적, 논리적 설계를 진행했습니다.  이를 바탕으로 테이블 생성 스크립트를 작성하여 데이터베이스를 구축했으며, 학생 및 좌석 데이터를 삽입하여 실제 운영 환경과 유사한 시스템을 구현했습니다. 이 과정을 통해 데이터베이스 설계 원칙을 적용하고, 실용적인 문제 해결 능력을 기를 수 있었습니다.