---
## Front matter
title: "Лабораторная работы №2. "
subtitle: "Markdown"
author: "Баптишта Матеуж" 

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

Научиться оформлять отчёты с помощью легковесного языка разметки Markdown.


# Задание

Сделаnm отчёт по предыдущей лабораторной работе в формате Markdown.
В качестве отчёта просьба предоставить отчёты в 3 форматах: pdf, docx и md (в архиве,
поскольку он должен содержать скриншоты, Makefile и т.д.)



# Теоретическое введение
                           
Markdown — это облегченный язык разметки с синтаксисом форматирования обычного текста. созданный Джоном Грубером и Аароном Шварцем в 2004 году, сегодня это один из самых популярных языков среди программистов. Для записи Markdown можно использовать любой текстовый редактор. Смысл маркдауна в том, что вы делаете разметку своего документа минимальными усилиями, а уже какой-то другой плагин или программа превращает вашу разметку в итоговый документ — например в HTML. Но можно и не в HTML, а в PDF или что-нибудь ещё.                          


# Выполнение лабораторной работы

Установка программного обеспечения(рис. @fig:001).

![dnf install gh](image/1.jpg){#fig:001 width=70%}

Базовая настройка git (рис. @fig:002).

![настройка git](image/2.jpg){#fig:002 width=70%}

Создайте ключи ssh (рис. @fig:003).

![нключи ssh](image/3.jpg){#fig:003 width=70%}

Создайте ключи pgp (рис. @fig:004).

![ключи pgp](image/4.jpg){#fig:004 width=70%}

Добавление PGP ключа в GitHub (рис. @fig:005).

![PGP ключа в GitHub](image/5.jpg){#fig:005 width=70%}

Настройка автоматических подписей коммитов git (рис. @fig:006).

![Настройка автоматических подписей коммитов git](image/6.jpg){#fig:006 width=70%}

Настройка gh (рис. @fig:007).

![Настройка gh](image/7.jpg){#fig:007 width=70%}

Шаблон для рабочего пространства Настройка каталога курса

![рабочего пространства](image/8.jpg){#fig:008 width=70%}

Сознание репозитория курса на основе шаблона (рис. @fig:009).

![рабочего пространства](image/9.jpg){#fig:009 width=70%}

Настройка каталога курса (рис. @fig:010).

![Настройка каталога курса](image/10.jpg){#fig:010 width=70%}

# Выводы

В процессе выполнения этой лабораторной работы я научилась работать с языком разметки Markdown. Познакомилась с базовым синтаксисом Mardown.

# Список литературы{.unnumbered}

::: {#refs}
:::
