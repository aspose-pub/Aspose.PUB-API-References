---
title: "System::Xml::XmlTextReader::ReadContentAsBase64 metodu"
linktitle: "ReadContentAsBase64"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlTextReader::ReadContentAsBase64 metodu. İçeriği okur ve C++'da Base64 çözümlenmiş ikili baytları döndürür."
type: docs
weight: 4700
url: /tr/cpp/system.xml/xmltextreader/readcontentasbase64/
---
## XmlTextReader::ReadContentAsBase64 method


İçeriği okur ve **Base64** çözülen ikili baytları döndürür.

```cpp
int32_t System::Xml::XmlTextReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
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
