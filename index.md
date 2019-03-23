---

layout: yandex2

style: |
    /* собственные стили можно писать здесь!! */
    .rrr { position: absolute; top: 150px; left: 810px;}
    .reviewexample { position: absolute; left: 50%; height: 100%; transform: translateX(-50%);}
    .img-center { margin: 120px auto; display: block; }
    .qrcode { display: block; position: absolute; right: 0; bottom: 0; }
    
---

# ![](themes/yandex2/images/logo-{{ site.presentation.lang }}.svg){:.logo}

## {{ site.presentation.title }}
{:.title}

### ![](themes/yandex2/images/title-logo-{{ site.presentation.lang }}.svg){{ site.presentation.service }}

{% if site.presentation.nda %}
![](themes/yandex2/images/title-nda.svg)
{:.nda}
{% endif %}

<div class="authors">
{% if site.author %}
<p>{{ site.author.name }}{% if site.author.position %}, {{ site.author.position }}{% endif %}</p>
{% endif %}

{% if site.author2 %}
<p>{{ site.author2.name }}{% if site.author2.position %}, {{ site.author2.position }}{% endif %}</p>
{% endif %}

</div>

## Что такое ШРИ?
{:.section}

## Что такое ШРИ?

**ШРИ — это курсы фронтенда, которые проводит Яндекс**
<br />

- {:.next}7 школ, первая в 2012 году
- {:.next}обучение бесплатно
- {:.next}два этапа по 1.5 месяца
  - {:.next}теория: лекции и домашние задания
  - {:.next}практика: работа над проектами в командах
- {:.next}собеседования в Яндекс

## Вступительное задание
{:.section}

## Вступительное задание

**Цель — отобрать кандидатов с нужными заниями и навыками.**
<br />

- {:.next}запрограммировать алгоритм на JavaScript
- {:.next}сверстать макеты

## Макеты
{:.fullscreen}

![](pictures/task2-layout.png)

## Вступительное задание

**Цель — отобрать кандидатов с нужными заниями и навыками.**
<br />

- запрограммировать алгоритм на JavaScript
- сверстать макеты
- "найди ошибки"

## Проверка заданий

![](pictures/check.png){:.img-center}

- {:.next}5 — на собеседование
- {:.next}3 — в другой раз
- {:.next}<b>4 — учиться в ШРИ</b>

## Первый этап: теория
{:.section}

## Темы лекций

- адаптивная верстка
- мультимедиа
- работа с Git
- Node.JS
- автотесты
- инфраструктура проектов

<div class="rrr" markdown="1">
- архитектура приложений
- алгоритмы и структуры данных
- клиентская производительность
- типизация: TypeScript
- БЭМ
- дизайн продукта
</div>

![](pictures/code1.gif){:.qrcode}

### [Видеозаписи лекций](https://www.youtube.com/playlist?list=PLKaafC45L_SRqYQW-nFYw8bOlm3IYc2BI)

## Темы лекций

- <b>адаптивная верстка</b>
- мультимедиа
- работа с Git
- Node.JS
- автотесты
- инфраструктура проектов

<div class="rrr" markdown="1">
- <b>архитектура приложений</b>
- алгоритмы и структуры данных
- <b>клиентская производительность</b>
- типизация: TypeScript
- БЭМ
- дизайн продукта
</div>

![](pictures/code1.gif){:.qrcode}

### [Видеозаписи лекций](https://www.youtube.com/playlist?list=PLKaafC45L_SRqYQW-nFYw8bOlm3IYc2BI)

## Темы лекций

- адаптивная верстка
- мультимедиа
- <b>работа с Git</b>
- <b>Node.JS</b>
- автотесты
- инфраструктура проектов

<div class="rrr" markdown="1">
- архитектура приложений
- алгоритмы и структуры данных
- клиентская производительность
- <b>типизация: TypeScript</b>
- БЭМ
- дизайн продукта
</div>

![](pictures/code1.gif){:.qrcode}

### [Видеозаписи лекций](https://www.youtube.com/playlist?list=PLKaafC45L_SRqYQW-nFYw8bOlm3IYc2BI)


## Темы лекций

- адаптивная верстка
- мультимедиа
- работа с Git
- Node.JS
- автотесты
- инфраструктура проектов

<div class="rrr" markdown="1">
- архитектура приложений
- алгоритмы и структуры данных
- клиентская производительность
- типизация: TypeScript
- БЭМ
- <b>дизайн продукта</b>
</div>
<div class="next" markdown="1">
**тренинг: публичные выступления**
**тренинг: работа в команде**
</div>

