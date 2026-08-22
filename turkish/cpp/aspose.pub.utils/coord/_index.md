---
title: "Aspose::Pub::Utils::Coord sınıfı"
linktitle: "Coord"
second_title: "Aspose.PUB için C++"
description: "Aspose::Pub::Utils::Coord sınıfı. Bu sınıf, PUB alanlarının koordinatlarıyla ilgili verileri temsil etmek için tasarlanmıştır. PUB'daki her alan, iki çift koordinata sahiptir: sol üst köşe koordinatları (XLeft, YTop) ve sağ alt köşe koordinatları (XRight, YBottom). Tüm koordinatlar özel bir ölçüm sisteminde - İngiliz Ölçü Birimi (EMU) - temsil edilir. Bu sınıfa, koordinat değerlerini İngiliz ölçü birimlerinden inçlere dönüştürmek için ek yöntemler eklenmiştir."
type: docs
weight: 100
url: /tr/cpp/aspose.pub.utils/coord/
---
## Coord class


Bu sınıf, PUB alanlarının koordinatlarıyla ilgili verileri temsil etmek için tasarlanmıştır. PUB'daki her alan, iki çift koordinata sahiptir: sol üst köşe koordinatları (XLeft, YTop) ve sağ alt köşe koordinatları (XRight, YBottom). Tüm koordinatlar özel bir ölçüm sisteminde - İngiliz Metriği Birimi (EMU) olarak temsil edilir. Bu sınıfa, koordinat değerlerini İngiliz metrik birimlerinden inçlere dönüştürmek için ek yöntemler eklenmiştir.

```cpp
class Coord : public System::ICloneable
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [CalculateHeight](./calculateheight/)() | Şeklin yüksekliğini (geçerli Coord nesnesi) hesaplar ve sonucu inç olarak döndürür. |
| [CalculateWidth](./calculatewidth/)() | Şeklin genişliğini (geçerli Coord nesnesi) hesaplar ve sonucu inç olarak döndürür. |
| [CalculateX](./calculatex/)(double) | X-koordinatı değerini doğal PUB ölçüm sisteminden inçlere dönüştürür. |
| [CalculateX](./calculatex/)() | X-koordinatı değerini doğal PUB ölçüm sisteminden inçlere dönüştürür. |
| [CalculateY](./calculatey/)(double) | Y-koordinatı değerini doğal PUB ölçüm sisteminden inçlere dönüştürür. |
| [CalculateY](./calculatey/)() | Y-koordinatı değerini doğal PUB ölçüm sisteminden inçlere dönüştürür. |
| [Clone](./clone/)() override | Nesnenin bir kopyası oluşturuldu. |
| [Coord](./coord/)() | Yapıcı. |
| [Coord](./coord/)(int32_t, int32_t, int32_t, int32_t) | Yapıcı. |
| [get_XLeft](./get_xleft/)() const | Sol üst köşenin X-koordinatı EMU cinsinden. |
| [get_XRight](./get_xright/)() const | Sağ alt köşenin X-koordinatı EMU cinsinden. |
| [get_YBottom](./get_ybottom/)() const | Sağ alt köşenin Y-koordinatı EMU cinsinden. |
| [get_YTop](./get_ytop/)() const | Sol üst köşenin Y-koordinatı EMU cinsinden. |
| [GetHeight](./getheight/)() | Geçerli [Coord](./) nesnesinin yüksekliğini doğal PUB ölçü birimlerinde döndürür. |
| [GetWidth](./getwidth/)() | Geçerli [Coord](./) nesnesinin genişliğini doğal PUB ölçü birimlerinde döndürür. |
## Ayrıca Bakınız

* Class [ICloneable](../../system/icloneable/)
* Namespace [Aspose::Pub::Utils](../)
* Library [Aspose.PUB for C++](../../)
