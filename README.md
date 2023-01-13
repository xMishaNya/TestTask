# Тестовое задание Frontend
13.01
*Что сделано:*
- Верстка блока книги
- Mock-обращение к ресурсу сайта mockapi.io с последующей конвертацией данных в json-файл

*В процессе:*
- Написание скрипта для смены блока книги на другой (с привязкой к кнопке)

*Что еще не сделано:*
- Поиск книг
- Фильтрация по данным книги
- Возможность изменять информацию

Я еще совсем не опытен в фронтенд разработке, сверстал немного страниц и совсем немного писал на javascript, поэтому может быть много ошибок в моем решении.

Верстку блока книги я делал через flexbox, в нем создал 2 подблока: с изображением и с описанием книги. Адаптивности под мобильные устройства особо не уделял внимание из за нехватки времени.
Кнопки смены книги, дизлайка и лайка книги тоже не успел сделать, но постарался сам блок книги сделать похожим на пример.

После верстки я зашел на сайт mockapi.io, зарегестрировался, создал ресурс с названием book и добавил туда все поля из ТЗ: название книги, автор, год издания, страницы, жанр и так далее.
Затем создал функцию, в которой указал ссылку на данный ресурс, методом fetch создал запрос на получение данных и передал данные в формате json в переменную.

После этого я начал создавать функцию, которая по текущему id берет все нужные данные из json-файла, вставляет их в html-код и возвращает его в html-файл в тег body.
Эта функция еще не дописана и скорее всего есть более простой способ замены одной книги на другую, но в голову пришла только эта идея.
Затем, чтобы переключаться между книгами, я хочу создать функцию, которая бы увеличивала/уменьшала текущий id и вызывала ранее описанную функцию и привязать к двум кнопкам (назад и вперед).

Поиск и фильтрацию книг, как я читал в документации mockapi, можно реализовать с помощью GET-запросов, но пока я особо не разбирался в этом.
Редактирование книг пока что точно не знаю как реализовать.

Я пока сделал небольшую часть задания, и я могу доделать его, если дадите больше времени :)
