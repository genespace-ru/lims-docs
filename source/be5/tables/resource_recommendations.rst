resource_recommendations
========================

Ресурсы - рекомендации
  Описывает связь между ресурсами для аннотации SNV и CNV и соответствующими методическими рекомендациями.

.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - ID
     - KEYTYPE PK

       autoincrement
     - 

   * - resource
     - INT

       Reference: resources
     - 

   * - recommendation
     - INT

       Reference: resources
     - 

   * - comment
     - TEXT

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

