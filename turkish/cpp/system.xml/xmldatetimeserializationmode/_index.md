---
title: "System::Xml::XmlDateTimeSerializationMode enum"
linktitle: "XmlDateTimeSerializationMode"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlDateTimeSerializationMode enum. Dize ile DateTime arasında C++'da dönüştürülürken zaman değerinin nasıl ele alınacağını belirtir."
type: docs
weight: 5800
url: /tr/cpp/system.xml/xmldatetimeserializationmode/
---
## XmlDateTimeSerializationMode enum


Dize ile [DateTime](../../system/datetime/) arasında dönüştürülürken zaman değerinin nasıl ele alınacağını belirtir.

```cpp
enum class XmlDateTimeSerializationMode
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Local | 0 | Yerel zaman olarak ele al. Eğer [DateTime](../../system/datetime/) nesnesi Koordinatlı Evrensel Zaman (UTC) temsil ediyorsa, yerel zamana dönüştürülür. |
| Utc | 1 | UTC olarak ele al. Eğer [DateTime](../../system/datetime/) nesnesi yerel zaman temsil ediyorsa, UTC'ye dönüştürülür. |
| Unspecified | 2 | Bir [DateTime](../../system/datetime/) dizeye dönüştürülüyorsa yerel zaman olarak ele al. Bir dize [DateTime](../../system/datetime/) nesnesine dönüştürülüyorsa, bir saat dilimi belirtilmişse yerel zamana dönüştür. |
| RoundtripKind | 3 | Dönüştürürken saat dilimi bilgisi korunmalıdır. |

## Ayrıca Bakınız

* Namespace [System::Xml](../)
* Library [Aspose.PUB for C++](../../)
