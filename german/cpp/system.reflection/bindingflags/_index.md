---
title: "System::Reflection::BindingFlags Enum"
linktitle: "BindingFlags"
second_title: "Aspose.PUB für C++"
description: "System::Reflection::BindingFlags Enum. Definiert Mitglieder- und Typensuchmodi sowie Bindungen in C++."
type: docs
weight: 1100
url: /de/cpp/system.reflection/bindingflags/
---
## BindingFlags enum


Definiert Modi für das Nachschlagen von Mitgliedern und Typen sowie Bindungen.

```cpp
enum class BindingFlags
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Default | 0 | Keine besonderen Optionen. |
| IgnoreCase | 1 | Ignoriere Groß-/Kleinschreibung des Namens bei der Suche nach dem Element. |
| DeclaredOnly | 2 | Nur nach Mitgliedern suchen, die im Typ deklariert sind und nicht in Basistypen. |
| Instance | 4 | Durchsuche Instanzmitglieder. |
| Statisch | 8 | Durchsuche statische Mitglieder. |
| Öffentlich | 16 | Durchsuche öffentliche Mitglieder. |
| NonPublic | 32 | Durchsuche nicht-öffentliche Mitglieder. |
| FlattenHierarchy | 64 | Durchsuche öffentliche und geschützte statische Mitglieder des Basistyps. |
| InvokeMethod | 256 | Ruft Methode auf. |
| CreateInstance | 512 | Erstellt eine Instanz des reflektierten Typs. |
| GetField | 1024 | Liefert den Feldwert. |
| SetField | 2048 | Setzt den Feldwert. |
| GetProperty | 4096 | Liefert den Eigenschaftswert. |
| SetProperty | 8192 | Setzt den Eigenschaftswert. |
| PutDispProperty | 16384 | Setzt COM-Eigenschaft. |
| PutRefDispProperty | 32768 | Setzt COM-Referenzeigenschaft. |
| ExactBinding | 65536 | Die Typbindung muss exakt sein, ohne Typänderungen. |
| SuppressChangeType | 131072 | Nicht unterstützt. |
| OptionalParamBinding | 262144 | Wählt die Überladung basierend auf der Argumentanzahl aus. |
| IgnoreReturn | 16777216 | Ignoriert den Rückgabewert der COM-Interop. |

## Siehe auch

* Namespace [System::Reflection](../)
* Library [Aspose.PUB for C++](../../)
