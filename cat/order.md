# ORDER



Заказ \(ORDER\) на поставку отправляет покупатель поставщику, указывая штрихкод продукта, его описание, заказанное количество, цену и прочую необходимую информацию.

<table>
  <thead>
    <tr>
      <th style="text-align:left"><b>Название поля</b>
      </th>
      <th style="text-align:left"><b>Тип</b>
      </th>
      <th style="text-align:left"><b>Формат</b>
      </th>
      <th style="text-align:left"><b>Описание</b>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><b><ORDER></b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">
        <DOCUMENTNAME></DOCUMENTNAME>
      </td>
      <td style="text-align:left">М</td>
      <td style="text-align:left">Число положительное</td>
      <td style="text-align:left">Название документа (220 —заказ)</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <NUMBER></NUMBER>
      </td>
      <td style="text-align:left">М</td>
      <td style="text-align:left">Строка (50)</td>
      <td style="text-align:left">Номер заказа</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <DATE></DATE>
      </td>
      <td style="text-align:left">М</td>
      <td style="text-align:left">Дата (ГГГГ-ММ-ДД)</td>
      <td style="text-align:left">Дата документа</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <ACTION></ACTION>
      </td>
      <td style="text-align:left">О</td>
      <td style="text-align:left">«4», «5», «27», «29»</td>
      <td style="text-align:left">4 — поставка изменена, 5 — замена документа, 29 — поставка принята, 27
        — поставка не принята</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <VERSION></VERSION>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Число положительное</td>
      <td style="text-align:left">Версия заказа</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <PROMO></PROMO>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">«0», «1»</td>
      <td style="text-align:left">Акция: 0 — нет, 1 — есть</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <DELIVERYDATE></DELIVERYDATE>
      </td>
      <td style="text-align:left">М</td>
      <td style="text-align:left">Дата (ГГГГ-ММ-ДД)</td>
      <td style="text-align:left">Дата поставки</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <DELIVERYTIME></DELIVERYTIME>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Время (чч:мм)</td>
      <td style="text-align:left">Время поставки</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <SHIPMENTDATE></SHIPMENTDATE>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Дата (ГГГГ-ММ-ДД)</td>
      <td style="text-align:left">Дата отгрузки6</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <SHIPMENTTIME></SHIPMENTTIME>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Время (чч:мм)</td>
      <td style="text-align:left">Время отгрузки</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <CAMPAIGNNUMBER></CAMPAIGNNUMBER>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Строка (70)</td>
      <td style="text-align:left">Номер договора на поставку</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <CAMPAIGNNUMBERDATE></CAMPAIGNNUMBERDATE>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Дата (ГГГГ-ММ-ДД)</td>
      <td style="text-align:left">Дата договора</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <CURRENCY></CURRENCY>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Строка (3)</td>
      <td style="text-align:left">Код валюты</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <TRANSPORTQUANTITY></TRANSPORTQUANTITY>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Число положительное</td>
      <td style="text-align:left">Количество машин</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <ORDERREFERENCENUMBER>5</ORDERREFERENCENUMBER>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left">Строка (16)</td>
      <td style="text-align:left">Уникальный номер заказа для отслеживания</td>
    </tr>
    <tr>
      <td style="text-align:left"><b><LIMES></b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left">Детали транспорта</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <LIMESNAME></LIMESNAME>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Строка (70)</td>
      <td style="text-align:left">Название рампы</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <DATEFROM></DATEFROM>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Дата (ГГГГ-ММ-ДД)</td>
      <td style="text-align:left">Дата прибытия транспорта</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <TIMEFROM></TIMEFROM>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Время (чч:мм)</td>
      <td style="text-align:left">Время прибытия транспорта</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <DATETO></DATETO>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Дата (ГГГГ-ММ-ДД)</td>
      <td style="text-align:left">Дата окончания отгрузки</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <TIMETO></TIMETO>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Время (чч:мм)</td>
      <td style="text-align:left">Время окончания отгрузки</td>
    </tr>
    <tr>
      <td style="text-align:left"><b></LIMES></b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">
        <VAT></VAT>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Число положительное</td>
      <td style="text-align:left">Ставка НДС, %</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <TRANSPORTATIONTYPES></TRANSPORTATIONTYPES>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Строка (35)</td>
      <td style="text-align:left">Вид транспортировки</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <TRANSPORTATIONMEANS></TRANSPORTATIONMEANS>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Строка (70)</td>
      <td style="text-align:left">Транспортное средство</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <TRANSPORTATIONCONDITION></TRANSPORTATIONCONDITION>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Строка (70)</td>
      <td style="text-align:left">Условия транспортировки</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <TRANSPORTATIONPAYMENTTYPE></TRANSPORTATIONPAYMENTTYPE>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Строка (35)</td>
      <td style="text-align:left">Тип оплаты доставки</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <TRANSPORTATIONROUTE></TRANSPORTATIONROUTE>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Строка (70)</td>
      <td style="text-align:left">Маршрут доставки</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <BLANKETORDERNUMBER></BLANKETORDERNUMBER>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Строка (35)</td>
      <td style="text-align:left">Номер бланкового заказа</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <INFOCODED></INFOCODED>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Строка (35)</td>
      <td style="text-align:left">Инфокод</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <DOCTYPE></DOCTYPE>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Строка (1)</td>
      <td style="text-align:left">
        <p>Тип документа:
          <br />O — оригинал,
          <br />R — замена,
          <br />D — удаление,</p>
        <p>F — фиктивность заказа</p>
        <p>PO — предзаказ</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">
        <CORRNUMBER></CORRNUMBER>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">
        <SUPORDER></SUPORDER>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Строка (35)</td>
      <td style="text-align:left">Номер заказа поставщика</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <KDKNUM></KDKNUM>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Строка (35)</td>
      <td style="text-align:left">Номер общего заказа КДК</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <ORDRTYPE></ORDRTYPE>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Строка (35)</td>
      <td style="text-align:left">Тип заказа</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <INFO></INFO>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Строка (70)</td>
      <td style="text-align:left">Свободный текст</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <EARLIESTDELIVERYDATE></EARLIESTDELIVERYDATE>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Дата (ГГГГ-ММ-ДД)</td>
      <td style="text-align:left">Дата не раньше</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <LATESTDELIVERYDATE></LATESTDELIVERYDATE>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Дата (ГГГГ-ММ-ДД)</td>
      <td style="text-align:left">Дата не позднее</td>
    </tr>
    <tr>
      <td style="text-align:left"><b><HEAD></b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">
        <SUPPLIER></SUPPLIER>
      </td>
      <td style="text-align:left">M</td>
      <td style="text-align:left">Число (13)</td>
      <td style="text-align:left">GLN поставщика</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <BUYER></BUYER>
      </td>
      <td style="text-align:left">M</td>
      <td style="text-align:left">Число (13)</td>
      <td style="text-align:left">GLN покупателя</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <BUYERCODE></BUYERCODE>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Строка (35)</td>
      <td style="text-align:left">Код покупателя</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <DELIVERYPLACE></DELIVERYPLACE>
      </td>
      <td style="text-align:left">M</td>
      <td style="text-align:left">Число (13)</td>
      <td style="text-align:left">GLN места доставки</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <FINALRECIPIENT></FINALRECIPIENT>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Число (13)</td>
      <td style="text-align:left">GLN конечного консигнатора</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <ORDERPARTNER></ORDERPARTNER>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Число (13)</td>
      <td style="text-align:left">GLN заказчика</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <INVOICEPARTNER></INVOICEPARTNER>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Число (13)</td>
      <td style="text-align:left">GLN плательщика</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <SENDER></SENDER>
      </td>
      <td style="text-align:left">M</td>
      <td style="text-align:left">Число (13)</td>
      <td style="text-align:left">GLN отправителя сообщения</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <RECIPIENT></RECIPIENT>
      </td>
      <td style="text-align:left">M</td>
      <td style="text-align:left">Число (13)</td>
      <td style="text-align:left">GLN получателя сообщения</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <CONSIGNEE></CONSIGNEE>
      </td>
      <td style="text-align:left">О11</td>
      <td style="text-align:left">Число (13)</td>
      <td style="text-align:left">GLN грузополучателя</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <RECIPIENTCODE></RECIPIENTCODE>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Строка (35)</td>
      <td style="text-align:left">Код получателя</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <RECIPIENTNAME></RECIPIENTNAME>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Строка (70)</td>
      <td style="text-align:left">Имя получателя</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <INFO></INFO>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Строка (70)</td>
      <td style="text-align:left">Свободный текст</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <DISCOUNTVALUE></DISCOUNTVALUE>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Число положительное</td>
      <td style="text-align:left">Размер скидки</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <RECIPIENTCONTACTFACE></RECIPIENTCONTACTFACE>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Строка (70)</td>
      <td style="text-align:left">Контактное лицо</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <RECIPIENTPHONE></RECIPIENTPHONE>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Строка (35)</td>
      <td style="text-align:left">Телефон получателя</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <RECIPIENTCITY></RECIPIENTCITY>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Строка (35)</td>
      <td style="text-align:left">Город получателя</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <RECIPIENTADRESS></RECIPIENTADRESS>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Строка (70)</td>
      <td style="text-align:left">Адрес получателя</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <EDIINTERCHANGEID></EDIINTERCHANGEID>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Строка (70)</td>
      <td style="text-align:left">Номер транзакции</td>
    </tr>
    <tr>
      <td style="text-align:left"> <b><POSITION></b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">
        <POSITIONNUMBER></POSITIONNUMBER>
      </td>
      <td style="text-align:left">М</td>
      <td style="text-align:left">Число положительное</td>
      <td style="text-align:left">Номер товарной позиции</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <PRODUCT></PRODUCT>
      </td>
      <td style="text-align:left">M</td>
      <td style="text-align:left">Число (8, 10, 14)</td>
      <td style="text-align:left">Штрихкод продукта</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <PRODUCTIDSUPPLIER></PRODUCTIDSUPPLIER>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Строка (16)</td>
      <td style="text-align:left">Артикул в БД</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <PRODUCTIDBUYER></PRODUCTIDBUYER>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Строка (16)</td>
      <td style="text-align:left">Артикул в БД покупателя</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <BUYERPARTNUMBER></BUYERPARTNUMBER>
      </td>
      <td style="text-align:left">О</td>
      <td style="text-align:left">Строка (16)</td>
      <td style="text-align:left">Внутренний системный номер артикула в БД покупателя</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <ORDEREDQUANTITY></ORDEREDQUANTITY>
      </td>
      <td style="text-align:left">M</td>
      <td style="text-align:left">Число положительное</td>
      <td style="text-align:left">Заказанное количество</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <QUANTITYOFCUINTU></QUANTITYOFCUINTU>
      </td>
      <td style="text-align:left">О</td>
      <td style="text-align:left">Число положительное</td>
      <td style="text-align:left">Количество в упаковке</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <ORDERUNIT></ORDERUNIT>
      </td>
      <td style="text-align:left">О</td>
      <td style="text-align:left">Строка (3)</td>
      <td style="text-align:left">Единицы измерения (см. Приложение 3)ﾧ</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <QUANTITYOFPACKS></QUANTITYOFPACKS>
      </td>
      <td style="text-align:left">О</td>
      <td style="text-align:left">Число положительное</td>
      <td style="text-align:left">Количество упаковок</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <ORDERPRICE></ORDERPRICE>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Число десятичное</td>
      <td style="text-align:left">Цена продукта без НДС</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <PRICEWITHVAT></PRICEWITHVAT>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Число десятичное</td>
      <td style="text-align:left">Цена продукта с НДС</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <AMOUNT></AMOUNT>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Число десятичное</td>
      <td style="text-align:left">Сумма товара (без НДС)</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <AMOUNTWITHVAT></AMOUNTWITHVAT>
      </td>
      <td style="text-align:left">О</td>
      <td style="text-align:left">Число десятичное</td>
      <td style="text-align:left">Сумма товара (с НДС)</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <VAT></VAT>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Число десятичное</td>
      <td style="text-align:left">Ставка НДС, %</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <CLAIMEDDELIVERYDATE></CLAIMEDDELIVERYDATE>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Дата (ГГГГ-ММ-ДД)</td>
      <td style="text-align:left">Объявленная дата доставки</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <CLAIMEDDELIVERYTIME></CLAIMEDDELIVERYTIME>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Время (чч:мм)</td>
      <td style="text-align:left">Объявленное время доставки</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <DELIVERYPLACE></DELIVERYPLACE>
      </td>
      <td style="text-align:left">О</td>
      <td style="text-align:left">Число (13)</td>
      <td style="text-align:left">GLN конечного места доставки</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <INFOCODED></INFOCODED>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Строка (35)</td>
      <td style="text-align:left">Инфокод</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <MINIMUMORDERQUANTITY></MINIMUMORDERQUANTITY>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Число положительное</td>
      <td style="text-align:left">Минимальное заказанное количество</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <MAXIMUMORDERQUANTITY></MAXIMUMORDERQUANTITY>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Число положительное</td>
      <td style="text-align:left">Максимально допустимое отгрузжаемое количество</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <PRODUCTIONCODE></PRODUCTIONCODE>
      </td>
      <td style="text-align:left">О</td>
      <td style="text-align:left">Строка (16)</td>
      <td style="text-align:left">Код алкогольной продукции</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <POSITIONKGM>50</POSITIONKGM>
      </td>
      <td style="text-align:left">М</td>
      <td style="text-align:left"></td>
      <td style="text-align:left">Всего килограмм по позиции</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <INFO></INFO>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Строка (90)</td>
      <td style="text-align:left">Свободный текст</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <COMPAIGNNUMBER></COMPAIGNNUMBER>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Строка (70)</td>
      <td style="text-align:left">Номер поставщика</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <EARLIESTDELIVERYDATE></EARLIESTDELIVERYDATE>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Дата (ГГГГ-ММ-ДД)</td>
      <td style="text-align:left">Поставка не раньше указанной даты</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <LATESTDELIVERYDATE></LATESTDELIVERYDATE>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Дата (ГГГГ-ММ-ДД)</td>
      <td style="text-align:left">Поставка не позднее указанной даты</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <LATESTDELIVERYTIME></LATESTDELIVERYTIME>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Время (чч:мм)</td>
      <td style="text-align:left">Поставка не позднее указанного времени</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <CONDITIONSTATUS></CONDITIONSTATUS>
      </td>
      <td style="text-align:left">О</td>
      <td style="text-align:left">Строка (3)</td>
      <td style="text-align:left">Статус кондиции (см. Приложение 2)ﾧ</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <PACKAGEID></PACKAGEID>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Число положительное</td>
      <td style="text-align:left">Идентификатор упаковки</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <CATEGORYNAME></CATEGORYNAME>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Строка (70)</td>
      <td style="text-align:left">Наименование категории товара</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <BRENDNAME></BRENDNAME>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Строка (70)</td>
      <td style="text-align:left">Наименование бренда</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <GROUPNAME>ведро 9.6кг</GROUPNAME>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left">Наименование группы товара</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <NOVELTY></NOVELTY>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left"></td>
      <td style="text-align:left">Новинка</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <COUNTPIECESINBOX></COUNTPIECESINBOX>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Число положительное</td>
      <td style="text-align:left">Количество частей в упаковке</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <COUNTBOXESINLAYER></COUNTBOXESINLAYER>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Число положительное</td>
      <td style="text-align:left">Количество упаковок на уровне</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <COUNTPERPALLET></COUNTPERPALLET>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Число положительное</td>
      <td style="text-align:left">Количество на паллете</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <WEIGHT></WEIGHT>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Число десятичное</td>
      <td style="text-align:left">Вес</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <PALLETS></PALLETS>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Число положительное</td>
      <td style="text-align:left">Количество паллет</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <COUNTRYORIGIN></COUNTRYORIGIN>
      </td>
      <td style="text-align:left">О</td>
      <td style="text-align:left">Строка (2)</td>
      <td style="text-align:left">Страна производитель</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <CALIBRE></CALIBRE>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Число положительное</td>
      <td style="text-align:left">Диаметр</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <PRICEWITHDISCOUNT></PRICEWITHDISCOUNT>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Число десятичное</td>
      <td style="text-align:left">Цена с учетом скидки</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <BOXESCOUNT></BOXESCOUNT>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Число положительное</td>
      <td style="text-align:left">Количество упаковок</td>
    </tr>
    <tr>
      <td style="text-align:left"> <b><CHARACTERISTIC></b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">
        <DESCRIPTION></DESCRIPTION>
      </td>
      <td style="text-align:left">О</td>
      <td style="text-align:left">Строка (70)</td>
      <td style="text-align:left">Описание продукта</td>
    </tr>
    <tr>
      <td style="text-align:left"> <b></CHARACTERISTIC></b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left"> <b><PACKING></b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">
        <PACKINGTYPE></PACKINGTYPE>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Строка (3)</td>
      <td style="text-align:left">Тип упаковки</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <PACKINGQUANTITY></PACKINGQUANTITY>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Число положительное</td>
      <td style="text-align:left">Количество упаковок</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <PACKINGUNIT></PACKINGUNIT>
      </td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">Число положительное</td>
      <td style="text-align:left">Упаковщик</td>
    </tr>
    <tr>
      <td style="text-align:left"> <b></PACKING></b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left"> <b></POSITION></b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left"><b> </HEAD></b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left"><b><ORDER></b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
  </tbody>
</table>