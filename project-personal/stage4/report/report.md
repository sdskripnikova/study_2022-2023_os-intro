---
## Front matter
title: "Отчёт по 4 лабораторной работе"
subtitle: "Операционные системы"
author: "Скрипникова София"

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

Прикрепиь ссылки на свои страницы, выложить посты - выполнить задания 4 этапа индивидуального проекта. 

# Выполнение лабораторной работы

1. Зашли на страницу сайта с помощью команды hugo server 

2. Добавила данные о себе: вдобавила ссыки на страницы. (рис. @fig:001),(рис. @fig:002)

![Текст](image/Снимок ип4.1.PNG){#fig:001 width=70%}

![Текст](image/Снимок ип4.2.PNG){#fig:002 width=70%}


3. Сделала пост по прошедшей неделе (рис. @fig:003),(рис. @fig:004)

![Текст](image/Снимок ип4.3.PNG){#fig:003 width=70%}

![Пост на сайте](image/Снимок ип4.4.PNG){#fig:004 width=70%}

4. Добавила пост на тему по выбору: Оформление отчета. (рис. @fig:005), (рис. @fig:006)

![Текст](image/Снимок ип4.5.PNG){#fig:005 width=70%}

![Пост на сайте](image/Снимок ип4.6.PNG){#fig:006 width=70%}



# Выводы

Я узнала ка менять информацию на сайте и смогла загрузить ссылки на свой страницы. Также научилась выкладывать посты на сайте.


