Интеграция по REST-протоколу 
============================

Отправка сообщений
--------------------

SMS
~~~

 .. code-block:: json
   :linenos:

   {
   "login":"ВАШ_ЛОГИН",
   "password":"ВАШ_ПАРОЛЬ",
   "useTimeDiff":true,
   "id":"8770630",
   "shortenLinks":false,
   "scheduleInfo":{
   "timeBegin":"10:00",
   "timeEnd":"12:00",
   "weekdaysSchedule":"123"
   }

Вкладки
-------

  .. tabs::

     .. tab:: Sphinx

        If your project uses Sphinx,
        we offer a special builder optimized for Sphinx projects.

     .. tab:: MkDocs

        If your project uses MkDocs,
        we offer a special builder optimized for MkDocs projects. 

       
Параметры сообщений
--------------------

Вставка HTML
~~~~~~~~~~~~

  .. raw:: html

     <b>hello world!</b>


