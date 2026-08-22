---
title: "System::ICustomFormatter::Format yöntemi"
linktitle: "Biçim"
second_title: "Aspose.PUB için C++"
description: "System::ICustomFormatter::Format yöntemi. C++'ta belirtilen biçimi kullanarak geçerli nesne tarafından temsil edilen bir değerin dizge temsili döndürür."
type: docs
weight: 100
url: /tr/cpp/system/icustomformatter/format/
---
## ICustomFormatter::Format method


Geçerli nesne tarafından temsil edilen bir değerin belirtilen biçimi kullanılarak dize temsili döndürür.

```cpp
virtual System::String System::ICustomFormatter::Format(System::String format, System::SharedPtr<System::Object> arg, System::SharedPtr<System::IFormatProvider> formatProvider)=0
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| biçim | System::String | Dize biçimi |
| arg | System::SharedPtr\<System::Object\> | Biçimlendirilecek nesne |
| formatProvider | System::SharedPtr\<System::IFormatProvider\> | Biçimlendirme bilgilerini sağlayan nesne |

### ReturnValue

**arg**'in, **format** ve **formatProvider** tarafından belirtilen biçime göre biçimlendirilmiş dizge temsili

## Ayrıca Bakınız

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [ICustomFormatter](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
