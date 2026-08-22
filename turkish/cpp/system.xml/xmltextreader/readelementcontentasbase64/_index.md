---
title: "System::Xml::XmlTextReader::ReadElementContentAsBase64 metodu"
linktitle: "ReadElementContentAsBase64"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlTextReader::ReadElementContentAsBase64 metodu. Öğeyi okur ve C++'da Base64 içeriğini çözer."
type: docs
weight: 4900
url: /tr/cpp/system.xml/xmltextreader/readelementcontentasbase64/
---
## XmlTextReader::ReadElementContentAsBase64 method


Öğeyi okur ve Base64 içeriğini çözer.

```cpp
int32_t System::Xml::XmlTextReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | ArrayPtr\<uint8_t\> | Sonuç metni kopyalanacak tampon. Bu değer **nullptr** olamaz. |
| indeks | int32_t | Sonucun kopyalanmaya başlanacağı tampondaki ofset. |
| sayım | int32_t | Tampona kopyalanacak maksimum bayt sayısı. Gerçek kopyalanan bayt sayısı bu yöntemden döndürülür. |

### ReturnValue

Tampona yazılan bayt sayısı.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
