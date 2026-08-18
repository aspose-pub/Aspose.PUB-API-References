---
title: "System::Xml::XPath::XPathNodeType enum"
linktitle: "XPathNodeType"
second_title: "Aspose.PUB für C++"
description: "System::Xml::XPath::XPathNodeType enum. Definiert die XPath-Knotentypen, die von der XPathNavigator-Klasse in C++ zurückgegeben werden können."
type: docs
weight: 1100
url: /de/cpp/system.xml.xpath/xpathnodetype/
---
## XPathNodeType enum


Definiert die [XPath](../)-Knotentypen, die von der [XPathNavigator](../xpathnavigator/)-Klasse zurückgegeben werden können.

```cpp
enum class XPathNodeType
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Root | 0 | Der Wurzelknoten des XML-Dokuments oder des Knotensbaums. |
| Element | 1 | Ein Element, zum Beispiel **<element>**. |
| Attribute | 2 | Ein Attribut, zum Beispiel **id='123'**. |
| Namensraum | 3 | Ein Namespace, zum Beispiel **xmlns=\"namespace\"**. |
| Text | 4 | Der Textinhalt eines Knotens. Entspricht dem Document [Object](../../system/object/) Model (DOM) [Text](../../system.text/) und CDATA-Knotentypen. Enthält mindestens ein Zeichen. |
| SignificantWhitespace | 5 | Ein Knoten mit Leerzeichen und **xml:space** auf **preserve** gesetzt. |
| Whitespace | 6 | Ein Knoten, der nur Leerzeichen enthält und keinen signifikanten Leerraum hat. Leerzeichen sind **'\x20'**, **'\x0d'**, **'\x0a'**, **'\x09'**. |
| ProcessingInstruction | 7 | Eine Verarbeitungsanweisung, wie **<?pi test?>**. Dies schließt keine XML-Deklarationen ein, die für die Klasse [XPathNavigator](../xpathnavigator/) nicht sichtbar sind. |
| Comment | 8 | Ein Kommentar, wie ****. |
| Alle | 9 | Jeder der XPathNodeType-Knotentypen. |

## Siehe auch

* Namespace [System::Xml::XPath](../)
* Library [Aspose.PUB for C++](../../)
