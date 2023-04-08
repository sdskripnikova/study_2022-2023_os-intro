---
## Front matter
title: "Шаблон отчёта по индивидуальному проекту"
subtitle: "Операционные системы"
author: "Скрипникова София Дмитриевна"

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

Добавить к сайту достижения

# Задачи

Добавить информацию о навыках.

Добавить информацию об опыте.

Добавить информацию о достижениях.

Сделать пост по прошедшей неделе.

Добавить пост на тему по выбору.


# Выполнение лабораторной работы

1. Добавить информацию о навыках (Skills).(рис. [-@fig:001]).

![Навыки](image/Снимок ип3.1.PNG){#fig:001 width=70%}

2. Добавить информацию об опыте (Experience). (рис. [-@fig:002])

![Опыт](image/Снимок ип3.2.PNG){#fig:002 width=70%}

3. Добавила информацию о достижениях (Accomplishments). (рис. [-@fig:003])

![Достижения](image/Снимок ип3.3.PNG){#fig:003 width=70%}

4. Сделать пост по прошедшей неделе. (рис. [-@fig:004]).

![Пост](image/Снимок ип3.4.PNG){#fig:004 width=70%}

5. Добавила пост на тему по выбору. Я выбрала "Язык разметки Markdown". (рис. [-@fig:005]).

![Пост](image/Снимок ип3.5.PNG){#fig:005 width=70%}


6. Сайт. (рис. [-@fig:006]).

![Сайт](image/Снимок ип3.6.PNG){#fig:006 width=70%}


# Выводы

В результате реализации третьего этапа индивидуального проекта я добавила на сайт достижения.

# Список литературы{.unnumbered}

::: {#refs}
:::
