---
title: "Блюда: потери при обработке продуктов и массовая замена продуктов"
date: 2022-07-11 00:00:00 +0300
tags: [потери, обработка продуктов, массовая замена, продукты, блюда, полуфабрикаты]
author: "Private CRM"
layout: post
canonical: "https://telegra.ph/Blyuda-poteri-pri-obrabotke-produktov-i-massovaya-zamena-produktov-07-11"
summary: "Переработан функционал потерь при обработке продуктов и добавлен удобный инструмент массовой замены продуктов в блюдах и полуфабрикатах."
---

### Потери при обработке продуктов
Мы переработали функционал применения потерь при холодной и горячей обработке продуктов. Ранее тип горячей обработки и проценты потерь задавались в самом продукте, но разных типов обработки может быть немало и даже при одном и том же типе обработки потери продукта могут отличаться от блюда к блюду. Поэтому мы решили отказаться от указания типов обработки и соответствующих им потерь в свойствах продуктов и дали возможность задавать потери продуктов индивидуально для каждого блюда.

<div style="text-align:center;">
  <img src="{{ '/assets/img/posts/2022-07-11-blyuda-poteri-pri-obrabotke-produktov-i-massovaya-zamena-produktov/1.jpg' | relative_url }}" alt="1" style="max-width:100%; height:auto; display:inline-block;" />
</div>

В продуктах оставили возможность задать проценты холодной и горячей обработки, но теперь они выступают как значения по умолчанию при добавлении продукта в блюдо.

Если вы использовали типы обработок в продуктах, то проценты из них автоматически переносятся в блюда, где они использовались. Это никак не влияет на расчеты в созданных блюдах.

### Массовая замена продуктов

Сделали удобный функционал для массовой замены продуктов в блюдах и полуфабрикатах. Находится в справочнике "Продукты" - "Действия".

<div style="text-align:center;">
  <img src="{{ '/assets/img/posts/2022-07-11-blyuda-poteri-pri-obrabotke-produktov-i-massovaya-zamena-produktov/2.jpg' | relative_url }}" alt="2" style="max-width:100%; height:auto; display:inline-block;" />
</div>

Выбираете продукт который хотите заменить и на что. Выбираете блюда, в которых производите замену, сохраняете и готово!

<div style="text-align:center;">
  <img src="{{ '/assets/img/posts/2022-07-11-blyuda-poteri-pri-obrabotke-produktov-i-massovaya-zamena-produktov/3.jpg' | relative_url }}" alt="3" style="max-width:100%; height:auto; display:inline-block;" />
</div>

Можно заменить продукт во всех блюдах и сразу удалить его.  

Также для удобства добавили в карточки блюд возможность посмотреть в каких диетах блюдо используется, а в карточке продуктов - в каких блюдах и полуфабрикатах используется продукт.

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2022-07-11-blyuda-poteri-pri-obrabotke-produktov-i-massovaya-zamena-produktov/4.jpg' | relative_url }}" alt="4" style="max-width:100%; height:auto; display:inline-block;" />
  <figcaption>В карточке блюда</figcaption>
</figure>

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2022-07-11-blyuda-poteri-pri-obrabotke-produktov-i-massovaya-zamena-produktov/5.jpg' | relative_url }}" alt="5" style="max-width:100%; height:auto; display:inline-block;" />
  <figcaption>В карточке продукта</figcaption>
</figure>
