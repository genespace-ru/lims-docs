workflow_runs
=============

Workflows
  Информация о запущенных и выполненных сценариях анализа.
Каждый сценарий состоит из набора задач.

.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - ID
     - KEYTYPE PK

       autoincrement
     - 

   * - project
     - KEYTYPE

       Reference: projects
     - Проект, для которого был запущен сценарий.

   * - sample
     - KEYTYPE

       can be null

       Reference: samples
     - Образец, для которого был запущен сценарий.

   * - workflow_info
     - KEYTYPE

       can be null

       Reference: workflow_info
     - Информация о сценарии.

   * - start
     - TIMESTAMP

       can be null
     - Время запуска сценария.

   * - end
     - TIMESTAMP

       can be null
     - Время окончания сценария.

   * - status
     - ENUM: 
        * completed
        * error
        * in_progress
        * scheduled
     - Статус выполнения сценария.

   * - params
     - JSON

       can be null
     - Параметры запуска.

   * - log
     - TEXT

       can be null
     - Лог сообщений.

   * - comment
     - VARCHAR(255)

       can be null
     - 

   * - creationDate___
     - TIMESTAMP

       Defult value: CURRENT_TIMESTAMP
     - 

   * - modificationDate___
     - TIMESTAMP

       can be null
     - 

   * - whoInserted___
     - VARCHAR(100)

       Defult value: 'Administrator'
     - 

   * - whoModified___
     - VARCHAR(100)

       can be null
     - 

