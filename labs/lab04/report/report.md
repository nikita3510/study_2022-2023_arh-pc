---
## Front matter
title: "Отчет по лабороторной работе 3"
subtitle: "дисциплина Архитектура компьютера"
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
Цели: Научится пользоваться github, чтобы можно было его использовать в дальнейшем

# Задание

Отчет при помощи markdown


# Выполнение лабораторной работы
1. Сначала была проведена предварительная конфигурация git, а также настройка utd-8

![git](image/Screenshot 2022-10-27 at 11-08-23 Л03_Зайцев_отчет.pdf.pdf.png){ #fig:1 width=70% }

2. Далее было задано имя начально ветки master, а также параметры autocrlf и safecrlf

![autocrlf safecrlf](image/Снимок экрана от 2022-10-27 11-18-02.png){ #fig:2 width=90% }

3. Создание SSH ключа:

![ssh](image/Снимок экрана от 2022-10-27 11-18-52.png){ #fig:3 width=90% }

4. Создание рабочего пространства и репозитория курса на основе шаблона. Я создал каталог и переместил его в репозиторий

![каталог](image/Снимок экрана от 2022-10-27 11-19-14.png){ #fig:4 width=90% }

5. Настройка каталога курса: Потом я удалил лишние файлыи создал необходимые каталоги

![нет ничего](image/Снимок экрана от 2022-10-27 11-19-24.png){ #fig:5 width=90% }

6. Далее отправил их на сервер(последняя команда)

![сервер](image/Снимок экрана от 2022-10-27 11-19-32.png){ #fig:6 width=90% }

При помощи ls и страницы git hub проверил правильность выполнения работы

![ls](image/Снимок экрана от 2022-10-27 11-19-41.png){ #fig:7 width=90% }

# Выводы
В ходе лабораторной работы я научился пользоваться таким сервером репозиториев как github, что в дальнейшем облегчит выполнение лабораторных работ

