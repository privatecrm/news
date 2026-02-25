---
layout: post
title: "Новая сборка: собираем заказы быстрее и без ошибок"
date: 2025-12-26
author: "PrivateCRM"
categories: [Обновления]
tags: [сборка заказов, производство, рационы]
canonical: "https://telegra.ph/Sborka-zakazov-12-26"
summary: "Обновлённый модуль «Сборка заказов» — сокращает время, минимизирует ошибки и адаптируется под ваш производственный процесс."
---

Друзья, сборка рационов по пакетам — это финишная прямая производства, где важна каждая деталь. Мы проанализировали ваши рабочие процессы и обратную связь, чтобы кардинально улучшить этот этап. Сегодня представляем масштабное обновление модуля **«Сборка заказов»**, которое превращает рутину в четкий и контролируемый процесс, экономит время и сводит человеческие ошибки к нулю.  

Универсального, единого для всех алгоритма сборки не существует. Поэтому мы сделали не просто новый интерфейс, а **интеллектуальный инструмент, который адаптируется под ваш производственный процесс**.

## Основные преимущества:

✅ **Экономия времени**: Система автоматически группирует идентичные по содержимому пакеты (день диеты + исключения/замены/допы). Не нужно вчитываться в предпочтения каждого клиента — вы фокусируетесь на вариантах комплектации.

✅ **Сборка стала проще**: Алгоритм сам подсказывает, что и куда класть. Не нужно знать и держать в голове нюансы процесса. Достаточно распечатать и действовать по списку — справится даже новичок.

✅ **Нет ошибок**: При комплектации сразу видно сколько и каких пакетов в заказе и какие в них расходники.

✅ **Гибкость**: Настройте отображение под ваш процесс — работайте так, как удобно именно вам.

✅ **Компактная печать**: Весь план сборки умещается на нескольких листах. Все фильтры и настройки учитываются при печати.

## Подготовка к работе: настройки

  * В зависимости от вашего производственного процесса укажите, когда собираются заказы — сразу **после готовки** или **перед доставкой**.

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2025-12-26-sborka-zakazov/1.jpg' | relative_url }}" alt="1" style="max-width:100%; height:auto; display:inline-block;" />
</figure>

> ⚠️Настройка также влияет на печать бланков заказов и наклеек.

  * Если вы комплектуете несколько рационов в один пакет, например рационы на выходные, то включите настройку **Рационы по одному адресу в один пакет**.

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2025-12-26-sborka-zakazov/2.jpg' | relative_url }}" alt="2" style="max-width:100%; height:auto; display:inline-block;" />
</figure>

  * Настройка для полуавтоматического режиме: если информация об исключениях пока хранится просто в комментариях, можно настроить чтобы все **рационы с комментариями производства относились к нестандартным**.

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2025-12-26-sborka-zakazov/3.jpg' | relative_url }}" alt="3" style="max-width:100%; height:auto; display:inline-block;" />
</figure>

> ⚠️Настройка также помечает рационы с комментарием производства как нестандартные в блоке **Для курьеров**

> ⚠️К нестандартным будут отнесены **ВСЕ** рационы с комментарием производства, независимо от того, есть ли исключение конкретно в данном рационе или нет. Для полноценной автоматизации процесса рекомендуем занести исключения в специальные поля в карточке **Клиента/Заказа**

  * Откройте **Производство** в смене, перейдите во вкладку **Сборка заказов**.
  * Если для стандартных рационов вам необходима информация по номерам заказов или именам клиентов — включите тумблер **Детализация**.

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2025-12-26-sborka-zakazov/4.jpg' | relative_url }}" alt="4" style="max-width:100%; height:auto; display:inline-block;" />
</figure>

  * Если нужна информация о перечне блюд в днях диет, включите настройку **Отображать состав диеты**

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2025-12-26-sborka-zakazov/5.jpg' | relative_url }}" alt="5" style="max-width:100%; height:auto; display:inline-block;" />
</figure>

  * Настройте отображение необходимых столбцов таблицы — нажмите карандашик справа.

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2025-12-26-sborka-zakazov/6.jpg' | relative_url }}" alt="6" style="max-width:100%; height:auto; display:inline-block;" />
</figure>

## Сборка заказов — шаг за шагом. 2 сценария

