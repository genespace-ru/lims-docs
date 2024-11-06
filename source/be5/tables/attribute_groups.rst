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
     - INT

       can be null
     - Порядок отображения групп аттрибутов в представлении.

   * - viewName
     - VARCHAR(100)

       can be null
     - Название view (из snv_.yaml) для отображения этой группы свойств.

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

