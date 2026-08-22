---
title: "System::ObjectExt sınıfı"
linktitle: "ObjectExt"
second_title: "Aspose.PUB için C++"
description: "System::ObjectExt sınıfı. Nesne olmayan C++ tipleri (dizeler, sayılar vb.) için çağrılan C# Object yöntemlerini taklit eden statik metodlar sağlar. Bu, örnek hizmeti olmayan statik bir tiptir. C++'ta hiçbir şekilde onun örneklerini oluşturmayınız."
type: docs
weight: 4900
url: /tr/cpp/system/objectext/
---
## ObjectExt class


Nesne olmayan C++ tipleri (dizeler, sayılar vb.) için çağrılan C# [Object](../object/) yöntemlerini taklit eden statik metodlar sağlar. Bu, örnek hizmeti olmayan statik bir tiptir. Herhangi bir yolla onun örneklerini oluşturmayınız.

```cpp
class ObjectExt : public System::ObjectType
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static [ArrayInitializerCast](./arrayinitializercast/)(From ...) | Dizi temel değerlerini dönüştürür (C# bunu otomatik yapar ancak C++ muhtemelen yapmaz). |
| static [Box](./box/)(const T\&) | Değer tiplerini [Object](../object/) tipine dönüştürmek için kutular. Enum tipleri için uygulanır. |
| static [Box](./box/)(const T\&) | Değer tiplerini [Object](../object/) tipine dönüştürmek için kutular. Enum olmayan tipler için uygulanır. |
| static [Box](./box/)(const T\&) | [Nullable](../nullable/) tiplerini [Object](../object/) tipine dönüştürmek için kutular. |
| static [Box](./box/)(const String\&) | Dize değerlerini kutular. |
| static [BoxEnum](./boxenum/)(T) | Enum tiplerini [Object](../object/) olarak yayılmak üzere kutular. |
| static [CastToIList](./casttoilist/)(const SmartPtr\<Object\>\&) |  |
| static [Coalesce](./coalesce/)(T0, T1) | Null olmayan tipler için '??' operatörünün çevirisinin uygulanması. |
| static [Coalesce](./coalesce/)(System::Nullable\<T0\>, T1) | Null olabilir tipler için '??' operatörünün çevirisinin uygulanması. |
| static [CoalesceInternal](./coalesceinternal/)(RT1, F) | Null olmayan tipler için '??' operatörünün çevirisinin uygulanması. RT2'nin RT1'e dönüştürülebilir olduğu durum için aşırı yükleme. |
| static [Equals](./equals/)(const T\&, const T2\&) |  |
| static [Equals](./equals/)(const T\&, const T2\&) | C++'ta herhangi bir tip için çalışan C# [Object.Equals](../object/equals/) çağrılarına alternatif. Akıllı işaretçi tipleri için aşırı yükleme. |
| static [Equals](./equals/)(T, const T2\&) | C++'ta herhangi bir tip için çalışan C# [Object.Equals](../object/equals/) çağrılarına alternatif. Yapı tipleri için aşırı yükleme. |
| static [Equals](./equals/)(const T\&, const T2\&) | C# [Object.Equals](../object/equals/) çağrıları için ikame, C++'da herhangi bir türde çalışır. Skaler türler için aşırı yükleme. |
| static [Equals](./equals/)(const char_t(&), String) | C# [Object.Equals](../object/equals/) çağrıları için ikame, C++'da herhangi bir türde çalışır. Dize karşılaştırmasıyla dize sabiti için aşırı yükleme. |
| static [Equals](./equals/)(const float\&, const float\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmaması gerekirken, iki NaN'in eşit kabul edildiği C#-style kayan nokta karşılaştırmasını taklit eder. |
| static [Equals](./equals/)(const double\&, const double\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmaması gerekirken, iki NaN'in eşit kabul edildiği C#-style kayan nokta karşılaştırmasını taklit eder. |
| static [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static [GetHashCode](./gethashcode/)(const T\&) | [GetHashCode()](./gethashcode/) çağrılarını uygular; hem [Object](../object/) alt sınıflarında hem de ilgili olmayan türlerde çalışır. |
| static [Is](./is/)(const U\&) | 'is' operatörü çevirisini uygular. 'final' sınıflar için optimize edilmiş işaretçi türleri özelleştirmesi. |
| static [Is](./is/)(const U\&) | 'is' operatörü çevirisini uygular. İşaretçi türleri için özelleştirme. |
| static [Is](./is/)(const Object\&) | 'is' operatörü çevirisini uygular. Değer türleri için özelleştirme. |
| static [Is](./is/)(const Object\&) | 'is' operatörü çevirisini uygular. Dönüştürülemez türler için özelleştirme. |
| static [Is](./is/)(const SmartPtr\<U\>\&) | 'is' operatörü çevirisini uygular. İşaretçi türleri için özelleştirme. |
| static [Is](./is/)(const ExceptionWrapper\<U\>\&) | 'is' operatörü çevirisini uygular. İstisna sarmalayıcı türleri için özelleştirme. |
| static [Is](./is/)(const SmartPtr\<Object\>\&) | 'is' operatörü çevirisini uygular. Nullable türleri için özelleştirme. |
| static [Is](./is/)(const SmartPtr\<Object\>\&) | 'is' operatörü çevirisini uygular. == operatörü tanımlı kutlanabilir türler için özelleştirme. |
| static [Is](./is/)(const SmartPtr\<Object\>\&) | 'is' operatörü çevirisini uygular. == operatörü tanımlanmamış kutlanabilir türler için özelleştirme. |
| static [Is](./is/)(const SmartPtr\<U\>\&) | 'is' operatörü çevirisini uygular. Enum türleri için özelleştirme. |
| static [Is](./is/)(const WeakPtr\<U\>\&) | 'is' operatörü çevirisini uygular. Enum türleri ve zayıf işaretçiler için özelleştirme. |
| static [Is](./is/)(const Nullable\<U\>\&) | 'is' operatörü çevirisini uygular. [Nullable](../nullable/) türü için özelleştirme. |
| static [Is](./is/)(const char16_t *) | 'is' operatörü çevirisini uygular. Dize sabiti için özelleştirme. |
| static [Is](./is/)(int32_t) | 'is' operatörü çevirisini uygular. Tam sayı sabiti için özelleştirme. |
| static [IsBoxedValue](./isboxedvalue/)(const SmartPtr\<Object\>\&) | Nesnenin kutlanmış bir değer olup olmadığını kontrol eder. |
| static [ObjectToUnknown](./objecttounknown/)(SmartPtr\<Object\>) | [Object](../object/) nesnesini bilinmeyen türe dönüştürür, hem akıllı işaretçi türünü hem de kutulanmış değer durumlarını ele alır. |
| static [ObjectToUnknown](./objecttounknown/)(SmartPtr\<Object\>) | [Object](../object/) nesnesini bilinmeyen türe dönüştürür, hem akıllı işaretçi türünü hem de kutulanmış değer durumlarını ele alır. |
| static [ToString](./tostring/)(const char_t *) | C# ToString metodunun ikamesi, herhangi bir C++ türünde çalışır. |
| static [ToString](./tostring/)(const Nullable\<T\>\&) | C# ToString metodunun ikamesi, herhangi bir C++ türünde çalışır. |
| static [ToString](./tostring/)(const T\&) | C# ToString metodunun ikamesi, herhangi bir C++ türünde çalışır. |
| static [ToString](./tostring/)(const T\&) | C# ToString metodunun ikamesi, herhangi bir C++ türünde çalışır. |
| static [ToString](./tostring/)(T\&) | C# ToString metodunun ikamesi, herhangi bir C++ türünde çalışır. |
| static [ToString](./tostring/)(T\&) | C# ToString metodunun ikamesi, herhangi bir C++ türünde çalışır. |
| static [ToString](./tostring/)(T\&&) | C# ToString metodunun ikamesi, herhangi bir C++ türünde çalışır. |
| static [ToString](./tostring/)(T\&) | C# ToString metodunun ikamesi, herhangi bir C++ türünde çalışır. |
| static [ToString](./tostring/)(const T\&) | C# ToString metodunun ikamesi, herhangi bir C++ türünde çalışır. |
| static [ToString](./tostring/)(T\&&) | C# ToString metodunun ikamesi, herhangi bir C++ türünde çalışır. |
| static [Unbox](./unbox/)(const SmartPtr\<Object\>\&) | [Object](../object/) 'a dönüştürüldükten sonra değer türlerini kutudan çıkarır. Enum türleri için uygulama. |
| static [Unbox](./unbox/)(const SmartPtr\<Object\>\&) | [Object](../object/) 'a dönüştürüldükten sonra değer türlerini kutudan çıkarır. Enum olmayan ve nullable olmayan türler için uygulama. |
| static [Unbox](./unbox/)(const SmartPtr\<Object\>\&) | [Object](../object/) 'a dönüştürüldükten sonra değer türlerini kutudan çıkarır. Enum olmayan ve nullable olmayan türler için uygulama. |
| static [Unbox](./unbox/)(E) | Enum türlerini tamsayıya kutudan çıkarır. |
| static [Unbox](./unbox/)(E) | Enum türlerini dönüştürür. |
| static [Unbox](./unbox/)(const SmartPtr\<Object\>\&) | Dize değerlerini kutudan çıkarır. |
| static [UnboxStringSafe](./unboxstringsafe/)(const SmartPtr\<Object\>\&) | Kutulanmış değerden dizeyi kutudan çıkarır. |
| static [UnboxToNullable](./unboxtonullable/)(const SmartPtr\<Object\>\&, bool) | Nesneyi null atanabilir tipe kutudan çıkarır. |
| static [UnknownIsNull](./unknownisnull/)(T) | Bilinmeyen tip nesnenin nullptr olup olmadığını kontrol eder. Skaler olmayan tipler için aşırı yükleme. |
| static [UnknownIsNull](./unknownisnull/)(T) | Bilinmeyen tip nesnenin nullptr olup olmadığını kontrol eder. Skaler tipler için aşırı yükleme. |
| static [UnknownToObject](./unknowntoobject/)(T) | Bilinmeyen tipi [Object](../object/) tipine dönüştürür, akıllı gösterici tipi ve değer tipi durumlarını her ikisini de ele alır. |
| static [UnknownToObject](./unknowntoobject/)(const T\&) | Bilinmeyen tipi [Object](../object/) tipine dönüştürür, akıllı gösterici tipi ve değer tipi durumlarını her ikisini de ele alır. |
## Ayrıca Bakınız

* Class [ObjectType](../objecttype/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
