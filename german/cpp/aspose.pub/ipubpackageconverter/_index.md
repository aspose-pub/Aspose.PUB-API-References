---
title: "Aspose::Pub::IPubPackageConverter Klasse"
linktitle: "IPubPackageConverter"
second_title: "Aspose.PUB für C++"
description: "Aspose::Pub::IPubPackageConverter Klasse. Deklariert Funktionalität zum Konvertieren mehrerer Publisher-Dokumente in ein angegebenes Format in C++."
type: docs
weight: 1400
url: /de/cpp/aspose.pub/ipubpackageconverter/
---
## IPubPackageConverter class


Deklariert die Funktionalität zum Konvertieren mehrerer Publisher-Dokumente in ein angegebenes Format.

```cpp
class IPubPackageConverter : public virtual System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual [ConvertToFormat](./converttoformat/)(System::SharedPtr\<PackageDocumentCollection\>, bool, PubExportFormats, PubDocumentType) | Konvertiert jedes Dokument aus der *inputDocumentCollection*-Liste in das angegebene Format und speichert die Ergebnisse im entsprechenden Speicher. Der zu speichernde Speichertyp wird durch den Parameter *outputType* angegeben. Verweise auf konvertierte Dokumente werden im zurückgegebenen [PackageDocumentCollection](../packagedocumentcollection/)-Objekt abgelegt. Wenn das *mergeFiles*-Flag gesetzt ist, werden alle konvertierten Dokumente in ein einzelnes Dokument in derselben Reihenfolge zusammengeführt, in der sie in der *inputDocumentCollection*-Liste platziert wurden. |
## Siehe auch

* Class [Object](../../system/object/)
* Namespace [Aspose::Pub](../)
* Library [Aspose.PUB for C++](../../)
