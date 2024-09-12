be5events
=========

Events

.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - ID
     - KEYTYPE PK

       autoincrement
     - 

   * - user_name
     - VARCHAR(100)

       Reference: users
     - 

   * - IP
     - VARCHAR(100)

       can be null
     - 

   * - startTime
     - DATETIME
     - 

   * - endTime
     - DATETIME

       can be null
     - 

   * - action
     - ENUM: 
        * logging
        * operation
        * other
        * print
        * process
        * query
        * queryBuilder
        * servlet
     - 

   * - entity
     - VARCHAR(40)

       can be null
     - 

   * - title
     - VARCHAR(255)

       can be null
     - 

   * - result
     - TEXT

       can be null
     - 

   * - exception
     - TEXT

       can be null
     - 

**Индексы**
   * IDX_EVENTS_START: startTime
   * IDX_EVENTS_USER_NAME: user_name