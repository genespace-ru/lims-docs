attribute_types
===============

Типы аттрибутов
  Типы  аттрибутов (свойств) для аннотации SNV и CNV.

.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - ID
     - KEYTYPE PK

       autoincrement
     - 

   * - title
     - VARCHAR(20)
     - Название типа аттрибута.

   * - description
     - TEXT

       can be null
     - Описание типа аттрибута.

   * - comment
     - TEXT

       can be null
     - Комментарий.

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

