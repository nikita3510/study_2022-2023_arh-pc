---
## Front matter
title: "Команды безусловного и условного переходов в Nasm."
subtitle: "Программирование ветвлений"
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

Изучение команд условного и безусловного переходов. Приобретение навы-
ков написания программ с использованием переходов. Знакомство с назначе-
нием и структурой файла листинга.

# Выполнение лабораторной работы

1. Создаем файл для работы с ним

![Комманды](image/Снимок экрана от 2022-12-01 10-48-10.png){ #fig:001 width=70% }

2. Вписываем в него следующие комманды и получаем вот такой вывод

![nasm...](image/Снимок экрана от 2022-12-01 10-55-15.png){ #fig:002 width=70% }

3. Добавив несколько строчек с коммандой jump выводим нужный результат

![jump](image/Снимок экрана от 2022-12-01 11-06-54.png){ #fig:003 width=70% }

4. Созданная программа и вывод её из 3 какое число больше

![A,B,C](image/Снимок экрана от 2022-12-01 11-20-45.png){ #fig:004 width=70% }

5. При помощи текстового редактора открыл файл листинга 

![листинг](image/Снимок экрана от 2022-12-01 11-25-37.png){ #fig:005 width=70% }

6. Удалив операнд у программы случается сбой и он не может создаться ,а посмотрев на него через mc покажет в чем ошибка 

![создание при помощи комманд](image/Снимок экрана от 2022-12-01 11-32-02.png){ #fig:006 width=70% }

![просмотр через мс](image/Снимок экрана от 2022-12-01 11-35-59.png){ #fig:007 width=70% }

# Выводы

Я научился позоваться коммандами условного и безусловного перехода
