---
## Front matter
title: "Лабораторная работа № 4"
subtitle: "Математическое моделирование"
author: "Королёв И.А."

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

Необходимо построить фазовый портрет гармонического осциллятора и найти решения уравнения.

# Задание

1. Колебания гармонического осциллятора без затуханий и без действий внешней силы

2. Колебания гармонического осциллятора с затуханиями и без действий внешней силы

3. Колебания гармонического осциллятора с затуханиями и с действием внешней силы

# Выполнение лабораторной работы

## Колебания гармонического осциллятора без затуханий и без действий внешней силы

Реализация	модели Колебания гармонического осциллятора без затуханий и без действий внешней силы (рис. [-@fig:001]).

![Реализация модели](image/4.png){#fig:001 width=70%}

Фазовый портрет (рис. [-@fig:002]).

![Результат](image/5.png){#fig:002 width=70%}

## Колебания гармонического осциллятора с затуханиями и без действий внешней силы

Реализация	модели Колебания гармонического осциллятора с затуханиями и без действий внешней силы (рис. [-@fig:003]).

![Реализация модели](image/6.png){#fig:003 width=70%}

Фазовый портрет (рис. [-@fig:004]).

![Результат](image/7.png){#fig:004 width=70%}

## Колебания гармонического осциллятора с затуханиями и с действием внешней силы

Реализация	модели Колебания гармонического осциллятора с затуханиями и с действием внешней силы (рис. [-@fig:005]).

![Реализация модели](image/8.png){#fig:005 width=70%}

Фазовый портрет (рис. [-@fig:006]).

![Результат](image/9.png){#fig:006 width=70%}

## Сравнение с реализацией OpenModelica

Реализация первого случая. (рис. [-@fig:007]).

![Реализация модели](image/1.png){#fig:007 width=70%}

Фазовый портрет (рис. [-@fig:008]).(рис. [-@fig:009])

![Результат](image/2.png){#fig:008 width=70%}

![Результат](image/3.png){#fig:009 width=70%}

# Вывод

Необходимо построить фазовый портрет гармонического осциллятора и найти решения уравнения.

# Список литературы{.unnumbered}

::: {#refs}
:::
