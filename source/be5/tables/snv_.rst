snv_
====

SNV
  Список найденных SNV. Для каждого образца создается отдельная таблица,
где название образца является суффиксом в названии таблицы.
Например: snv_sample1.
Поля vcf_(chrom, pos, id, ref, alt, qual, filter, info) являются обязательными
полями VCF v.4.2 (https://samtools.github.io/hts-specs/VCFv4.2.pdf).
Их подробное описание смотри в спецификации VCFv4.2.
Ограничение - один VCF файл должен содержать данные только для одного образца.

.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - ID
     - KEYTYPE PK

       autoincrement
     - 

   * - vcf_chrom
     - VARCHAR(50)
     - Хромосома.

   * - vcf_pos
     - INT
     - Позиция на хромосоме.

   * - vcf_id
     - VARCHAR(200)

       can be null
     - Список идентификаторов, разделитель - ;

   * - vcf_ref
     - VARCHAR(50)
     - Основания ( A,C,G,T,N) в референсном геноме.

   * - vcf_alt
     - VARCHAR(50)
     - Альтернативные основания.

   * - vcf_qual
     - DECIMAL(4,1)

       can be null
     - Качество, Phred-scaled quality score for the assertion made in ALT.

   * - vcf_filter
     - VARCHAR(50)
     - Статус, PASS - если поизиция прошла все фильтры.

   * - vcf_info
     - TEXT

       can be null
     - Дополнительная информация в формате ключ-значение.

   * - vcf_format
     - VARCHAR(1000)
     - Формат для поля генотип.

   * - attributes
     - JSON

       can be null
     - Все аттрибуты (VCF info, format; VEP annotation и другие).

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

