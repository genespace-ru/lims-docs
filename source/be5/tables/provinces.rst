provinces
=========


.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - ID
     - VARCHAR(30) PK
     - 

   * - countryID
     - CHAR(2)

       Reference: countries
     - 

   * - name
     - VARCHAR(255)
     - 

**Индексы**
   * IDX_PROVINCES_CID: countryID