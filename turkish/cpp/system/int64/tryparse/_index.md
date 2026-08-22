---
title: "System::Int64::TryParse yöntemi"
linktitle: "TryParse"
second_title: "Aspose.PUB için C++"
description: "C++'ta System::Int64 sınıfının TryParse yöntemini nasıl kullanılır."
type: docs
weight: 200
url: /tr/cpp/system/int64/tryparse/
---
## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int64_t\&) method




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int64_t &result)
```

## Ayrıca Bakınız

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [Int64](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int64_t\&) method




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int64_t &result)
```

## Ayrıca Bakınız

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [Int64](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int64_t\&) method


Belirtilen sayının dize temsili içeren dizeyi, sağlanan biçimlendirme bilgileri ve sayı stili kullanarak eşdeğer 64-bit işaretli tam sayıya dönüştürür.

```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int64_t &result)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | const String\& | Dönüştürülecek dize. |
| styles | Globalization::NumberStyles | Bir sayının dize temsilinin izin verilen stilini belirten NumberStyles enum değerlerinin bit düzeyinde bir kombinasyonu. |
| sağlayıcı | const SharedPtr\<IFormatProvider\>\& | Dize biçim bilgilerini içeren bir nesneye işaretçi. |
| sonuç | int64_t\& | Dönüşüm sonucunun yerleştirildiği 64 bit işaretli tam sayı değişkenine referans. |

### ReturnValue

Dönüşüm başarılıysa true, aksi takdirde - false.

## Ayrıca Bakınız

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Int64](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Int64::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int64_t\&) method




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int64_t &result)
```

## Ayrıca Bakınız

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Class [Int64](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Int64::TryParse(const String\&, int64_t\&) method


Belirtilen sayının dize temsili içeren dizeyi eşdeğer 64-bit işaretli tam sayıya dönüştürür.

```cpp
static bool System::Int64::TryParse(const String &value, int64_t &result)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | const String\& | Dönüştürülecek dize. |
| sonuç | int64_t\& | Dönüşüm sonucunun yerleştirildiği 64 bit işaretli tam sayı değişkenine referans. |

### ReturnValue

Dönüşüm başarılıysa true, aksi takdirde - false.

## Ayrıca Bakınız

* Class [String](../../string/)
* Class [Int64](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
