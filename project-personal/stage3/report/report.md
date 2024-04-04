---
## Front matter
title: "Отчёт по третьему этапу индивидуального проекта"
subtitle: "дисциплина: Операционные системы"
author: "Студент: Арутюнян Эрик Левонович"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Добавить к сайту достижения.

# Задание

1. Добавить информацию о навыках (Skills).
2. Добавить информацию об опыте (Experience).
3. Добавить информацию о достижениях (Accomplishments).
4. Сделать пост по прошедшей неделе.
6. Добавить пост на тему: "Язык разметки Markdown"

# Выполнение индивидуального проекта

Для начала добавим информацию о навыках. Для этого мы должны проделать данный путь: "work", "blog", "content" и зайти в файл "_index.md".(рис. [-@fig:001]).

![Добавление навыков](image/1.png){ #fig:001 width=100% }

Теперь нам нужно добавить информацию об опыте.(рис. [-@fig:002]).

![Добавление опыта](image/2.png){ #fig:002 width=100% }

Теперь добавим наши достижения (рис. [-@fig:003]).

![Добавление достижений](image/3.png){ #fig:003 width=100% }

В каталоге "post" создаём два каталога "Markdown" и "Моя 2 неделя", в которые добавим написанные нами тексты для постов (рис. [-@fig:004]).

![Создание постов](image/4.png){ #fig:004 width=100% }

Чтобы вся наша информация выгрузилась на сайт, откроем в каталоге "blog" терминал и запустим команду hugo (рис. [-@fig:005]).

![Запуск команды hugo](image/5.png){ #fig:005 width=100% }

Как только команда hugo выполнилась перейдём первым этапом в подкаталог "public" и проделаем указанные на скриншоте действия (рис. [-@fig:006]). Вторым этапом проделаем все те же самые действия, но уже в каталоге "blog" (рис. [-@fig:007]).

![Выгрузка из подкаталога "public"](image/6.png){ #fig:006 width=100% }
	
![Выгрузка из каталога "blog"](image/7.png){ #fig:007 width=100% }

Последним шагом перейдём на наш сайт и посмотрим итог работы (рис. [-@fig:008]), (рис. [-@fig:009]), (рис. [-@fig:010]), (рис. [-@fig:011]).

![Навыки](image/8.png){ #fig:008 width=100% }

![Опыт](image/9.png){ #fig:009 width=100% }

![Достижения](image/10.png){ #fig:010 width=100% }

![Новые посты на сайте](image/11.png){ #fig:011 width=100% }

# Выводы

В ходе выполнения третьего этапа индивидуального проекта мы научились добавлять к сайту достижения.
