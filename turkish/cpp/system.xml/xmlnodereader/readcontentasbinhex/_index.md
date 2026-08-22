---
title: "System::Xml::XmlNodeReader::ReadContentAsBinHex yöntemi"
linktitle: "ReadContentAsBinHex"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlNodeReader::ReadContentAsBinHex yöntemi. C++'da içeriği okur ve BinHex çözülen ikili baytları döndürür."
type: docs
weight: 3300
url: /tr/cpp/system.xml/xmlnodereader/readcontentasbinhex/
---
## XmlNodeReader::ReadContentAsBinHex method


İçeriği okur ve BinHex ile çözülen ikili baytları döndürür.

```cpp
int32_t System::Xml::XmlNodeReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
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
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
