persistent_logins
=================

Persistent logins

.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - series
     - VARCHAR(64) PK
     - 

   * - user_name
     - VARCHAR(100)

       Reference: users
     - 

   * - token
     - VARCHAR(64)
     - 

   * - last_used
     - DATETIME
     - 

