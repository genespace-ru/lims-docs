sequencing_data
===============

Данные секвенирования для каждого связанного образца

.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - ID
     - KEYTYPE PK

       autoincrement
     - 

   * - run_sample_id
     - KEYTYPE

       Reference: run_samples
     - 

   * - read_count
     - BIGINT

       can be null
     - 

   * - base_count
     - BIGINT

       can be null
     - 

   * - quality_score
     - DECIMAL(15,4)

       can be null
     - 

   * - sequence_data
     - TEXT
     - 

   * - creationDate___
     - TIMESTAMP

       can be null
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

