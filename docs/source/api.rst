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

    .. tab:: Test 1

        Test text 1


    .. tab:: Test 1

        Test text 2   

       
Параметры сообщений
--------------------

Вставка HTML
~~~~~~~~~~~~

  .. raw:: html

     <b>hello world!</b>


