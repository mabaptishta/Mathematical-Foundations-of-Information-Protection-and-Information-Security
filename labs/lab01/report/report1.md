---
## Front matter
title: "Отчёт по лабораторной работе №1


Математические основы защиты информации и информационной безопасности"
subtitle: "Шифры простой замены"
author: "Выполнил: Мануэл Марсия Педру, 


НФИмд-02-25, 1032255503"
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
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---


# Цель работы

Изучить шифры простой замены и научиться их реализовывать.

# Выполнение лабораторной работы

## Реализация шифра Цезаря с произвольным ключом K

Шифр Цезаря — это древнейший шифр подстановки, в котором каждая буква исходного 
текста заменяется другой буквой, сдвинутой на фиксированное число позиций в алфавите. 
Этот метод очень прост: например, при сдвиге на 3, А становится Г, Б — Д и так далее. 
Для восстановления исходного текста нужно сдвинуть буквы в обратном направлении. 

## Реализация шифра Атбаш

Шифр Атбаш — это простейший шифр замены, в котором буквы алфавита заменяются в обратном порядке: первая буква становится последней, 
вторая — предпоследней и так далее. Например, A становится Z, B — Y, а C — X. Этот метод изначально применялся для еврейского алфавита, 
откуда и получил свое название от первых букв «алеф» и «тав»:

Выполним реализацию этого алгоритма на языке Python (рис. [-@fig:001]):

![Реализация шифра цезаря с произвольным ключом K И Реализация шифра Атбаш](image/1.PNG){ #fig:001 width=100% height=100% }

Проверим работу алгоритма (рис. [-@fig:002]):

![Реализация шифра цезаря с произвольным ключом K И Реализация шифра Атбаш](image/2.PNG){ #fig:002 width=100% height=100% }

Проверим работу алгоритма (рис. [-@fig:003]):

![Проверим работу алгоритма (рис. [-@fig:003]):](image/3.PNG){ #fig:003 width=100% height=100% }





