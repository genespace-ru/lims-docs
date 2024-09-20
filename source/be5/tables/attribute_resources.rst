attribute_resources
===================

Ресурсы для аттрибутов
  Ресурсы, которые были использованы для вычисления значения аттрибута при аннотации SNV и CNV.

Как правило, для каждого аттрибута необходимо указать:
  * базу данных;
  * программу;
  * рекомендацию. 

Pending: версионирование ресурсов.

.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - ID
     - KEYTYPE PK

       autoincrement
     - 

   * - attribute
     - INT

       Reference: attributes
     - Аттрибут.

   * - resource
     - INT

       Reference: resources
     - Ресурс (программа, база данных или рекомендация), использованная для получения значения аттрибута.

   * - comment
     - TEXT

       can be null
     - 

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

