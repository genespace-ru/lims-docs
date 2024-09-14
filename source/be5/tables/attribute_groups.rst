attribute_groups
================

Группа аттрибутов
  Группа для группирования аттрибутов (свойств) для аннотации SNV и CNV.

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
     - VARCHAR(100)
     - Название группы. Где это возможно используются названия группы аттрибутов из VEP и/или Genomenal.

   * - title_ru
     - VARCHAR(100)

       can be null
     - 

   * - description
     - TEXT

       can be null
     - Описание группы аттрибутов. Где это возможно используются названия аттрибутов из VEP и/или Genomenal.

   * - description_ru
     - TEXT

       can be null
     - Описание группы аттрибутов. Где это возможно используются названия аттрибутов из VEP и/или Genomenal.

   * - comment
     - TEXT

       can be null
     - Комментарий.

   * - displayOrder
     - VARCHAR(5)

       can be null
     - Порядок отображения групп аттрибутов в представлении.

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

