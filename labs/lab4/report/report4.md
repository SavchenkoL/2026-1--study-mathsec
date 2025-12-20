---
# Front matter
lang: ru-RU
title: "Лабораторная работа №4"
subtitle: "Практикум по научному письму"
author: "Савченко Елизавета Николаевна"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
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
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Узнать о LaTeX, продолжить изучение его возможностей. Добавить графику из внешнего источника в LaTeX. 

# Задание

1. Добавить графику из внешнего источника в LaTeX. 
2. Освоить новый графический пакет.
3. Научиться оформлять изображения в LaTeX.


# Выполнение лабораторной работы

 
здесь мы использовали новую среду, center, чтобы расположить изображение горизонтально по центру страницы. 

![Программа 1](image/1.png){ #fig:001 width=70% }

 
LaTeX автоматически масштабирует изображение, чтобы сохранить соотношение сторон. 

![Программа 2](image/2.png){ #fig:002 width=70% }

Можем масштабировать изображения или поворачивать их на определённый угол. Кроме того, можно обрезать изображение.

![Программа 3](image/3.png){ #fig:003 width=70% }

Традиционно при вёрстке, особенно в технических документах, графические элементы могут перемещаться в другое место документа. Это называется плавающим элементом.   

![Программа 4](image/4.png){ #fig:004 width=70% }

Часто требуется, чтобы рисунок отображался в выводе именно там, где он находится во входных данных. Пакет float позволяет это сделать при помощи опции H. 

![Программа 5](image/5.png){ #fig:005 width=70% }

Если нам необходимо несколько сред, это можно сделать с помощью пакета trivfloat. Он предоставляет единую команду \\trivfloat для создания новых типов плавающей среды 

![Программа 6](image/6.png){ #fig:006 width=70% }

При написании документа любой длины вам понадобится ссылаться на пронумерованные элементы, такие как рисунки, таблицы или уравнения.LaTeX может автоматически добавлять нужные номера. 

![Программа 7](image/7.png){ #fig:007 width=70% }

Превратим перекрестные ссылки в гиперссылки с помощью пакета hyperref.

![Программа 8](image/8.png){ #fig:008 width=70% }

На этом лабораторная работа закончена. 

# Выводы

1. Добавил графику из внешнего источника в LaTeX. 
2. Освоил новый графический пакет.
3. Научился оформлять изображения в LaTeX.

# Список литературы

Лабораторная работа №4
Практикум по научному письму [Электронный ресурс]. URL: https://esystem.rudn.ru/pluginfile.php/2862317/mod_folder/content/0/Practical-scientific-writing.pdf

