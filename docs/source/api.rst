Интеграция по REST-протоколу 
============================

Отправка сообщений
--------------------
SMS
~~~

.. code-block:: python
   :emphasize-lines: 1-3,5

   def some_function():
       interesting = False
       print 'This line is highlighted.'
       print 'This one is not...'
       print '...but this one is.'


 .. code-block:: json

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
