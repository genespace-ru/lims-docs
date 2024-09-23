snv_transcripts_history
=======================

SNV транскрипты (архив)
  Список ранее найденных и проаннотированных транскриптов и их свойств для соответствующей SNV.

.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - ID
     - KEYTYPE PK

       autoincrement
     - 

   * - SNV
     - INT

       Reference: snv_history
     - ссылка на SNV, к которой относится данный транскрипт

   * - transcript
     - VARCHAR(50)
     - Идентификатор транскрипта.

   * - attributes
     - JSON

       can be null
     - Значения аттрибутов в формате JSON (название аттрибута - значение).

