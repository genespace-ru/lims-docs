be5eventParams
==============

Event Parameters

.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - ID
     - KEYTYPE PK

       autoincrement
     - 

   * - logID
     - KEYTYPE

       Reference: be5events
     - 

   * - paramName
     - VARCHAR(255)
     - 

   * - paramValue
     - TEXT

       can be null
     - 

**Индексы**
   * IDX_EVENTPARS_LOGID: logID