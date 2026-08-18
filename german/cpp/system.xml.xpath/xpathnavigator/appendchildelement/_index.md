---
title: "System::Xml::XPath::XPathNavigator::AppendChildElement Methode"
linktitle: "AppendChildElement"
second_title: "Aspose.PUB für C++"
description: "System::Xml::XPath::XPathNavigator::AppendChildElement Methode. Erstellt einen neuen Kind-Elementknoten am Ende der Liste der Kindknoten des aktuellen Knotens unter Verwendung des Namensraumpräfixes, des lokalen Namens und der Namensraum-URI, die mit dem angegebenen Wert in C++ spezifiziert sind."
type: docs
weight: 200
url: /de/cpp/system.xml.xpath/xpathnavigator/appendchildelement/
---
## XPathNavigator::AppendChildElement method


Erstellt einen neuen untergeordneten Elementknoten am Ende der Liste der untergeordneten Knoten des aktuellen Knotens unter Verwendung des angegebenen Namespace‑Präfixes, des lokalen Namens und der angegebenen Namespace‑URI mit dem angegebenen Wert.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChildElement(String prefix, String localName, String namespaceURI, String value)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Präfix | String | Das Namensraumpräfix des neuen Kind-Elementknotens (falls vorhanden). |
| localName | String | Der lokale Name des neuen Kind-Elementknotens (falls vorhanden). |
| namespaceURI | String | Die Namensraum-URI des neuen Kind-Elementknotens (falls vorhanden). [String::Empty](../../../system/string/empty/) und **nullptr** sind äquivalent. |
| value | String | Der Wert des neuen Kind-Elementknotens. Wenn [String::Empty](../../../system/string/empty/) oder **nullptr** übergeben werden, wird ein leeres Element erstellt. |

## Siehe auch

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PUB for C++](../../../)
