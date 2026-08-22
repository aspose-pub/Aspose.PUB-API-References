---
title: "Aspose::Pub::IPubPackageConverter sınıfı"
linktitle: "IPubPackageConverter"
second_title: "Aspose.PUB için C++"
description: "Aspose::Pub::IPubPackageConverter sınıfı. C++'da birden fazla Publisher belgesini belirli bir formata dönüştürmek için işlevselliği bildirir."
type: docs
weight: 1400
url: /tr/cpp/aspose.pub/ipubpackageconverter/
---
## IPubPackageConverter class


Birden fazla Publisher belgesini belirtilen formata dönüştürme işlevselliğini bildirir.

```cpp
class IPubPackageConverter : public virtual System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [ConvertToFormat](./converttoformat/)(System::SharedPtr\<PackageDocumentCollection\>, bool, PubExportFormats, PubDocumentType) | Her belgeyi *inputDocumentCollection* listesinden belirtilen formata dönüştürür ve sonuçları uygun depolama alanına kaydeder. Kaydedilecek depolama türü *outputType* parametresiyle belirtilir. Dönüştürülen belgelere referanslar döndürülen [PackageDocumentCollection](../packagedocumentcollection/) nesnesine yerleştirilir. *mergeFiles* bayrağı ayarlanmışsa, tüm dönüştürülen belgeler *inputDocumentCollection* listesine yerleştirildikleri aynı sırada tek bir belgede birleştirilir. |
## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [Aspose::Pub](../)
* Library [Aspose.PUB for C++](../../)
