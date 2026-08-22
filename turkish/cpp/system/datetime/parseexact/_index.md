---
title: "System::DateTime::ParseExact yöntemi"
linktitle: "ParseExact"
second_title: "Aspose.PUB için C++"
description: "C++ içinde System::DateTime sınıfının ParseExact yönteminin nasıl kullanılacağı"
type: docs
weight: 6700
url: /tr/cpp/system/datetime/parseexact/
---
## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles)
```

## Ayrıca Bakınız

* Class [DateTime](../)
* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles)
```

## Ayrıca Bakınız

* Class [DateTime](../)
* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) method


Belirtilen tarih ve saat değerinin dize temsilini, belirtilen biçimler, kültüre özgü biçim bilgileri ve stil kullanarak eşdeğer bir [DateTime](../) nesnesine dönüştürür. Dize temsilinin biçimi, belirtilen biçimlerden bir veya daha fazlasıyla tam olarak eşleşmelidir. Dönüştürme başarısız olursa bir istisna fırlatır.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | const String\& | Dönüştürülecek tarih ve saat değerinin dize temsili. |
| biçimler | const ArrayPtr\<String\>\& | Dize biçimlerinin dizisi. |
| provider | const SharedPtr\<IFormatProvider\>\& | Kültüre özgü biçim bilgilerini sağlayan [IFormatProvider](../../iformatprovider/) nesnesi. |
| styles | Globalization::DateTimeStyles | Enum değerlerinin bit düzeyinde birleşimi, **s** hakkında ek bilgi, **s** içinde bulunabilecek stil öğeleri hakkında bilgi veya **s**'nin bir [DateTime](../) nesnesine dönüşümü hakkında bilgi sağlar. |

### ReturnValue

Belirtilen dize tarafından temsil edilen tarih ve saat değerine eşdeğer bir tarih ve saat değerini temsil eden yeni bir [DateTime](../) sınıfı örneği.

## Ayrıca Bakınız

* Class [DateTime](../)
* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles)
```

## Ayrıca Bakınız

* Class [DateTime](../)
* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## Ayrıca Bakınız

* Class [DateTime](../)
* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## Ayrıca Bakınız

* Class [DateTime](../)
* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) method


Belirtilen biçim ve kültüre özgü biçim bilgilerini kullanarak bir tarih ve saat değerinin belirtilen dize temsilini eşdeğer [DateTime](../) nesnesine dönüştürür. Dize temsilinin biçimi, belirtilen biçimle tam olarak eşleşmelidir. Dönüştürme başarısız olursa bir istisna fırlatır.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | const String\& | Dönüştürülecek tarih ve saat değerinin dize temsili. |
| biçim | const String\& | Dize biçimi. |
| provider | const SharedPtr\<IFormatProvider\>\& | Kültüre özgü biçim bilgilerini sağlayan [IFormatProvider](../../iformatprovider/) nesnesi. |
| styles | Globalization::DateTimeStyles | Enum değerlerinin bit düzeyinde birleşimi, **s** hakkında ek bilgi, **s** içinde bulunabilecek stil öğeleri hakkında bilgi veya **s**'nin bir [DateTime](../) nesnesine dönüşümü hakkında bilgi sağlar. |

### ReturnValue

Belirtilen dize tarafından temsil edilen tarih ve saat değerine eşdeğer bir tarih ve saat değerini temsil eden yeni bir [DateTime](../) sınıfı örneği.

## Ayrıca Bakınız

* Class [DateTime](../)
* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## DateTime::ParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## Ayrıca Bakınız

* Class [DateTime](../)
* Class [String](../../string/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
