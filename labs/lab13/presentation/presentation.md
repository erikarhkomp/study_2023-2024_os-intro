---
## Front matter
lang: ru-RU
title: Лабораторная работа №13.
subtitle: 
author:
  - Арутюнян Эрик Левонович
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 2 мая 2024


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

Ознакомление с инструментами поиска файлов и фильтрации текстовых данных.
Приобретение практических навыков: по управлению процессами (и заданиями), по
проверке использования диска и обслуживанию файловых систем.


# Процесс выполнения лабораторной работы

## Запишем в файл file.txt названия файлов

![выполнение команды](image/1.png){#fig:001 width=70%}

## Выведем имена всех файлов из file.txt

![вывод файлов](image/2.png){#fig:002 width=70%}

![запись файлов в conf.txt](image/3.png){#fig:003 width=70%}

## Определим какие файлы в домашнем каталоге начинаются с символа с. 
    
![два варианта](image/4.png){#fig:004 width=70%}

## Выведем на экран имена файлов из каталога /etc, начинающиеся с символа h

![выполнеине команды](image/5.png){#fig:005 width=70%}

## Запустим в фоновом режиме процесс, который будет записывать в файл ~/logfile файлы, имена который начинаются с log, удалим logfile.

![выполнение команды](image/6.png){#fig:006 width=70%}

## Запустим из консоли в фоновом редиме gedit.
 
![запуск gedit](image/7.png){#fig:007 width=70%}

## Определим индефикатор процесса с помощью команды ps 

![выполнение команды](image/8.png){#fig:008 width=70%}

## Изучим команду kill и с помощью неё прекратим gedit

![команда man kill](image/9.png){#fig:009 width=70%}


![команда kill gedit](image/10.png){#fig:010 width=70%}

## Изучим и выполним команды df и du

![команды man](image/11.png){#fig:011 width=70%}


![man df](image/12.png){#fig:012 width=70%}


![man du](image/13.png){#fig:013 width=70%}


![выполнение команды df](image/14.png){#fig:014 width=70%}

## С помощью команды find выведем именя всех директорий 


![команда find](image/15.png){#fig:015 width=70%}

## Выводы

Мы ознакомились с инструментами поиска файлов и фильтрации текстовых данных. Приобрели практические навыки: по управлению процессами (и заданиями), по проверке использования диска и обслуживанию файловых систем.

