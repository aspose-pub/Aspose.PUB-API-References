---
title: "System::IO::FileInfo::Replace-Methode"
linktitle: "Ersetzen"
second_title: "Aspose.PUB für C++"
description: "System::IO::FileInfo::Replace-Methode. Ersetzt den Inhalt einer angegebenen Zieldatei durch die durch das aktuelle FileInfo-Objekt dargestellte Datei und erstellt in C++ eine Sicherungskopie der ersetzten Datei."
type: docs
weight: 2000
url: /de/cpp/system.io/fileinfo/replace/
---
## FileInfo::Replace(const String\&, const String\&) method


Ersetzt den Inhalt einer angegebenen Zieldatei durch die durch das aktuelle [FileInfo](../)-Objekt dargestellte Datei und erstellt eine Sicherungskopie der ersetzten Datei.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destinationFileName | const String\& | Ein Name der zu ersetzenden Datei |
| destinationBackupFileName | const String\& | Ein Name der Sicherungsdatei |

### ReturnValue

Ein FileInfor-Objekt, das die Datei darstellt, auf die **destinationFileName** verweist

## Siehe auch

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## FileInfo::Replace(const String\&, const String\&, bool) method


Ersetzt den Inhalt einer angegebenen Zieldatei durch die durch das aktuelle [FileInfo](../)-Objekt dargestellte Datei und erstellt eine Sicherungskopie der ersetzten Datei.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destinationFileName | const String\& | Ein Name der zu ersetzenden Datei |
| destinationBackupFileName | const String\& | Ein Name der Sicherungsdatei |
| ignoreMetadataErrors | bool | Gibt an, ob die Merge-Fehler von der ersetzten Datei zur Ersatzdatei ignoriert werden sollen (true) oder nicht (false) |

### ReturnValue

Ein FileInfor-Objekt, das die Datei darstellt, auf die **destinationFileName** verweist

## Siehe auch

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
