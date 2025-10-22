---
title: 8-puzzle
date: 2025-03-29
links:
  - name: 8-puzzle github link
    url: https://github.com/yeeuneey/8-puzzle.git
    icon: link
tags:
  - Ai
  - Python
---

<br>

8-puzzle을 해결하는 탐색 알고리즘을 구현하는 프로젝트.

<!--more-->

<div style="text-align: center; margin: 28px 0;">
  <a href="/uploads/8-puzzle-report.pdf" download class="hb-btn">
    <svg xmlns="http://www.w3.org/2000/svg" fill="none"
         viewBox="0 0 24 24" stroke="currentColor">
      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
            d="M4 16v2a2 2 0 002 2h12a2 2 0 002-2v-2M7 10l5 5 5-5M12 15V3" />
    </svg>
    보고서 PDF 다운로드
  </a>
</div>

기존에는 경로 전체를 복사하는 방식으로 인해 탐색 깊이가 깊어질수록 성능 저하와 메모리 낭비 문제가 발생했습니다. 이를 해결하기 위해 state, action, cost, parent 정보를 캡슐화한 node 클래스를 도입하여 메모리 사용을 최적화했습니다. parent 포인터를 역추적하여 최종 경로를 재구성하는 path() 메서드를 구현하였고, 이를 DFS, BFS, UCS, A* 등 모든 탐색 알고리즘에 공통적으로 적용하여 구조적 통일성과 효율성을 동시에 달성했습니다. 더 나아가, 다양한 난이도에 따른 각 알고리즘의 성능을 체계적으로 측정하고 분석하여 데이터에 기반한 객관적인 결론을 도출했습니다.