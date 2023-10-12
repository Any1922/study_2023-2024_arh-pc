---
## Front matter
title: "Отчёт по лабораторной работе №3"
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

Целью работы является освоение процедуры оформления отчетов с помощью легковесного
языка разметки Markdown


# Выполнение лабораторной работы

Переходим в каталог курса и используем команду git pull (рис.1).

![Переход в рабочее протранство](image/1.png){#fig:001 width=70%}

На экране видим, что мы получили все изменения с центрального репозитория. 

Далее создаём файлы report в форматах pdf и docx с помощью команды make (рис.2).

![Использовани команды make](image/2.png){#fig:002 width=70%}

Проверяем наличие этих файлов, а затем удаляем их с помощью make clean (рис.3).

![Использовани команды make](image/3.png){#fig:003 width=70%}

Мы видим, Что файлы в форматах pdf и docx созданы. 
А затем проверяем, что каталоги удалены (рис.4).

![Проверка](image/4.png){#fig:004 width=70%}

После этого открываем отчёт в редакторе gedit и заполняем нужные поля в отчёте (рис.5, 6)

![Открываем gedit](image/5.png){#fig:005 width=70%}

![Заполняем отчёт](image/6.png){#fig:006 width=70%}


# Выполнение задания к лабораторной работе

**Задание№1** Скомпилировать отчёт по лабораторной работе №2 в Markdown. Создать файлы в docx и pdf.

Откроем шаблон лабораторной работы №2 с помощью gedit report.md и отредактируем его в соответствии с готовым отчётом (рис.7).

![Отредактировали отчёт по ЛР№2 в Markdown](image/7.png){#fig:007 width=70%}

Далее с помощью make создаём файлы ЛР№2 в форматах docx и pdf (рис.8).

![Создание файлов report.pdg и report.doxc](image/8.png){#fig:008 width=70%}

Проверили, что файлы созданы. 

Далее отправляем файлы на github (рис.9)

![Отправка файлов в центральный репозиторий](image/9.png){#fig:009 width=70%}

Проверим, что все три файла есть на GitHub (рис.10).

![GitHub](image/10.png){#fig:010 width=70%}

# Выводы

Мы освоили процедуры оформления отчетов с помощью языка разметки Markdown и научились с ним работать.

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
