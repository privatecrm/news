---
title: "Замена в заказе. Улучшения"
date: 2024-12-17 00:00:00 +0300
tags: [замены, блюда, исключения, заказы]
author: "Private CRM"
layout: post
canonical: "https://telegra.ph/Zamena-v-zakaze-Uluchsheniya-12-17"
toc: false
summary: "Улучшения механики замены блюд в заказе: отображение исключений, сортировка списка замен, фильтр по отклонению калорийности и сохранение введённых значений."
---

Доброго дня, друзья! Знаем, вы очень ждёте функционал Замены на производстве, поэтому активно занимаемся его разработкой, а пока что внесли улучшения в Замены в заказе:

1. Добавили отображение исключений у блюд и производственный комментарий, чтобы необходимая информация по предпочтениям клиента была перед глазами при осуществлении замен:

    <figure style="text-align:center;">
      <img src="{{ '/assets/img/posts/2024-12-17-zamena-v-zakaze-uluchsheniya/1.jpg' | relative_url }}" alt="1" style="max-width:100%; height:auto; display:inline-block;" />
    </figure>

2. Улучшили сортировку выпадающего списка блюд на замену - сначала идут подходящие блюда из группы на замену, далее блюда, в которых есть продукт-исключение, а следом - блюда-исключения.

    <figure style="text-align:center;">
      <img src="{{ '/assets/img/posts/2024-12-17-zamena-v-zakaze-uluchsheniya/2.jpg' | relative_url }}" alt="2" style="max-width:100%; height:auto; display:inline-block;" />
    </figure>
    
    Если выбрать блюдо с пометкой (Исключен продукт)/(Исключено), будет выведено предупреждение под выбранным блюдом:
    
    <figure style="text-align:center;">
      <img src="{{ '/assets/img/posts/2024-12-17-zamena-v-zakaze-uluchsheniya/3.jpg' | relative_url }}" alt="3" style="max-width:100%; height:auto; display:inline-block;" />
      <img src="{{ '/assets/img/posts/2024-12-17-zamena-v-zakaze-uluchsheniya/4.jpg' | relative_url }}" alt="4" style="max-width:100%; height:auto; display:inline-block;" />
    </figure>
    
    Таким образом, все блюда-исключения и блюда с исключенным продуктом будут внизу в выпадающем списке. Сортировка по ккал от минимум до максимума сохраняется.
    
    <figure style="text-align:center;">
      <img src="{{ '/assets/img/posts/2024-12-17-zamena-v-zakaze-uluchsheniya/5.jpg' | relative_url }}" alt="5" style="max-width:100%; height:auto; display:inline-block;" />
    </figure>

3. Добавили возможность указать процент допустимого отклонения от калорийности блюда-исключения на 100 г - для ограничения выпадающего списка блюд на замену.  

   Например, у блюда-исключения на 100 г 300 ккал. Тогда, если указать 10% отклонения, то в выпадающем списке будут блюда, у которых на 100 г отклонение +-10% от 300 ккал, т.е. от 270 до 330 ккал.

   Запоминается последнее введённое значение.
   
   Подробнее на видео (со звуком):
   
   <div style="text-align:center;">
     <iframe width="100%" height="480" src="https://www.youtube.com/embed/0utUS68uY8I?si=bU-R95yjkfotngP9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen style="max-width:100%;"></iframe>
   </div>
