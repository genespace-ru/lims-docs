run_metrics
===========

Метрики и статистика запусков

.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - ID
     - KEYTYPE PK

       autoincrement
     - 

   * - run_id
     - KEYTYPE

       Reference: runs
     - 

   * - name
     - VARCHAR(200)
     - 

   * - value
     - DECIMAL(15,4)
     - 

   * - creationDate___
     - TIMESTAMP

       can be null
     - 

   * - modificationDate___
     - TIMESTAMP

       can be null
     - 

   * - whoInserted___
     - VARCHAR(100)

       can be null
     - 

   * - whoModified___
     - VARCHAR(100)

       can be null
     - 

