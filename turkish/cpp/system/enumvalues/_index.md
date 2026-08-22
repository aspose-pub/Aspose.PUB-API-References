---
title: "System::EnumValues sınıfı"
linktitle: "EnumValues"
second_title: "Aspose.PUB için C++"
description: "System::EnumValues sınıfı. C++'da E enum tipinin sabitleri hakkında meta bilgi sağlar."
type: docs
weight: 2300
url: /tr/cpp/system/enumvalues/
---
## EnumValues class


**E** enum tipinin sabitleri hakkında meta bilgi sağlar.

```cpp
template<typename E,class Guard>class EnumValues : public System::EnumValuesBase
```


| Parametre | Açıklama |
| --- | --- |
| E | Sayım türü |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [EnumValues](./enumvalues/)() | Bir örnek oluşturur. |
| [GetNames](./getnames/)() const override | **E** sayımının tüm adlarını içeren bir dizi döndürür. |
| static [GetNames](../enumvaluesbase/getnames/)(const TypeInfo\&) | Belirtilen bir sayımda sabitlerin adlarını içeren bir dizi alır. |
| [GetUnderlyingType](./getunderlyingtype/)() const override | Belirtilen sayımın temel tipini döndürür. |
| static [GetUnderlyingType](../enumvaluesbase/getunderlyingtype/)(const TypeInfo\&) | Belirtilen sayımın temel tipini döndürür. |
| [GetValueOf](./getvalueof/)(const String\&, bool) const override | Belirtilen ada sahip enum sabitinin kutulanmış değerini döndürür. |
| [GetValueOf](./getvalueof/)(long) const override | Belirtilen değere sahip enum sabitinin kutulanmış değerini döndürür. |
| [GetValues](./getvalues/)() const override | **E** sayımının tüm değerlerini içeren bir dizi döndürür. |
| static [GetValues](../enumvaluesbase/getvalues/)(const TypeInfo\&) | Belirtilen sayım tipinin tüm değerlerini içeren bir dizi döndürür. |
| static [Parse](../enumvaluesbase/parse/)(const TypeInfo\&, const String\&, bool) | Belirtilen ada sahip, belirtilen sayım tipinin enum sabitinin değerini temsil eden bir nesne döndürür. |
| static [ToObject](../enumvaluesbase/toobject/)(const TypeInfo\&, uint64_t) | Belirtilen 64 bit işaretsiz tam sayı değerini bir enum üyesine dönüştürür. |
| static [ToObject](../enumvaluesbase/toobject/)(const TypeInfo\&, const SharedPtr\<Object\>\&) | Belirtilen tam sayı değerine sahip nesneyi bir enum üyesine dönüştürür. |
| virtual [~EnumValues](./~enumvalues/)() | Yıkıcı. |

## Ayrıca Bakınız

* Class [EnumValuesBase](../enumvaluesbase/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
