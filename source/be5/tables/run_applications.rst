run_applications
================

Приложения, которые могут использоваться в запусках для анализа данных

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

   * - version
     - VARCHAR(50)

       can be null
     - 

   * - description
     - TEXT

       can be null
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

