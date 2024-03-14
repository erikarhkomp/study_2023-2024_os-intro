---
## Front matter
lang: ru-RU
title: Лабораторная работа №6.
subtitle: 
author:
  - Арутюнян Эрик Левонович
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 22 февраля 2024


## Formatting
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
toc: false
slide_level: 2
theme: metropolis
header-includes:
- \metroset{progressbar=frametitle,sectionpage=progressbar, numbering=fraction}
- '\makeatletter'
- '\beamer@ignorenonframefalse'
- '\makeatother'
aspectratio: 43
section-titles: true

---

# Цели и задачи работы

## Цели и задачи

Приобретение практических навыков взаимодействия пользователя с системой по-
средством командной строки

# Процесс выполнения лабораторной работы

## Определим полное имя вашего домашнего каталога.

![Имя домашнего каталога](image/1.png){#fig:001 width=70%}

## Перейдём в каталог /tmp

![Переход в каталог /tmp](image/2.png){#fig:002 width=70%}

## Выведем на экран содержимое каталога /tmp с помощью команды ls

![ls](image/3.png){#fig:003 width=70%}

## Сравним команды ls -a и ls -F

![ls -a](image/4.png){#fig:004 width=70%}
![ls -F](image/5.png){#fig:005 width=70%}
## Определим, есть ли в каталоге /var/spool подкаталог с именем cron

![Проверяем содержимое каталога /var/spool](image/6.png){#fig:006 width=70%}

## Переходим в домашний каталог

![Домашний каталог](image/7.png){#fig:007 width=70%}

## Определим, кто является владельцем файлов и подкаталогов с помоью команды ls -l

![Имя домашнего каталога](image/8.png){#fig:008 width=70%}

## В домашнем каталоге создаём новый каталог с именем newdir.

![Создание каталога newdir](image/9.png){#fig:009 width=70%}

## В каталоге ~/newdir создаём новый каталог с именем morefun.

![Создание каталога morefun](image/10.png){#fig:010 width=70%}

## Cоздаём одной командой три новых каталога с именами

![Создание каталогов и их удаление](image/11.png){#fig:011 width=70%}

##

![Команда man ls](image/12.png){#fig:012 width=70%}

##

![ -R, --recursive](image/13.png){#fig:013 width=70%}

##

![--time-style=TIME_STYLE](image/14.png){#fig:014 width=70%}

##

![Команда man cd](image/15.png){#fig:015 width=70%}

##

![Команда man pwd](image/16.png){#fig:016 width=70%}

##

![Команда man mkdir](image/17.png){#fig:017 width=70%}

##

![Команда man rmdir](image/18.png){#fig:018 width=70%}

##

![Команда man rm](image/19.png){#fig:019 width=70%}

## Получим при помощи команды history

![Команда history](image/20.png){#fig:020 width=70%}
![Команда history](image/21.png){#fig:021 width=70%}

## Выполним модификацию и исполнение нескольких команд из буфера команд

![Модификация команды №493](image/22.png){#fig:022 width=70%}
![Модификация команды №494](image/23.png){#fig:023 width=70%}

## Выводы

Мы приобрели практические навыки взаимодействия пользователя с системой по-
средством командной строки.
