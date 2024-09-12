analyses
========


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

   * - icon
     - VARCHAR(100)

       can be null
     - 

   * - description
     - TEXT

       can be null
     - 

   * - data
     - TEXT
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

