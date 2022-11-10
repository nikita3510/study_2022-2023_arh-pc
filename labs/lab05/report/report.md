---
## Front matter
title: "Создание и процесс обработки программ на языке ассемблера NASM"
subtitle: "Лабораторная работа 5"
author: "Зайцев Никита"

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

Освоение процедуры компиляции и сборки программ, написанных на ассем-
блере NASM

# Задание

Создать комманду ,чтобы выводить текст


# Выполнение лабораторной работы

1. Создал каталог и файл

![комманды создания](image/Снимок экрана от 2022-11-10 10-56-20.png){ #fig:001 width=70% }

2. Вставил текст в создаваемый файл

![text](image/Снимок экрана от 2022-11-10 10-56-40.png){ #fig:002 width=70% }

3.  Написал код создавая файлы разных расширений 

![nasm](image/Снимок экрана от 2022-11-10 11-57-18.png){ #fig:003 width=70% }

4. Проверка создания 

![ls](image/Снимок экрана от 2022-11-10 11-09-31.png){ #fig:004 width=70% }

5. Запуск исполняемого файла 

![привет мир](image/Снимок экрана от 2022-11-10 12-04-42.png){ #fig:005 width=70% }

6. Задание для самостоятельной работы 

![мое имя и фамилия](image/Снимок экрана от 2022-11-10 11-57-18.png){ #fig:006 width=70% }

# Выводы

Я освоил компиляция и сборку программ, написанных на ассемблере NASM
