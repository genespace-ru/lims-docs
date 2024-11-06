sample_types
============

Sample type
  Типы образцов. Например, метагеномика, кровь, опухоль и т.п.

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

   * - template
     - KEYTYPE

       can be null

       Reference: sample_templates
     - Шаблон для описания мета-данных для соответствующего типа образцов.

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

