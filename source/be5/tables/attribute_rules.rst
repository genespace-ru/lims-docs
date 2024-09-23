attribute_rules
===============

Правила
  Правила для вычисления аттрибутов для аннотации SNV и CNV.

.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - ID
     - KEYTYPE PK

       autoincrement
     - 

   * - attribute
     - INT

       Reference: attributes
     - Аттрибут, значение которого вычисляется.

   * - code
     - TEXT
     - Код (JavaScript) для вычисления значения аттрибута.

   * - desription
     - TEXT

       can be null
     - Описание кода для вычисления значения аттрибута.

   * - comment
     - TEXT

       can be null
     - Название аттрибута. Где это возможно используются названия аттрибутов из VEP и/или Genomenal.

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

