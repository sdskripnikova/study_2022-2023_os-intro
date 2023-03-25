---
## Front matter
title: "Отчет по индивидуальному проекту. Этап №2"
subtitle: "Дисциплина: Операционные системы"
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

Добавить к сайту данные о себе.

# Задачи

- Разместить фотографию владельца сайта.

- Разместить краткое описание владельца сайта (Biography).

- Добавить информацию об интересах (Interests).

- Добавить информацию от образовании (Education).

- Сделать пост по прошедшей неделе.

- Добавить пост на тему по выбору.

# Выполнение лабораторной работы

1. Разместить фотографию владельца сайта. (рис. [-@fig:001]).

![Фото](report/image/Снимок ип2.1.PNG){#fig:001 width=70%}

2. Разместить краткое описание владельца сайта (Biography). (рис. [-@fig:002])

![Биография](image/Снимок ип2.2.PNG){#fig:002 width=70%}

3. Добавить информацию об интересах (Interests). (рис. [-@fig:003])

![Интересы](image/Снимок ип2.3.PNG){#fig:003 width=70%}

4. Добавить информацию от образовании (Education). (рис. [-@fig:004])

![Интересы](image/Снимок ип2.4.PNG){#fig:004 width=70%}

5. Сделать пост по прошедшей неделе. (рис. [-fig:005])

![Пост](image/Снимок ип2.5.PNG){#fig:005 width=70%}

6. Добавить пост на тему по выбору: Управление версиями Git. (рис. [-@fig:006])

![Пост по теме](image/Снимок ип2.6.PNG){#fig:006 width=70%}

7. Загрузила на GitHub. (рис. [-@fig:007])

![Загрузка](image/Снимок ип2.7.PNG){#fig:007 width=70%}

# Вывод

В результате реализации второго этапа индивидуального проекта я добавила на сайт данные о себе.


::: {#refs}
:::
