---
title: "System::Xml::XmlNode::get_ParentNode Methode"
linktitle: "get_ParentNode"
second_title: "Aspose.PUB für C++"
description: "System::Xml::XmlNode::get_ParentNode Methode. Gibt den übergeordneten Knoten dieses Knotens zurück (für Knoten, die über Eltern verfügen) in C++."
type: docs
weight: 2100
url: /de/cpp/system.xml/xmlnode/get_parentnode/
---
## XmlNode::get_ParentNode method


Gibt den übergeordneten Knoten dieses Knotens zurück (für Knoten, die übergeordnete Knoten haben können).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::get_ParentNode() final
```


### ReturnValue

Der [XmlNode](../), der das übergeordnete Element des aktuellen Knotens ist.
## Hinweise



Wenn ein Knoten gerade erst erstellt wurde und noch nicht zum Baum hinzugefügt wurde oder wenn er aus dem Baum entfernt wurde, ist der übergeordnete Knoten **nullptr**. Für alle anderen Knoten hängt der zurückgegebene Wert vom [XmlNode::get_NodeType](../get_nodetype/) des Knotens ab. Die folgende Tabelle beschreibt die möglichen Rückgabewerte für die **get_NodeType** Methode. |||
|-|-|
| NodeType | Rückgabewert von ParentNode |
| Attribute, Document, DocumentFragment, Entity, Notation | Gibt nullptr zurück; diese Knoten haben keine Eltern. |
| CDATA | Gibt das Element oder die Entity-Referenz zurück, das/die den CDATA-Abschnitt enthält. |
| Comment | Gibt das Element, die Entity-Referenz, den Dokumenttyp oder das Dokument zurück, das den Kommentar enthält. |
| DocumentType | Gibt den Dokumentknoten zurück. |
| Element | Gibt den übergeordneten Knoten des Elements zurück. Wenn das Element der Wurzelknoten im Baum ist, ist der übergeordnete Knoten der Dokumentknoten. |
| EntityReference | Gibt das Element, das Attribut oder die Entity-Referenz zurück, das/die die Entity-Referenz enthält. |
| ProcessingInstruction | Gibt das Dokument, das Element, den Dokumenttyp oder die Entity-Referenz zurück, das/die die Verarbeitungsanweisung enthält. |
| Text | Gibt das übergeordnete Element, Attribut oder die Entity-Referenz zurück, das/die den Textknoten enthält. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
