samples
=======

Образцы
  Отдельные образцы для секвинирования. За основу взяты поля Illumina.

.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - ID
     - KEYTYPE PK

       autoincrement
     - 

   * - project
     - KEYTYPE

       Reference: projects
     - Проект, которому принадлежит данный образец.

   * - typeID
     - KEYTYPE

       can be null

       Reference: sample_types
     - Тип данных образца.

   * - title
     - VARCHAR(100)
     - 

   * - description
     - TEXT

       can be null
     - 

   * - metadata
     - TEXT

       can be null
     - 

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

