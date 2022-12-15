---
## Front matter
title: "Шаблон отчёта по лабораторной работе"
subtitle: "Простейший вариант"
author: "Дмитрий Сергеевич Кулябов"

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

Приобрести навыки написания программ для работы с файлами

# Выполнение лабораторной работы

1. Создаем файлы для работы с ними

![файлы и touch](image/Снимок экрана от 2022-12-15 12-06-46.png){ #fig:001 width=70% }

2. Открываем файл вписываем листинг и проверяем его работу 

![результат файла](image/Снимок экрана от 2022-12-15 12-16-58.png){ #fig:002 width=70% }

3. С помощью команды ‘chmod’ изменяем права доступа к исполняемому файлу lab11-1. Запрещаем его выполнение для всех (права владельца, права группы и права остальных. Мы можем заметить, что произошла обишка: отказано в доступе. Это произошло, потому что мы запретили выполнение этого файла, тем самым ограничив в правах доступа к нему. 

![chmod](image/Снимок экрана от 2022-12-15 12-22-48.png){ #fig:003 width=70% }

4. Теперь с помощью той же комнады попытаемся изменить права доступа к файлу lab11-2.asm. с исходным текстом программы. Файл стал успешно исполняемым, но после его запуска произошли ошибки. Так вышло, потому что каждую строчку нашей программы компьютер попытался выполнить в терменале. Обшибки обосновываются тем, что команды не найдены, эти строки непонятны для терминала.

![изменение прав доступа](image/Снимок экрана от 2022-12-15 12-30-00.png){ #fig:004 width=70% }

5. Предоставляем права при помощи той же комманды chmod файлу reas.txt в соответствии с моим вариантом

![изменение прав доступа](image/Снимок экрана от 2022-12-15 12-30-00.png){ #fig:005 width=70% }

6. В символьном виде имее –x r– -w-.

![изменение прав доступа](image/Снимок экрана от 2022-12-15 12-32-03.png){ #fig:006 width=70% }

#Самостоятельная работа
1. Создаем два файла 

![файлы lab11-2 и name.txt ](image/Снимок экрана от 2022-12-15 12-32-03.png){ #fig:007 width=70% }

2. сама программа

![программа ](image/Снимок экрана от 2022-12-15 13-08-05.png){ #fig:008 width=70% }

![продолжение ](image/Снимок экрана от 2022-12-15 13-08-17.png){ #fig:009 width=70% }

3. Проверка выполнения: 

![проверка ](image/Снимок экрана от 2022-12-15 13-07-24.png){ #fig:008 width=70% }
# Выводы

В ходе выполнения данной лаболраторной работы я преобрела навыки написа-
ния программ для работы с файлами.

# Список литературы{.unnumbered}

::: {#refs}
:::
