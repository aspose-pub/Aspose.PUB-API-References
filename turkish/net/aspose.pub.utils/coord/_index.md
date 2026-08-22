---
title: "Sınıf Coord"
second_title: "Aspose.PUB için .NET API Referansı"
description: "Aspose.Pub.Utils.Coord sınıfı. Bu sınıf, PUB alanlarının koordinatlarıyla ilgili verileri temsil etmek için tasarlanmıştır. PUB'daki her alan, üst‑sol köşe XLeft YTop ve alt‑sağ köşe XRight YBottom koordinat çiftlerine sahiptir. Tüm koordinatlar özel bir ölçüm sistemi olan İngiliz Metriği Birimi (EMU) ile temsil edilir. Bu sınıfa, koordinat değerlerini İngiliz metrik birimlerinden inçlere dönüştürmek için ek yöntemler eklenmiştir."
type: docs
weight: 350
url: /tr/net/aspose.pub.utils/coord/
---
## Coord class

Bu sınıf, PUB alanlarının koordinatlarıyla ilgili verileri temsil etmek üzere tasarlanmıştır. PUB'daki her alan, iki çift koordinata sahiptir: sol üst köşe koordinatları (XLeft, YTop) ve sağ alt köşe koordinatları (XRight, YBottom). Tüm koordinatlar özel bir ölçüm sisteminde - İngiliz Metriği Birimi (EMUs) - temsil edilir. Bu sınıfa, koordinat değerlerini İngiliz ölçü birimlerinden inçlere dönüştürmek için ek yöntemler eklenmiştir.

```csharp
public class Coord : ICloneable
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [Coord](coord/#constructor)() | Yapıcı |
| [Coord](coord/#constructor_1)(int, int, int, int) | Yapıcı |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [XLeft](../../aspose.pub.utils/coord/xleft/) { get; } | Üst‑sol köşenin X koordinatı (EMU cinsinden) |
| [XRight](../../aspose.pub.utils/coord/xright/) { get; } | Alt‑sağ köşenin X koordinatı (EMU cinsinden) |
| [YBottom](../../aspose.pub.utils/coord/ybottom/) { get; } | Alt‑sağ köşenin Y koordinatı (EMU cinsinden) |
| [YTop](../../aspose.pub.utils/coord/ytop/) { get; } | Üst‑sol köşenin Y koordinatı (EMU cinsinden) |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [CalculateHeight](../../aspose.pub.utils/coord/calculateheight/)() | Şeklin (geçerli Coord nesnesi) yüksekliğini hesaplar ve sonucu inç olarak döndürür |
| [CalculateWidth](../../aspose.pub.utils/coord/calculatewidth/)() | Şeklin (geçerli Coord nesnesi) genişliğini hesaplar ve sonucu inç olarak döndürür |
| [CalculateX](../../aspose.pub.utils/coord/calculatex/#calculatex)() | X‑koordinatı değerini doğal PUB metrik sisteminden inçlere dönüştürür |
| [CalculateX](../../aspose.pub.utils/coord/calculatex/#calculatex_1)(double) | X‑koordinatı değerini doğal PUB metrik sisteminden inçlere dönüştürür |
| [CalculateY](../../aspose.pub.utils/coord/calculatey/#calculatey)() | Y‑koordinatı değerini doğal PUB metrik sisteminden inçlere dönüştürür |
| [CalculateY](../../aspose.pub.utils/coord/calculatey/#calculatey_1)(double) | Y‑koordinatı değerini doğal PUB metrik sisteminden inçlere dönüştürür |
| [Clone](../../aspose.pub.utils/coord/clone/)() | Nesnenin bir kopyası oluşturuldu |
| [GetHeight](../../aspose.pub.utils/coord/getheight/)() | Mevcut Coord nesnesinin yüksekliğini doğal PUB ölçü birimlerinde döndürür |
| [GetWidth](../../aspose.pub.utils/coord/getwidth/)() | Mevcut Coord nesnesinin genişliğini doğal PUB ölçü birimlerinde döndürür |

### Ayrıca bakınız

* namespace [Aspose.Pub.Utils](../../aspose.pub.utils/)
* assembly [Aspose.PUB](../../)


