---
title: "System::Xml::XmlTextReader::ReadElementContentAsBinHex method"
linktitle: "ReadElementContentAsBinHex"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlTextReader::ReadElementContentAsBinHex method. Elemanı okur ve BinHex içeriğini C++'ta çözer."
type: docs
weight: 5000
url: /tr/cpp/system.xml/xmltextreader/readelementcontentasbinhex/
---
## XmlTextReader::ReadElementContentAsBinHex method


Öğeyi okur ve **BinHex** içeriğini çözer.

```cpp
int32_t System::Xml::XmlTextReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
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
