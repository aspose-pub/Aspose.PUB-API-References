---
title: "System::Xml::ValidationType enum"
linktitle: "ValidationType"
second_title: "Aspose.PUB için C++"
description: "System::Xml::ValidationType enum. C++'de gerçekleştirilecek doğrulama türünü belirtir."
type: docs
weight: 5500
url: /tr/cpp/system.xml/validationtype/
---
## ValidationType enum


Gerçekleştirilecek doğrulama türünü belirtir.

```cpp
enum class ValidationType
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| None | 0 | Doğrulama yapılmaz ve doğrulama hataları atılmaz. Bu ayar, XML 1.0 uyumlu doğrulama yapmayan bir ayrıştırıcı oluşturur. |
| Auto | 1 | DTD veya şema bilgisi bulunursa doğrular. |
| DTD | 2 | DTD'ye göre doğrular. |
| XDR | 3 | XML-Data Reduced (XDR) şemalarına, satır içi XDR şemaları dahil, göre doğrula. XDR şemaları **x-schema** ad alanı öneki veya [XmlValidatingReader::get_Schemas](../xmlvalidatingreader/get_schemas/) değeri kullanılarak tanınır. |
| Schema | 4 | XML [Schema](../../system.xml.schema/) tanım dili (XSD) şemalarına, satır içi XML Şemaları dahil, göre doğrula. XML Şemaları, **schemaLocation** özniteliği kullanılarak veya sağlanan **Schemas** ile ad alanı URI'lerine ilişkilendirilir. |

## Ayrıca Bakınız

* Namespace [System::Xml](../)
* Library [Aspose.PUB for C++](../../)
