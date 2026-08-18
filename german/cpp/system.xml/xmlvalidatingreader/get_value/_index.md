---
title: "System::Xml::XmlValidatingReader::get_Value Methode"
linktitle: "get_Value"
second_title: "Aspose.PUB für C++"
description: "System::Xml::XmlValidatingReader::get_Value Methode. Gibt den Textwert des aktuellen Knotens in C++ zurück."
type: docs
weight: 2900
url: /de/cpp/system.xml/xmlvalidatingreader/get_value/
---
## XmlValidatingReader::get_Value method


Gibt den Textwert des aktuellen Knotens zurück.

```cpp
String System::Xml::XmlValidatingReader::get_Value() override
```


### ReturnValue

Der zurückgegebene Wert hängt vom XmlValidatingReader::NodeType des Knotens ab.
## Hinweise



Die folgende Tabelle listet Knotentypen auf, die einen zurückzugebenden Wert haben. Alle anderen Knotentypen geben [String::Empty](../../../system/string/empty/) zurück. |||
|-|-|
| Knotentyp | Wert |
| Attribute | Der Wert des Attributs. |
| CDATA | Der Inhalt des CDATA-Abschnitts. |
| Comment | Der Inhalt des Kommentars. |
| DocumentType | Das interne Subset. |
| ProcessingInstruction | Der gesamte Inhalt, ohne das Ziel. |
| SignificantWhitespace | Der Weißraum zwischen Markup in einem gemischten Inhaltsmodell. |
| Text | Der Inhalt des Textknotens. |
| Whitespace | Der Weißraum zwischen Markup. |
| XmlDeclaration | Der Inhalt der Deklaration. |

## Siehe auch

* Class [String](../../../system/string/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
