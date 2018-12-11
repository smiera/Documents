
аказ (ORDER) на поставку отправляет покупатель поставщику, указывая штрихкод продукта, его описание, заказанное количество, цену и прочую необходимую информацию.

**Название поля**|**Тип**|**Формат**|**Описание**
|------------------------------------------------------------- | ------- | -------------------- | ------------------------------------------------------------------------------------------------------
**ORDER**| | |
     DOCUMENTNAMEDOCUMENTNAME|М|Число положительное|Название документа (220 —заказ)
     NUMBERNUMBER|М|Строка (50)|Номер заказа
     DATEDATE|М|Дата (ГГГГ-ММ-ДД)|Дата документа
     ACTIONACTION|О|«4», «5», «27», «29»|4 — поставка изменена, 5 — замена документа, 29 — поставка принята, 27 — поставка не принята
     VERSIONVERSION|O|Число положительное|Версия заказа
     PROMOPROMO|O|«0», «1»|Акция: 0 — нет, 1 — есть
     DELIVERYDATEDELIVERYDATE|М|Дата (ГГГГ-ММ-ДД)|Дата поставки
     DELIVERYTIMEDELIVERYTIME|O|Время (чч:мм)|Время поставки
     SHIPMENTDATESHIPMENTDATE|O|Дата (ГГГГ-ММ-ДД)|Дата отгрузки6
     SHIPMENTTIMESHIPMENTTIME|O|Время (чч:мм)|Время отгрузки
     CAMPAIGNNUMBERCAMPAIGNNUMBER|O|Строка (70)|Номер договора на поставку
     CAMPAIGNNUMBERDATECAMPAIGNNUMBERDATE|O|Дата (ГГГГ-ММ-ДД)|Дата договора
     CURRENCYCURRENCY|O|Строка (3)|Код валюты
     TRANSPORTQUANTITYTRANSPORTQUANTITY|O|Число положительное|Количество машин
     ORDERREFERENCENUMBER5ORDERREFERENCENUMBER| |Строка (16)|Уникальный номер заказа для отслеживания
     **LIMES**| | |Детали транспорта
          LIMESNAMELIMESNAME|O|Строка (70)|Название рампы
          DATEFROMDATEFROM|O|Дата (ГГГГ-ММ-ДД)|Дата прибытия транспорта
          TIMEFROMTIMEFROM|O|Время (чч:мм)|Время прибытия транспорта
          DATETODATETO|O|Дата (ГГГГ-ММ-ДД)|Дата окончания отгрузки
          TIMETOTIMETO|O|Время (чч:мм)|Время окончания отгрузки
     **LIMES**| | |
     VATVAT|O|Число положительное|Ставка НДС, %
     TRANSPORTATIONTYPESTRANSPORTATIONTYPES|O|Строка (35)|Вид транспортировки
     TRANSPORTATIONMEANSTRANSPORTATIONMEANS|O|Строка (70)|Транспортное средство
     TRANSPORTATIONCONDITIONTRANSPORTATIONCONDITION|O|Строка (70)|Условия транспортировки
     TRANSPORTATIONPAYMENTTYPETRANSPORTATIONPAYMENTTYPE|O|Строка (35)|Тип оплаты доставки
     TRANSPORTATIONROUTETRANSPORTATIONROUTE|O|Строка (70)|Маршрут доставки
     BLANKETORDERNUMBERBLANKETORDERNUMBER|O|Строка (35)|Номер бланкового заказа
     INFOCODEDINFOCODED|O|Строка (35)|Инфокод
     DOCTYPEDOCTYPE|O|Строка (1)|(((



     CORRNUMBERCORRNUMBER| | |
     SUPORDERSUPORDER|O|Строка (35)|Номер заказа поставщика
     KDKNUMKDKNUM|O|Строка (35)|Номер общего заказа КДК
     ORDRTYPEORDRTYPE|O|Строка (35)|Тип заказа
     INFOINFO|O|Строка (70)|Свободный текст
     EARLIESTDELIVERYDATEEARLIESTDELIVERYDATE|O|Дата (ГГГГ-ММ-ДД)|Дата не раньше
     LATESTDELIVERYDATELATESTDELIVERYDATE|O|Дата (ГГГГ-ММ-ДД)|Дата не позднее
     **HEAD**| | |
          SUPPLIERSUPPLIER|M|Число (13)|GLN поставщика
          BUYERBUYER|M|Число (13)|GLN покупателя
          BUYERCODEBUYERCODE|O|Строка (35)|Код покупателя
          DELIVERYPLACEDELIVERYPLACE|M|Число (13)|GLN места доставки
          FINALRECIPIENTFINALRECIPIENT|O|Число (13)|GLN конечного консигнатора
          ORDERPARTNERORDERPARTNER|O|Число (13)|GLN заказчика
          INVOICEPARTNERINVOICEPARTNER|O|Число (13)|GLN плательщика
          SENDERSENDER|M|Число (13)|GLN отправителя сообщения
          RECIPIENTRECIPIENT|M|Число (13)|GLN получателя сообщения
          CONSIGNEECONSIGNEE|О11|Число (13)|GLN грузополучателя
          RECIPIENTCODERECIPIENTCODE|O|Строка (35)|Код получателя
          RECIPIENTNAMERECIPIENTNAME|O|Строка (70)|Имя получателя
          INFOINFO|O|Строка (70)|Свободный текст
          DISCOUNTVALUEDISCOUNTVALUE|O|Число положительное|Размер скидки
          RECIPIENTCONTACTFACERECIPIENTCONTACTFACE|O|Строка (70)|Контактное лицо
          RECIPIENTPHONERECIPIENTPHONE|O|Строка (35)|Телефон получателя
          RECIPIENTCITYRECIPIENTCITY|O|Строка (35)|Город получателя
          RECIPIENTADRESSRECIPIENTADRESS|O|Строка (70)|Адрес получателя
          EDIINTERCHANGEIDEDIINTERCHANGEID|O|Строка (70)|Номер транзакции
          **POSITION**| | |
               POSITIONNUMBERPOSITIONNUMBER|М|Число положительное|Номер товарной позиции
               PRODUCTPRODUCT|M|Число (8, 10, 14)|Штрихкод продукта
               PRODUCTIDSUPPLIERPRODUCTIDSUPPLIER|O|Строка (16)|Артикул в БД
               PRODUCTIDBUYERPRODUCTIDBUYER|O|Строка (16)|Артикул в БД покупателя
               BUYERPARTNUMBERBUYERPARTNUMBER|О|Строка (16)|Внутренний системный номер артикула в БД покупателя
               ORDEREDQUANTITYORDEREDQUANTITY|M|Число положительное|Заказанное количество
               QUANTITYOFCUINTUQUANTITYOFCUINTU|О|Число положительное|Количество в упаковке
               ORDERUNITORDERUNIT|О|Строка (3)|Единицы измерения (см. Приложение 3)ﾧ
               QUANTITYOFPACKSQUANTITYOFPACKS|О|Число положительное|Количество упаковок
               ORDERPRICEORDERPRICE|O|Число десятичное|Цена продукта без НДС
               PRICEWITHVATPRICEWITHVAT|O|Число десятичное|Цена продукта с НДС
               AMOUNTAMOUNT|O|Число десятичное|Сумма товара (без НДС)
               AMOUNTWITHVATAMOUNTWITHVAT|О|Число десятичное|Сумма товара (с НДС)
               VATVAT|O|Число десятичное|Ставка НДС, %
               CLAIMEDDELIVERYDATECLAIMEDDELIVERYDATE|O|Дата (ГГГГ-ММ-ДД)|Объявленная дата доставки
               CLAIMEDDELIVERYTIMECLAIMEDDELIVERYTIME|O|Время (чч:мм)|Объявленное время доставки
               DELIVERYPLACEDELIVERYPLACE|О|Число (13)|GLN конечного места доставки
               INFOCODEDINFOCODED|O|Строка (35)|Инфокод
               MINIMUMORDERQUANTITYMINIMUMORDERQUANTITY|O|Число положительное|Минимальное заказанное количество
               MAXIMUMORDERQUANTITY MAXIMUMORDERQUANTITY|O|Число положительное|Максимально допустимое отгрузжаемое количество
               PRODUCTIONCODEPRODUCTIONCODE|О|Строка (16)|Код алкогольной продукции
               POSITIONKGM50POSITIONKGM|М| |Всего килограмм по позиции
               INFOINFO|O|Строка (90)|Свободный текст
               COMPAIGNNUMBERCOMPAIGNNUMBER|O|Строка (70)|Номер поставщика
               EARLIESTDELIVERYDATEEARLIESTDELIVERYDATE|O|Дата (ГГГГ-ММ-ДД)|Поставка не раньше указанной даты
               LATESTDELIVERYDATELATESTDELIVERYDATE|O|Дата (ГГГГ-ММ-ДД)|Поставка не позднее указанной даты
               LATESTDELIVERYTIMELATESTDELIVERYTIME|O|Время (чч:мм)|Поставка не позднее указанного времени
               CONDITIONSTATUSCONDITIONSTATUS|О|Строка (3)|Статус кондиции (см. Приложение 2)ﾧ
               PACKAGEIDPACKAGEID|O|Число положительное|Идентификатор упаковки
               CATEGORYNAMECATEGORYNAME|O|Строка (70)|Наименование категории товара
               BRENDNAMEBRENDNAME|O|Строка (70)|Наименование бренда
               GROUPNAMEведро 9.6кгGROUPNAME| | |Наименование группы товара
               NOVELTYNOVELTY|O| |Новинка
               COUNTPIECESINBOXCOUNTPIECESINBOX|O|Число положительное|Количество частей в упаковке
               COUNTBOXESINLAYERCOUNTBOXESINLAYER|O|Число положительное|Количество упаковок на уровне
               COUNTPERPALLETCOUNTPERPALLET|O|Число положительное|Количество на паллете
               WEIGHTWEIGHT|O|Число десятичное|Вес
               PALLETSPALLETS|O|Число положительное|Количество паллет
               COUNTRYORIGINCOUNTRYORIGIN|О|Строка (2)|Страна производитель
               CALIBRECALIBRE|O|Число положительное|Диаметр
               PRICEWITHDISCOUNTPRICEWITHDISCOUNT|O|Число десятичное|Цена с учетом скидки
               BOXESCOUNTBOXESCOUNT|O|Число положительное|Количество упаковок
               **CHARACTERISTIC**| | |
                    DESCRIPTIONDESCRIPTION|О|Строка (70)|Описание продукта
               **CHARACTERISTIC**| | |
               **PACKING**| | |
                    PACKINGTYPEPACKINGTYPE|O|Строка (3)|Тип упаковки
                    PACKINGQUANTITYPACKINGQUANTITY|O|Число положительное|Количество упаковок
                    PACKINGUNITPACKINGUNIT|O|Число положительное|Упаковщик
               **PACKING**| | |
          **POSITION**| | |
     **HEAD**| | |
**ORDER**| | |

