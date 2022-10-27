---
## Front matter
title: "Лабораторная работа N4"
subtitle: "Язык разметки Markdown"
author: "Зайцев Никита Кириллович"

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
lot: false # List of tables
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

Целью работы является освоение процедуры оформления отчетов с помощью
легковесного языка разметки Markdown.

# Задание

отчет по выполнению



# Выполнение лабораторной работы

1. При помощи комманды make скомпелировал файлы pdf jpg

![make](image/Снимок экрана от 2022-10-27 10-49-20.png){ #fig:1 width=90% }

2. При помощи комманды make clean удалил ранее созданные файлs

![make clean](image/Снимок экрана от 2022-10-27 10-54-13.png){ #fig:2 width=90% }

3. Потом я открыл файл report.md и создал в нем отчет 3 лабороторной работы и загрузил на github

![git](image/Снимок экрана от 2022-10-27 10-49-20.png){ #fig:3 width=90% }

# Выводы
При помощи языка разметки markdown можно создавать текстовые документы и редактировать их,также он создает их в различных расширениях,что очень упрощает жизнь.

