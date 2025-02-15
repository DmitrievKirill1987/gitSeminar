# Справочник команд для Git и синтаксис языка Markdown

[Перейти к разделу "Основные команды Git"](##-Основные-команды-Git)

[Перейти к разделу "Основные команды работы с ветками"](##-Основные-команды-работы-с-ветками)

[Перейти к разделу "Основные команды работы с удаленными репозиториями"](##-Основные-команды-работы-с-удалеными-репозиториями)

[Перейти к разделу "Синтаксис языка Markdown"](##-Синтаксис-языка-Markdown)

    [Перейти к разделу "Основные команды Git"](##-Основные-команды-Git)

    [Перейти к разделу "Синтаксис языка Markdown"](##-Синтаксис-языка-Markdown)

## Основные команды Git

**git init** - инициализация локального репозитория

**git status** - получить информацию от git о его текущем состоянии

**git add** - добавить файл или файлы к следующему комиту

**git add .** - добавляет все файлы в проекте к отслеживанию

**git commit -am "message"** - git add + git commit (Работает только после 1-го ручного добавления в отслеживании)

**git commit -m "message"** - создание коммита

**gir log** - вывод на экран истории всех коммитов с их же хэш-кодами

**git checkout** - переход от одного коммита к другому

**git checkout master** - переход к актуальному состоянию и продолжить работу

**git diff** - увидеть разницу между текущим файлом и закоммиченным файлом

## Основные команды работы с ветками

* git branch - посмотреть список веток в репозитории

* git branch <название ветки> - создать новую ветку

* git checkout <название ветки> - переход на другую ветку

* git branch -d <название ветки> - удалить ветку

* git log --graph - визуализирует коммиты

* git checkout -b <название ветки> - создание и переход в новую ветку

## Основные команды работы с удаленными репозиториями

1. git clone <url-адрес репозитория> – клонирование внешнего репозитория на  локальный ПК

2. git pull – получение изменений и слияние с локальной версией

3. git push – отправляет локальную версию репозитория на внешний

## Синтаксис языка Markdown

## Заголовок 
    #Заголовок - выделение заголовков. Количество символов “#” задаёт уровень заголовка  (поддерживается 6 уровней).

- ненумерованный список 1 уровня
  - ненумерованный список 2 уровня
    - ненумерованный список 3 уровня

          " * " или " - " – подчёркиванием этими символами (не более 3 подряд) выделяют ненумерованные списки  первого (“ * ”) и второго (“ - ”) уровней.

**Полужирное начертание** или __Полужирное начертание__

    **Полужирное начертание** или __Полужирное начертание__

*Курсивное начертание* или _Курсивное начертание_

    *Курсивное начертание* или _Курсивное начертание_

***Полужирное курсивное начертание***

    ***Полужирное курсивное начертание***

~~Зачёркнутый текст~~

    ~~Зачёркнутый текст~~

1. Нумерованный список
2. 1. Нумерованный список
3. 1. 1. Нумерованный список

              1, 2, 3 … – нумерованные списки


> Information the user should notice

&#8220; &#8221; &#8217; &#8216; - Кавычки и апострофы

    &#8220; &#8221; &#8217; &#8216;

<!--- Here's my comment ---> Тут комментарий

    <!--- Here's my comment --->

![<Image>](/AUDI.jpg)

    ![<Image>](/AUDI.jpg)

Для загрузки домашнего задания к семинару перейди в [раздел практическое задание](https://gb.ru/lessons/300006/homework).

    Для загрузки домашнего задания к семинару перейди в [раздел практическое задание](https://gb.ru/lessons/300006/homework).