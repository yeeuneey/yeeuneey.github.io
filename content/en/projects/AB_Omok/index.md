---
title: AB_Omok
date: 2025-04-13
links:
  - name: Omok github link
    url: https://github.com/yeeuneey/AB_Omok.git
    icon: link
tags:
  - Ai
  - Python
---

<br>

AB_Omok을 해결하는 탐색 알고리즘을 구현하는 프로젝트.

<!--more-->

<div style="text-align: center; margin: 28px 0;">
  <a href="/uploads/omok-report.pdf" download class="hb-btn">
    <svg xmlns="http://www.w3.org/2000/svg" fill="none"
         viewBox="0 0 24 24" stroke="currentColor">
      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
            d="M4 16v2a2 2 0 002 2h12a2 2 0 002-2v-2M7 10l5 5 5-5M12 15V3" />
    </svg>
    보고서 PDF 다운로드
  </a>
</div>

기존의 무작위 방식 AI를 개선하기 위해, 알파-베타 가지치기(alpha-beta pruning) 알고리즘을 도입하여 전략적인 AI를 구현했습니다. 오목판의 모든 라인을 분석해 점수를 매기는 <strong>평가 함수(evaluate function)</strong>를 통해 현재 상태의 유불리를 판단하며, 특히 상대의 공격에 더 높은 가중치를 부여하여 방어 중심의 플레이를 하도록 설계했습니다.

탐색 시간을 줄이고 성능을 최적화하기 위해, 돌 주변의 의미 있는 후보 수들만 탐색 공간에 포함시켰습니다. 또한, 타임아웃 발생 시 중앙부터 탐색하는 백업 로직을 추가하여 AI의 안정성을 높였습니다. 이러한 개선을 통해 단순한 랜덤 플레이어를 넘어, 전략적으로 수를 예측하고 방어와 공격을 수행하는 고도화된 AI를 완성할 수 있었습니다.