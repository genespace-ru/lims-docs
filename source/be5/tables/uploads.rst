uploads
=======

Загрузки

.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - ID
     - KEYTYPE PK

       autoincrement
     - 

   * - fileName
     - VARCHAR(200)
     - 

   * - tableName
     - VARCHAR(200)

       can be null
     - 

   * - type
     - ENUM: 
        * BAM
        * BED
        * CRAM
        * FASTA
        * FASTQ
        * GFF
        * GTF
        * SAM
        * VEP
        * unknown
     - 

   * - comment
     - TEXT

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

   * - creationDate___
     - DATETIME

       can be null
     - 

   * - modificationDate___
     - DATETIME

       can be null
     - 

