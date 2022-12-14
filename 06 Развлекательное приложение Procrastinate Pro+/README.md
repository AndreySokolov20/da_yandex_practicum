# Маркетинговый анализ эффективности развлекательного приложения Procrastinate Pro+
Несколько прошлых месяцев наш бизнес постоянно нес убытки - в привлечение пользователей была вложена куча денег, а толку никакого. Нам необходимо разобраться в причинах этой ситуации.

У нас в распоряжении есть лог сервера с данными о посещениях приложения новыми пользователями, зарегистрировавшимися в период с 2019-05-01 по 2019-10-27, выгрузка их покупок за этот период, а также статистика рекламных расходов.

Нам предстоит изучить, как люди пользуются продуктом, когда они начинают покупать, сколько денег приносит каждый клиент, когда он окупается и какие факторы отрицательно влияют на привлечение пользователей.

## Цель исследования:

1. Выделить причины неэффективности привлечения пользователей;
2. Сформировать рекомендации для отдела маркетинга для повышения эффективности.

## Ход исследования:

Данные для исследования мы получим тремя файлами:

- /datasets/visits_info_short.csv. - лог сервера с информацией о посещениях сайта;
- /datasets/orders_info_short.csv. - информация о заказах;
- /datasets/costs_info_short.csv. - информация о затратах на маркетинг.

Исследование пройдёт в 5 этапов:

* Обзор данных.
* Обработка данных.
* Исследовательский анализ данных.
* Эффективность маркетинга.
* Оценка окупаемости рекламы для привлечения пользователей

## Используемые библиотеки:
* Python
* Pandas
* Numpy
* Matplotlib
