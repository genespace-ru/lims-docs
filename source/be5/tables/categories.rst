categories
==========


.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - ID
     - KEYTYPE PK

       autoincrement
     - 

   * - entity
     - VARCHAR(30)

       Reference: entities
     - 

   * - publicID
     - VARCHAR(100)

       can be null
     - 

   * - name
     - VARCHAR(255)
     - 

   * - parentID
     - KEYTYPE

       can be null

       Reference: categories
     - 

   * - description
     - TEXT

       can be null
     - 

**Индексы**
   * IDX_CAT_ENTITY_PAR: entity, parentID
   * IDX_CAT_ENTITY_PUB: entity, publicID
   * IDX_CAT_PARENT_ID: parentID
   * IDX_CAT_PUBLICID: publicID