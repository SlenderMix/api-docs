---
title: /misc/online
position: 3.3
type: get
description: Количество игроков онлайн
right_code: |
  ~~~ json
  {
    "total": 14444,
    "separated": {
      "ann": 430,
      "bb": 764,
      "gg": 365,
      "lobby": 3465,
      "sw": 3756,
      "bw": 3658,
      "mw": 543,
      "kpvp": 212,
      "dr": 178,
      "bp": 294,
      "hg": 779
    }
  }
  ~~~
  {: title="Пример запроса" url="/misc/online" }
---

Возвращает количество игроков онлайн. В сумме и по каждой игре отдельно.

Список всех полных названий игр можно посмотреть с помощью метода [misc/games](#apimisc_games_get).

<h6>Ответ</h6>
total
: Общий онлайн на MiniGames.

separated
: Онлайн отдельно по каждой мини игре.
