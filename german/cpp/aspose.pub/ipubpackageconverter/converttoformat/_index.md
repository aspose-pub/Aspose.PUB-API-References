---
title: "Aspose::Pub::IPubPackageConverter::ConvertToFormat Methode"
linktitle: "ConvertToFormat"
second_title: "Aspose.PUB für C++"
description: "Aspose::Pub::IPubPackageConverter::ConvertToFormat method. Konvertiert jedes Dokument aus der inputDocumentCollection-Liste in das angegebene Format und speichert die Ergebnisse im entsprechenden Speicher. Der zu speichernde Speichertyp wird durch den Parameter outputType angegeben. Verweise auf konvertierte Dokumente werden im zurückgegebenen PackageDocumentCollection-Objekt abgelegt. Wenn das mergeFiles-Flag gesetzt ist, werden alle konvertierten Dokumente in ein einzelnes Dokument in derselben Reihenfolge zusammengeführt, in der sie in der inputDocumentCollection-Liste platziert wurden, in C++."
type: docs
weight: 100
url: /de/cpp/aspose.pub/ipubpackageconverter/converttoformat/
---
## IPubPackageConverter::ConvertToFormat method


Konvertiert jedes Dokument aus der *inputDocumentCollection*-Liste in das angegebene Format und speichert die Ergebnisse im entsprechenden Speicher. Der zu verwendende Speichertyp wird durch den *outputType*-Parameter angegeben. Verweise auf konvertierte Dokumente werden im zurückgegebenen [PackageDocumentCollection](../../packagedocumentcollection/)-Objekt abgelegt. Wenn das *mergeFiles*-Flag gesetzt ist, werden alle konvertierten Dokumente in ein einzelnes Dokument in derselben Reihenfolge zusammengeführt, in der sie in der *inputDocumentCollection*-Liste standen.

```cpp
virtual System::SharedPtr<PackageDocumentCollection> Aspose::Pub::IPubPackageConverter::ConvertToFormat(System::SharedPtr<PackageDocumentCollection> inputDocumentCollection, bool mergeFiles, PubExportFormats outputFormat, PubDocumentType outputType)=0
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputDocumentCollection | System::SharedPtr\<PackageDocumentCollection\> | Sammlung von Eingabedokumenten. |
| mergeFiles | bool | Gibt an, ob alle Ausgabedokumente zu einem einzigen zusammengeführt werden sollen. |
| outputFormat | PubExportFormats | Ausgabeformat. |
| outputType | PubDocumentType | Ausgabetyp für Speicherung. |

### ReturnValue

Verweise auf die konvertierten Dokumente im [PackageDocumentCollection](../../packagedocumentcollection/) Objekt.



## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PackageDocumentCollection](../../packagedocumentcollection/)
* Enum [PubExportFormats](../../pubexportformats/)
* Enum [PubDocumentType](../../pubdocumenttype/)
* Class [IPubPackageConverter](../)
* Namespace [Aspose::Pub](../../)
* Library [Aspose.PUB for C++](../../../)
