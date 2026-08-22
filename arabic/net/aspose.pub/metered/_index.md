---
title: "فئة Metered"
second_title: "Aspose.PUB لـ .NET مرجع API"
description: "فئة Aspose.Pub.Metered. توفر طرقًا لتعيين المفتاح القابل للقياس"
type: docs
weight: 190
url: /ar/net/aspose.pub/metered/
---
## Metered class

يوفر طرقًا لتعيين المفتاح المقيس.

```csharp
public class Metered
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Metered](metered/)() | يُنشئ نسخة جديدة من هذه الفئة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [SetMeteredKey](../../aspose.pub/metered/setmeteredkey/)(string, string) | يضبط المفتاح العام والخاص القابل للقياس |
| static [GetConsumptionCredit](../../aspose.pub/metered/getconsumptioncredit/)() | يحصل على رصيد الاستهلاك |
| static [GetConsumptionQuantity](../../aspose.pub/metered/getconsumptionquantity/)() | يحصل على حجم ملف الاستهلاك |

## أمثلة

في هذا المثال، سيتم محاولة تعيين المفتاح العام والخاص القابل للقياس

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

ملف jar المكوّن:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### انظر أيضًا

* namespace [Aspose.Pub](../../aspose.pub/)
* assembly [Aspose.PUB](../../)


