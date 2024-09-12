classifications
===============

Assigned categories

.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - ID
     - KEYTYPE PK

       autoincrement
     - 

   * - recordID
     - VARCHAR(200)
     - 

   * - categoryID
     - KEYTYPE

       Reference: categories
     - 

   * - importID
     - KEYTYPE

       can be null

       Reference: import
     - 

   * - whoInserted___
     - VARCHAR(100)

       can be null
     - 

   * - creationDate___
     - DATETIME

       can be null
     - 

**Индексы**
   * IDX_CLASSIF1: recordID, categoryID
   * IDX_CLASSIF2: categoryID, recordID