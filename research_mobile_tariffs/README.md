# Исследование тарифов сотового оператора

## Данные

В наличие были следующие данные по клиентам и тарифам сотового оператора:

- информация о пользователях
    - уникальный идентификатор пользователя
    - имя пользователя
    - фамилия пользователя
    - возраст пользователя (годы)
    - дата подключения тарифа (день, месяц, год)
    - дата прекращения пользования тарифом (если значение пропущено, то тариф ещё действовал на момент выгрузки данных)
    - город проживания пользователя
    - название тарифного плана

- информация о звонках
    - уникальный номер звонка
    - дата звонка
    - длительность звонка в минутах
    - идентификатор пользователя, сделавшего звонок

- информация о сообщениях
    - уникальный номер сообщения
    - дата сообщения
    - идентификатор пользователя, отправившего сообщение- информация об интернет-сессиях
    
- информация о тарифах
    - уникальный номер сессии
    - объём потраченного за сессию интернет-трафика (в мегабайтах)
    - дата интернет-сессии
    - идентификатор пользователя

## Задача

Определить кто клиенты оператора: откуда, каким тарифом пользуются, сколько звонков и сообщений каждый отправил за 2018 год. Так же необходимо проанализировать поведение клиентов и сделать вывод — какой тарифный план лучше «Смарт» или «Ультра».

## Вывод

По результатам проведённого анализа выборки клиентов федерального оператора сотовой связи «Мегалайн» были сделаны выводы о степени использования абонентами различных тарифов минутами разговоров, смс и интернет трафика. Так же были проверены гипотезу что средняя выручка пользователей из Москвы отличается от выручки пользователей из других регионов. Было сделано сравнение между двумя тарифами и сделан соотвествующий вывод.

## Используемые библиотеки

*pandas*

*numpy*

*scipy*

*matplotlib*

*seaborn*

## Если проект не открывается на гитхабе 

https://nbviewer.jupyter.org/github/BlackDragonAB/SharedProjects/blob/main/research_mobile_tariffs/mobile_tariffs_project.ipynb
