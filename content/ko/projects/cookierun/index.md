---
title: CookieRun Game
date: 2024-06-03
links:
  - name: 게임 클라이언트 (Front-End)
    url: https://github.com/yeeuneey/CookieRun-Front.git
    icon: link
  - name: 게임 서버 (Back-End)
    url: https://github.com/yeeuneey/CookieRun-Server.git
    icon: link
tags:
  - oop
  - Game
  - Java
---

CookieRun-Game의 클라이언트와 서버를 구현하는 프로젝트.

<!--more-->

자바로 작성된 기존 쿠키런 프로젝트를 바탕으로 4가지 모드와 pvp 모드를 더한 버전을 구현하였습니다. 점수 모드는 체력이 0이 될 때까지 달린 후, 총 점수를 반영하는 시스템이고, 실시간 pvp 모드는 실시간으로 플레이어들이 경쟁을 할 수 있는 시스템입니다. pvp에 속도전, 버티기 2가지 모드를 구현하였습니다.

서버 및 순위 판은 플레이한 점수 or pvp 승패 결과를 통한 모드 별 순위 판을 위해 소켓 통신 기반의 실시간 서버를 구현하였습니다.