---
title: "Расписание по тарифу"
date: 2023-10-02 00:00:00 +0300
categories: [Обновления]
tags: [расписание, тарифы, календарь доставок]
author: "Private CRM"
layout: post
canonical: "https://telegra.ph/Raspisanie-po-tarifu-10-02"
toc: false
summary: "Инструкция: как создать расписание по тарифу, если тариф соответствует фиксированному количеству дней."
---

Если необходимо создать расписание по тарифу, которому соответствует определённое количество дней (а не диапазон дней или нет связки тарифа с количеством дней), то сделайте 2 следующих шага:

  1. В Справочники-Тарифы укажите количество дней питания клиента для автоматического создания расписания.

<div style="text-align:center;">
  <img src="{{ '/assets/img/posts/2023-10-02-raspisanie-po-tarifu/1.jpg' | relative_url }}" alt="1" style="max-width:100%; height:auto; display:inline-block;" />
</div>

2. При создании/редактировании заказа выберите первый день питания клиента, от которой программа рассчитает расписание, учитывая количество дней питания (заданное в Справочники-Тарифы) и расписание (заданное в Справочники-Расписания доставок).

<div style="text-align:center;">
  <img src="{{ '/assets/img/posts/2023-10-02-raspisanie-po-tarifu/2.jpg' | relative_url }}" alt="2" style="max-width:100%; height:auto; display:inline-block;" />
</div>

Пример: создаём расписание по тарифу 5 дней от дня питания 03.10 (вт), расписание: вечерняя доставка 2х рационов через день. Получим:

<div style="text-align:center;">
  <img src="{{ '/assets/img/posts/2023-10-02-raspisanie-po-tarifu/3.jpg' | relative_url }}" alt="3" style="max-width:100%; height:auto; display:inline-block;" />
</div>
