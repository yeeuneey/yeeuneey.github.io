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

Project implementing search algorithms for the AB_Omok game.

<!--more-->

<div style="text-align: center; margin: 28px 0;">
  <a href="/uploads/omok-report.pdf" download class="hb-btn">
    <svg xmlns="http://www.w3.org/2000/svg" fill="none"
         viewBox="0 0 24 24" stroke="currentColor">
      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
            d="M4 16v2a2 2 0 002 2h12a2 2 0 002-2v-2M7 10l5 5 5-5M12 15V3" />
    </svg>
    Download Report PDF
  </a>
</div>

To improve upon the original random-move AI, I implemented an alpha-beta pruning search that results in a more strategic opponent. The evaluation function analyzes every line on the Gomoku board to score the current position, prioritizing defensive play by giving heavier weight to the opponent’s threats.

To cut search time and boost performance, the algorithm only expands meaningful candidate moves near existing stones. A fallback routine starts from the center when a timeout occurs, improving resilience. These changes transform the AI from a purely random player into one that plans ahead, balances offense and defense, and responds intelligently to the game state.
