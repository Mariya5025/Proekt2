<h1 align="center"> Дипломное задание по курсу «JavaScript-программирование для начинающих»</h1>
Создание «Cайта для онлайн бронирования билетов».
Были представлены следующие компоненты системы:
Верстка
Backend

<h2>Задача</h2>
Разработать сайт бронирования билетов онлайн

<h2>Сущности</h2>
Кинозал
Помещение, в котором демонстрируются фильмы. Режим работы определяется расписанием на день. Зал — прямоугольный, состоит из N*M различных зрительских мест.

<h2>Зрительское место</h2>
Место в кинозале. Зрительские места могут быть VIP и обычные.

<h2>Фильм</h2>
Информация о фильме заполняется администратором. Фильм связан с сеансом в кинозале.

<h2>Сеанс</h2>
Сеанс — это временной промежуток, в котором в кинозале будет показываться фильм. На сеанс могут быть забронированы билеты.

<h2>Билет</h2>
QR-код c уникальным кодом бронирования, в котором обязательно указаны место, ряд, сеанс. Билет действителен строго на свой сеанс.

<h2>Роли пользователей системы</h2>
Гость — неавторизованный посетитель сайта

<h2>Возможности гостя</h2>
просмотр расписания
просмотр информации о фильмах
выбор места в кинозале
бронирование билета

<h2>Реализация проекта</h2>
<ul>
<li>Адаптирована исходная верстка под планшетные и мобильные устройства. 
<li>Верстка корректно отображается на устройствах с шириной экрана 320px и более.
<li>Разработана API для взаимодействия с Backend.
<li>Получение списков всех залов, кинофильмов и сеансов
<li>Получение актуальной схемы посадочных мест на выбранный сеанс
<li>Заказ билета
<li>Запрограммирована гостевая часть сайта
<li>Стек технологий
</ul>

<h2>В проекте использовались следующие технологии:</h2>
<ul>
<li>HTML
<li>CSS (включая медиазапросы)
<li>JavaScript
<li>Git
<li>Сторонние библиотеки
<li>QRCreator.js - JavaScript библиотека для создания QR-кодов.
</ul>
<h2>GitHub Pages</h2>
Проект доступен на GitHub Pages по следующей ссылке: https://mariya5025.github.io/Proekt2/

<h2>Задание</h2>
Исходный проект задания: https://github.com/VladaIsakova/js-cp-diploma-edited/
