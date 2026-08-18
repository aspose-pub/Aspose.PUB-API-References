---
title: "System::IO::Directory::GetFiles Methode"
linktitle: "GetFiles"
second_title: "Aspose.PUB für C++"
description: "System::IO::Directory::GetFiles Methode. Durchsucht die Dateien, die die angegebenen Suchkriterien entweder im angegebenen Verzeichnis oder im gesamten Verzeichnisbaum, der im angegebenen Verzeichnis verwurzelt ist, in C++ erfüllen."
type: docs
weight: 1200
url: /de/cpp/system.io/directory/getfiles/
---
## Directory::GetFiles method


Durchsucht die Dateien, die die angegebenen Suchkriterien erfüllen, entweder im angegebenen Verzeichnis oder im gesamten Verzeichnisbaum, der im angegebenen Verzeichnis verwurzelt ist.

```cpp
static ArrayPtr<String> System::IO::Directory::GetFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pfad | const String\& | Vollständiger oder relativer Pfad zum Verzeichnis, in dem gesucht werden soll |
| searchPattern | const String\& | Das Namensmuster der zu suchenden Dateien |
| searchOption | SearchOption | Gibt an, ob die Suche nur im angegebenen Verzeichnis oder im gesamten Verzeichnisbaum, der im angegebenen Verzeichnis verwurzelt ist, durchgeführt werden soll |

### ReturnValue

Ein Array voller Pfade der gefundenen Dateien, deren Namen **searchPattern** entsprechen

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
