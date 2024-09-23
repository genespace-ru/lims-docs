pathogenicity_authority
=======================

Патогенность (основание)
  Справочник источников для проставления патогенности.

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

   * - resource
     - INT

       Reference: resources
     - Ресурс, используемый для рекоммендаций.

   * - comment
     - TEXT

       can be null
     - Комментарий.

   * - creationDate___
     - TIMESTAMP

       can be null

       Defult value: CURRENT_TIMESTAMP
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

