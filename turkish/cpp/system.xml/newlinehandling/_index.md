---
title: "System::Xml::NewLineHandling enum'ı"
linktitle: "NewLineHandling"
second_title: "Aspose.PUB için C++"
description: "System::Xml::NewLineHandling enum'ı. C++'da satır sonlarının nasıl işleneceğini belirtir."
type: docs
weight: 5200
url: /tr/cpp/system.xml/newlinehandling/
---
## NewLineHandling enum


Satır sonlarının nasıl işleneceğini belirtir.

```cpp
enum class NewLineHandling
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Replace | 0 | Satır sonu karakterleri, [XmlWriterSettings::set_NewLineChars](../xmlwritersettings/set_newlinechars/) değerinde belirtilen karakterle eşleşecek şekilde değiştirilir. |
| Entitize | 1 | Satır sonu karakterleri varlık (entity) haline getirilir. Bu ayar, çıktı normalleştiren bir [XmlReader](../xmlreader/) tarafından okunduğunda tüm karakterleri korur. |
| None | 2 | Satır sonu karakterleri değişmeden kalır. Çıktı, girdiye aynı olur. |

## Ayrıca Bakınız

* Namespace [System::Xml](../)
* Library [Aspose.PUB for C++](../../)
