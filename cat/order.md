
аказ (ORDER) на поставку отправляет покупатель поставщику, указывая штрихкод продукта, его описание, заказанное количество, цену и прочую необходимую информацию.

**Название поля**|**Тип**|**Формат**|**Описание**
|------------------------------------------------------------- | ------- | -------------------- | ------------------------------------------------------------------------------------------------------
**ORDER**| | |
     DOCUMENTNAME/DOCUMENTNAME|М|Число положительное|Название документа (220 —заказ)
     NUMBER/NUMBER|М|Строка (50)|Номер заказа
     DATE/DATE|М|Дата (ГГГГ-ММ-ДД)|Дата документа
     ACTION/ACTION|О|«4», «5», «27», «29»|4 — поставка изменена, 5 — замена документа, 29 — поставка принята, 27 — поставка не принята
     VERSION/VERSION|O|Число положительное|Версия заказа
     PROMO/PROMO|O|«0», «1»|Акция: 0 — нет, 1 — есть
     DELIVERYDATE/DELIVERYDATE|М|Дата (ГГГГ-ММ-ДД)|Дата поставки
     DELIVERYTIME/DELIVERYTIME|O|Время (чч:мм)|Время поставки
     SHIPMENTDATE/SHIPMENTDATE|O|Дата (ГГГГ-ММ-ДД)|Дата отгрузки6
     SHIPMENTTIME/SHIPMENTTIME|O|Время (чч:мм)|Время отгрузки
     CAMPAIGNNUMBER/CAMPAIGNNUMBER|O|Строка (70)|Номер договора на поставку
     CAMPAIGNNUMBERDATE/CAMPAIGNNUMBERDATE|O|Дата (ГГГГ-ММ-ДД)|Дата договора
     CURRENCY/CURRENCY|O|Строка (3)|Код валюты
     TRANSPORTQUANTITY/TRANSPORTQUANTITY|O|Число положительное|Количество машин
     ORDERREFERENCENUMBER5/ORDERREFERENCENUMBER| |Строка (16)|Уникальный номер заказа для отслеживания
     **LIMES**| | |Детали транспорта
          LIMESNAME/LIMESNAME|O|Строка (70)|Название рампы
          DATEFROM/DATEFROM|O|Дата (ГГГГ-ММ-ДД)|Дата прибытия транспорта
          TIMEFROM/TIMEFROM|O|Время (чч:мм)|Время прибытия транспорта
          DATETO/DATETO|O|Дата (ГГГГ-ММ-ДД)|Дата окончания отгрузки
          TIMETO/TIMETO|O|Время (чч:мм)|Время окончания отгрузки
     **/LIMES**| | |
     VAT/VAT|O|Число положительное|Ставка НДС, %
     TRANSPORTATIONTYPES/TRANSPORTATIONTYPES|O|Строка (35)|Вид транспортировки
     TRANSPORTATIONMEANS/TRANSPORTATIONMEANS|O|Строка (70)|Транспортное средство
     TRANSPORTATIONCONDITION/TRANSPORTATIONCONDITION|O|Строка (70)|Условия транспортировки
     TRANSPORTATIONPAYMENTTYPE/TRANSPORTATIONPAYMENTTYPE|O|Строка (35)|Тип оплаты доставки
     TRANSPORTATIONROUTE/TRANSPORTATIONROUTE|O|Строка (70)|Маршрут доставки
     BLANKETORDERNUMBER/BLANKETORDERNUMBER|O|Строка (35)|Номер бланкового заказа
     INFOCODED/INFOCODED|O|Строка (35)|Инфокод
     DOCTYPE/DOCTYPE|O|Строка (1)|(((



     CORRNUMBER/CORRNUMBER| | |
     SUPORDER/SUPORDER|O|Строка (35)|Номер заказа поставщика
     KDKNUM/KDKNUM|O|Строка (35)|Номер общего заказа КДК
     ORDRTYPE/ORDRTYPE|O|Строка (35)|Тип заказа
     INFO/INFO|O|Строка (70)|Свободный текст
     EARLIESTDELIVERYDATE/EARLIESTDELIVERYDATE|O|Дата (ГГГГ-ММ-ДД)|Дата не раньше
     LATESTDELIVERYDATE/LATESTDELIVERYDATE|O|Дата (ГГГГ-ММ-ДД)|Дата не позднее
     **HEAD**| | |
          SUPPLIER/SUPPLIER|M|Число (13)|GLN поставщика
          BUYER/BUYER|M|Число (13)|GLN покупателя
          BUYERCODE/BUYERCODE|O|Строка (35)|Код покупателя
          DELIVERYPLACE/DELIVERYPLACE|M|Число (13)|GLN места доставки
          FINALRECIPIENT/FINALRECIPIENT|O|Число (13)|GLN конечного консигнатора
          ORDERPARTNER/ORDERPARTNER|O|Число (13)|GLN заказчика
          INVOICEPARTNER/INVOICEPARTNER|O|Число (13)|GLN плательщика
          SENDER/SENDER|M|Число (13)|GLN отправителя сообщения
          RECIPIENT/RECIPIENT|M|Число (13)|GLN получателя сообщения
          CONSIGNEE/CONSIGNEE|О11|Число (13)|GLN грузополучателя
          RECIPIENTCODE/RECIPIENTCODE|O|Строка (35)|Код получателя
          RECIPIENTNAME/RECIPIENTNAME|O|Строка (70)|Имя получателя
          INFO/INFO|O|Строка (70)|Свободный текст
          DISCOUNTVALUE/DISCOUNTVALUE|O|Число положительное|Размер скидки
          RECIPIENTCONTACTFACE/RECIPIENTCONTACTFACE|O|Строка (70)|Контактное лицо
          RECIPIENTPHONE/RECIPIENTPHONE|O|Строка (35)|Телефон получателя
          RECIPIENTCITY/RECIPIENTCITY|O|Строка (35)|Город получателя
          RECIPIENTADRESS/RECIPIENTADRESS|O|Строка (70)|Адрес получателя
          EDIINTERCHANGEID/EDIINTERCHANGEID|O|Строка (70)|Номер транзакции
          **POSITION**| | |
               POSITIONNUMBER/POSITIONNUMBER|М|Число положительное|Номер товарной позиции
               PRODUCT/PRODUCT|M|Число (8, 10, 14)|Штрихкод продукта
               PRODUCTIDSUPPLIER/PRODUCTIDSUPPLIER|O|Строка (16)|Артикул в БД
               PRODUCTIDBUYER/PRODUCTIDBUYER|O|Строка (16)|Артикул в БД покупателя
               BUYERPARTNUMBER/BUYERPARTNUMBER|О|Строка (16)|Внутренний системный номер артикула в БД покупателя
               ORDEREDQUANTITY/ORDEREDQUANTITY|M|Число положительное|Заказанное количество
               QUANTITYOFCUINTU/QUANTITYOFCUINTU|О|Число положительное|Количество в упаковке
               ORDERUNIT/ORDERUNIT|О|Строка (3)|Единицы измерения (см. Приложение 3)ﾧ
               QUANTITYOFPACKS/QUANTITYOFPACKS|О|Число положительное|Количество упаковок
               ORDERPRICE/ORDERPRICE|O|Число десятичное|Цена продукта без НДС
               PRICEWITHVAT/PRICEWITHVAT|O|Число десятичное|Цена продукта с НДС
               AMOUNT/AMOUNT|O|Число десятичное|Сумма товара (без НДС)
               AMOUNTWITHVAT/AMOUNTWITHVAT|О|Число десятичное|Сумма товара (с НДС)
               VAT/VAT|O|Число десятичное|Ставка НДС, %
               CLAIMEDDELIVERYDATE/CLAIMEDDELIVERYDATE|O|Дата (ГГГГ-ММ-ДД)|Объявленная дата доставки
               CLAIMEDDELIVERYTIME/CLAIMEDDELIVERYTIME|O|Время (чч:мм)|Объявленное время доставки
               DELIVERYPLACE/DELIVERYPLACE|О|Число (13)|GLN конечного места доставки
               INFOCODED/INFOCODED|O|Строка (35)|Инфокод
               MINIMUMORDERQUANTITY/MINIMUMORDERQUANTITY|O|Число положительное|Минимальное заказанное количество
               MAXIMUMORDERQUANTITY /MAXIMUMORDERQUANTITY|O|Число положительное|Максимально допустимое отгрузжаемое количество
               PRODUCTIONCODE/PRODUCTIONCODE|О|Строка (16)|Код алкогольной продукции
               POSITIONKGM50/POSITIONKGM|М| |Всего килограмм по позиции
               INFO/INFO|O|Строка (90)|Свободный текст
               COMPAIGNNUMBER/COMPAIGNNUMBER|O|Строка (70)|Номер поставщика
               EARLIESTDELIVERYDATE/EARLIESTDELIVERYDATE|O|Дата (ГГГГ-ММ-ДД)|Поставка не раньше указанной даты
               LATESTDELIVERYDATE/LATESTDELIVERYDATE|O|Дата (ГГГГ-ММ-ДД)|Поставка не позднее указанной даты
               LATESTDELIVERYTIME/LATESTDELIVERYTIME|O|Время (чч:мм)|Поставка не позднее указанного времени
               CONDITIONSTATUS/CONDITIONSTATUS|О|Строка (3)|Статус кондиции (см. Приложение 2)ﾧ
               PACKAGEID/PACKAGEID|O|Число положительное|Идентификатор упаковки
               CATEGORYNAME/CATEGORYNAME|O|Строка (70)|Наименование категории товара
               BRENDNAME/BRENDNAME|O|Строка (70)|Наименование бренда
               GROUPNAMEведро 9.6кг/GROUPNAME| | |Наименование группы товара
               NOVELTY/NOVELTY|O| |Новинка
               COUNTPIECESINBOX/COUNTPIECESINBOX|O|Число положительное|Количество частей в упаковке
               COUNTBOXESINLAYER/COUNTBOXESINLAYER|O|Число положительное|Количество упаковок на уровне
               COUNTPERPALLET/COUNTPERPALLET|O|Число положительное|Количество на паллете
               WEIGHT/WEIGHT|O|Число десятичное|Вес
               PALLETS/PALLETS|O|Число положительное|Количество паллет
               COUNTRYORIGIN/COUNTRYORIGIN|О|Строка (2)|Страна производитель
               CALIBRE/CALIBRE|O|Число положительное|Диаметр
               PRICEWITHDISCOUNT/PRICEWITHDISCOUNT|O|Число десятичное|Цена с учетом скидки
               BOXESCOUNT/BOXESCOUNT|O|Число положительное|Количество упаковок
               **CHARACTERISTIC**| | |
                    DESCRIPTION/DESCRIPTION|О|Строка (70)|Описание продукта
               **/CHARACTERISTIC**| | |
               **PACKING**| | |
                    PACKINGTYPE/PACKINGTYPE|O|Строка (3)|Тип упаковки
                    PACKINGQUANTITY/PACKINGQUANTITY|O|Число положительное|Количество упаковок
                    PACKINGUNIT/PACKINGUNIT|O|Число положительное|Упаковщик
               **/PACKING**| | |
          **/POSITION**| | |
     **/HEAD**| | |
**ORDER**| | |

