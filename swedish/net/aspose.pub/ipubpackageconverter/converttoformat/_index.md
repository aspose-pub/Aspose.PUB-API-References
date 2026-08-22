---
title: "IPubPackageConverter.ConvertToFormat"
second_title: "Aspose.PUB för .NET API-referens"
description: "IPubPackageConverter‑metod. Konverterar varje dokument från listan inputDocumentCollection till det angivna formatet och sparar resultaten i lämplig lagring. Typ av lagring som ska sparas anges av parametern outputType. Referenser till konverterade dokument placeras i det returnerade PackageDocumentCollection‑objektet. Om flaggan mergeFiles är satt kommer alla konverterade dokument att slås samman till ett enda dokument i samma ordning som de placerades i listan inputDocumentCollection."
type: docs
weight: 10
url: /sv/net/aspose.pub/ipubpackageconverter/converttoformat/
---
## IPubPackageConverter.ConvertToFormat method

Konverterar varje dokument från listan *inputDocumentCollection* till det angivna formatet och sparar resultaten i lämplig lagring. Typ av lagring som ska sparas anges av parametern *outputType*. Referenser till konverterade dokument placeras i det returnerade [`PackageDocumentCollection`](../../packagedocumentcollection/)‑objektet. Om flaggan *mergeFiles* är satt kommer alla konverterade dokument att slås samman till ett enda dokument i samma ordning som de placerades i listan *inputDocumentCollection*.

```csharp
public PackageDocumentCollection ConvertToFormat(PackageDocumentCollection inputDocumentCollection, 
    bool mergeFiles, PubExportFormats outputFormat, PubDocumentType outputType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputDocumentCollection | PackageDocumentCollection | Samling av inmatningsdokument. |
| mergeFiles | Boolean | Anger om alla utdatafiler ska slås samman till en enda. |
| outputFormat | PubExportFormats | Utdataformat. |
| outputType | PubDocumentType | Typ av lagring för utdata. |

### Returvärde

Referenser till de konverterade dokumenten i [`PackageDocumentCollection`](../../packagedocumentcollection/)‑objektet.

### Se även

* class [PackageDocumentCollection](../../packagedocumentcollection/)
* enum [PubExportFormats](../../pubexportformats/)
* enum [PubDocumentType](../../pubdocumenttype/)
* interface [IPubPackageConverter](../)
* namespace [Aspose.Pub](../../ipubpackageconverter/)
* assembly [Aspose.PUB](../../../)


