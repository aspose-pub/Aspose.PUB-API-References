---
title: "System::IO::DirectoryInfo::EnumerateFiles Methode"
linktitle: "EnumerateFiles"
second_title: "Aspose.PUB für C++"
description: "System::IO::DirectoryInfo::EnumerateFiles Methode. Gibt eine aufzählbare Sammlung zurück, die alle Dateien enthält, die sich im Verzeichnis befinden, das durch das aktuelle Objekt in C++ repräsentiert wird."
type: docs
weight: 600
url: /de/cpp/system.io/directoryinfo/enumeratefiles/
---
## DirectoryInfo::EnumerateFiles() method


Gibt eine aufzählbare Sammlung zurück, die alle im vom aktuellen Objekt repräsentierten Verzeichnis befindlichen Dateien enthält.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles()
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## DirectoryInfo::EnumerateFiles(const String\&) method


Durchsucht das vom aktuellen Objekt repräsentierte Verzeichnis nach Dateien, die die angegebenen Suchkriterien erfüllen.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| searchPattern | const String\& | Das Namensmuster der zu suchenden Dateien |

### ReturnValue

Die aufzählbare Sammlung von Shared-Pointern zu [FileInfo](../../fileinfo/) Objekten, die die gefundenen Dateien darstellen, deren Namen dem **searchPattern** entsprechen.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## DirectoryInfo::EnumerateFiles(const String\&, SearchOption) method


Durchsucht entweder das vom aktuellen Objekt repräsentierte Verzeichnis oder den gesamten Verzeichnisbaum, der im vom aktuellen Objekt repräsentierten Verzeichnis verwurzelt ist, nach Dateien, die die angegebenen Suchkriterien erfüllen.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern, SearchOption searchOption)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| searchPattern | const String\& | Das Namensmuster der zu suchenden Dateien |
| searchOption | SearchOption | Gibt an, ob die Suche nur im Verzeichnis, das durch das aktuelle Objekt repräsentiert wird, oder im gesamten Verzeichnisbaum, der im Verzeichnis, das durch das aktuelle Objekt repräsentiert wird, verwurzelt ist, durchgeführt werden muss. |

### ReturnValue

Die aufzählbare Sammlung von Shared-Pointern zu [FileInfo](../../fileinfo/) Objekten, die die gefundenen Dateien darstellen, deren Namen dem **searchPattern** entsprechen.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
