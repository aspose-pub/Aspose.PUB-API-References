---
title: "System::Xml::XmlNamedNodeMap::SetNamedItem Methode"
linktitle: "SetNamedItem"
second_title: "Aspose.PUB für C++"
description: "System::Xml::XmlNamedNodeMap::SetNamedItem Methode. Fügt einen XmlNode unter Verwendung seines XmlNode::get_Name-Werts in C++ hinzu."
type: docs
weight: 1000
url: /de/cpp/system.xml/xmlnamednodemap/setnameditem/
---
## XmlNamedNodeMap::SetNamedItem method


Fügt ein [XmlNode](../../xmlnode/) unter Verwendung seines [XmlNode::get_Name](../../xmlnode/get_name/) Werts hinzu.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::SetNamedItem(SharedPtr<XmlNode> node)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| node | SharedPtr\<XmlNode\> | Ein [XmlNode](../../xmlnode/) zum Speichern im [XmlNamedNodeMap](../). Wenn bereits ein Knoten mit diesem Namen in der Karte vorhanden ist, wird er durch den neuen ersetzt. |

### ReturnValue

Wenn das **node** einen vorhandenen Knoten mit demselben Namen ersetzt, wird der alte Knoten zurückgegeben; andernfalls wird **nullptr** zurückgegeben.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
