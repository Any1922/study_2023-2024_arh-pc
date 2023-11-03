---
## Front matter
title: "Отчёт по лабораторной работе №6"
subtitle: "дисциплина: Архитектура компьютеров"
author: "Маслова Анна Павловна"

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

Освоение арифметических инструкций языка ассемблера NASM. 

# Выполнение лабораторной работы

Сначала создадим каталог для программ лабораторной работы №6. Перейдём в него и создадим в нём файл *lab6-1.asm*  (рис. @fig:001).

![Создание lab06 и файла lab6-1.asm](image/1.png){#fig:001 width=70%}


![Создание lab06 и файла lab6-1.asm](image/1.png){#fig:001 width=70%}
![Создание lab06 и файла lab6-1.asm](image/1.png){#fig:001 width=70%}
![Создание lab06 и файла lab6-1.asm](image/1.png){#fig:001 width=70%}
![Создание lab06 и файла lab6-1.asm](image/1.png){#fig:001 width=70%}
![Создание lab06 и файла lab6-1.asm](image/1.png){#fig:001 width=70%}
![Создание lab06 и файла lab6-1.asm](image/1.png){#fig:001 width=70%}
![Создание lab06 и файла lab6-1.asm](image/1.png){#fig:001 width=70%}
![Создание lab06 и файла lab6-1.asm](image/1.png){#fig:001 width=70%}
![Создание lab06 и файла lab6-1.asm](image/1.png){#fig:001 width=70%}
![Создание lab06 и файла lab6-1.asm](image/1.png){#fig:001 width=70%}
![Создание lab06 и файла lab6-1.asm](image/1.png){#fig:001 width=70%}
![Создание lab06 и файла lab6-1.asm](image/1.png){#fig:001 width=70%}
![Создание lab06 и файла lab6-1.asm](image/1.png){#fig:001 width=70%}
![Создание lab06 и файла lab6-1.asm](image/1.png){#fig:001 width=70%}
![Создание lab06 и файла lab6-1.asm](image/1.png){#fig:001 width=70%}
![Создание lab06 и файла lab6-1.asm](image/1.png){#fig:001 width=70%}
![Создание lab06 и файла lab6-1.asm](image/1.png){#fig:001 width=70%}
![Создание lab06 и файла lab6-1.asm](image/1.png){#fig:001 width=70%}
![Создание lab06 и файла lab6-1.asm](image/1.png){#fig:001 width=70%}
![Создание lab06 и файла lab6-1.asm](image/1.png){#fig:001 width=70%}
![Создание lab06 и файла lab6-1.asm](image/1.png){#fig:001 width=70%}
![Создание lab06 и файла lab6-1.asm](image/1.png){#fig:001 width=70%}
![Создание lab06 и файла lab6-1.asm](image/1.png){#fig:001 width=70%}

# Выводы

Мы освоили арифметические инструкции языка ассемблера NASM, научились составлять арифметические программы.

# Список литературы{.unnumbered}

1. GDB: The GNU Project Debugger. — URL: https://www.gnu.org/software/gdb/.
2. GNU Bash Manual. — 2016. — URL: https://www.gnu.org/software/bash/manual/.
3. Midnight Commander Development Center. — 2021. — URL: https://midnight-commander.
org/.
4. NASM Assembly Language Tutorials. — 2021. — URL: https://asmtutor.com/.
5. Newham C. Learning the bash Shell: Unix Shell Programming. — O’Reilly Media, 2005. —
354 с. — (In a Nutshell). — ISBN 0596009658. — URL: http://www.amazon.com/Learning-
bash-Shell-Programming-Nutshell/dp/0596009658.
6. Robbins A. Bash Pocket Reference. — O’Reilly Media, 2016. — 156 с. — ISBN 978-1491941591.
7. The NASM documentation. — 2021. — URL: https://www.nasm.us/docs.php.
8. Zarrelli G. Mastering Bash. — Packt Publishing, 2017. — 502 с. — ISBN 9781784396879.
9. Колдаев В. Д., Лупин С. А. Архитектура ЭВМ. — М. : Форум, 2018.
10. Куляс О. Л., Никитин К. А. Курс программирования на ASSEMBLER. — М. : Солон-Пресс,
2017.
