
Заказ (ORDER) на поставку отправляет покупатель поставщику, указывая штрихкод продукта, его описание, заказанное количество, цену и прочую необходимую информацию.

|**Название поля**|**Тип**|**Формат**|**Описание**
| :--- | :--- | :--- | :--- 
|**&ltORDER&gt**| | | заказа
|     &ltDOCUMENTNAME&gt&lt/DOCUMENTNAME&gt|М|Число положительное|Название документа (220 —заказ)
|     &ltNUMBER&gt&lt/NUMBER&gt|М|Строка (50)|Номер заказа
|     &ltDATE&gt&lt/DATE&gt|М|Дата (ГГГГ-ММ-ДД)|Дата документа
|     &ltACTION&gt&lt/ACTION&gt|О|«4», «5», «27», «29»|4 — поставка изменена, 5 — замена документа, 29 — поставка принята, 27 — поставка не принята
|     &ltVERSION&gt&lt/VERSION&gt|O|Число положительное|Версия заказа
|     &ltPROMO&gt&lt/PROMO&gt|O|«0», «1»|Акция: 0 — нет, 1 — есть
|     &ltDELIVERYDATE&gt&lt/DELIVERYDATE&gt|М|Дата (ГГГГ-ММ-ДД)|Дата поставки
|     &ltDELIVERYTIME&gt&lt/DELIVERYTIME&gt|O|Время (чч:мм)|Время поставки
|     &ltSHIPMENTDATE&gt&lt/SHIPMENTDATE&gt|O|Дата (ГГГГ-ММ-ДД)|Дата отгрузки6
|     &ltSHIPMENTTIME&gt&lt/SHIPMENTTIME&gt|O|Время (чч:мм)|Время отгрузки
|     &ltCAMPAIGNNUMBER&gt&lt/CAMPAIGNNUMBER&gt|O|Строка (70)|Номер договора на поставку
|     &ltCAMPAIGNNUMBERDATE&gt&lt/CAMPAIGNNUMBERDATE&gt|O|Дата (ГГГГ-ММ-ДД)|Дата договора
|     &ltCURRENCY&gt&lt/CURRENCY&gt|O|Строка (3)|Код валюты
|     &ltTRANSPORTQUANTITY&gt&lt/TRANSPORTQUANTITY&gt|O|Число положительное|Количество машин
|     &ltORDERREFERENCENUMBER&gt5&lt/ORDERREFERENCENUMBER&gt| |Строка (16)|Уникальный номер заказа для отслеживания
|     **&ltLIMES&gt**| | |Детали транспорта
|          &ltLIMESNAME&gt&lt/LIMESNAME&gt|O|Строка (70)|Название рампы
|          &ltDATEFROM&gt&lt/DATEFROM&gt|O|Дата (ГГГГ-ММ-ДД)|Дата прибытия транспорта
|          &ltTIMEFROM&gt&lt/TIMEFROM&gt|O|Время (чч:мм)|Время прибытия транспорта
|          &ltDATETO&gt&lt/DATETO&gt|O|Дата (ГГГГ-ММ-ДД)|Дата окончания отгрузки
|          &ltTIMETO&gt&lt/TIMETO&gt|O|Время (чч:мм)|Время окончания отгрузки
|     **&lt/LIMES&gt**| | |
|     &ltVAT&gt&lt/VAT&gt|O|Число положительное|Ставка НДС, %
|     &ltTRANSPORTATIONTYPES&gt&lt/TRANSPORTATIONTYPES&gt|O|Строка (35)|Вид транспортировки
|     &ltTRANSPORTATIONMEANS&gt&lt/TRANSPORTATIONMEANS&gt|O|Строка (70)|Транспортное средство
|     &ltTRANSPORTATIONCONDITION&gt&lt/TRANSPORTATIONCONDITION&gt|O|Строка (70)|Условия транспортировки
|     &ltTRANSPORTATIONPAYMENTTYPE&gt&lt/TRANSPORTATIONPAYMENTTYPE&gt|O|Строка (35)|Тип оплаты доставки
|     &ltTRANSPORTATIONROUTE&gt&lt/TRANSPORTATIONROUTE&gt|O|Строка (70)|Маршрут доставки
|     &ltBLANKETORDERNUMBER&gt&lt/BLANKETORDERNUMBER&gt|O|Строка (35)|Номер бланкового заказа
|     &ltINFOCODED&gt&lt/INFOCODED&gt|O|Строка (35)|Инфокод
|     &ltDOCTYPE&gt&lt/DOCTYPE&gt|O|Строка (1)|(((
Тип документа:
O — оригинал,
R — замена,
D — удаление,
F — фиктивность заказа
PO — предзаказ
)))
|     &ltCORRNUMBER&gt&lt/CORRNUMBER&gt| | |
|     &ltSUPORDER&gt&lt/SUPORDER&gt|O|Строка (35)|Номер заказа поставщика
|     &ltKDKNUM&gt&lt/KDKNUM&gt|O|Строка (35)|Номер общего заказа КДК
|     &ltORDRTYPE&gt&lt/ORDRTYPE&gt|O|Строка (35)|Тип заказа
|     &ltINFO&gt&lt/INFO&gt|O|Строка (70)|Свободный текст
|     &ltEARLIESTDELIVERYDATE&gt&lt/EARLIESTDELIVERYDATE&gt|O|Дата (ГГГГ-ММ-ДД)|Дата не раньше
|     &ltLATESTDELIVERYDATE&gt&lt/LATESTDELIVERYDATE&gt|O|Дата (ГГГГ-ММ-ДД)|Дата не позднее
|     **&ltHEAD&gt**| | |
|          &ltSUPPLIER&gt&lt/SUPPLIER&gt|M|Число (13)|GLN поставщика
|          &ltBUYER&gt&lt/BUYER&gt|M|Число (13)|GLN покупателя
|          &ltBUYERCODE&gt&lt/BUYERCODE&gt|O|Строка (35)|Код покупателя
|          &ltDELIVERYPLACE&gt&lt/DELIVERYPLACE&gt|M|Число (13)|GLN места доставки
|          &ltFINALRECIPIENT&gt&lt/FINALRECIPIENT&gt|O|Число (13)|GLN конечного консигнатора
|          &ltORDERPARTNER&gt&lt/ORDERPARTNER&gt|O|Число (13)|GLN заказчика
|          &ltINVOICEPARTNER&gt&lt/INVOICEPARTNER&gt|O|Число (13)|GLN плательщика
|          &ltSENDER&gt&lt/SENDER&gt|M|Число (13)|GLN отправителя сообщения
|          &ltRECIPIENT&gt&lt/RECIPIENT&gt|M|Число (13)|GLN получателя сообщения
|          &ltCONSIGNEE&gt&lt/CONSIGNEE&gt|О11|Число (13)|GLN грузополучателя
|          &ltRECIPIENTCODE&gt&lt/RECIPIENTCODE&gt|O|Строка (35)|Код получателя
|          &ltRECIPIENTNAME&gt&lt/RECIPIENTNAME&gt|O|Строка (70)|Имя получателя
|          &ltINFO&gt&lt/INFO&gt|O|Строка (70)|Свободный текст
|          &ltDISCOUNTVALUE&gt&lt/DISCOUNTVALUE&gt|O|Число положительное|Размер скидки
|          &ltRECIPIENTCONTACTFACE&gt&lt/RECIPIENTCONTACTFACE&gt|O|Строка (70)|Контактное лицо
|          &ltRECIPIENTPHONE&gt&lt/RECIPIENTPHONE&gt|O|Строка (35)|Телефон получателя
|          &ltRECIPIENTCITY&gt&lt/RECIPIENTCITY&gt|O|Строка (35)|Город получателя
|          &ltRECIPIENTADRESS&gt&lt/RECIPIENTADRESS&gt|O|Строка (70)|Адрес получателя
|          &ltEDIINTERCHANGEID&gt&lt/EDIINTERCHANGEID&gt|O|Строка (70)|Номер транзакции
|          **&ltPOSITION&gt**| | |
|               &ltPOSITIONNUMBER&gt&lt/POSITIONNUMBER&gt|М|Число положительное|Номер товарной позиции
|               &ltPRODUCT&gt&lt/PRODUCT&gt|M|Число (8, 10, 14)|Штрихкод продукта
|               &ltPRODUCTIDSUPPLIER&gt&lt/PRODUCTIDSUPPLIER&gt|O|Строка (16)|Артикул в БД
|               &ltPRODUCTIDBUYER&gt&lt/PRODUCTIDBUYER&gt|O|Строка (16)|Артикул в БД покупателя
|               &ltBUYERPARTNUMBER&gt&lt/BUYERPARTNUMBER&gt|О|Строка (16)|Внутренний системный номер артикула в БД покупателя
|               &ltORDEREDQUANTITY&gt&lt/ORDEREDQUANTITY&gt|M|Число положительное|Заказанное количество
|               &ltQUANTITYOFCUINTU&gt&lt/QUANTITYOFCUINTU&gt|О|Число положительное|Количество в упаковке
|               &ltORDERUNIT&gt&lt/ORDERUNIT&gt|О|Строка (3)|Единицы измерения (см. Приложение 3)ﾧ
|               &ltQUANTITYOFPACKS&gt&lt/QUANTITYOFPACKS&gt|О|Число положительное|Количество упаковок
|               &ltORDERPRICE&gt&lt/ORDERPRICE&gt|O|Число десятичное|Цена продукта без НДС
|               &ltPRICEWITHVAT&gt&lt/PRICEWITHVAT&gt|O|Число десятичное|Цена продукта с НДС
|               &ltAMOUNT&gt&lt/AMOUNT&gt|O|Число десятичное|Сумма товара (без НДС)
|               &ltAMOUNTWITHVAT&gt&lt/AMOUNTWITHVAT&gt|О|Число десятичное|Сумма товара (с НДС)
|               &ltVAT&gt&lt/VAT&gt|O|Число десятичное|Ставка НДС, %
|               &ltCLAIMEDDELIVERYDATE&gt&lt/CLAIMEDDELIVERYDATE&gt|O|Дата (ГГГГ-ММ-ДД)|Объявленная дата доставки
|               &ltCLAIMEDDELIVERYTIME&gt&lt/CLAIMEDDELIVERYTIME&gt|O|Время (чч:мм)|Объявленное время доставки
|               &ltDELIVERYPLACE&gt&lt/DELIVERYPLACE&gt|О|Число (13)|GLN конечного места доставки
|               &ltINFOCODED&gt&lt/INFOCODED&gt|O|Строка (35)|Инфокод
|               &ltMINIMUMORDERQUANTITY&gt&lt/MINIMUMORDERQUANTITY&gt|O|Число положительное|Минимальное заказанное количество
|               &ltMAXIMUMORDERQUANTITY&gt &lt/MAXIMUMORDERQUANTITY&gt|O|Число положительное|Максимально допустимое отгрузжаемое количество
|               &ltPRODUCTIONCODE&gt&lt/PRODUCTIONCODE&gt|О|Строка (16)|Код алкогольной продукции
|               &ltPOSITIONKGM&gt50&lt/POSITIONKGM&gt|М| |Всего килограмм по позиции
|               &ltINFO&gt&lt/INFO&gt|O|Строка (90)|Свободный текст
|               &ltCOMPAIGNNUMBER&gt&lt/COMPAIGNNUMBER&gt|O|Строка (70)|Номер поставщика
|               &ltEARLIESTDELIVERYDATE&gt&lt/EARLIESTDELIVERYDATE&gt|O|Дата (ГГГГ-ММ-ДД)|Поставка не раньше указанной даты
|               &ltLATESTDELIVERYDATE&gt&lt/LATESTDELIVERYDATE&gt|O|Дата (ГГГГ-ММ-ДД)|Поставка не позднее указанной даты
|               &ltLATESTDELIVERYTIME&gt&lt/LATESTDELIVERYTIME&gt|O|Время (чч:мм)|Поставка не позднее указанного времени
|               &ltCONDITIONSTATUS&gt&lt/CONDITIONSTATUS&gt|О|Строка (3)|Статус кондиции (см. Приложение 2)ﾧ
|               &ltPACKAGEID&gt&lt/PACKAGEID&gt|O|Число положительное|Идентификатор упаковки
|               &ltCATEGORYNAME&gt&lt/CATEGORYNAME&gt|O|Строка (70)|Наименование категории товара
|               &ltBRENDNAME&gt&lt/BRENDNAME&gt|O|Строка (70)|Наименование бренда
|               &ltGROUPNAME&gtведро 9.6кг&lt/GROUPNAME&gt| | |Наименование группы товара
|               &ltNOVELTY&gt&lt/NOVELTY&gt|O| |Новинка
|               &ltCOUNTPIECESINBOX&gt&lt/COUNTPIECESINBOX&gt|O|Число положительное|Количество частей в упаковке
|               &ltCOUNTBOXESINLAYER&gt&lt/COUNTBOXESINLAYER&gt|O|Число положительное|Количество упаковок на уровне
|               &ltCOUNTPERPALLET&gt&lt/COUNTPERPALLET&gt|O|Число положительное|Количество на паллете
|               &ltWEIGHT&gt&lt/WEIGHT&gt|O|Число десятичное|Вес
|               &ltPALLETS&gt&lt/PALLETS&gt|O|Число положительное|Количество паллет
|               &ltCOUNTRYORIGIN&gt&lt/COUNTRYORIGIN&gt|О|Строка (2)|Страна производитель
|               &ltCALIBRE&gt&lt/CALIBRE&gt|O|Число положительное|Диаметр
|               &ltPRICEWITHDISCOUNT&gt&lt/PRICEWITHDISCOUNT&gt|O|Число десятичное|Цена с учетом скидки
|               &ltBOXESCOUNT&gt&lt/BOXESCOUNT&gt|O|Число положительное|Количество упаковок
|               **&ltCHARACTERISTIC&gt**| | |
|                    &ltDESCRIPTION&gt&lt/DESCRIPTION&gt|О|Строка (70)|Описание продукта
|               **&lt/CHARACTERISTIC&gt**| | |
|               **&ltPACKING&gt**| | |
|                    &ltPACKINGTYPE&gt&lt/PACKINGTYPE&gt|O|Строка (3)|Тип упаковки
|                    &ltPACKINGQUANTITY&gt&lt/PACKINGQUANTITY&gt|O|Число положительное|Количество упаковок
|                    &ltPACKINGUNIT&gt&lt/PACKINGUNIT&gt|O|Число положительное|Упаковщик
|               **&lt/PACKING&gt**| | |
|          **&lt/POSITION&gt**| | |
|     **&lt/HEAD&gt**| | |
|**&ltORDER&gt**| | |

