---
title: "Aspose::Pub Namensraum"
linktitle: "Aspose::Pub"
second_title: "Aspose.PUB für C++"
description: "So verwenden Sie das Aspose::Pub Namensraum in C++."
type: docs
weight: 100
url: /de/cpp/aspose.pub/
---



## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [AssemblyConstants](./assemblyconstants/) | Definiert die Konstanten, die an der Lizenzprüfung für die Komponente teilnehmen. Diese wurden früher direkt als Assembly-Attribute definiert, aber ich habe sie in eine separate Klasse verschoben, weil ich im .NET Compact Framework nicht auf Assembly-Attribute zugreifen kann. Jetzt verwendet der Lizenzcode, wenn er für das .NET Compact Framework kompiliert wird, diese Konstanten anstelle der Assembly-Attribute. |
| [BaseStyle](./basestyle/) | Deklariert die Grundfunktionalität für PUB-Stile. |
| [BuildVersionInfo](./buildversioninfo/) | Diese Klasse liefert Informationen über den aktuellen Produkt-Build. |
| [DocSummaryInfo](./docsummaryinfo/) | [Document](./document/) Zusammenfassungsinformationen. |
| [Document](./document/) | Stellt ein PUB-Dokument dar, enthält alle Felder und relevanten Werte. |
| [Fill](./fill/) |  |
| [FolderFontSource](./folderfontsource/) | Stellt den Ordner dar, der Schriftdateien enthält. |
| [FontSource](./fontsource/) | Stellt eine Basisklasse für die Schriftquelle dar. |
| [FontSubstitution](./fontsubstitution/) | Stellt eine Klasse für eine Schriftart-Ersetzungsstrategie basierend auf dem Schriftartnamen dar. |
| [GradientFill](./gradientfill/) |  |
| [ImageFill](./imagefill/) |  |
| [IPdfConverter](./ipdfconverter/) | Deklariert die Funktionalität zum Konvertieren eines PUB-Dokuments in ein PDF-Dokument. |
| [IPubConverter](./ipubconverter/) | Deklariert die Funktionalität zum Konvertieren eines PUB-Dokuments in das angegebene Format. |
| [IPubPackageConverter](./ipubpackageconverter/) | Deklariert die Funktionalität zum Konvertieren mehrerer Publisher-Dokumente in ein angegebenes Format. |
| [IPubParser](./ipubparser/) | Deklariert die Funktionalität, die eine Publisher-Datei analysiert und ein [Document](./document/)-Objekt als Ergebnis der Analyse zurückgibt. |
| [License](./license/) | Stellt Methoden zur Lizenzierung der Komponente bereit. |
| [MetaInfo](./metainfo/) | Basisklasse für Zusammenfassungs-Info-Objekte. |
| [Metered](./metered/) | Stellt Methoden zum Festlegen des gemessenen Schlüssels bereit. |
| [MeteredBillingService](./meteredbillingservice/) | Diese interne Klasse wird verwendet, um den gemessenen Zustand des Kunden zu verwalten. |
| [MeteredCountService](./meteredcountservice/) | Diese interne Klasse wird verwendet, um die Verbrauchsdaten des Kunden zu verwalten; die Einheit ist MB. |
| [PackageDocumentCollection](./packagedocumentcollection/) | Stellt eine Sammlung von Publisher-Dokumenten für die Paketkonvertierung dar. |
| [PackageDocumentItem](./packagedocumentitem/) | Basisklasse für Publisher-Dokumentreferenzen zur Verwendung in Paketkonvertierungen. Stellt Felder zum Festlegen der Ausgabedatenquelle für das konvertierte Dokument bereit – [OutputFileName](../) für eine Datei auf dem Datenträger und [OutputStream](../) für einen Stream. Außerdem werden Konvertierungseinstellungen bereitgestellt. |
| [PackageFileItem](./packagefileitem/) | Entwickelt, um in Paketkonvertierungen ein Publisher-Dokument über eine Datei zu referenzieren. |
| [PackageStreamItem](./packagestreamitem/) | Entwickelt, um in Paketkonvertierungen ein Publisher-Dokument über einen Stream zu referenzieren. |
| [ParagraphStyle](./paragraphstyle/) | Diese Klasse beschreibt den Stil eines PUB-Absatzes. |
| [PatternFill](./patternfill/) |  |
| [PubEmbeddedFont](./pubembeddedfont/) |  |
| [PubFactory](./pubfactory/) | Fabrik für PUB-Objekte. |
| [PubPackageConverter](./pubpackageconverter/) |  |
| [PubToPdfConversionOptions](./pubtopdfconversionoptions/) | Optionen für den Export in das PDF-Format. |
| [SolidFill](./solidfill/) |  |
| [StopPoint](./stoppoint/) |  |
| [SummaryInfo](./summaryinfo/) | Zusammenfassende Informationen. |
| [TextGroup](./textgroup/) | Textgruppe. |
| [TextParagraph](./textparagraph/) | Stellt einen PUB-Textabsatz dar. |
| [TextPartDisplayParams](./textpartdisplayparams/) | Entwickelt, um Text zu halten, der für Endbenutzer angezeigt werden soll. Fälle wie das Dokument 383.pub erzeugen eine Situation, in der der Originaltext aus dem Publisher-Dokument nicht ohne Änderungen den Endbenutzern angezeigt werden kann. Im Moment reicht es aus, einfach die modifizierte Version des Originaltexts zu speichern, die sich vom Original nur in Unicode-Werten unterscheidet, aber künftig könnten Fälle auftreten, in denen die modifizierte Version nicht nur in Unicode, sondern auch in Textlänge und Ähnlichem vom Original abweicht. Wenn solche Fälle auftreten, sollte diese Klasse angepasst werden, um den neuen Anforderungen an den angezeigten Text gerecht zu werden. |
| [TextStyle](./textstyle/) | Beschreibt den PUB-Textstil. |
## Enums

| Aufzählung | Beschreibung |
| --- | --- |
| [AlignmentType](./alignmenttype/) | Ausrichtungsart. |
| [FillTypes](./filltypes/) |  |
| [LineSpacingType](./linespacingtype/) | Zeilenabstandsart. |
| [MeteredState](./meteredstate/) | Stellt mögliche gemessene Zustände dar. |
| [PubDocumentType](./pubdocumenttype/) | Stellt den Speichertyp für ein Dokument dar. |
| [PubExportFormats](./pubexportformats/) | Gibt das Format zum Exportieren eines Publisher-Dokuments an. |
| [PubFormatVersion](./pubformatversion/) |  |
| [SuperscriptType](./superscripttype/) | Hochstellungstyp. |
| [UnderlineType](./underlinetype/) | Unterstreichungsart. |
