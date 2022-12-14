============================================================================================
============================================================================================
==                            Описание электронного приложения                            ==
==                                к книге Владимира Дронова                               ==
==                   "Laravel 8: Быстрая разработка веб-сайтов на PHP"                    ==
============================================================================================
============================================================================================




--------------------------------------------------------------------------------------------
1. Состав архива
--------------------------------------------------------------------------------------------

Архив с электронным приложением включает в себя следующие файлы и папки:

 * bboard     - папка с исходным кодом веб-сайта электронной доски объявлений,
                разрабатываемого на протяжении глав 1-2 книги на PHP и Laravel;

 * readme.txt - этот файл.



--------------------------------------------------------------------------------------------
2. Развертывание веб-сайта
--------------------------------------------------------------------------------------------

Предполагается, что исполняющая среда PHP уже установлена.

 1. Извлечь из архива папку bboard со всем ее содержимым.

 2. Запустить командную строку.

 3. В командной строке выполнить переход в извлеченную из архива папку bboard.

 4. Установить необходимые звисимости, отдав команду:

          composer install

    Через некоторое время все зависимости, включая сам Laravel, будут установлены.

 5. Запустить отладочный веб-сервер Laravel, отдав команду в командной строке:

          php artisan serve

 6. Запустить любой веб-обозреватель и перейти на сайт, набрав интернет-адрес
    http://localhost:8000/.



--------------------------------------------------------------------------------------------
3. Зарегистрированные пользователи веб-сайта
--------------------------------------------------------------------------------------------

Читатели книги могут выполнять вход на сайт электронной доски объявлений от имени одного
из двух зарегистрированных на сайте пользователей (адрес электронной почты : пароль):

    admin@bboard.ru : admin

    editor@bboard.ru : supereditor



--------------------------------------------------------------------------------------------
4. Авторские права
--------------------------------------------------------------------------------------------

 * Авторские неимущественные права на сайт принадлежат автору книги Владимиру Дронову.

 * Код сайта или его фрагменты могут быть свободно использованы для разработки других
   решений.