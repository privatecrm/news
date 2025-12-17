---
title: "Обновлённая страница заказа"
date: 2024-07-09 00:00:00 +0300
categories: [Обновления]
tags: [заказы]
author: "PrivateCRM"
layout: post
canonical: "https://telegra.ph/Obnovlyonnaya-stranica-zakaza-07-09"
summary: "Переосмысленный интерфейс страницы заказа с реактивным обновлением баланса и стоимости, ручной корректировкой цены и улучшенным отображением информации."
---

Доброго дня! Обновили интерфейс главной вкладки Информации о заказе, добавили реактивное обновление Баланса и Стоимости заказа (подробнее об этом — ниже), ускорили загрузку страницы, пофиксили мелкие баги.

### 1. Интерфейс

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2024-07-09-obnovlyonnaya-stranica-zakaza/1.jpg' | relative_url }}" alt="Новый интерфейс заказа" style="max-width:100%; height:auto; display:inline-block;" />
</figure>

Стал компактнее и нагляднее.

* Для введения **ручной корректировки цены** нажмите значок карандашика справа от Стоимости заказа:

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2024-07-09-obnovlyonnaya-stranica-zakaza/2.jpg' | relative_url }}" alt="Корректировка цены — карандашик" style="max-width:100%; height:auto; display:inline-block;" />
</figure>

Введите нужное значение в появившемся боксе:

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2024-07-09-obnovlyonnaya-stranica-zakaza/3.jpg' | relative_url }}" alt="Ввод значения корректировки" style="max-width:100%; height:auto; display:inline-block;" />
</figure>

Нажмите зелёный значок галочки — введённая корректировка отобразится в истории и будет пересчитана Стоимость заказа:

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2024-07-09-obnovlyonnaya-stranica-zakaza/4.jpg' | relative_url }}" alt="Галочка — сохранить корректировку" style="max-width:100%; height:auto; display:inline-block;" />
</figure>

Если введённые данные верны, то для сохранения изменений в заказе на вкладке Информация о заказе нажмите кнопку **Сохранить заказ** внизу страницы (об этом сообщит красный значок с подсказкой-предупреждением):

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2024-07-09-obnovlyonnaya-stranica-zakaza/5.jpg' | relative_url }}" alt="Сохранение заказа" style="max-width:100%; height:auto; display:inline-block;" />
  <img src="{{ '/assets/img/posts/2024-07-09-obnovlyonnaya-stranica-zakaza/6.jpg' | relative_url }}" alt="Подсказка — сохранить заказ" style="max-width:100%; height:auto; display:inline-block;" />
</figure>

Чтобы посмотреть историю логов корректировки стоимости - нажмите на эту надпись:

<div style="text-align:center;">
  <video controls style="max-width:100%; height:auto;">
    <source src="{{ '/assets/img/posts/2024-07-09-obnovlyonnaya-stranica-zakaza/7.mp4' | relative_url }}" type="video/mp4">
    Ваш браузер не поддерживает видео.
  </video>
</div>

* Кнопка **Печати** теперь отстоит отдельно от вкладок — в правой части:

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2024-07-09-obnovlyonnaya-stranica-zakaza/8.jpg' | relative_url }}" alt="Галочка — сохранить корректировку" style="max-width:100%; height:auto; display:inline-block;" />
</figure>

* Вместо строки **Диета** теперь более подробная информация по Рационам подписки:  
  Диета (Тариф): количество рационов:

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2024-07-09-obnovlyonnaya-stranica-zakaza/9.jpg' | relative_url }}" alt="Информация по Рационам" style="max-width:100%; height:auto; display:inline-block;" />
</figure>

---

### 2. Реактивное обновление Баланса и Стоимости заказа

Теперь не нужно обновлять страницу после изменения цены на вкладке **Календаря доставок** для обновления Баланса клиента — он обновится автоматически после внесённых изменений:

<div style="text-align:center;">
  <video controls style="max-width:100%; height:auto;">
    <source src="{{ '/assets/img/posts/2024-07-09-obnovlyonnaya-stranica-zakaza/10.mp4' | relative_url }}" type="video/mp4">
    Ваш браузер не поддерживает видео.
  </video>
</div>

Также обновится Стоимость заказа на вкладках **Оплата** и **Информация о заказе** без перезагрузки.

‼️ Для применения окончательных изменений в заказе (например, если вы поменяли скидки или внесли корректировки стоимости) — как и прежде, нужно нажать кнопку **Сохранить заказ**.

Удобного пользования! 
 
Всегда с вами, команда PrivateCRM
