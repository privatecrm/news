---
title: "Закрепление клиента за менеджером"
date: 2023-11-30 00:00:00 +0300
tags: [клиенты, менеджеры, права доступа]
author: "PrivateCRM"
layout: post
canonical: "https://telegra.ph/Naznachennyj-menedzher-11-30"
toc: false
summary: "Добавлена возможность привязки клиента к менеджеру и фильтрация заказов/клиентов по назначенному менеджеру."
---

Добавили возможность привязки клиента к менеджеру! Теперь всех клиентов можно распределить по менеджерам. А на страницах Заказов и Клиентов - применить фильтр По менеджерам (скрины - в самом низу страницы). Но сначала приведем общие характеристики Менеджера клиентов.
1. **Все существующие клиенты** назначены на пользователей, которые их **создали**. Проверьте, пожалуйста, и при необходимости скорректируйте назначенного менеджера!
2. Настраивается в карточке клиента:

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2023-11-30-zakreplenie-klienta-za-menedzherom/1.jpg' | relative_url }}" alt="Настройка менеджера в карточке клиента" style="max-width:100%; height:auto; display:inline-block;" />
</figure>

3. В выпадающем списке отображаются менеджеры, у которых в группе пользователей/у пользователя свойство "Менеджер клиентов" отмечено галочкой:

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2023-11-30-zakreplenie-klienta-za-menedzherom/2.jpg' | relative_url }}" alt="Свойство Менеджер клиентов в группе пользователей" style="max-width:100%; height:auto; display:inline-block;" />
  <figcaption>Свойство «Менеджер клиентов» в группе пользователей</figcaption>
</figure>

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2023-11-30-zakreplenie-klienta-za-menedzherom/3.jpg' | relative_url }}" alt="Свойство Менеджер клиентов у пользователя" style="max-width:100%; height:auto; display:inline-block;" />
  <figcaption>Свойство «Менеджер клиентов» у пользователя</figcaption>
</figure>

4. При создании заказа с НОВЫМ клиентом, этому клиенту назначается менеджером текущий пользователь (НО только если он состоит в группе с галочкой менеджеров).

5. Чтобы редактировать менеджера в СОЗДАННОМ клиенте, нужно право №311:

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2023-11-30-zakreplenie-klienta-za-menedzherom/4.jpg' | relative_url }}" alt="Права для редактирования менеджера" style="max-width:100%; height:auto; display:inline-block;" />
</figure>

Страница заказов, отфильтрованных по назначенному менеджеру, имеет вид:

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2023-11-30-zakreplenie-klienta-za-menedzherom/5.jpg' | relative_url }}" alt="Заказы, отфильтрованные по назначенному менеджеру" style="max-width:100%; height:auto; display:inline-block;" />
</figure>

Страница клиентов, отфильтрованных по назначенному менеджеру, имеет вид:

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2023-11-30-zakreplenie-klienta-za-menedzherom/6.jpg' | relative_url }}" alt="Клиенты, отфильтрованные по назначенному менеджеру" style="max-width:100%; height:auto; display:inline-block;" />
</figure>

Обращаем внимание, что на странице Клиенты при выборе фильтра по назначенному менеджеру фильтр по датам становится неактивным. Т.е. можно увидеть всех клиентов по назначенному менеджеру.

P.S. Старый фильтр "по менеджерам" переименовали в "по действиям менеджеров":

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2023-11-30-zakreplenie-klienta-za-menedzherom/7.jpg' | relative_url }}" alt="Фильтр по действиям менеджеров" style="max-width:100%; height:auto; display:inline-block;" />
</figure>
