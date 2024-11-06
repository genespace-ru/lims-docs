attributes
==========

Аттрибуты
  Аттрибуты (свойства) для аннотации SNV и CNV.

.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - ID
     - KEYTYPE PK

       autoincrement
     - 

   * - entity
     - VARCHAR(50)
     - Сущность, к которой относится данный аттрибут.

   * - groupID
     - INT

       can be null

       Reference: attribute_groups
     - Группа, к которой принадлежит аттрибут.

   * - title
     - VARCHAR(100)
     - Название аттрибута. Где это возможно используются названия аттрибутов из VEP и/или Genomenal.

   * - title_ru
     - VARCHAR(100)

       can be null
     - 

   * - description
     - TEXT

       can be null
     - Описание аттрибута. Где это возможно используются названия аттрибутов из VEP и/или Genomenal.

   * - description_ru
     - TEXT

       can be null
     - Описание аттрибута. Где это возможно используются названия аттрибутов из VEP и/или Genomenal.

   * - comment
     - TEXT

       can be null
     - Комментарий.

   * - type
     - INT

       Reference: attribute_types
     - Тип аттрибута. Используется предопределенный справочник типов аттрибутов attribute_types.

   * - dictionary
     - VARCHAR(100)

       can be null
     - Справочник для возможных значений аттрибута. Где это возможно используются значения из VEP и/или Genomenal.

   * - storage
     - ENUM: 
        * json
        * query
     - Где хранится значение аттрибута.
* json - в формате json поля 'attributes' соответствующей таблицы сущности.
* query - вычисляется значением запроса и идет как поле значений запроса.

   * - level
     - ENUM: 
        * CNV
        * SNV
        * transcript
     - Уровень к которому относится аттрибут - к самой SNV/CNV или транскрипту.

   * - editable
     - ENUM: 
        * no
        * yes
     - Можно ли редактировать этот аттрибут вручную.

   * - displayIfEmpty
     - ENUM: 
        * no
        * yes
     - Нужно ли показывать значение этого аттрибута в представлении, если оно пустое.

   * - displayOrder
     - INT

       Defult value: 99
     - Порядок отображения значения аттрибута в представлении.

   * - urlMask
     - VARCHAR(100)

       can be null
     - Маска для формирования гиперссылки для значения свойства.

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

