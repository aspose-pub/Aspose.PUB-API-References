---
title: "System::Decimal::TryParse yöntemi"
linktitle: "TryParse"
second_title: "Aspose.PUB için C++"
description: "System::Decimal::TryParse yöntemi. Belirtilen dizeyi, içinde bir sayının dize temsilini içeren, C++'ta eşdeğer Decimal değerine dönüştürür."
type: docs
weight: 5800
url: /tr/cpp/system/decimal/tryparse/
---
## Decimal::TryParse(const String\&, Decimal\&) method


Bir sayının dize temsilini içeren belirtilen dizeyi eşdeğer [Decimal](../) değerine dönüştürür.

```cpp
static bool System::Decimal::TryParse(const String &value, Decimal &result)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | const String\& | Dönüştürülecek dize |
| result | Decimal\& | Dönüşüm sonucunun yerleştirileceği bir [Decimal](../) değişkenine referans |

### ReturnValue

Dönüşüm başarılıysa doğru, aksi takdirde - yanlış

## Ayrıca Bakınız

* Class [String](../../string/)
* Class [Decimal](../)
* Class [Decimal](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Decimal::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, Decimal\&) method


Sağlanan biçimlendirme bilgileri ve sayı stilini kullanarak bir sayının dize temsilini içeren belirtilen dizeyi eşdeğer [Decimal](../) değerine dönüştürür.

```cpp
static bool System::Decimal::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, Decimal &result)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | const String\& | Dönüştürülecek dize |
| styles | Globalization::NumberStyles | Bir sayının dize temsilinin izin verilen stilini belirten NumberStyles enum değerlerinin bit düzeyinde birleşimi |
| sağlayıcı | const SharedPtr\<IFormatProvider\>\& | Dize format bilgilerini içeren bir nesneye işaretçi |
| sonuç | Decimal\& | Bir çıktı argümanı; dönüşüm sonucunu içerir |

### ReturnValue

Dönüşüm başarılıysa doğru, aksi takdirde - yanlış

## Ayrıca Bakınız

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Decimal](../)
* Class [Decimal](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
