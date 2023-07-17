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

.. code-block:: java
   :emphasize-lines: 1-3,5

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
  },
  "destAddr":"Номер_Абонента",
  "message":{
    "type":"SMS",
    "data":{
      "text":"Текст. Follow link: <http://verylongurl.com/very/long/url>",
      "serviceNumber":"НОМЕР_ОТПРАВИТЕЛЯ",
      "ttl":10
    }
  }
}

Параметры сообщений
--------------------

Параметры запроса для отправки сообщения
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
