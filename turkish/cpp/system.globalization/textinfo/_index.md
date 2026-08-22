---
title: "System::Globalization::TextInfo sınıfı"
linktitle: "TextInfo"
second_title: "Aspose.PUB için C++"
description: "System::Globalization::TextInfo sınıfı. Yerel ayara özgü metin özelliklerini tanımlar. Ayarlayıcı işlemler yalnızca yalnızca okunamayan (read-only) olmayan nesnelerde etkinleştirilir. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek, yığına (stack) ya da operator new ile oluşturulmamalıdır; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Bu sınıf her zaman System::SmartPtr işaretçisine sarılmalı ve bu işaretçi C++'de fonksiyonlara argüman olarak geçirilmelidir."
type: docs
weight: 2800
url: /tr/cpp/system.globalization/textinfo/
---
## TextInfo class


Yerel ayara özgü metin özelliklerini tanımlar. Ayarlayıcı işlemler yalnızca yalnızca okunamayan olmayan nesnelerde etkinleştirilir. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek, yığına (stack) ya da operator new ile oluşturulmamalıdır; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Bu sınıf her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarılmalı ve bu işaretçi fonksiyonlara argüman olarak geçirilmelidir.

```cpp
class TextInfo : public System::ICloneable
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Clone](./clone/)() override | RTTI bilgisi. |
| [Equals](./equals/)(SharedPtr\<Object\>) override |  |
| virtual [get_ANSICodePage](./get_ansicodepage/)() const | ANSI kod sayfasını alır. |
| [get_CultureName](./get_culturename/)() const | Kültür adını alır. |
| virtual [get_EBCDICCodePage](./get_ebcdiccodepage/)() const | EBCDIC kod sayfasını alır. |
| [get_IsReadOnly](./get_isreadonly/)() const | Biçimin yalnızca okunabilir olup olmadığını kontrol eder. |
| [get_IsRightToLeft](./get_isrighttoleft/)() const | Metnin soldan sağa yazılıp yazılmadığını kontrol eder. |
| [get_LCID](./get_lcid/)() const | Yerel kimliğini (locale ID) alır. |
| virtual [get_ListSeparator](./get_listseparator/)() const | Liste ayırıcıyı alır. |
| virtual [get_MacCodePage](./get_maccodepage/)() const | Macintosh kod sayfasını alır. |
| virtual [get_OEMCodePage](./get_oemcodepage/)() const | OEM kod sayfasını alır. |
| [GetHashCode](./gethashcode/)() const override | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin benzeri. Özel nesnelerin hashlenmesini sağlar. |
| [operator=](./operator=/)(const TextInfo\&) |  |
| static [ReadOnly](./readonly/)(const TextInfoPtr\&) | Kültürün yalnızca okunabilir bir sürümünü alır. |
| virtual [set_ListSeparator](./set_listseparator/)(String) | Liste ayıracını ayarlar. |
| [TextInfo](./textinfo/)(const TextInfo\&) | RTTI bilgisi. |
| virtual [ToLower](./tolower/)(char_t) const | Karakteri küçük harfe dönüştürür. |
| virtual [ToLower](./tolower/)(String) const | Dizgiyi küçük harfe dönüştürür. |
| [ToString](./tostring/)() const override | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| [ToTitleCase](./totitlecase/)(String) const | Dizgiyi başlık biçimine dönüştürür (zaten büyük harfle olan kısaltmalar hariç). |
| virtual [ToUpper](./toupper/)(char_t) const | Karakteri büyük harfe dönüştürür. |
| virtual [ToUpper](./toupper/)(String) const | Dizgiyi büyük harfe dönüştürür. |
## Ayrıca Bakınız

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Globalization](../)
* Library [Aspose.PUB for C++](../../)
