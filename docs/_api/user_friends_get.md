---
title: /user/:id/friends
position: 1.3
type: get
description: Получает друзей игрока
right_code: |
  ~~~ json
  {
    "user": {
      "id": 134568,
      "username": "xtrafrancyz",
      "level": 5,
      "rank": "ADMIN",
      "playedSeconds": 3106732
    },
    "friends": [
      {
        "id": 105889,
        "username": "rsboe",
        "level": 8,
        "rank": "BUILDER",
        "playedSeconds": 5508358
      },
      {
        "id": 94245,
        "username": "Okssi",
        "level": 10,
        "rank": "CHIEF",
        "playedSeconds": 2596550
      },
      {
        "id": 113654,
        "username": "SmaIK",
        "level": 3,
        "rank": "ADMIN",
        "playedSeconds": 1300227
      }
    ]
  }
  ~~~
  {: title="Пример запроса" url="/user/134568/friends" }
---

<h6>Параметры</h6>
id
: id игрока.

Возвращает список друзей игрока.
