---
## Front matter
title: "Отчет по лабораторной работа № 2"
subtitle: "Математическое моделирование"
author: "Королев Иван Андреевич"

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

Задача о погоне. Рассмотрим задачу преследования браконьеров береговой охраной. Необходимо определить по какой траектории необходимо двигаться катеру, чтоб нагнать лодку.

# Задание

Написать решение задачи о погоне на языке программирования Julia.

# Теоретическое введение

Julia — высокоуровневый свободный язык программирования с динамической типизацией, созданный для математических вычислений. Эффективен также и для написания программ общего назначения. Синтаксис языка схож с синтаксисом других математических языков, однако имеет некоторые существенные отличия.

# Выполнение лабораторной работы

## Решение задача о погоне из примера лабораторной работы

Решение задача о погоне из примера лабораторной работы. Построение траектории движения катера береговой охраны и лодки при n=2.  (рис. [-@fig:001]).

![Задаем начальные параметры задачи, функция движения лодки, функция движения катера](image/9.png){#fig:001 width=70%}

Решение ДУ для 1-го случая (рис. [-@fig:002]).

![Решение ДУ для 1-го случая](image/1.png){#fig:002 width=70%}

Решение ДУ для 2-го случая (рис. [-@fig:003]).

![Решение ДУ для 2-го случая](image/2.png){#fig:003 width=70%}

Подготовка данных для движения лодки (рис. [-@fig:004]).

![Подготовка данных для движения лодки](image/3.png){#fig:004 width=70%}

Траектория движения катера для 1-го случая (рис. [-@fig:005]).

![Траектория движения катера для 1-го случая](image/4.png){#fig:005 width=70%}

Траектория движения катера для 2-го случая (рис. [-@fig:006]).

![Траектория движения катера для 2-го случая](image/5.png){#fig:006 width=70%}

## Решение 12 Варианта самостоятельного задания

Задаем начальные параметры из условия задания, , функция движения лодки, функция движения катера, решение ДУ для 1-го случая, решение ДУ для 2-го случая, подготовка данных(рис. [-@fig:007]).

![Решение задачи](image/6.png){#fig:007 width=70%}

Траектории движения катера и лодки, точки пересечения. (рис. [-@fig:008]), (рис. [-@fig:009]).

![Решение задачи](image/7.png){#fig:008 width=70%}

![Решение задачи](image/8.png){#fig:009 width=70%}

# Выводы

 Рассмотрел задачу преследования браконьеров береговой охраной. Определил по какой траектории необходимо двигаться катеру, чтоб нагнать лодку.

# Список литературы{.unnumbered}

::: {#refs}
:::
