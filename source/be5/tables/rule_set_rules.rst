rule_set_rules
==============

Правила для набора правил
  Таблица связка, указывающая, какие правила в какой набор входят.

.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - ID
     - KEYTYPE PK

       autoincrement
     - 

   * - rule_set
     - INT

       Reference: rule_sets
     - Идентификатор набора правил.

   * - rule
     - INT

       Reference: rules
     - Идентификатор правила.

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

