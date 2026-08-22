---
title: "System::Xml::XmlElement::SetAttributeNode yöntemi"
linktitle: "SetAttributeNode"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlElement::SetAttributeNode yöntemi. C++'de belirtilen XmlAttribute'ı ekler."
type: docs
weight: 2700
url: /tr/cpp/system.xml/xmlelement/setattributenode/
---
## XmlElement::SetAttributeNode(SharedPtr\<XmlAttribute\>) method


Belirtilen [XmlAttribute](../../xmlattribute/) ekler.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(SharedPtr<XmlAttribute> newAttr)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newAttr | SharedPtr\<XmlAttribute\> | Bu öğe için öznitelik koleksiyonuna eklenecek [XmlAttribute](../../xmlattribute/) düğümü. |

### ReturnValue

Öznitelik aynı ada sahip mevcut bir özniteliği değiştirirse, eski [XmlAttribute](../../xmlattribute/) döndürülür; aksi takdirde **nullptr** döndürülür.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlElement::SetAttributeNode(String, String) method


Belirtilen [XmlAttribute](../../xmlattribute/) ekler.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(String localName, String namespaceURI)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| localName | String | Özniteliğin yerel adı. |
| namespaceURI | String | Özniteliğin ad alanı URI'si. |

### ReturnValue

Eklenecek [XmlAttribute](../../xmlattribute/).

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
