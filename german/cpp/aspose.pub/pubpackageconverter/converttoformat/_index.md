---
title: "Aspose::Pub::PubPackageConverter::ConvertToFormat Methode"
linktitle: "ConvertToFormat"
second_title: "Aspose.PUB für C++"
description: "Aspose::Pub::PubPackageConverter::ConvertToFormat Methode. Konvertiert jedes Dokument aus der inputDocumentCollection‑Liste in das angegebene Format und speichert die Ergebnisse im entsprechenden Speicher. Der zu verwendende Speichertyp wird durch den Parameter outputType angegeben. Verweise auf konvertierte Dokumente werden im zurückgegebenen PackageDocumentCollection‑Objekt abgelegt. Wenn das mergeFiles‑Flag gesetzt ist, werden alle konvertierten Dokumente in ein einzelnes Dokument in derselben Reihenfolge zusammengeführt, in der sie in der inputDocumentCollection‑Liste standen, in C++."
type: docs
weight: 100
url: /de/cpp/aspose.pub/pubpackageconverter/converttoformat/
---
## PubPackageConverter::ConvertToFormat method


Konvertiert jedes Dokument aus der *inputDocumentCollection*-Liste in das angegebene Format und speichert die Ergebnisse im entsprechenden Speicher. Der zu verwendende Speichertyp wird durch den *outputType*-Parameter angegeben. Verweise auf konvertierte Dokumente werden im zurückgegebenen [PackageDocumentCollection](../../packagedocumentcollection/)-Objekt abgelegt. Wenn das *mergeFiles*-Flag gesetzt ist, werden alle konvertierten Dokumente in ein einzelnes Dokument in derselben Reihenfolge zusammengeführt, in der sie in der *inputDocumentCollection*-Liste standen.

```cpp
System::SharedPtr<PackageDocumentCollection> Aspose::Pub::PubPackageConverter::ConvertToFormat(System::SharedPtr<PackageDocumentCollection> inputDocs, bool mergeFiles, PubExportFormats outputFormat, PubDocumentType outputType) override
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
* Class [PubPackageConverter](../)
* Namespace [Aspose::Pub](../../)
* Library [Aspose.PUB for C++](../../../)
