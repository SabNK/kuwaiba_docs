New Equipment
++++++++++++++

Предположим, что в установленный нами шкаф :doc:`ТШК№100 </start/try_on/new_rack>`
необходимо установить оптический кросс, и волокна в кроссе по проекту 
развариваются на оборудование соседней подстанции - ПС 500кВ "Липецкая". 

Как прописать это программе kuwaiba?
-------------------------------------

На картинке ниже показано верное название кросса, которое указывает, в какую 
сторону разварены волокна в ODF.

.. image:: /res/try_on/cross_odf_voronezh.PNG

Также внутри добавляем порты. В данном случае, не создавая их в ODF, в полном
объеме, а только те, которые разварены. По проекту это порты 15-16.

Все важные поля свойств также должны быть заполнены в кроссе: ``owner``, 
``vendor``, ``seriaNumber``, ``position`` (обязательно прописываем, в какой 
юнит вставлен ODF).

В последствии, при создании ПС 500кВ "Липецкая" и кросса, установленного на ней,
появится возможность коннекта двух ODF в kuwaiba.

