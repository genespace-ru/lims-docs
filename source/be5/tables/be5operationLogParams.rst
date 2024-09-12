be5operationLogParams
=====================

Parameters of Operation Logs

.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - ID
     - KEYTYPE PK

       autoincrement
     - 

   * - operLogID
     - KEYTYPE

       Reference: be5operationLogs
     - 

   * - type
     - ENUM: 
        * context
        * input
        * session
     - 

   * - paramName
     - VARCHAR(255)
     - 

   * - paramValue
     - TEXT

       can be null
     - 

**Индексы**
   * IDX_OP_LOG_P_OID: operLogID
   * IDX_OP_LOG_P_OID_N: operLogID, paramName