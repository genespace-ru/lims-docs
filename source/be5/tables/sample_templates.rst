sample_templates
================

Sample templates
  Шаблон для описания свойств образца. Содержит описание набора аттрибутов, которые используются для описания образца.

.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - ID
     - KEYTYPE PK
     - 

   * - title
     - VARCHAR(100)
     - 

   * - description
     - TEXT

       can be null
     - 

   * - data
     - TEXT
     - Шаблон для описания свойств образца данных (в разработке @todo).

   * - comment
     - TEXT

       can be null
     - 

   * - creationDate___
     - TIMESTAMP

       Defult value: CURRENT_TIMESTAMP
     - 

   * - modificationDate___
     - TIMESTAMP

       can be null
     - 

   * - whoInserted___
     - VARCHAR(100)

       Defult value: 'Administrator'
     - 

   * - whoModified___
     - VARCHAR(100)

       can be null
     - 

