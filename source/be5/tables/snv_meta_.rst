snv_meta_
=========

SNV meta
  Мета информация по ключам для VCF файла с SNV. Для каждого образца создается отдельная таблица,
где название образца является суффиксом в названии таблицы.
Например: snv_meta_sample1.
Ограничение - один VCF файл должен содержать данные только для одного образца.

.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - section
     - VARCHAR(50)
     - Название секции или поля. Например':' INFO, FORMAT, contig

   * - value
     - VARCHAR(10000)
     - Значение секции, неразобранное на части.

   * - ID
     - VARCHAR(50)

       can be null
     - Название ключа, например':' PASS, GT

   * - description
     - VARCHAR(200)

       can be null
     - Описание данные в ключе.

   * - type
     - ENUM: 
        * Character
        * Flag
        * Float
        * Integer
        * String
     - Тип данных в поле

   * - number
     - VARCHAR(2)

       can be null
     - Число значений в поле.

   * - url
     - VARCHAR(200)

       can be null
     - URL для контига.

