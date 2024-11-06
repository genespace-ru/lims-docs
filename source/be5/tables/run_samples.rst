run_samples
===========

Связь запусков и образцов

.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - ID
     - KEYTYPE PK

       autoincrement
     - 

   * - run_id
     - KEYTYPE

       Reference: runs
     - 

   * - sample_id
     - KEYTYPE

       Reference: samples
     - 

   * - plate
     - VARCHAR(100)

       can be null
     - 

   * - well
     - VARCHAR(100)

       can be null
     - 

   * - index_plate_well
     - VARCHAR(100)

       can be null
     - 

   * - I7_index_id
     - VARCHAR(100)

       can be null
     - 

   * - index1
     - VARCHAR(100)

       can be null
     - 

   * - I5_index_id
     - VARCHAR(100)

       can be null
     - 

   * - index2
     - VARCHAR(100)

       can be null
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

