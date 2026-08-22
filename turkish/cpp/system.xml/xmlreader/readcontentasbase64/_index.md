---
title: "System::Xml::XmlReader::ReadContentAsBase64 yöntemi"
linktitle: "ReadContentAsBase64"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlReader::ReadContentAsBase64 yöntemi. İçeriği okur ve Base64 çözümlenmiş ikili baytları C++'ta döndürür."
type: docs
weight: 4000
url: /tr/cpp/system.xml/xmlreader/readcontentasbase64/
---
## XmlReader::ReadContentAsBase64 method


İçeriği okur ve Base64 ile çözülen ikili baytları döndürür.

```cpp
virtual int32_t System::Xml::XmlReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
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
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
