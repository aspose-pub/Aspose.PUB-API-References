---
title: "System::IO::DirectoryInfo::GetFiles Methode"
linktitle: "GetFiles"
second_title: "Aspose.PUB für C++"
description: "System::IO::DirectoryInfo::GetFiles Methode. Gibt ein Array zurück, das Shared-Pointer zu FileInfo-Objekten enthält, die alle Verzeichnisse darstellen, die sich im Verzeichnis befinden, das durch das aktuelle Objekt in C++ repräsentiert wird."
type: docs
weight: 1300
url: /de/cpp/system.io/directoryinfo/getfiles/
---
## DirectoryInfo::GetFiles() method


Gibt ein Array zurück, das Shared-Pointer zu [FileInfo](../../fileinfo/) Objekten enthält, die alle Verzeichnisse darstellen, die sich im Verzeichnis befinden, das durch das aktuelle Objekt repräsentiert wird.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles()
```

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## DirectoryInfo::GetFiles(const String\&) method


Durchsucht das vom aktuellen Objekt repräsentierte Verzeichnis nach Dateien, die die angegebenen Suchkriterien erfüllen.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| searchPattern | const String\& | Das Namensmuster der zu suchenden Dateien |

### ReturnValue

Ein Array von Shared-Pointern zu [FileInfo](../../fileinfo/) Objekten, die die gefundenen Dateien darstellen, deren Namen dem **searchPattern** entsprechen.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## DirectoryInfo::GetFiles(const String\&, SearchOption) method


Durchsucht entweder das vom aktuellen Objekt repräsentierte Verzeichnis oder den gesamten Verzeichnisbaum, der im vom aktuellen Objekt repräsentierten Verzeichnis verwurzelt ist, nach Dateien, die die angegebenen Suchkriterien erfüllen.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern, SearchOption searchOption)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| searchPattern | const String\& | Das Namensmuster der zu suchenden Dateien |
| searchOption | SearchOption | Gibt an, ob die Suche nur im Verzeichnis, das durch das aktuelle Objekt repräsentiert wird, oder im gesamten Verzeichnisbaum, der im Verzeichnis, das durch das aktuelle Objekt repräsentiert wird, verwurzelt ist, durchgeführt werden muss. |

### ReturnValue

Ein Array von Shared-Pointern zu [FileInfo](../../fileinfo/) Objekten, die die gefundenen Dateien darstellen, deren Namen dem **searchPattern** entsprechen.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
