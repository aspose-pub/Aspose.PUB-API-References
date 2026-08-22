---
title: "System::Xml::XmlReader::ReadContentAsBinHex yöntemi"
linktitle: "ReadContentAsBinHex"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlReader::ReadContentAsBinHex yöntemi. İçeriği okur ve BinHex çözümlenmiş ikili baytları C++'ta döndürür."
type: docs
weight: 4100
url: /tr/cpp/system.xml/xmlreader/readcontentasbinhex/
---
## XmlReader::ReadContentAsBinHex method


İçeriği okur ve **BinHex** çözülen ikili baytları döndürür.

```cpp
virtual int32_t System::Xml::XmlReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
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
