---
title: CookieRun Game
date: 2024-06-03
links:
  - name: client (Front-End) github link
    url: https://github.com/yeeuneey/CookieRun-Front.git
    icon: link
  - name: server (Back-End) github link
    url: https://github.com/yeeuneey/CookieRun-Server.git
    icon: link
tags:
  - oop
  - Game
  - Java
---

<br>

Project implementing both client and server components of the CookieRun game.

<!--more-->

Building on the original Java-based CookieRun game, I added normal and hard difficulty levels plus two distinct PVP modes. Each mode delivers a unique play style: the Speed mode rewards reaching the finish line first, while the Survival mode challenges players to stay alive longer than their rival. The expanded roster of modes gives players richer content and more demanding objectives.

At the heart of the project is a real-time socket server that enables stable multiplayer interaction. Player scores and win/loss records are sent to the server and reflected instantly on mode-specific leaderboards. For PVP, I introduced the Elo rating system used in chess to evaluate skill beyond simple records, which makes matchmaking fairer and produces a competitive ranking environment.
