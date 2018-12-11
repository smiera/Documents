**Название поля**|**Тип**|**Формат**|**Описание**
 ----- | ------- | -------------------- | --------------------------
**ORDER**| | |
     <DOCUMENTNAME><DOCUMENTNAME>|М|Число положительное|Название документа (220 —заказ)
     <NUMBER></NUMBER>|М|Строка (50)|Номер заказа
     <DATE></DATE>|М|Дата (ГГГГ-ММ-ДД)|Дата документа
     <ACTION></ACTION>|О|«4», «5», «27», «29»|4 — поставка изменена, 5 — замена документа, 29 — поставка принята, 27 — поставка не принята
     <VERSION></VERSION>|O|Число положительное|Версия заказа
     <PROMO></PROMO>|O|«0», «1»|Акция: 0 — нет, 1 — есть
     <DELIVERYDATE></DELIVERYDATE>|М|Дата (ГГГГ-ММ-ДД)|Дата поставки
     <DELIVERYTIME></DELIVERYTIME>|O|Время (чч:мм)|Время поставки
     <SHIPMENTDATE></SHIPMENTDATE>|O|Дата (ГГГГ-ММ-ДД)|Дата отгрузки6
     <SHIPMENTTIME></SHIPMENTTIME>|O|Время (чч:мм)|Время отгрузки
     <CAMPAIGNNUMBER></CAMPAIGNNUMBER>|O|Строка (70)|Номер договора на поставку
     <CAMPAIGNNUMBERDATE></CAMPAIGNNUMBERDATE>|O|Дата (ГГГГ-ММ-ДД)|Дата договора
     <CURRENCY></CURRENCY>|O|Строка (3)|Код валюты
     <TRANSPORTQUANTITY></TRANSPORTQUANTITY>|O|Число положительное|Количество машин
     <ORDERREFERENCENUMBER>5</ORDERREFERENCENUMBER>| |Строка (16)|Уникальный номер заказа для отслеживания
     **<LIMES>**| | |Детали транспорта
          <LIMESNAME></LIMESNAME>|O|Строка (70)|Название рампы
          <DATEFROM></DATEFROM>|O|Дата (ГГГГ-ММ-ДД)|Дата прибытия транспорта
          <TIMEFROM></TIMEFROM>|O|Время (чч:мм)|Время прибытия транспорта
          <DATETO></DATETO>|O|Дата (ГГГГ-ММ-ДД)|Дата окончания отгрузки
          <TIMETO></TIMETO>|O|Время (чч:мм)|Время окончания отгрузки
                **</LIMES>**| | |
