rules
=====

Правила
  Правила для вычисления аттрибутов для аннотации SNV и CNV.

Pending: input - список входных аттрибутов. Пока перечисляются их title через запятую.

.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - ID
     - KEYTYPE PK

       autoincrement
     - 

   * - input
     - JSON
     - Список аттрибутов, которые служат входными значениями.

   * - priority
     - INT
     - приоритет вычисления аттрибута.

   * - attribute
     - INT

       Reference: attributes
     - Аттрибут, значение которого вычисляется.

   * - code
     - TEXT
     - Код (Java/Groovy) для вычисления значения аттрибута.

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

