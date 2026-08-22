---
title: "System::Xml::XmlValidatingReader::ReadElementContentAsBase64 yöntemi"
linktitle: "ReadElementContentAsBase64"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlValidatingReader::ReadElementContentAsBase64 yöntemi. Öğeyi okur ve C++'ta Base64 içeriğini çözer."
type: docs
weight: 4300
url: /tr/cpp/system.xml/xmlvalidatingreader/readelementcontentasbase64/
---
## XmlValidatingReader::ReadElementContentAsBase64 method


Öğeyi okur ve Base64 içeriğini çözer.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
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
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
