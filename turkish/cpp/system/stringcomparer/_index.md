---
title: "System::StringComparer sınıfı"
linktitle: "StringComparer"
second_title: "Aspose.PUB için C++"
description: "System::StringComparer sınıfı. Farklı karşılaştırma modlarını kullanarak dizeleri karşılaştırır. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek, yığına ya da new operatörüyle oluşturulmamalıdır, aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın C++'ta."
type: docs
weight: 5700
url: /tr/cpp/system/stringcomparer/
---
## StringComparer class


Farklı karşılaştırma modlarını kullanarak dizeleri karşılaştırır. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek, yığına ya da new operatörüyle oluşturulmamalıdır, aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Bu sınıfı her zaman [System::SmartPtr](../smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class StringComparer : public virtual System::Object,
                       public System::Collections::Generic::IComparer<String>,
                       public System::Collections::Generic::IEqualityComparer<String>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Compare](./compare/)(args_type, args_type) const override | Mevcut ayarları kullanarak iki dizeyi karşılaştırır. |
| static [Create](./create/)(const System::SharedPtr\<System::Globalization::CultureInfo\>\&, bool) | Kültüre özgü karşılaştırıcı oluşturur. |
| [Equals](./equals/)(String, String) const override | Mevcut ayarları kullanarak iki dize eşit mi kontrol eder. |
| static [get_CurrentCulture](./get_currentculture/)() | Mevcut kültür karşılaştırıcı tek örnek. |
| static [get_CurrentCultureIgnoreCase](./get_currentcultureignorecase/)() | Mevcut kültür büyük/küçük harf duyarsız karşılaştırıcı tek örnek. |
| static [get_InvariantCulture](./get_invariantculture/)() | Evrensel kültür karşılaştırıcı tek örnek. |
| static [get_InvariantCultureIgnoreCase](./get_invariantcultureignorecase/)() | Evrensel kültür büyük/küçük harf duyarsız karşılaştırıcı tek örnek. |
| static [get_Ordinal](./get_ordinal/)() | Sıralı karşılaştırıcı tek örnek. |
| static [get_OrdinalIgnoreCase](./get_ordinalignorecase/)() | Sıralı büyük/küçük harf duyarsız karşılaştırıcı tek örnek. |
| [GetHashCode](./gethashcode/)(String) const override | Dizenin hash kodunu alır. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [args_type](./args_type/) | RTTI bilgisi. |
## Ayrıca Bakınız

* Class [Object](../object/)
* Class [IComparer](../../system.collections.generic/icomparer/)
* Class [IEqualityComparer](../../system.collections.generic/iequalitycomparer/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
