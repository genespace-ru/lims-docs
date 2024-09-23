snv_history
===========

SNV архив
  Список ранее найденных и проаннотированных SNV, которые могут быть 
повторно использованы для аннотации новых образцов.

.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - ID
     - KEYTYPE PK

       autoincrement
     - 

   * - VEP_ID
     - VARCHAR(50)

       can be null
     - Идентификатор SNV в VEP файле.

   * - location
     - VARCHAR(50)
     - Расположение SNV в стандартном формате (chr:start or chr:start-end)

   * - allele
     - VARCHAR(10)
     - Вариант, исопльзуемы для рассчета последствий SNV.

   * - pathogenicity
     - INT

       can be null

       Reference: pathogenicity
     - Патогенность SNV

   * - pathogenicityAuthority
     - INT

       can be null

       Reference: pathogenicity_authority
     - Автор или рекоммендации, по которой проставлена патогенность.

   * - attributes
     - JSON

       can be null
     - Значения аттрибутов в формате JSON (название аттрибута - значение).

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

