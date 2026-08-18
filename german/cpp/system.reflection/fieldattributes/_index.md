---
title: "System::Reflection::FieldAttributes enum"
linktitle: "FieldAttributes"
second_title: "Aspose.PUB für C++"
description: "System::Reflection::FieldAttributes enum. Reflektierte Feldattribute in C++."
type: docs
weight: 1200
url: /de/cpp/system.reflection/fieldattributes/
---
## FieldAttributes enum


Reflektierte Feldattribute.

```cpp
enum class FieldAttributes
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| FieldAccessMask | 7 | Maskierung für den Zugriff auf Mitglieder. Verwenden Sie diese Maske, um Zugänglichkeitsinformationen abzurufen. |
| PrivateScope | 0 | Nicht referenzierbare Mitglieder. |
| Private | 1 | Private Mitglieder. |
| FamANDAssem | 2 | Private und assembly-gebundene Mitglieder. |
| Assembly | 3 | Assembly-gebundene Mitglieder. |
| Family | 4 | Mitglieder, die vom Typ und dessen Untertypen zugänglich sind. |
| FamORAssem | 5 | Mitglieder, die vom Typ, von Untertypen und von der Assembly aus zugänglich sind. |
| Öffentlich | 6 | Mitglieder, die von jedermann aus zugänglich sind. |
| Statisch | 16 | Statische Mitglieder im Gegensatz zu Instanzmitgliedern. |
| InitOnly | 32 | Konstante Mitglieder, die nur initialisiert, aber nicht geändert werden können. |
| Literal | 64 | Zur Compile‑Zeit konstante Mitglieder. |
| NotSerialized | 128 | Nicht serialisierte Mitglieder. |
| SpecialName | 512 | Spezialfeld eines der unten genannten Namen. |
| PinvokeImpl | 8192 | Interop‑weitergeleitete Implementierung. |
| ReservedMask | 38144 | Reservierte Flags nur für die Laufzeitverwendung. |
| RTSpecialName | 1024 | Runtime sollte die Namencodierung prüfen. |
| HasFieldMarshal | 4096 | Marshalling‑Informationen sind vorhanden. |
| HasDefault | 32768 | Standardwert ist vorhanden. |
| HasFieldRVA | 256 | RVA ist vorhanden. |

## Siehe auch

* Namespace [System::Reflection](../)
* Library [Aspose.PUB for C++](../../)
