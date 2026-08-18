---
title: "System::IO::Directory::EnumerateFileSystemEntries Methode"
linktitle: "EnumerateFileSystemEntries"
second_title: "Aspose.PUB für C++"
description: "System::IO::Directory::EnumerateFileSystemEntries Methode. Durchsucht die Dateien und Verzeichnisse, die die angegebenen Suchkriterien entweder im angegebenen Verzeichnis oder im gesamten Verzeichnisbaum, der im angegebenen Verzeichnis verwurzelt ist, in C++ erfüllen."
type: docs
weight: 500
url: /de/cpp/system.io/directory/enumeratefilesystementries/
---
## Directory::EnumerateFileSystemEntries method


Durchsucht die Dateien und Verzeichnisse, die die angegebenen Suchkriterien erfüllen, entweder im angegebenen Verzeichnis oder im gesamten Verzeichnisbaum, der im angegebenen Verzeichnis verwurzelt ist.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pfad | const String\& | Vollständiger oder relativer Pfad zum Verzeichnis, in dem gesucht werden soll |
| searchPattern | const String\& | Das Namensmuster der zu suchenden Dateien und Verzeichnisse |
| searchOption | SearchOption | Gibt an, ob die Suche nur im angegebenen Verzeichnis oder im gesamten Verzeichnisbaum, der im angegebenen Verzeichnis verwurzelt ist, durchgeführt werden soll |

### ReturnValue

Die aufzählbare Sammlung voller Pfade der gefundenen Dateien und Verzeichnisse, deren Namen **searchPattern** entsprechen

## Siehe auch

* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
