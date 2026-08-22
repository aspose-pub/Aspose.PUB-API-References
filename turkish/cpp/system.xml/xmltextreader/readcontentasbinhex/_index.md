---
title: "System::Xml::XmlTextReader::ReadContentAsBinHex yöntemi"
linktitle: "ReadContentAsBinHex"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlTextReader::ReadContentAsBinHex yöntemi. İçeriği okur ve C++'ta BinHex çözümlenmiş ikili baytları döndürür."
type: docs
weight: 4800
url: /tr/cpp/system.xml/xmltextreader/readcontentasbinhex/
---
## XmlTextReader::ReadContentAsBinHex method


İçeriği okur ve **BinHex** çözülen ikili baytları döndürür.

```cpp
int32_t System::Xml::XmlTextReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
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
