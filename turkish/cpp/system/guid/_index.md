---
title: "System::Guid sınıfı"
linktitle: "Guid"
second_title: "Aspose.PUB için C++"
description: "System::Guid sınıfı. Küresel olarak Benzersiz Tanımlayıcıyı (GUID) temsil eder. Bu tip yığına (stack) tahsis edilmeli ve fonksiyonlara değer olarak ya da referansla geçirilmelidir. C++'ta bu tipin nesnelerini yönetmek için System::SmartPtr sınıfını asla kullanmayın."
type: docs
weight: 3000
url: /tr/cpp/system/guid/
---
## Guid class


Küresel olarak Benzersiz Tanımlayıcıyı (GUID) temsil eder. Bu tip yığına (stack) tahsis edilmeli ve fonksiyonlara değer olarak ya da referansla geçirilmelidir. Bu tipin nesnelerini yönetmek için [System::SmartPtr](../smartptr/) sınıfını asla kullanmayın.

```cpp
class Guid
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [CompareTo](./compareto/)(const Guid\&) const | Geçerli ve belirtilen nesneler tarafından temsil edilen GUID'lerin aritmetik karşılaştırmasını gerçekleştirir. |
| [Equals](./equals/)(const Guid\&) const | Geçerli ve belirtilen nesneler tarafından temsil edilen GUID'lerin eşit olup olmadığını belirler. |
| [GetHashCode](./gethashcode/)() const | Mevcut nesne için bir karma kodu döndürür. |
| [Guid](./guid/)() | Tüm sıfırlardan oluşan bir GUID'i temsil eden bir nesne oluşturur. |
| [Guid](./guid/)(const ArrayPtr\<uint8_t\>\&) | İmzasız 8-bit tamsayı değerlerinden oluşan bir dizi olarak belirtilen GUID'i temsil eden bir nesne oluşturur. |
| [Guid](./guid/)(const System::Details::ArrayView\<uint8_t\>\&) | İmzasız 8-bit tamsayı değerlerinin dizi görünümü olarak belirtilen GUID'i temsil eden bir nesne oluşturur. |
| [Guid](./guid/)(const String\&) | Bir dize olarak belirtilen GUID'i temsil eden bir nesne oluşturur. |
| [Guid](./guid/)(int32_t, int16_t, int16_t, const ArrayPtr\<uint8_t\>\&) | Belirtilen GUID bileşenlerinden bir [Guid](./) sınıf örneği oluşturur. |
| [Guid](./guid/)(int32_t, int16_t, int16_t, const System::Details::ArrayView\<uint8_t\>\&) | Belirtilen GUID bileşenlerinden bir [Guid](./) sınıf örneği oluşturur. |
| [Guid](./guid/)(int32_t, int16_t, int16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) | Belirtilen imzasız tamsayılar ve baytlardan bir [Guid](./) sınıf örneği oluşturur. |
| [Guid](./guid/)(uint32_t, uint16_t, uint16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) | Belirtilen imzasız tamsayılar ve baytlardan bir [Guid](./) sınıf örneği oluşturur. |
| [Guid](./guid/)(const Guid\&) | Belirtilen nesneyle aynı GUID'i temsil eden bir nesne oluşturur. |
| static [NewGuid](./newguid/)() | Yeni bir GUID oluşturur ve onu temsil eden bir [Guid](./) nesnesi döndürür. |
| [operator!=](./operator!=/)(const Guid\&) const | Geçerli ve belirtilen nesneler tarafından temsil edilen GUID'lerin eşit olmamasını belirler. |
| [operator=](./operator=/)(const Guid\&) | Belirtilen [Guid](./) nesnesi tarafından temsil edilen GUID değerini geçerli nesneye atar. |
| [operator==](./operator==/)(const Guid\&) const | Geçerli ve belirtilen nesneler tarafından temsil edilen GUID'lerin eşit olup olmadığını belirler. |
| static [Parse](./parse/)(const String\&) | Bir GUID'in belirtilen dize temsilini eşdeğer [Guid](./) nesnesine dönüştürür. |
| [ToByteArray](./tobytearray/)() const | Geçerli nesne tarafından temsil edilen GUID'i bayt dizisine dönüştürür. |
| [ToString](./tostring/)() const | Geçerli nesne tarafından temsil edilen GUID'i dize temsiline dönüştürür. |
| [ToString](./tostring/)(const String\&) const | Geçerli nesne tarafından temsil edilen GUID'i belirtilen dize biçimini kullanarak dize temsiline dönüştürür. |
| [ToString](./tostring/)(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const | Geçerli nesne tarafından temsil edilen GUID'i belirtilen dize biçimi ve Kültür kullanarak dize temsiline dönüştürür. |
| static [TryParse](./tryparse/)(const String\&, Guid\&) | Belirtilen dizeyi [Guid](./) nesnesine dönüştürmeye çalışır. |
| [~Guid](./~guid/)() | Yıkıcı. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [Empty](./empty/) | Değeri 0 olan bir GUID'i temsil eder. |
## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
