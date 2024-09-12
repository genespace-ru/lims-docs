attachments
===========


.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - ID
     - KEYTYPE PK

       autoincrement
     - 

   * - ownerID
     - VARCHAR(50)
     - 

   * - fileName
     - VARCHAR(255)
     - 

   * - tag
     - VARCHAR(100)

       can be null
     - 

   * - mimeType
     - VARCHAR(100)

       can be null

       Defult value: 'application/octet-stream'

       Reference: mimeTypes
     - 

   * - data
     - BLOB

       can be null
     - 

   * - description
     - VARCHAR(255)

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

