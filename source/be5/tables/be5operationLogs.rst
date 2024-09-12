be5operationLogs
================

Operation Logs

.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - ID
     - KEYTYPE PK

       autoincrement
     - 

   * - table_name
     - VARCHAR(30)

       Reference: entities
     - 

   * - operation_name
     - VARCHAR(100)
     - 

   * - user_name
     - VARCHAR(100)

       Reference: users
     - 

   * - localeString
     - VARCHAR(30)

       can be null
     - 

   * - appUrl
     - VARCHAR(150)

       can be null
     - 

   * - executedAt
     - DATETIME
     - 

   * - remoteAddr
     - VARCHAR(255)

       can be null
     - 

   * - result
     - TEXT

       can be null
     - 

**Индексы**
   * IDX_OP_LOGS_TNAME: table_name, operation_name
   * IDX_OP_LOGS_UTOE: user_name, table_name, operation_name, executedAt