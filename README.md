## Сообщение к заданию:
Задание заняло выполнить 18 часов.
Выполнила пункт 3 и 4.

Я использовала 

React, 
Material UI, 
Redux для стейт менеджмента,
Reselect для фильтра ,
Redux-saga для асинхронного получения данных.

## Выполнила пункты:

## Два режима просмотра данных: 
* табличный вид 
* плиточный вид 

## Отображение списка контактов: (Fetch with Redux-saga)
* день рождения пользователя должен быть в американском формате 
* email должен быть кликабельным с возможностью скопировать 
* телефон должен быть кликабельным с возможностью скопировать 
* адрес должен быть в формате:   /страна/ номер улицы название улицы, город, штат индекс 
номер улицы название улицы, город, штат индекс 

## Возможность фильтровать данные: (Reselect)
* по полному имени;
* по половому признаку;
* по национальности; 
* по создателю контакта;

## Подробнее о фильтре: (Reselect)
* Фильтрация происходит без ручной отправки формы.
* Очистка фильтра возвращает коллекцию к изначальному состоянию.
* Фильтруется вся коллекция.

## Статистика по данным:  (Reselect)
* размер коллекции 
* кол-во мужчин, женщин и неопределившихся 
* вывести кого больше
* кол-во контактов по каждой национальности 
По клику на имя или аватар пользователя есть переход на страницу просмотра данных пользователя 
При возврате со страницы просмотра на страницу списка контактов, должно быть сохранено и применено ранее выбранное состояние фильтра, сортировки и пагинации.

## Чтобы я хотела улучшить в своём приложении:
Мобильная версия требует корректировок;
Сообщение об ошибке при возвращении ошибки из запроса c API;

