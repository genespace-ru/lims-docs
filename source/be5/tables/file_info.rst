file_info
=========

Files
  Информация о файлах с данными и результатами

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
     - VARCHAR(255)
     - 

   * - mimeType
     - VARCHAR(100)

       can be null

       Defult value: 'application/octet-stream'

       Reference: mimeTypes
     - 

   * - fileType
     - KEYTYPE

       can be null

       Reference: file_types
     - 

   * - path
     - VARCHAR(255)
     - Полный путь до файла, относительно проекта.

   * - size
     - INT
     - Размер файла в байтах.

   * - project
     - KEYTYPE

       Reference: projects
     - Проект, которому принадлежит файл.

   * - entity
     - VARCHAR(255)

       can be null
     - Сущность, с которой связан файл (sample, project).

   * - entityID
     - KEYTYPE

       can be null
     - Идентификатор сущности, с которой связан файл.

   * - comment
     - VARCHAR(255)

       can be null
     - 

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

