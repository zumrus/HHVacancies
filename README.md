
![](https://raw.githubusercontent.com/AndreyRysistov/DatasetsForPandas/main/hh%20label.jpg)
# <center> Анализ вакансий из HeadHunter </center>
## Оглавление
1. [Описание проекта](#Описание-проекта)
2. [Описание данных](#Описание-данных)
3. [Зависимости](#Используемые-зависимости)
4. [Установка проекта](#Установка-проекта)
5. [Использование проекта](#Использование-проекта)
6. [Авторы](#Авторы)
7. [Выводы](#Выводы)

## Описание проекта

Проект представляет собой проверочный этап обучения (Project-2) на платформе SkillFactory. Его особенностью является отсутствие локальной базы данных: доступ к ней необходимо получать, создавая sql-запросы. База вакаесий предоставлена сайтом поиска вакансий hh.ru. 

Основные этапы проекта:
* Предварительный анализ.
* Детальный анализ вакансий.
* Анализ работодателей.
* Предметный анализ.
* Дополнительное исследование и общие выводы


**О структуре проекта:**
* [Project-2. HH_vacancies.ipynb](./Project-2.%20HH_vacancies.ipynb) - jupyter-ноутбук, содержащий основной код проекта.


## Описание данных
В этом проекте используются данные выгруженные с сайта поиска вакансий hh.ru. Исходный датасет представляет собой набор данных из таблицы с информацией о вакансиях, которую предоставили работодатели. Данные разбиты на 5 таблиц: данные по вакансиям, таблица-справочник, которая хранит код региона и его название, таблица-справочник со списком работодателей, таблица-справочник вариантов сфер деятельности работодателей и дополнительная таблица, которая существует для организации связи между работодателями и сферами их деятельности. Для доступа донным требуется составлять SQL-запросы, а потом передавать из в Python.


## Используемые зависимости
* Python (3.9):
    * [pandas (1.5.3)](https://pandas.pydata.org)
    * [psycopg2 (2.9.6)](https://pypi.org/project/psycopg2/)
    * [matplotlib (3.7.1)](https://matplotlib.org)
    * [seaborn (0.12.2)](https://seaborn.pydata.org)
    * [plotly.express (5.13.1)](https://plotly.com/python/plotly-express/)

## Установка проекта

```
git clone https://github.com/zumrus/HHVacancies
```

## Использование проекта
Вся информация о работе представлена в jupyter-ноутбуке Project-2. HH_vacancies.ipynb.

## Авторы

* Марат zumrus Хамадеев

## Выводы

Данный учебный проект призван продемонстрировать мои навыки исследования написания SQL-запросов и их обработки на языке Python, а также проанализировать вакансии и работодателей. Особое внимание уделено вакансиям, связанным с работой с данными. Согласно выводам, Data Science - это перспективное направление, которое только начало развиваться. 