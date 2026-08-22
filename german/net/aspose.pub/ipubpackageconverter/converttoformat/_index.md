---
title: "IPubPackageConverter.ConvertToFormat"
second_title: "Aspose.PUB für .NET API-Referenz"
description: "IPubPackageConverter-Methode. Konvertiert jedes Dokument aus der inputDocumentCollection-Liste in das angegebene Format und speichert die Ergebnisse im entsprechenden Speicher. Der zu verwendende Speichertyp wird durch den Parameter outputType angegeben. Verweise auf die konvertierten Dokumente werden im zurückgegebenen PackageDocumentCollection-Objekt abgelegt. Ist das mergeFiles-Flag gesetzt, werden alle konvertierten Dokumente zu einem einzigen Dokument in derselben Reihenfolge zusammengeführt, in der sie in der inputDocumentCollection-Liste standen."
type: docs
weight: 10
url: /de/net/aspose.pub/ipubpackageconverter/converttoformat/
---
## IPubPackageConverter.ConvertToFormat method

Konvertiert jedes Dokument aus der *inputDocumentCollection*-Liste in das angegebene Format und speichert die Ergebnisse im entsprechenden Speicher. Der zu verwendende Speichertyp wird durch den *outputType*-Parameter angegeben. Verweise auf die konvertierten Dokumente werden im zurückgegebenen [`PackageDocumentCollection`](../../packagedocumentcollection/)-Objekt abgelegt. Ist das *mergeFiles*-Flag gesetzt, werden alle konvertierten Dokumente zu einem einzigen Dokument in derselben Reihenfolge zusammengeführt, in der sie in der *inputDocumentCollection*-Liste standen.

```csharp
public PackageDocumentCollection ConvertToFormat(PackageDocumentCollection inputDocumentCollection, 
    bool mergeFiles, PubExportFormats outputFormat, PubDocumentType outputType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputDocumentCollection | PackageDocumentCollection | Sammlung von Eingabedokumenten. |
| mergeFiles | Boolean | Gibt an, ob alle Ausgabedokumente zu einem einzigen zusammengeführt werden sollen. |
| outputFormat | PubExportFormats | Ausgabeformat. |
| outputType | PubDocumentType | Speichertyp für die Ausgabe. |

### Rückgabewert

Verweise auf die konvertierten Dokumente im [`PackageDocumentCollection`](../../packagedocumentcollection/)-Objekt.

### Siehe auch

* class [PackageDocumentCollection](../../packagedocumentcollection/)
* enum [PubExportFormats](../../pubexportformats/)
* enum [PubDocumentType](../../pubdocumenttype/)
* interface [IPubPackageConverter](../)
* namespace [Aspose.Pub](../../ipubpackageconverter/)
* assembly [Aspose.PUB](../../../)


