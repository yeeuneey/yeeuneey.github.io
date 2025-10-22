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

Project implementing search algorithms to solve the 8-puzzle.

<!--more-->

<div style="text-align: center; margin: 28px 0;">
  <a href="/uploads/8-puzzle-report.pdf" download class="hb-btn">
    <svg xmlns="http://www.w3.org/2000/svg" fill="none"
         viewBox="0 0 24 24" stroke="currentColor">
      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
            d="M4 16v2a2 2 0 002 2h12a2 2 0 002-2v-2M7 10l5 5 5-5M12 15V3" />
    </svg>
    Download Report PDF
  </a>
</div>

Earlier iterations copied the entire path for every node, which caused performance degradation and wasted memory as the search depth increased. To resolve this, I introduced a node class that encapsulates state, action, cost, and parent information, significantly reducing memory usage. By backtracking the parent pointer, the path() method reconstructs the final route, and this structure is shared across DFS, BFS, UCS, A*, and every other search algorithm to provide both consistency and efficiency. I also measured and analyzed algorithm performance at multiple difficulty levels to draw data-driven conclusions about their behavior.
