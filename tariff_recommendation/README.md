# Проект "Рекомендация тарифов"

## Данные

Каждый объект в наборе данных — это информация о поведении одного пользователя за месяц. Известно:
- сalls — количество звонков,
- minutes — суммарная длительность звонков в минутах,
- messages — количество sms-сообщений,
- mb_used — израсходованный интернет-трафик в Мб,
- is_ultra — каким тарифом пользовался в течение месяца («Ультра» — 1, «Смарт» — 0).

## Задача

Нужно построить модель для задачи классификации с максимально большим значением accuracy, которая выберет подходящий тариф. Довести долю правильных ответов по крайней мере до 0.75. Проверить `accuracy` на тестовой выборке.

## Используемые библиотеки

*pandas*, *datetime*, *sklearn*
