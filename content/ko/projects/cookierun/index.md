---
title: CookieRun Game
date: 2024-06-03
links:
  - name: 클라이언트 (Front-End) github link
    url: https://github.com/yeeuneey/CookieRun-Front.git
    icon: link
  - name: 서버 (Back-End) github link
    url: https://github.com/yeeuneey/CookieRun-Server.git
    icon: link
tags:
  - oop
  - Game
  - Java
---

CookieRun-Game의 클라이언트와 서버를 구현하는 프로젝트.

<!--more-->

기존의 자바 기반 쿠키런 게임을 확장하여, 일반 모드와 하드 모드, 그리고 두 가지 방식의 PVP 모드를 새롭게 구현했습니다.  각 모드는 독자적인 플레이 경험을 제공하며, 특히 PVP 모드는 실시간 경쟁의 재미를 더했습니다. 스피드 모드에서는 상대보다 먼저 결승선에 도달해야 하며, 버티기 모드에서는 더 오래 살아남는 것이 목표입니다. 이러한 다양한 모드를 통해 플레이어들에게 풍부한 콘텐츠와 도전적인 과제를 제공하고자 했습니다.

이 프로젝트의 핵심은 소켓 통신 기반의 실시간 서버를 구축하여 안정적인 멀티플레이 환경을 제공하는 것입니다.  플레이어의 점수와 승패 기록은 서버에 전송되어 모드별 순위표에 실시간으로 반영됩니다. 특히 PVP 모드에는 체스에서 사용되는 Elo 레이팅 시스템을 도입하여, 단순한 승패 기록을 넘어 플레이어의 실력을 객관적으로 평가하고, 이를 바탕으로 공정한 매칭과 경쟁적인 랭킹 시스템을 구현했습니다.