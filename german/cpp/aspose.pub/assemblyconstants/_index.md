---
title: "Aspose::Pub::AssemblyConstants class"
linktitle: "AssemblyConstants"
second_title: "Aspose.PUB für C++"
description: "Aspose::Pub::AssemblyConstants class. Definiert die Konstanten, die an der Lizenzprüfung für die Komponente teilnehmen. Diese wurden früher direkt als Assembly-Attribute definiert, aber ich habe sie in eine separate Klasse verschoben, weil ich im .NET Compact Framework nicht auf Assembly-Attribute zugreifen kann. Jetzt verwendet der Lizenzcode, wenn er für das .NET Compact Framework kompiliert wird, diese Konstanten anstelle der Assembly-Attribute in C++."
type: docs
weight: 100
url: /de/cpp/aspose.pub/assemblyconstants/
---
## AssemblyConstants class


Definiert die Konstanten, die an der Lizenzprüfung für die Komponente teilnehmen. Diese wurden früher direkt als Assembly-Attribute definiert, aber ich habe sie in eine separate Klasse verschoben, weil ich im .NET Compact Framework nicht auf Assembly-Attribute zugreifen kann. Jetzt verwendet der Lizenzcode, wenn er für das .NET Compact Framework kompiliert wird, diese Konstanten anstelle der Assembly-Attribute.

```cpp
class AssemblyConstants : public System::Object
```

## Felder

| Feld | Beschreibung |
| --- | --- |
| static [Family](./family/) |  |
| static [Platform](./platform/) |  |
| static [Producer](./producer/) | Der Erzeuger der **Pdf**-Datei. |
| static [Product](./product/) | Dies wird vom Lizenzcode von **Aspose** verwendet, um zu überprüfen, ob die Lizenz für das richtige Produkt ist. |
| static [ReleaseDate](./releasedate/) | Dies wird vom Lizenzcode von **Aspose** verwendet, um das Ablaufdatum des Abonnements zu prüfen. Sie müssen dies auf das Datum setzen, an dem Sie ein Release oder einen Hotfix veröffentlichen. |
| static [Title](./title/) |  |
| static [Version](./version/) | Die Version der Assembly. |
## Siehe auch

* Class [Object](../../system/object/)
* Namespace [Aspose::Pub](../)
* Library [Aspose.PUB for C++](../../)
