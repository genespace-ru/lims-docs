devices
=======


.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - ID
     - KEYTYPE PK

       autoincrement
     - 

   * - sn
     - VARCHAR(100)
     - serial number

   * - title
     - TEXT
     - 

   * - typeID
     - INT

       Reference: device_types
     - 

   * - tocken
     - VARCHAR(100)

       can be null
     - authorisation key for remote access

   * - statusID
     - INT

       Reference: device_statuses
     - 

   * - stats
     - JSON

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

