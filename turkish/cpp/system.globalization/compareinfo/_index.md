---
title: "System::Globalization::CompareInfo class"
linktitle: "CompareInfo"
second_title: "Aspose.PUB için C++"
description: "System::Globalization::CompareInfo sınıfı. Kültüre duyarlı dize karşılaştırması yapar. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığıt üzerinde veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarmalayın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 400
url: /tr/cpp/system.globalization/compareinfo/
---
## CompareInfo class


Kültüre duyarlı dize karşılaştırması yapar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığıt üzerinde veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class CompareInfo : public virtual System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [Compare](./compare/)(const String\&, const String\&) const | Dizeleri karşılaştırır. Henüz uygulanmadı. |
| virtual [Compare](./compare/)(const String\&, const String\&, CompareOptions) const | Dizeleri karşılaştırır. Yalnızca Ordinal ve OrdinalIgnoreCase modları desteklenir. |
| virtual [Compare](./compare/)(const String\&, int, int, const String\&, int, int) const | Bir dizenin bir bölümünü ikinci dizenin bir bölümüyle karşılaştırır. Henüz uygulanmadı. |
| virtual [Compare](./compare/)(const String\&, int, const String\&, int, CompareOptions) const | Bir dizenin son bölümünü ikinci dizenin son bölümüyle dize karşılaştırma yöntemlerini kullanarak karşılaştırır. Henüz uygulanmadı. |
| virtual [Compare](./compare/)(const String\&, int, const String\&, int) const | Bir dizenin son bölümünü ikinci dizenin son bölümüyle karşılaştırır. Henüz uygulanmadı. |
| virtual [Compare](./compare/)(const String\&, int, int, const String\&, int, int, CompareOptions) const | Bir dizenin bir bölümünü ikinci dizenin bir bölümüyle dize karşılaştırma yöntemlerini kullanarak karşılaştırır. Henüz uygulanmadı. |
| [CompareInfo](./compareinfo/)(const CompareInfo\&) | RTTI bilgisi. |
| [Equals](./equals/)(SharedPtr\<Object\>) override |  |
| [get_LCID](./get_lcid/)() const | Karşılaştırıcıyla ilişkili kültürün LCID'sini alır. |
| virtual [get_Name](./get_name/)() const | Karşılaştırıcıyla ilişkili kültürün adını alır. |
| [get_Version](./get_version/)() const | Sıralama sürümü hakkında bilgi alır. |
| static [GetCompareInfo](./getcompareinfo/)(int, const SharedPtr\<Reflection::Assembly\>\&) | Belirtilen kültürle ilişkili [CompareInfo](./) nesnesini alır ve belirtilen derlemede dize karşılaştırma yöntemlerini kullanır. |
| static [GetCompareInfo](./getcompareinfo/)(const String\&, const SharedPtr\<Reflection::Assembly\>\&) | Belirtilen kültürle ilişkili [CompareInfo](./) nesnesini alır ve belirtilen derlemede dize karşılaştırma yöntemlerini kullanır. |
| static [GetCompareInfo](./getcompareinfo/)(int) | Belirtilen kültürle ilişkili [CompareInfo](./) nesnesini alır. |
| static [GetCompareInfo](./getcompareinfo/)(const String\&) | Belirtilen kültürle ilişkili [CompareInfo](./) nesnesini alır. |
| virtual [GetHashCode](./gethashcode/)(const String\&, CompareOptions) const | Belirtilen karşılaştırma seçeneklerine göre dize karma kodunu alır. |
| [GetHashCode](./gethashcode/)() const override | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin benzeri. Özel nesnelerin hashlenmesini sağlar. |
| virtual [GetSortKey](./getsortkey/)(const String\&, CompareOptions) const | Belirtilen dize için belirtilen karşılaştırma seçeneklerini kullanarak [SortKey](../sortkey/) nesnesini alır. |
| virtual [GetSortKey](./getsortkey/)(const String\&) const | Belirtilen dize için [SortKey](../sortkey/) nesnesini alır. |
| virtual [IndexOf](./indexof/)(const String\&, const String\&, int, int) const | Alt dizeyi arar. |
| virtual [IndexOf](./indexof/)(const String\&, const String\&, int, CompareOptions) const | Alt dizeyi arar. Yalnızca Ordinal modu desteklenir. |
| virtual [IndexOf](./indexof/)(const String\&, const String\&, int, int, CompareOptions) const | Alt dizeyi arar. Yalnızca Ordinal modu desteklenir. |
| virtual [IndexOf](./indexof/)(const String\&, char16_t, int, int, CompareOptions) const | Belirtilen karakteri arar. Yalnızca Ordinal modu desteklenir. |
| virtual [IndexOf](./indexof/)(const String\&, const String\&, int) const | Alt dizeyi arar. |
| virtual [IndexOf](./indexof/)(const String\&, char16_t) const | Belirtilen karakteri arar. |
| virtual [IndexOf](./indexof/)(const String\&, const String\&) const | Alt dizeyi arar. |
| virtual [IndexOf](./indexof/)(const String\&, char16_t, int, CompareOptions) const | Belirtilen karakteri arar. Yalnızca Ordinal modu desteklenir. |
| virtual [IndexOf](./indexof/)(const String\&, char16_t, int, int) const | Belirtilen karakteri arar. |
| virtual [IndexOf](./indexof/)(const String\&, char16_t, int) const | Belirtilen karakteri arar. |
| virtual [IndexOf](./indexof/)(const String\&, const String\&, CompareOptions) const | Alt dizeyi arar. Yalnızca Ordinal modu desteklenir. |
| virtual [IndexOf](./indexof/)(const String\&, char16_t, CompareOptions) const | Belirtilen karakteri arar. Yalnızca Ordinal modu desteklenir. |
| virtual [IsPrefix](./isprefix/)(const String\&, const String\&, CompareOptions) const | Belirtilen dizeyi, belirtilen karşılaştırma seçeneklerini kullanarak belirtilen önekle başlayıp başlamadığını denetler. |
| virtual [IsPrefix](./isprefix/)(const String\&, const String\&) const | Belirtilen dizeyi belirtilen önekle başlayıp başlamadığını denetler. |
| static [IsSortable](./issortable/)(char16_t) | Belirtilen karakterin sıralanabilir olup olmadığını denetler. |
| static [IsSortable](./issortable/)(const String\&) | Belirtilen dizenin sıralanabilir olup olmadığını denetler. |
| virtual [IsSuffix](./issuffix/)(const String\&, const String\&, CompareOptions) const | Belirtilen dizeyi, belirtilen karşılaştırma seçeneklerini kullanarak belirtilen sonek ile bitip bitmediğini denetler. |
| virtual [IsSuffix](./issuffix/)(const String\&, const String\&) const | Belirtilen dizgenin belirtilen sonek ile bitip bitmediğini denetler. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, const String\&) const | Belirtilen alt dizgenin son oluşumunu arar. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, const String\&, int, int, CompareOptions) const | Belirtilen alt dizgenin son oluşumunu belirtilen karşılaştırma seçeneklerini kullanarak arar. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, char16_t, int, int, CompareOptions) const | Belirtilen karakterin son oluşumunu belirtilen karşılaştırma seçeneklerini kullanarak arar. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, const String\&, int, int) const | Belirtilen dizgenin son oluşumunu arar. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, const String\&, int, CompareOptions) const | Belirtilen dizgenin son oluşumunu belirtilen karşılaştırma seçeneklerini kullanarak arar. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, char16_t, int, CompareOptions) const | Belirtilen karakterin son oluşumunu belirtilen karşılaştırma seçeneklerini kullanarak arar. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, const String\&, int) const | Belirtilen dizgenin son oluşumunu arar. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, char16_t, int) const | Belirtilen karakterin son oluşumunu arar. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, const String\&, CompareOptions) const | Belirtilen dizgenin son oluşumunu belirtilen karşılaştırma seçeneklerini kullanarak arar. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, char16_t, CompareOptions) const | Belirtilen karakterin son oluşumunu belirtilen karşılaştırma seçeneklerini kullanarak arar. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, char16_t) const | Belirtilen karakterin son oluşumunu arar. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, char16_t, int, int) const | Belirtilen karakterin son oluşumunu arar. |
| [operator=](./operator=/)(const CompareInfo\&) |  |
| [ToString](./tostring/)() const override | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Globalization](../)
* Library [Aspose.PUB for C++](../../)
