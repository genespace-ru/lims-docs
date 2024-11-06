snv_features_
=============

SNV (features)
  Список features SNV (транскрипт, регуляторный район и т.п.) и их свойств для соответствующей SNV.
Для каждого образца создается отдельная таблица,
где название образца является суффиксом в названии таблицы.
Например: snv_features_sample1.

.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - ID
     - KEYTYPE PK

       autoincrement
     - 

   * - snv
     - INT

       Reference: snv_
     - ссылка на SNV, к которой относится данный транскрипт

   * - feature
     - VARCHAR(50)
     - Тип особенности (Transcript, RegulatoryFeature и т.п.).

   * - attributes
     - JSON

       can be null
     - Значения аттрибутов в формате JSON (название аттрибута - значение).

