---
title: "System::Xml::XmlReader::get_Name Methode"
linktitle: "get_Name"
second_title: "Aspose.PUB für C++"
description: "System::Xml::XmlReader::get_Name Methode. Wenn sie in einer abgeleiteten Klasse überschrieben wird, liefert sie den qualifizierten Namen des aktuellen Knotens in C++."
type: docs
weight: 1500
url: /de/cpp/system.xml/xmlreader/get_name/
---
## XmlReader::get_Name method


Wird in einer abgeleiteten Klasse überschrieben, gibt den qualifizierten Namen des aktuellen Knotens zurück.

```cpp
virtual String System::Xml::XmlReader::get_Name()
```


### ReturnValue

Der qualifizierte Name des aktuellen Knotens. Zum Beispiel ist **Name** **bk:book** für das Element **<bk:book>**.
## Hinweise



Der zurückgegebene Name hängt vom Wert von [XmlReader::get_NodeType](../get_nodetype/) des Knotens ab. Die folgenden Knotentypen geben die aufgeführten Werte zurück. Alle anderen Knotentypen geben eine leere Zeichenkette zurück. |||
|-|-|
| Knotentyp | Name |
| Attribute | Der Name des Attributs. |
| DocumentType | Der Dokumenttypname. |
| Element | Der Tag-Name. |
| EntityReference | Der Name der referenzierten Entität. |
| ProcessingInstruction | Das Ziel der Verarbeitungsanweisung. |
| XmlDeclaration | Die literal Zeichenkette xml. |

## Siehe auch

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
