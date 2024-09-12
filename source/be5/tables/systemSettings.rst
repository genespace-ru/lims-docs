systemSettings
==============

System Settings

.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - section_name
     - VARCHAR(255)

       Defult value: 'system'
     - 

   * - setting_name
     - VARCHAR(64)
     - 

   * - setting_value
     - TEXT
     - 

**Индексы**
   * I_UE_SS_SN_SN: UNIQUE section_name, setting_name