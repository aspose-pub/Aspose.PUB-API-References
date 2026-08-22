---
title: "System::Int16::TryParse yöntemi"
linktitle: "TryParse"
second_title: "Aspose.PUB için C++"
description: "C++'ta System::Int16 sınıfının TryParse yöntemini nasıl kullanılır."
type: docs
weight: 200
url: /tr/cpp/system/int16/tryparse/
---
## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int16_t\&) method




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int16_t &result)
```

## Ayrıca Bakınız

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [Int16](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int16_t\&) method




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int16_t &result)
```

## Ayrıca Bakınız

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [Int16](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int16_t\&) method


Belirtilen sayının dize temsili içeren dizeyi, sağlanan biçimlendirme bilgileri ve sayı stili kullanılarak eşdeğer 16-bit işaretli tam sayıya dönüştürür.

```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int16_t &result)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | const String\& | Dönüştürülecek dize. |
| styles | Globalization::NumberStyles | Bir sayının dize temsilinin izin verilen stilini belirten NumberStyles enum değerlerinin bit düzeyinde bir kombinasyonu. |
| sağlayıcı | const SharedPtr\<IFormatProvider\>\& | Dize biçim bilgilerini içeren bir nesneye işaretçi. |
| sonuç | int16_t\& | Dönüşüm sonucunun konulduğu 16 bit işaretli tam sayı değişkenine referans. |

### ReturnValue

Dönüşüm başarılıysa true, aksi takdirde - false.

## Ayrıca Bakınız

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Int16](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Int16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int16_t\&) method




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int16_t &result)
```

## Ayrıca Bakınız

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Class [Int16](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Int16::TryParse(const String\&, int16_t\&) method


Belirtilen sayının dize temsili içeren dizeyi eşdeğer 16-bit işaretli tam sayıya dönüştürür.

```cpp
static bool System::Int16::TryParse(const String &value, int16_t &result)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | const String\& | Dönüştürülecek dize. |
| sonuç | int16_t\& | Dönüşüm sonucunun konulduğu 16 bit işaretli tam sayı değişkenine referans. |

### ReturnValue

Dönüşüm başarılıysa true, aksi takdirde - false.

## Ayrıca Bakınız

* Class [String](../../string/)
* Class [Int16](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
