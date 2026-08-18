---
title: "System::IO::FileOptions Enum"
linktitle: "FileOptions"
second_title: "Aspose.PUB für C++"
description: "System::IO::FileOptions Enum. Stellt erweiterte Optionen für die Erstellung eines FileStream-Objekts in C++ dar."
type: docs
weight: 3200
url: /de/cpp/system.io/fileoptions/
---
## FileOptions enum


Stellt erweiterte Optionen für die Erstellung des [FileStream](../filestream/) Objekts dar.

```cpp
enum class FileOptions
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | 0 | Keine zusätzlichen Optionen. |
| Verschlüsselt | 16384 | Die Datei ist verschlüsselt. NICHT IMPLEMENTIERT. |
| DeleteOnClose | 67108864 | Die Datei sollte automatisch gelöscht werden, wenn sie nicht mehr verwendet wird. |
| SequentialScan | 134217728 | Die Datei sollte sequenziell zugegriffen werden. |
| RandomAccess | 268435456 | Auf die Datei wird zufällig zugegriffen. |
| Asynchronous | 1073741824 | Die Datei kann für asynchrone I/O-Operationen verwendet werden. NICHT IMPLEMENTIERT. |
| WriteThrough | n/a | Alle Schreibvorgänge sollten direkt auf die Festplatte gehen und dabei jeglichen Zwischenspeicher umgehen. |

## Siehe auch

* Namespace [System::IO](../)
* Library [Aspose.PUB for C++](../../)
