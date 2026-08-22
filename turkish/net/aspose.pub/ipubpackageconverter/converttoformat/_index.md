---
title: "IPubPackageConverter.ConvertToFormat"
second_title: "Aspose.PUB için .NET API Referansı"
description: "IPubPackageConverter yöntemi. inputDocumentCollection listesindeki her belgeyi belirtilen formata dönüştürür ve sonuçları uygun depolama alanına kaydeder. Kaydedilecek depolama türü outputType parametresiyle belirtilir. Dönüştürülen belgelere referanslar, döndürülen PackageDocumentCollection nesnesine yerleştirilir. mergeFiles bayrağı ayarlanmışsa, tüm dönüştürülen belgeler, inputDocumentCollection listesine yerleştirildikleri aynı sırada tek bir belgede birleştirilir."
type: docs
weight: 10
url: /tr/net/aspose.pub/ipubpackageconverter/converttoformat/
---
## IPubPackageConverter.ConvertToFormat method

Her belgeyi *inputDocumentCollection* listesinden belirtilen formata dönüştürür ve sonuçları uygun depolama alanına kaydeder. Kaydedilecek depolama türü *outputType* parametresiyle belirtilir. Dönüştürülen belgelere referanslar, döndürülen [`PackageDocumentCollection`](../../packagedocumentcollection/) nesnesine yerleştirilir. *mergeFiles* bayrağı ayarlanmışsa, tüm dönüştürülen belgeler, *inputDocumentCollection* listesine yerleştirildikleri aynı sırada tek bir belgede birleştirilir.

```csharp
public PackageDocumentCollection ConvertToFormat(PackageDocumentCollection inputDocumentCollection, 
    bool mergeFiles, PubExportFormats outputFormat, PubDocumentType outputType)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputDocumentCollection | PackageDocumentCollection | Giriş belgelerinin koleksiyonu. |
| mergeFiles | Boolean | Tüm çıktı belgelerinin tek bir belgeye birleştirilip birleştirilmeyeceğini belirtir. |
| outputFormat | PubExportFormats | Çıktı formatı. |
| outputType | PubDocumentType | Çıktı depolama türü. |

### Dönüş Değeri

Dönüştürülen belgelere referanslar, [`PackageDocumentCollection`](../../packagedocumentcollection/) nesnesinde bulunur.

### Ayrıca bakınız

* class [PackageDocumentCollection](../../packagedocumentcollection/)
* enum [PubExportFormats](../../pubexportformats/)
* enum [PubDocumentType](../../pubdocumenttype/)
* interface [IPubPackageConverter](../)
* namespace [Aspose.Pub](../../ipubpackageconverter/)
* assembly [Aspose.PUB](../../../)


