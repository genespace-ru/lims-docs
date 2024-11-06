task_runs
=========

Tasks
  Информация о запущенных и выполненных задачах.

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
     - Проект, для которого была запущена задача.

   * - sample
     - KEYTYPE

       can be null

       Reference: samples
     - Образец, для которого была запущена задача.

   * - workflow
     - KEYTYPE

       can be null

       Reference: workflow_runs
     - Сценарий, в рамках которого была запущена задача.

   * - task_info
     - KEYTYPE

       can be null

       Reference: task_info
     - Информация о задаче (классе).

   * - start
     - TIMESTAMP

       can be null
     - Время запуска задачи.

   * - end
     - TIMESTAMP

       can be null
     - Время окончания задачи.

   * - status
     - ENUM: 
        * completed
        * error
        * in_progress
        * scheduled
     - Статус выполнения задачи.

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

