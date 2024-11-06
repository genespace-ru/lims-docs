file_types
==========

Типы файлов
  Типы  файлов с данными и результатами.

.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - ID
     - KEYTYPE PK

       autoincrement
     - 

   * - suffix
     - VARCHAR(100)
     - Тип файла.

   * - icon
     - VARCHAR(200)

       can be null
     - Иконка для отображения типа файлов.

   * - description
     - TEXT

       can be null
     - 

   * - comment
     - TEXT

       can be null
     - Комментарий.

   * - creationDate___
     - TIMESTAMP

       Defult value: CURRENT_TIMESTAMP
     - 

   * - modificationDate___
     - TIMESTAMP

       can be null
     - 

   * - whoInserted___
     - VARCHAR(100)

       Defult value: 'Administrator'
     - 

   * - whoModified___
     - VARCHAR(100)

       can be null
     - 

