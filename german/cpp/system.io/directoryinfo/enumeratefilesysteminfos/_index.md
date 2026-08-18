---
title: "System::IO::DirectoryInfo::EnumerateFileSystemInfos Methode"
linktitle: "EnumerateFileSystemInfos"
second_title: "Aspose.PUB für C++"
description: "System::IO::DirectoryInfo::EnumerateFileSystemInfos Methode. Gibt eine aufzählbare Sammlung zurück, die alle Dateien und Verzeichnisse enthält, die sich im vom aktuellen Objekt dargestellten Verzeichnis befinden, in C++."
type: docs
weight: 700
url: /de/cpp/system.io/directoryinfo/enumeratefilesysteminfos/
---
## DirectoryInfo::EnumerateFileSystemInfos() method


Gibt eine aufzählbare Sammlung zurück, die alle im vom aktuellen Objekt repräsentierten Verzeichnis befindlichen Dateien und Verzeichnisse enthält.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos()
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## DirectoryInfo::EnumerateFileSystemInfos(const String\&) method


Durchsucht das vom aktuellen Objekt repräsentierte Verzeichnis nach Dateien und Verzeichnissen, die die angegebenen Suchkriterien erfüllen.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| searchPattern | const String\& | Das Namensmuster der zu suchenden Dateien und Verzeichnisse |

### ReturnValue

Die aufzählbare Sammlung gemeinsamer Zeiger auf die [FileSystemInfo](../../filesysteminfo/)-Objekte, die die gefundenen Dateien und Verzeichnisse repräsentieren, deren Namen dem **searchPattern** entsprechen.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [String](../../../system/string/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## DirectoryInfo::EnumerateFileSystemInfos(const String\&, SearchOption) method


Durchsucht entweder das vom aktuellen Objekt repräsentierte Verzeichnis oder den gesamten Verzeichnisbaum, der im vom aktuellen Objekt repräsentierten Verzeichnis verwurzelt ist, nach Dateien und Verzeichnissen, die die angegebenen Suchkriterien erfüllen.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| searchPattern | const String\& | Das Namensmuster der zu suchenden Dateien und Verzeichnisse |
| searchOption | SearchOption | Gibt an, ob die Suche nur im Verzeichnis, das durch das aktuelle Objekt repräsentiert wird, oder im gesamten Verzeichnisbaum, der im Verzeichnis, das durch das aktuelle Objekt repräsentiert wird, verwurzelt ist, durchgeführt werden muss. |

### ReturnValue

Die aufzählbare Sammlung gemeinsamer Zeiger auf die [FileSystemInfo](../../filesysteminfo/)-Objekte, die die gefundenen Dateien und Verzeichnisse repräsentieren, deren Namen dem **searchPattern** entsprechen.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
