# Исследование пользователей мобильного приложения

## Цель исследования

Определить группу пользователей, которая приносит наибольший доход для компании.

## Описание проекта

В рамках исследования анализируются данные о событиях, совершенных в мобильном приложении. В этом приложении пользователи размещают объявления о продаже ненужных вещей. В датасете содержатся данные пользователей, впервые совершивших действия в приложении после 7 октября 2019 года.

## Навыки и инструменты
- pandas
- numpy 
- datetime
- matplotlib
- plotly
- plotly.express
- seaborn 
- matplotlib.ticker
- когортный анализ
- проверка стастических гипотез
- метрики юнит-экономики

### Вывод
Была проведена исследовательская работа по выявлению группы с большей конверсией. Проанализированы:
- доли пользователей из источников yandex и google, построена круговая диаграмма.
- популярные событий в приложении. 
- Retention Rate по дням, построена тепловая карта.
- время сессии каждого пользователя.
- Построен график динамики частоты сессии по датам в будние и выходные дни. 
- Проведен расчет конверсии в целевое действие - просмотр контакта.
- Проведен анализ пользователей путем разделения их на четыре группы Low, Medium, High, Very High, в зависимости от частоты совершаемых действий
