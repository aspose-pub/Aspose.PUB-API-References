---
title: "Aspose::Pub::PackageDocumentItem Klasse"
linktitle: "PackageDocumentItem"
second_title: "Aspose.PUB für C++"
description: "Aspose::Pub::PackageDocumentItem Klasse. Basisklasse für Publisher-Dokumentreferenzen zur Verwendung bei Paketkonvertierungen. Stellt Felder zum Festlegen der Ausgabeverbindung für das konvertierte Dokument bereit – OutputFileName für eine Datei auf dem Datenträger und OutputStream für einen Stream. Außerdem werden Konvertierungseinstellungen in C++ bereitgestellt."
type: docs
weight: 2200
url: /de/cpp/aspose.pub/packagedocumentitem/
---
## PackageDocumentItem class


Basisklasse für Publisher-Dokumentreferenzen zur Verwendung in Paketkonvertierungen. Stellt Felder zum Festlegen der Ausgabedatenquelle für das konvertierte Dokument bereit – [OutputFileName](../) für eine Datei auf dem Datenträger und [OutputStream](../) für einen Stream. Außerdem werden Konvertierungseinstellungen bereitgestellt.

```cpp
class PackageDocumentItem : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_ConversionOptions](./get_conversionoptions/)() const | Konvertierungseinstellungen. |
| [get_OutputFileName](./get_outputfilename/)() const | Name der Ausgabedatei. Vollständiger Pfad ist erforderlich. |
| [get_OutputStream](./get_outputstream/)() const | Ausgabestream zum Speichern des Konvertierungsergebnisses. |
| [PackageDocumentItem](./packagedocumentitem/)(System::String) | Konstruktor. |
| [PackageDocumentItem](./packagedocumentitem/)(System::String, System::SharedPtr\<PubToPdfConversionOptions\>) | Konstruktor. |
| [PackageDocumentItem](./packagedocumentitem/)(System::SharedPtr\<System::IO::Stream\>) | Konstruktor. |
| [PackageDocumentItem](./packagedocumentitem/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<PubToPdfConversionOptions\>) | Konstruktor. |
| [set_ConversionOptions](./set_conversionoptions/)(System::SharedPtr\<PubToPdfConversionOptions\>) | Konvertierungseinstellungen. |
| [set_OutputFileName](./set_outputfilename/)(System::String) | Name der Ausgabedatei. Vollständiger Pfad ist erforderlich. |
| [set_OutputStream](./set_outputstream/)(System::SharedPtr\<System::IO::Stream\>) | Ausgabestream zum Speichern des Konvertierungsergebnisses. |
## Siehe auch

* Class [Object](../../system/object/)
* Namespace [Aspose::Pub](../)
* Library [Aspose.PUB for C++](../../)
