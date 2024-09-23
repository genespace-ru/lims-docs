snv_
====

SNV
  Список найденных SNV. Для каждого образца создается отдельная таблица,
где название образца является суффиксом в названии таблицы.
Например: snv_sample1.

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

   * - isAttached
     - ENUM: 
        * no
        * yes
     - Нужно ли закрепить, отмеченные SNV, в начале представления.

   * - isHidden
     - ENUM: 
        * no
        * yes
     - Нужно ли показывать SNV в представлении.

   * - includeInReport
     - ENUM: 
        * no
        * yes
     - Нужно ли включать SNV в отчет.

   * - reportComment
     - ENUM: 
        * no
        * yes
     - Нужно ли включать SNV в отчет.

