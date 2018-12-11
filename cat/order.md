# ORDER

Заказ \(ORDER\) на поставку отправляет покупатель поставщику, указывая штрихкод продукта, его описание, заказанное количество, цену и прочую необходимую информацию.





| Название поля | Тип  | Формат | Описание |
| :--- | :--- | :--- | :--- |
| &lt;TRANSPORTATIONTYPES&gt;&lt;/TRANSPORTATIONTYPES&gt; |  | Строка \(70\) | Маршрут доставки |
|     &lt;DOCUMENTNAME&gt;&lt;/DOCUMENTNAME&gt; | М | Число положительное | Название документа \(220 —заказ\) |
|          &lt;NUMBER&gt;&lt;/NUMBER&gt; | М | Строка \(50\) | Номер заказа |
| &lt;DATE&gt;&lt;/DATE&gt; | М | Дата \(ГГГГ-ММ-ДД\) | Дата документа |
|               &lt;ACTION&gt;&lt;/ACTION&gt; | О | «4», «5», «27», «29» | 4 — поставка изменена, 5 — замена документа, 29 — поставка принята, 27 — поставка не принята |
| &lt;VERSION&gt;&lt;/VERSION&gt; | O | Число положительное | Версия заказа |
| &lt;PROMO&gt;&lt;/PROMO&gt; | O | «0», «1» | Акция: 0 — нет, 1 — есть |
| &lt;DELIVERYDATE&gt;&lt;/DELIVERYDATE&gt; | М | Дата \(ГГГГ-ММ-ДД\) | Дата поставки |
| &lt;DELIVERYTIME&gt;&lt;/DELIVERYTIME&gt; | O | Время \(чч:мм\) | Время поставки |
| &lt;SHIPMENTDATE&gt;&lt;/SHIPMENTDATE&gt; | O | Дата \(ГГГГ-ММ-ДД\) | Дата отгрузки6 |
| &lt;SHIPMENTTIME&gt;&lt;/SHIPMENTTIME&gt; | O | Время \(чч:мм\) | Время отгрузки |
| &lt;CAMPAIGNNUMBER&gt;&lt;/CAMPAIGNNUMBER&gt; | O | Строка \(70\) | Номер договора на поставку |
| &lt;CAMPAIGNNUMBERDATE&gt;&lt;/CAMPAIGNNUMBERDATE&gt; | O | Дата \(ГГГГ-ММ-ДД\) | Дата договора |
| &lt;CURRENCY&gt;&lt;/CURRENCY&gt; | O | Строка \(3\) | Код валюты |
| &lt;TRANSPORTQUANTITY&gt;&lt;/TRANSPORTQUANTITY&gt; | O | Число положительное | Количество машин |
|               &lt;ORDERREFERENCENUMBER&gt;5&lt;/ORDERREFERENCENUMBER&gt; |  | Строка \(16\) | Уникальный номер заказа для отслеживания |
| **&lt;LIMES&gt;** |  |  | Детали транспорта |
| &lt;LIMESNAME&gt;&lt;/LIMESNAME&gt; | O | Строка \(70\) | Название рампы |
| &lt;DATEFROM&gt;&lt;/DATEFROM&gt; | O | Дата \(ГГГГ-ММ-ДД\) | Дата прибытия транспорта |
| &lt;TIMEFROM&gt;&lt;/TIMEFROM&gt; | O | Время \(чч:мм\) | Время прибытия транспорта |
| &lt;DATETO&gt;&lt;/DATETO&gt; | O | Дата \(ГГГГ-ММ-ДД\) | Дата окончания отгрузки |
| &lt;TIMETO&gt;&lt;/TIMETO&gt; | O | Время \(чч:мм\) | Время окончания отгрузки |
| **&lt;/LIMES&gt;** |  |  |  |
| &lt;VAT&gt;&lt;/VAT&gt; | O | Число положительное | Ставка НДС, % |
| &lt;TRANSPORTATIONTYPES&gt;&lt;/TRANSPORTATIONTYPES&gt; | O | Строка \(35\) | Вид транспортировки |
| &lt;TRANSPORTATIONMEANS&gt;&lt;/TRANSPORTATIONMEANS&gt; | O | Строка \(70\) | Транспортное средство |
| &lt;TRANSPORTATIONCONDITION&gt;&lt;/TRANSPORTATIONCONDITION&gt; | O | Строка \(70\) | Условия транспортировки |
| &lt;TRANSPORTATIONPAYMENTTYPE&gt;&lt;/TRANSPORTATIONPAYMENTTYPE&gt; | O | Строка \(35\) | Тип оплаты доставки |
| &lt;TRANSPORTATIONROUTE&gt;&lt;/TRANSPORTATIONROUTE&gt; | O | Строка \(70\) | Маршрут доставки |
| &lt;BLANKETORDERNUMBER&gt;&lt;/BLANKETORDERNUMBER&gt; | O | Строка \(35\) | Номер бланкового заказа |
| &lt;INFOCODED&gt;&lt;/INFOCODED&gt; | O | Строка \(35\) | Инфокод |



