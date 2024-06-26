---
## Front matter
title: "Отчёт по четвёртому этапу индивидуального проекта"
subtitle: "дисциплина: Операционные системы"
author: "Студент:Арутюнян Эрик Левонович"

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

Добавить к сайту ссылки на научные и библиометрические ресурсы.

# Задание

1. Зарегистрироваться и разместить ссылку на сайт eLibrary.
2. Зарегистрироваться и разместить ссылку на сайт Google Scholar.
3. Зарегистрироваться и разместить ссылку на сайт ORCID.
4. Зарегистрироваться и разместить ссылку на сайт Mendeley.
6. Зарегистрироваться и разместить ссылку на сайт ResearchGate.
7. Зарегистрироваться и разместить ссылку на сайт Academia.edu.
8. Зарегистрироваться и разместить ссылку на сайт arXiv.
9. Зарегистрироваться и разместить ссылку на сайт github.
10. Сделать пост по прошедшей неделе.
11. Добавить пост на тему: "Создание презентаций".

# Выполнение индивидуального проекта

После того, как мы зарегистрировались на всех нужных ресурсах, приступим к добавлению ссылок на наш сайт. Для этого мы должны проделать данный путь: "work", "blog", "content", "authors", "admin". Внутри каталога "admin" мы открываем файл "_index.md" (рис. [-@fig:001]).

![Открытие нужного файла для редактирования](image/1.png){ #fig:001 width=100% }

В разделе "social" меняем icon_pack на ai и пишем название нужных нам логотипов. Всю информацию о логотипах и нужных паков можно узнать по ссылке: https://wowchemy.com/docs/getting-started/page-builder/#icons. Также не забываем добавить ссылки на ресурсы (рис. [-@fig:002]).

![Добавление ссылок на сайт](image/2.png){ #fig:002 width=100% }

Теперь создадим каталоги для наших новых постов и назовём их: "Моя-3-неделя" и "Презентация в Markdown". Чтобы создать эти каталоги нужно проделать следующий путь: "work", "blog", "content", "post" (рис. [-@fig:003]).

![Создание каталогов для новых постов](image/3.png){ #fig:003 width=100% }

Добавим информацию для наших постов, которую мы написали заранее (рис. [-@fig:004]).

![Добавление информации для поста "Презентация на Markdown"](image/4.png){ #fig:004 width=100% }

Добавим еще дополнительную информацию для наших постов, но только теперь в другом файле. (рис. [-@fig:005]).

![Добавление информации для поста "Презентация на Markdown"](image/5.png){ #fig:005 width=100% }

Чтобы вся наша информация выгрузилась на сайт, откроем в каталоге "blog" терминал и запустим команду hugo (рис. [-@fig:006]).

![Запуск команды hugo](image/6.png){ #fig:006 width=100% }

Как только команда hugo выполнилась перейдём первым этапом в подкаталог "public" и проделаем указанные на скриншоте действия (рис. [-@fig:007]). Вторым этапом проделаем все те же самые действия, но уже в каталоге "blog" (рис. [-@fig:008]).

![Выгрузка из подкаталога "public"](image/7.png){ #fig:007 width=100% }
	
![Выгрузка из каталога "blog"](image/8.png){ #fig:008 width=100% }

Последним шагом перейдём на наш сайт и посмотрим итог работы (рис. [-@fig:009]), (рис. [-@fig:010]).

![Ссылки на научные и библиометрические ресурсы](image/9.png){ #fig:009 width=100% }

![Новые посты](image/10.png){ #fig:010 width=100% }

# Выводы

В ходе выполнения четвёртого этапа индивидуального проекта мы научились добавлять к сайту ссылки на научные и библиометрические ресурсы.
