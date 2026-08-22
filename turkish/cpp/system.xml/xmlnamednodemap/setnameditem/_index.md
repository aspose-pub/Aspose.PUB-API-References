---
title: "System::Xml::XmlNamedNodeMap::SetNamedItem yöntemi"
linktitle: "SetNamedItem"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlNamedNodeMap::SetNamedItem yöntemi. C++'ta XmlNode::get_Name değerini kullanarak bir XmlNode ekler."
type: docs
weight: 1000
url: /tr/cpp/system.xml/xmlnamednodemap/setnameditem/
---
## XmlNamedNodeMap::SetNamedItem method


Bir [XmlNode](../../xmlnode/) ekler, [XmlNode::get_Name](../../xmlnode/get_name/) değerini kullanarak.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::SetNamedItem(SharedPtr<XmlNode> node)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| node | SharedPtr\<XmlNode\> | [XmlNamedNodeMap](../) içinde saklanacak bir [XmlNode](../../xmlnode/). Aynı ada sahip bir düğüm zaten haritada varsa, yeni olanla değiştirilir. |

### ReturnValue

Eğer **node** aynı ada sahip mevcut bir düğümü değiştirirse, eski düğüm döndürülür; aksi takdirde, **nullptr** döndürülür.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
