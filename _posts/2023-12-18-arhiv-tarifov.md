---
title: "Архив тарифов"
date: 2023-12-18 00:00:00 +0300
categories: [Обновления]
tags: [тарифы, заказы]
author: "PrivateCRM"
layout: post
canonical: "https://telegra.ph/Arhiv-tarifov-12-18"
toc: false
summary: "Теперь при удалении тарифа он попадает в архив и не удаляется из заказов и аналитики — инструкция и скриншоты."
---

Друзья! Мы реализовали тот нюанс работы с удаленными Тарифами, о котором вы нас просили: теперь при удалении тарифа он попадает в архив, а архивный тариф не удаляется из заказов и аналитики.

Как удалить тариф? На странице тарифа внизу - кнопка Удалить:

<div style="text-align:center;">
  <img src="{{ '/assets/img/posts/2023-12-18-arhiv-tarifov/1.jpg' | relative_url }}" alt="Кнопка Удалить" style="max-width:100%; height:auto; display:inline-block;" />
</div>

Удаленный тариф попадает в Архив. Посмотреть все архивные тарифы можно по кнопке Архив:

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2023-12-18-arhiv-tarifov/2.jpg' | relative_url }}" alt="Кнопка Архив" style="max-width:100%; height:auto; display:inline-block;" />
  <figcaption>кнопка Архив на странице Тарифов</figcaption>
</figure>

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2023-12-18-arhiv-tarifov/3.jpg' | relative_url }}" alt="Страница архивных тарифов" style="max-width:100%; height:auto; display:inline-block;" />
  <figcaption>Страница архивных тарифов</figcaption>
</figure>

Можно перейти на карточку удаленного тарифа, чтобы посмотреть его настройки, цены. Изменять архивный тариф нельзя.

<div style="text-align:center;">
  <img src="{{ '/assets/img/posts/2023-12-18-arhiv-tarifov/4.jpg' | relative_url }}" alt="Карточка архивного тарифа" style="max-width:100%; height:auto; display:inline-block;" />
</div>

Удаленный тариф не удаляется из заказов, в которых был применен:

<div style="text-align:center;">
  <img src="{{ '/assets/img/posts/2023-12-18-arhiv-tarifov/5.jpg' | relative_url }}" alt="Тариф в заказах" style="max-width:100%; height:auto; display:inline-block;" />
</div>

Статистика по удаленному тарифу не удаляется из отчета по тарифам и рационам:

<div style="text-align:center;">
  <img src="{{ '/assets/img/posts/2023-12-18-arhiv-tarifov/6.jpg' | relative_url }}" alt="Статистика по тарифу" style="max-width:100%; height:auto; display:inline-block;" />
</div>

Удаленный тариф нельзя применить в новом заказе/добавленных днях созданного заказа.
