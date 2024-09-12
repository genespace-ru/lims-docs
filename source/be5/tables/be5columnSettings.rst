be5columnSettings
=================

Column settings

.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - ID
     - KEYTYPE PK

       autoincrement
     - 

   * - table_name
     - VARCHAR(30)
     - 

   * - query_name
     - VARCHAR(255)
     - 

   * - column_name
     - VARCHAR(255)
     - 

   * - user_name
     - VARCHAR(100)

       can be null

       Reference: users
     - 

   * - role_name
     - VARCHAR(50)

       can be null
     - 

   * - wrap
     - VARCHAR(3)

       Defult value: 'no'
     - 

   * - nowrap
     - VARCHAR(3)

       Defult value: 'no'
     - 

   * - visible
     - BOOL

       Defult value: 'yes'
     - 

   * - width
     - VARCHAR(5)

       can be null
     - 

   * - quick
     - BOOL

       Defult value: 'no'
     - 

   * - grouping
     - BOOL

       Defult value: 'no'
     - 

   * - sort
     - ENUM: 
        * ASC
        * DEFAULT
        * DESC
     - 

   * - aggregate
     - ENUM: 
        * AVG
        * COUNT
        * DEFAULT
        * SUM
     - 

