# Статистический анализ данных: Cервис аренды самокатов GoFast

## Описание проекта

В данном проекте проводится исследовательский и статистический анализ пользовательских данных сервиса аренды самокатов GoFast. 
Цель исследования — понять поведение пользователей, изучить различия между клиентами с подпиской и без, а также проверить гипотезы, 
которые могут помочь бизнесу принять обоснованные решения для роста и развития.
Проект реализован в рамках учебного курса по Data Science и направлен на развитие навыков анализа данных, 
визуализации, работы с гипотезами и расчёта выручки.

## Этапы выполнения проекта

Загрузка и предобработка данных:
Импорт CSV-файлов, проверка типов данных и пропущенных значений.
Приведение дат к нужному формату и выделение месяца.
Обработка дубликатов и пропусков.

Исследовательский анализ данных:
Частота встречаемости городов.
Соотношение подписчиков и пользователей без подписки.
Возрастная структура клиентов.
Анализ расстояний и длительности поездок.

Объединение данных:
Создание общего датафрейма, объединяющего пользователей, поездки и параметры подписок.
Сравнительный анализ двух категорий клиентов: с подпиской и без неё.

Проверка гипотез.

## Описание данных

users_go.csv — информация о пользователях
user_id — ID пользователя
name — имя
age — возраст
city — город
subscription_type — тип подписки (free, ultra)

rides_go.csv — информация о поездках
user_id — ID пользователя
distance — расстояние поездки в метрах
duration — продолжительность в минутах
date — дата поездки

subscriptions_go.csv — тарифы подписок
subscription_type — тип подписки
minute_price — цена за минуту
start_ride_price — стоимость старта
subscription_fee — ежемесячная плата

Используемые инструменты
Python
Pandas
Matplotlib / Seaborn
SciPy (для проверки гипотез)
Jupyter Notebook / Google Colab

Заключение
Результаты анализа помогут сервису GoFast:
сегментировать пользователей;
оценить окупаемость подписки;
выявить потенциально выгодных клиентов;
обосновать продуктовые решения с опорой на статистику.
Проект охватывает весь цикл аналитической работы — от загрузки и очистки данных до визуализации, расчёта метрик и проверки бизнес-гипотез.