---
title: "Aspose::Pub::IPubPackageConverter::ConvertToFormat yöntemi"
linktitle: "ConvertToFormat"
second_title: "Aspose.PUB için C++"
description: "Aspose::Pub::IPubPackageConverter::ConvertToFormat yöntemi. inputDocumentCollection listesindeki her belgeyi belirtilen formata dönüştürür ve sonuçları uygun depolama alanına kaydeder. Kaydedilecek depolama türü outputType parametresiyle belirtilir. Dönüştürülen belgelere referanslar döndürülen PackageDocumentCollection nesnesine yerleştirilir. mergeFiles bayrağı ayarlanmışsa, tüm dönüştürülen belgeler C++'ta inputDocumentCollection listesine yerleştirildikleri aynı sırayla tek bir belgede birleştirilir."
type: docs
weight: 100
url: /tr/cpp/aspose.pub/ipubpackageconverter/converttoformat/
---
## IPubPackageConverter::ConvertToFormat method


Her belgeyi *inputDocumentCollection* listesinden belirtilen formata dönüştürür ve sonuçları uygun depolama alanına kaydeder. Kaydedilecek depolama türü *outputType* parametresiyle belirtilir. Dönüştürülen belgelere referanslar döndürülen [PackageDocumentCollection](../../packagedocumentcollection/) nesnesine yerleştirilir. *mergeFiles* bayrağı ayarlanmışsa, tüm dönüştürülen belgeler *inputDocumentCollection* listesine yerleştirildikleri aynı sırada tek bir belgeye birleştirilir.

```cpp
virtual System::SharedPtr<PackageDocumentCollection> Aspose::Pub::IPubPackageConverter::ConvertToFormat(System::SharedPtr<PackageDocumentCollection> inputDocumentCollection, bool mergeFiles, PubExportFormats outputFormat, PubDocumentType outputType)=0
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputDocumentCollection | System::SharedPtr\<PackageDocumentCollection\> | Girdi belgelerinin koleksiyonu. |
| mergeFiles | bool | Tüm çıktı belgelerinin tek bir belgeye birleştirilip birleştirilmeyeceğini belirtir. |
| outputFormat | PubExportFormats | Çıktı formatı. |
| outputType | PubDocumentType | Çıktı depolama türü. |

### ReturnValue

Dönüştürülen belgelere ait referanslar [PackageDocumentCollection](../../packagedocumentcollection/) nesnesinde.



## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PackageDocumentCollection](../../packagedocumentcollection/)
* Enum [PubExportFormats](../../pubexportformats/)
* Enum [PubDocumentType](../../pubdocumenttype/)
* Class [IPubPackageConverter](../)
* Namespace [Aspose::Pub](../../)
* Library [Aspose.PUB for C++](../../../)
