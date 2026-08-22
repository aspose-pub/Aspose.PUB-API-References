---
title: "System::Xml::XmlValidatingReader::ReadContentAsBinHex metodu"
linktitle: "ReadContentAsBinHex"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlValidatingReader::ReadContentAsBinHex metodu. İçeriği okur ve BinHex çözümlenmiş ikili baytları C++'da döndürür."
type: docs
weight: 4200
url: /tr/cpp/system.xml/xmlvalidatingreader/readcontentasbinhex/
---
## XmlValidatingReader::ReadContentAsBinHex method


İçeriği okur ve BinHex ile çözülen ikili baytları döndürür.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
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
