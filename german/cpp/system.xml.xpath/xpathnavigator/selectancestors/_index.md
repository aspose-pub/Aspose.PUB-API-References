---
title: "System::Xml::XPath::XPathNavigator::SelectAncestors-Methode"
linktitle: "SelectAncestors"
second_title: "Aspose.PUB für C++"
description: "System::Xml::XPath::XPathNavigator::SelectAncestors-Methode. Wählt alle Vorfahrenknoten des aktuellen Knotens aus, die den angegebenen lokalen Namen und die Namespace-URI in C++ besitzen."
type: docs
weight: 7200
url: /de/cpp/system.xml.xpath/xpathnavigator/selectancestors/
---
## XPathNavigator::SelectAncestors(String, String, bool) method


Wählt alle Vorfahrenknoten des aktuellen Knotens aus, die den angegebenen lokalen Namen und Namespace‑URI besitzen.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(String name, String namespaceURI, bool matchSelf)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | String | Der lokale Name der Vorfahrenknoten. |
| namespaceURI | String | Die Namespace-URI der Vorfahrenknoten. |
| matchSelf | bool | Um den Kontextknoten in die Auswahl einzubeziehen, **true**; andernfalls **false**. |

### ReturnValue

Ein [XPathNodeIterator](../../xpathnodeiterator/), das die ausgewählten Knoten enthält. Die zurückgegebenen Knoten sind in umgekehrter Dokumentreihenfolge.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PUB for C++](../../../)
## XPathNavigator::SelectAncestors(XPathNodeType, bool) method


Wählt alle Vorfahrenknoten des aktuellen Knotens aus, die einen passenden XPathNodeType haben.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(XPathNodeType type, bool matchSelf)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | XPathNodeType | Der XPathNodeType der Vorgängerknoten. |
| matchSelf | bool | Um den Kontextknoten in die Auswahl einzubeziehen, **true**; andernfalls **false**. |

### ReturnValue

Ein [XPathNodeIterator](../../xpathnodeiterator/), das die ausgewählten Knoten enthält. Die zurückgegebenen Knoten sind in umgekehrter Dokumentreihenfolge.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Enum [XPathNodeType](../../xpathnodetype/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PUB for C++](../../../)