![](pictures/code1.gif){:.qrcode}

### [Видеозаписи лекций](https://www.youtube.com/playlist?list=PLKaafC45L_SRqYQW-nFYw8bOlm3IYc2BI)


## Кто читает лекции

- {:.next}разработчики из Яндекса
- {:.next}участвуют в ШРИ добровольно
  - {:.next}чтобы лучше разобратсья в теме
  - {:.next}улучшить навыки выступлений
  - {:.next}нравится учить студентов
- {:.next} повторное чтение лекций

## Информацию трудно воспринимать на слух
{:.blockquote}

## Задачи лекции

1. ~~Раскрыть тему подробно~~
2. {:.next}<b>Сформировать общую картину</b>

## Навигация в торговорм центре
{:.fullscreen}

![](pictures/navigation.jpg)

## Задачи лекции

1. ~~Раскрыть тему подробно~~
2. Сформировать общую картину
3. <b>Объяснить сложные идеи</b>

## Лектор видит реакцию студентов
{:.fullscreen}

![](pictures/lecture.jpg)

## Домашние задания —<br />основная обучающая активность
{:.blockquote}

## Домашние задания

- каждое задание — мини-проект
- результат — pull request

<div class="next" markdown="1">
Примеры заданий:

- <b>Node.JS:</b> написать серверное приложение
- {:.next}<b>автотесты:</b> написать модульные и интеграционные тесты
- {:.next}<b>типизация:</b> переписать проект на TypeScript
</div>


## Code rview
{:.fullscreen}

![](pictures/reviewexample.png){:.reviewexample}

## Темы лекций

- адаптивная верстка
- мультимедиа
- работа с Git
- Node.JS
- автотесты
- инфраструктура проектов

<div class="rrr" markdown="1">
- архитектура приложений
- <b>алгоритмы и структуры данных</b>
- <b>клиентская производительность</b>
- типизация: TypeScript
- БЭМ
- дизайн продукта
</div>

![](pictures/code1.gif){:.qrcode}

### [Видеозаписи лекций](https://www.youtube.com/playlist?list=PLKaafC45L_SRqYQW-nFYw8bOlm3IYc2BI)


## Алгоритмический марафон
{:.fullscreen}

![](pictures/marathon.jpg){:.reviewexample}

## Второй этап: практика
{:.section}

## Второй этап: практика

**Студенты работают над проектами в командах**
<br />

- {:.next}эмуляция реальной работы
- {:.next}нужно комплексно применить знания
- {:.next}важно разделение теории и практики

## Проекты должны быть настоящими

Критерии отбора проектов:

- {:.next}проект приносит пользу и реализуем
- {:.next}проработаны требования
- {:.next}можно реализовать за 1.5 месяца

## Примеры проектов: сервис
{:.fullscreen}

![](pictures/shri-account.png)

## Примеры проектов: библиотека
{:.fullscreen}

![](pictures/map.png)

## Примеры проектов: прототип
{:.fullscreen}

![](pictures/mail.png)

### https://habr.com/ru/company/yandex/blog/439884/

## Режим работы 1
{:.fullscreen}

![](pictures/project1.png)


## Режим работы 2
{:.fullscreen}

![](pictures/project5.png)

## Режим работы 3
{:.fullscreen}

![](pictures/project6.png)

## Вручение дипломов
{:.fullscreen}

![](pictures/theend.jpg)

## Зачем проводить ШРИ?
{:.section}

## Контакты
{:.contacts}

{% if site.author %}

<figure markdown="1">

### {{ site.author.name }}

{% if site.author.position %}
{{ site.author.position }}
{% endif %}

</figure>

{% endif %}

{% if site.author2 %}

<figure markdown="1">

### {{ site.author2.name }}

{% if site.author2.position %}
{{ site.author2.position }}
{% endif %}

</figure>

{% endif %}

<!-- разделитель контактов -->
-------

<!-- left -->
- {:.mail}dima117a@yandex-team.ru
- {:.telegram}dima117a
- {:.github}dima117

<!-- right -->

## ШРИ — 2019
{:.shout}

![](pictures/code2.gif){:.qrcode}

### [Оставить заявку](https://yandex.ru/promo/academy/shri)

<!-- 

- {:.mail}author@yandex-team.ru
- {:.phone}+7-999-888-7766
- {:.github}author
- {:.bitbucket}author
- {:.twitter}@author
- {:.telegram}author
- {:.skype}author
- {:.instagram}author
- {:.facebook}author
- {:.vk}@author
- {:.ok}@author

-->
