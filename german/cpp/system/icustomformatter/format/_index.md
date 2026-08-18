---
title: "System::ICustomFormatter::Format Methode"
linktitle: "Format"
second_title: "Aspose.PUB für C++"
description: "System::ICustomFormatter::Format Methode. Gibt eine Zeichenkettenrepräsentation eines Werts zurück, der vom aktuellen Objekt dargestellt wird, unter Verwendung des angegebenen Formats in C++."
type: docs
weight: 100
url: /de/cpp/system/icustomformatter/format/
---
## ICustomFormatter::Format method


Gibt eine Zeichenkettenrepräsentation eines Wertes zurück, der vom aktuellen Objekt mit dem angegebenen Format dargestellt wird.

```cpp
virtual System::String System::ICustomFormatter::Format(System::String format, System::SharedPtr<System::Object> arg, System::SharedPtr<System::IFormatProvider> formatProvider)=0
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Format | System::String | Das Zeichenkettenformat |
| arg | System::SharedPtr\<System::Object\> | Das zu formatierende Objekt |
| formatProvider | System::SharedPtr\<System::IFormatProvider\> | Das Objekt, das die Formatierungsinformationen bereitstellt |

### ReturnValue

Die Zeichenkettenrepräsentation von **arg**, formatiert gemäß dem von **format** und **formatProvider** angegebenen Format

## Siehe auch

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [ICustomFormatter](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
