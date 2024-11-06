rule_sets
=========

Наборы правил
  Наборы правил, используемые для аннотации SNV и CNV.

.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - ID
     - KEYTYPE PK

       autoincrement
     - 

   * - title
     - VARCHAR(100)
     - Название набора правил.

   * - version
     - VARCHAR(50)

       can be null
     - Версия ресурса.

   * - description
     - TEXT

       can be null
     - 

   * - recommendation
     - INT

       can be null

       Reference: resources
     - Ссылка на рекомендации, на основе которых построен данный набор правил.

   * - comment
     - TEXT

       can be null
     - Разные комментарии, в том числе вопросы и замечания.

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