### Сценарий 1: сборка после готовки одного дня питания, каждый рацион — в отдельный пакет

Готовится и сразу собирается 11 день диеты — рацион на среду.

#### **Шаг 1.** Собираем нестандартные рационы.

Для диеты 1200 ккал система показывает 2 варианта **нестандартных** рационов:

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2025-12-26-sborka-zakazov/7.jpg' | relative_url }}" alt="7" style="max-width:100%; height:auto; display:inline-block;" />
</figure>

**Вариант А** (3 пакета): Рацион **без мяты** в блюде *«Каша овсяная на кокосовом молоке 190г»*.

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2025-12-26-sborka-zakazov/8.jpg' | relative_url }}" alt="8" style="max-width:100%; height:auto; display:inline-block;" />
</figure>

**Вариант Б** (2 пакета): рацион с заменой *«Каши овсяной на кокосовом молоке 190г»* на *«Кукурузную кашу с клубникой и миндалем 209г»*.

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2025-12-26-sborka-zakazov/9.jpg' | relative_url }}" alt="9" style="max-width:100%; height:auto; display:inline-block;" />
</figure>

#### **Шаг 2.** Комплектуем пакеты расходниками (приборы, наклейки, бланки).

Взгляните на правую часть таблицы:

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2025-12-26-sborka-zakazov/10.jpg' | relative_url }}" alt="10" style="max-width:100%; height:auto; display:inline-block;" />
</figure>

  * В столбце *«Заказы (пакеты)»* указаны номера заказов и количество пакетов данного типа на каждый заказ, например, **3846(2)**.

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2025-12-26-sborka-zakazov/11.jpg' | relative_url }}" alt="11" style="max-width:100%; height:auto; display:inline-block;" />
</figure>

  * Значок вилки/ножа показывает, в какие заказы нужно положить приборы.
  * Информация о расходниках — в верхней части вкладки.
  * Общее количество заказов — в шапке таблицы.

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2025-12-26-sborka-zakazov/12.jpg' | relative_url }}" alt="12" style="max-width:100%; height:auto; display:inline-block;" />
</figure>

🖨️ Печать бланков и наклеек:

  * вкладка *Печать → Бланки заказов*
  * вкладка *Печать → Наклейки на пакеты*

#### **Шаг 3.** Собираем стандартные рационы.

  * Состав стандартных рационов отображается под шапкой диеты (жёлтая подсветка).
  * Количество стандартных пакетов указано в шапке и в таблице (оранжевые рамки).
<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2025-12-26-sborka-zakazov/13.jpg' | relative_url }}" alt="13" style="max-width:100%; height:auto; display:inline-block;" />
</figure>

  * Внизу таблицы указано, в какие пакеты нужно добавить расходники.
    В 5 пакетах приборы не нужны, в 1 пакет — нужны.

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2025-12-26-sborka-zakazov/14.jpg' | relative_url }}" alt="14" style="max-width:100%; height:auto; display:inline-block;" />
</figure>

#### **Шаг 4.** Повторяем сборку для других диет.

### Сценарий 2: сборка перед доставкой разных дней питания, рационы по одному адресу — в 1 пакет

Перед доставкой собираются 13, 14 и 15 дни диеты — рационы на пятницу, субботу и воскресенье. Рационы на пятницу доставляются утром, на субботу и воскресенье — вечером.

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2025-12-26-sborka-zakazov/15.jpg' | relative_url }}" alt="15" style="max-width:100%; height:auto; display:inline-block;" />
</figure>

Для декомпозиции сложной сборки на простые шаги будем использовать фильтры по *времени Доставки* и *Дню питания*.

#### 🌞Утренняя доставка

Соберём пакеты, которые доставляются утром.

##### **Шаг 1.** Собираем нестандартные рационы

Для диеты 1500 ккал система показывает 1 вариант **нестандартных** рационов (2 пакета) с дополнительным блюдом *«Птитим с говядиной 155г»*.

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2025-12-26-sborka-zakazov/16.jpg' | relative_url }}" alt="16" style="max-width:100%; height:auto; display:inline-block;" />
</figure>

##### **Шаг 2.** Комплектуем нестандартные пакеты расходниками.

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2025-12-26-sborka-zakazov/17.jpg' | relative_url }}" alt="17" style="max-width:100%; height:auto; display:inline-block;" />
</figure>

