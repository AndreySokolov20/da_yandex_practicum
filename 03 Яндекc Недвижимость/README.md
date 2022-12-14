# Исследование объявлений о продаже квартир

В нашем распоряжении данные сервиса Яндекc Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет. Необходимо определить рыночную стоимость объектов недвижимости. Наша задача — установить параметры. Это позволит построить автоматизированную систему: она отследит аномалии и мошенническую диеятельность.

По каждой квартире на продажу доступны два вида данных. Первые вписаны пользователем, вторые получены автоматически на основе картографических данных (расстояние до центра, аэропорта, ближайшего парка и водоёма и т.п.).

Апартаменты — это нежилые помещения, которые не относятся к жилому фонду, но имеют необходимые условия для проживания.


## Цель исследования:

1. Изучение параметров: площадь, цена, число комнат, высота потолков.
2. Изучение времени продаж квартир.
3. Определение редких и выбивающихся значений.
4. Определение факторов, влияющих на стоимость квартир.
5. Определение 10 населённых пунктов с наибольшим числом объявлений.
6. Анализ расположения квартир от центра.

## Ход исследования:

Данные о поведении пользователей получим из файла real_estate_data.csv. 

Исследование пройдёт в 4 этапа:

* Обзор данных.
* Предобработка данных.
* Расчёты и добавление результатов в таблицу.
* Исследовательский анализ данных.


## Используемые библиотеки:
* Python
* Pandas
* Matplotlib
* Seaborn
