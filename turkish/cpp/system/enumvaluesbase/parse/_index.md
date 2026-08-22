---
title: "System::EnumValuesBase::Parse yöntemi"
linktitle: "Ayrıştır"
second_title: "Aspose.PUB için C++"
description: "System::EnumValuesBase::Parse yöntemi. Belirtilen isimle C++'da belirtilen enum tipinin sabit değerini temsil eden bir nesne döndürür."
type: docs
weight: 400
url: /tr/cpp/system/enumvaluesbase/parse/
---
## EnumValuesBase::Parse method


Belirtilen ada sahip, belirtilen sayım tipinin enum sabitinin değerini temsil eden bir nesne döndürür.

```cpp
static SharedPtr<Object> System::EnumValuesBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | const TypeInfo\& | Döndürülecek enum değerinin tipini temsil eden [TypeInfo](../../typeinfo/) nesnesi |
| str | const String\& | Enum sabitinin adı |
| ignoreCase | bool | Enum sabitinin adını yorumlarken büyük/küçük harfin göz ardı edilip edilmeyeceğini belirtir. |

### ReturnValue

**str** içinde belirtilen isimli enum sabitinin değerini temsil eden bir nesne.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [TypeInfo](../../typeinfo/)
* Class [String](../../string/)
* Class [EnumValuesBase](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