##### **Шаг 3.** Собираем стандартные рационы и комплектуем их расходниками.

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2025-12-26-sborka-zakazov/18.jpg' | relative_url }}" alt="18" style="max-width:100%; height:auto; display:inline-block;" />
</figure>

##### **Шаг 4.** Аналогично собираем рационы утренней доставки для других диет.

#### 🌚Вечерняя доставка

Теперь соберём пакеты, которые доставляются вечером.

В сумме: **5 пакетов** — из них **3 стандартных** (2 варианта комплектации: одинарные/двойные) и **2 нестандартных** (1 вариант комплектации).

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2025-12-26-sborka-zakazov/19.jpg' | relative_url }}" alt="19" style="max-width:100%; height:auto; display:inline-block;" />
</figure>

##### **Шаг 1.** Сначала будем собирать рационы 15 дня диеты (ВС), чтобы они лежали в пакете под рационом 14 дня для удобства клиента.

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2025-12-26-sborka-zakazov/20.jpg' | relative_url }}" alt="20" style="max-width:100%; height:auto; display:inline-block;" />
</figure>

###### **Шаг 1.2.** Собираем нестандартные рационы.
В нашем примере нет нестандартных рационов 15 дня (изменения в нестандартном пакете касаются дня 14).

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2025-12-26-sborka-zakazov/21.jpg' | relative_url }}" alt="21" style="max-width:100%; height:auto; display:inline-block;" />
</figure>

###### **Шаг 1.3.** Собираем все стандартные рационы 15 дня в 3 пакета.

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2025-12-26-sborka-zakazov/22.jpg' | relative_url }}" alt="22" style="max-width:100%; height:auto; display:inline-block;" />
</figure>

###### **Шаг 1.4.** Комплектуем нестандартные пакеты расходниками.

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2025-12-26-sborka-zakazov/23.jpg' | relative_url }}" alt="23" style="max-width:100%; height:auto; display:inline-block;" />
</figure>

###### **Шаг 1.5.** Аналогично собираем рационы 15 дня (ВС) для других диет.
<br> 

##### **Шаг 2.** Теперь будем собирать рационы 14 дня диеты (СБ).

###### **Шаг 2.1.** Собираем нестандартные рационы.
Для диеты 1500 ккал система показывает 1 вариант **нестандартных** рационов (2 пакета) с одинаковыми исключениями по продукту в 2 блюдах.

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2025-12-26-sborka-zakazov/24.jpg' | relative_url }}" alt="24" style="max-width:100%; height:auto; display:inline-block;" />
</figure>

Доукомпектовываем 2 нестандартных пакета, в которые уже собраны рационы 15 дня диеты (ВС) и расходники.

###### **Шаг 2.2.** Собираем стандартные рационы.

Всего рационов 3. Из них:

  * 2 пойдёт в обычный пакет (только день 14).
  * 1 пойдёт в сдвоенный пакет (14+15), в котором уже собран 15 день диеты (ВС).

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2025-12-26-sborka-zakazov/25.jpg' | relative_url }}" alt="25" style="max-width:100%; height:auto; display:inline-block;" />
</figure>
###### **Шаг 2.3.** Комплектуем стандартные пакеты расходниками.

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2025-12-26-sborka-zakazov/26.jpg' | relative_url }}" alt="26" style="max-width:100%; height:auto; display:inline-block;" />
</figure>

###### **Шаг 2.4.** Повторяем сборку для других диет.

## ➡️ Что ещё улучшили:

  * **Сборка разовых заказов** (бывшая «Розница»): Добавили состав для каждого заказа, свои настройки отображения и печать.

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2025-12-26-sborka-zakazov/27.jpg' | relative_url }}" alt="27" style="max-width:100%; height:auto; display:inline-block;" />
</figure>

  * **Сборка контейнеров**: Добавили фильтры по приемам пищи и печать.

<figure style="text-align:center;">
  <img src="{{ '/assets/img/posts/2025-12-26-sborka-zakazov/28.jpg' | relative_url }}" alt="28" style="max-width:100%; height:auto; display:inline-block;" />
</figure>

Попробуйте новую сборку в деле!

Расскажите в комментариях, под какие ваши производственные процессы её можно ещё улучшить❓
<br>     

С заботой о вашей эффективности,

команда PrivateCRM💪