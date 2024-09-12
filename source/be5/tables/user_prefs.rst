user_prefs
==========

User Preferences

.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - user_name
     - VARCHAR(100)

       Reference: users
     - 

   * - pref_name
     - VARCHAR(30)
     - 

   * - pref_value
     - TEXT
     - 

**Индексы**
   * I_USERPREFS_UNAME: UNIQUE user_name, pref_name