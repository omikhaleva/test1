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


       
Параметры сообщений
--------------------

Параметры запроса для отправки сообщения
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

  .. raw:: html

     <b>hello world!</b>


  .. tabs::

     .. tab:: Sphinx

        If your project uses Sphinx,
        we offer a special builder optimized for Sphinx projects.

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

     .. tab:: MkDocs

        If your project uses MkDocs,
        we offer a special builder optimized for MkDocs projects.

        
