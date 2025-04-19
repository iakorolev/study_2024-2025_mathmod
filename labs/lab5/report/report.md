---
## Front matter
title: "Лабораторная работа № 5"
subtitle: "Математическое моделирование"
author: "Королёв Иван Андреевич"

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
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
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

Необходимо построить модель "Хищник-жертва"

# Задание

Построить модель "Хищник-жертва" и найти стационарное состояние системы

# Выполнение лабораторной работы

Определение системы ДУ и указание параметров системы (рис. [-@fig:001]).

![Определение системы ДУ](image/1.png){#fig:001 width=70%}

Начальные условия и решение системы ДУ (рис. [-@fig:002]).

![Решение системы ДУ](image/2.png){#fig:002 width=70%}

График численности жертв и хищников во времени (рис. [-@fig:003]).

![График численности жертв и хищников во времени](image/3.png){#fig:003 width=70%}

Нахождение стационарного состояния (рис. [-@fig:004]).

![Нахождение стационарного состояния](image/4.png){#fig:004 width=70%}

Стационарная точка (рис. [-@fig:005]).

![Стационарная точка](image/5.png){#fig:005 width=70%}

Фазовый портрет (рис. [-@fig:006]).

![Фазовый портрет](image/6.png){#fig:006 width=70%}

# Выводы

Построил модель "Хищник-жертва"

# Список литературы{.unnumbered}

::: {#refs}
:::
