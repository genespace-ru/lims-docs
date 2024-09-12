Nextflow
========

Nextflow выступает в качестве агента для запуска скриптов для анализа данных.

Для этого Nextflow запускается с опцией -with-tower.

Также необходимо выставить значения переменных:
* TOWER_ACCESS_TOKEN
* TOWER_WORKFLOW_ID 

Реально эти переменные не используются, но нужны, чтобы Nextflow запустилось в качестве агента.

.. code-block:: 

    export TOWER_ACCESS_TOKEN=stub
    export TOWER_WORKFLOW_ID=stub
    ./nextflow run script.nf -with-tower 'http://lims_url:8200/nf'

После запуска Nextflow посылает сообщения LIMS о ходе выполнения сценария,
используя trace сервис:
https://cloud.seqera.io/openapi/index.html

Описание таблиц
---------------
Результаты соответствующих запросов от Nextflow записываются в виде полученного JSON
в соответствующие поля таблицы nf_workflows в виде JSONB.
            
PostgreSQL имеет специальный синтаксис для работы с полями JSONB. 
При необходимости они также могут быть индексированы.

.. kroki::  ./be5/diagrams/nextflow.puml png
           
.. include:: ./be5/tables/nf_workflows.rstincl
.. include:: ./be5/tables/nf_heartbeat.rstincl
