task_info
=========

Task info
  Информация о типах задач (импорт, контроль качества и т.п.).
Pending: 
- формат и хранение аттрибутов для запуска задачи
- иконка для представления задачи.

.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - ID
     - KEYTYPE PK

       autoincrement
     - 

   * - title
     - VARCHAR(20)
     - Название задачи.

   * - description
     - TEXT

       can be null
     - Описание задачи, может быть текст HTML.

   * - comment
     - TEXT

       can be null
     - Комментарий.

   * - params
     - JSON

       can be null
     - Описание параметров для запуска, чтобы из них можно было автоматически 
сформировать форму для ввода параметров. 

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

