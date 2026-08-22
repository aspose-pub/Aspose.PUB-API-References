---
title: "Класс Metered"
second_title: "Справочник API Aspose.PUB для .NET"
description: "Класс Aspose.Pub.Metered. Предоставляет методы для установки метрированного ключа"
type: docs
weight: 190
url: /ru/net/aspose.pub/metered/
---
## Metered class

Предоставляет методы для установки измеряемого ключа.

```csharp
public class Metered
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Metered](metered/)() | Инициализирует новый экземпляр этого класса. |

## Методы

| Имя | Описание |
| --- | --- |
| [SetMeteredKey](../../aspose.pub/metered/setmeteredkey/)(string, string) | Устанавливает публичный и приватный метрированный ключ |
| static [GetConsumptionCredit](../../aspose.pub/metered/getconsumptioncredit/)() | Получает кредит потребления |
| static [GetConsumptionQuantity](../../aspose.pub/metered/getconsumptionquantity/)() | Получает размер файла потребления |

## Примеры

В этом примере будет предпринята попытка установить публичный и приватный метрированный ключ

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

файл jar компонента:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### См. также

* namespace [Aspose.Pub](../../aspose.pub/)
* assembly [Aspose.PUB](../../)


