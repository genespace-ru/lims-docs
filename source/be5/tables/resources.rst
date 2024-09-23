resources
=========

Ресурсы (для аннотации)
  Программы, базы данных и рекоммендации, используемые для аннотации SNV и CNV.

.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - ID
     - KEYTYPE PK

       autoincrement
     - 

   * - type
     - ENUM: 
        * database
        * other
        * program
        * recommendation
     - Тип ресурса.

   * - title
     - VARCHAR(20)
     - Название ресурса.

   * - version
     - VARCHAR(20)

       can be null
     - Версия ресурса.

   * - description
     - TEXT

       can be null
     - 

   * - url
     - VARCHAR(100)

       can be null
     - Ссылка на сайт ресурса.

   * - license
     - VARCHAR(200)

       can be null
     - Лицензия, по которой распространяется ресурс.

   * - comment
     - TEXT

       can be null
     - Разные комментарии, в том числе вопросы и замечания.

   * - creationDate___
     - TIMESTAMP

       can be null

       Defult value: CURRENT_TIMESTAMP
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

