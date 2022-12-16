# **Проектная работа студентки Яндекс.Практикум отделения аналитики**
[Яндекс.Практикум] (https://practicum.yandex.ru/)

#  Проектная работа: Анализ бизнес-показателей

## Описание проекта:
Вы — маркетинговый аналитик развлекательного приложения Procrastinate Pro+.     
Несмотря на огромные вложения в рекламу, последние несколько месяцев компания терпит убытки.     
Ваша задача — разобраться в причинах и помочь компании выйти в плюс.      
  
    
**Исходные данные:** 
    
Есть данные о пользователях, привлечённых с 1 мая по 27 октября 2019 года:  
  
 - лог сервера с данными об их посещениях,  
 - выгрузка их покупок за этот период,  
 - рекламные расходы.  
    
**Задачи:**   
      
Требуется изучить:  

 - откуда приходят пользователи и какими устройствами они пользуются,
 - сколько стоит привлечение пользователей из различных рекламных каналов;
 - сколько денег приносит каждый клиент,
 - когда расходы на привлечение клиента окупаются,
 - какие факторы мешают привлечению клиентов.
    


### Описание данных:
1. Датафрейм visits хранит столбцы со следующей информацией о посещениях сайта:  

User Id — уникальный идентификатор пользователя;  
Region — страна пользователя;   
Device — тип устройства пользователя;  
Channel — идентификатор источника перехода;  
Session Start — дата и время начала сессии;  
Session End — дата и время окончания сессии. 

2. Датафрейм orders хранит следующую информацию о покупках:  

User Id — уникальный идентификатор пользователя;  
Event Dt — дата и время покупки;  
Revenue — сумма заказа.  

3. Датафрейм costs хранит следующую информацию о расходах на рекламу:  

Channel — идентификатор рекламного источника;  
dt — дата проведения рекламной кампании;  
Costs — расходы на эту кампанию.  

## Инструменты:  
Pyton  
Pandas  
Matplotlib  
Numpy  
Jupyter Notebook  

## Итоги исследования
Были проведены исследования по всем поставленным задачам и сделаны выводы по каждому. 
Даны рекомендации маркетологам.
С результатами вы можете ознакомиться в файле.

## Ссылка на репозиторий: 
