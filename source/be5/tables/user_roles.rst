user_roles
==========

Role assignments

.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - user_name
     - VARCHAR(100)

       Reference: users
     - 

   * - role_name
     - VARCHAR(100)

       Reference: roles
     - 

**Индексы**
   * IDX_UR_FULL: UNIQUE user_name, role_name