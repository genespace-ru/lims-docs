runs
====

Запуски
  Запуски секвенатора

.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - ID
     - KEYTYPE PK

       autoincrement
     - 

   * - project_id
     - KEYTYPE

       Reference: projects
     - 

   * - name
     - VARCHAR(100)
     - 

   * - status
     - ENUM: 
        * completed
        * in_progress
     - 

   * - data
     - TEXT

       can be null
     - данные из/для файла запуска секвенатора

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

