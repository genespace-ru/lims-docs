samples
=======

Образцы
  Отдельные образцы для секвинирования. За основу взяты поля Illumina.

.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - ID
     - KEYTYPE PK

       autoincrement
     - 

   * - name
     - VARCHAR(100)
     - 

   * - type
     - VARCHAR(50)
     - 

   * - template_id
     - KEYTYPE

       can be null

       Reference: sample_templates
     - 

   * - plate
     - VARCHAR(100)

       can be null
     - 

   * - well
     - VARCHAR(100)

       can be null
     - 

   * - index_plate
     - VARCHAR(100)

       can be null
     - 

   * - index_well
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

   * - description
     - TEXT

       can be null
     - 

   * - file_path
     - VARCHAR(300)

       can be null
     - 

   * - file_size
     - INT

       can be null
     - 

   * - metadata
     - TEXT

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

