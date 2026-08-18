---
title: "Aspose::Pub::PubPackageConverter Klasse"
linktitle: "PubPackageConverter"
second_title: "Aspose.PUB für C++"
description: "Wie man die Aspose::Pub::PubPackageConverter Klasse in C++ verwendet."
type: docs
weight: 2900
url: /de/cpp/aspose.pub/pubpackageconverter/
---
## PubPackageConverter class




```cpp
class PubPackageConverter : public Aspose::Pub::IPubPackageConverter
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [ConvertToFormat](./converttoformat/)(System::SharedPtr\<PackageDocumentCollection\>, bool, PubExportFormats, PubDocumentType) override | Konvertiert jedes Dokument aus der *inputDocumentCollection*-Liste in das angegebene Format und speichert die Ergebnisse im entsprechenden Speicher. Der zu speichernde Speichertyp wird durch den Parameter *outputType* angegeben. Verweise auf konvertierte Dokumente werden im zurückgegebenen [PackageDocumentCollection](../packagedocumentcollection/)-Objekt abgelegt. Wenn das *mergeFiles*-Flag gesetzt ist, werden alle konvertierten Dokumente in ein einzelnes Dokument in derselben Reihenfolge zusammengeführt, in der sie in der *inputDocumentCollection*-Liste platziert wurden. |
## Siehe auch

* Class [IPubPackageConverter](../ipubpackageconverter/)
* Namespace [Aspose::Pub](../)
* Library [Aspose.PUB for C++](../../)
