---
title: "Gränssnitt IPubPackageConverter"
second_title: "Aspose.PUB för .NET API-referens"
description: "Aspose.Pub.IPubPackageConverter-gränssnitt. Deklarerar funktionalitet för att konvertera flera Publisher-dokument till ett angivet format"
type: docs
weight: 140
url: /sv/net/aspose.pub/ipubpackageconverter/
---
## IPubPackageConverter interface

Deklarerar funktionalitet för att konvertera flera Publisher-dokument till ett angivet format.

```csharp
public interface IPubPackageConverter
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [ConvertToFormat](../../aspose.pub/ipubpackageconverter/converttoformat/)(PackageDocumentCollection, bool, PubExportFormats, PubDocumentType) | Konverterar varje dokument från listan *inputDocumentCollection* till det angivna formatet och sparar resultaten i lämplig lagring. Typ av lagring att spara anges av parametern *outputType*. Referenser till konverterade dokument placeras i det returnerade [`PackageDocumentCollection`](../packagedocumentcollection/)‑objektet. Om flaggan *mergeFiles* är satt, kommer alla konverterade dokument att slås samman till ett enda dokument i samma ordning som de placerades i listan *inputDocumentCollection*. |

### Se även

* namespace [Aspose.Pub](../../aspose.pub/)
* assembly [Aspose.PUB](../../)


