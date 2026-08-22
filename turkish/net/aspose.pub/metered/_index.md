---
title: "Metered sınıfı"
second_title: "Aspose.PUB için .NET API Referansı"
description: "Aspose.Pub.Metered sınıfı. Ölçülen anahtarı ayarlamak için yöntemler sağlar"
type: docs
weight: 190
url: /tr/net/aspose.pub/metered/
---
## Metered class

Ölçülen anahtarı ayarlamak için yöntemler sağlar.

```csharp
public class Metered
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [Metered](metered/)() | Bu sınıfın yeni bir örneğini başlatır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [SetMeteredKey](../../aspose.pub/metered/setmeteredkey/)(string, string) | Ölçülen genel ve özel anahtarı ayarlar |
| static [GetConsumptionCredit](../../aspose.pub/metered/getconsumptioncredit/)() | Tüketim kredisini alır |
| static [GetConsumptionQuantity](../../aspose.pub/metered/getconsumptionquantity/)() | Tüketim dosya boyutunu alır |

## Örnekler

Bu örnekte, ölçülen genel ve özel anahtarı ayarlamaya çalışılacak

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

bileşen jar dosyası:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### Ayrıca bakınız

* namespace [Aspose.Pub](../../aspose.pub/)
* assembly [Aspose.PUB](../../)


