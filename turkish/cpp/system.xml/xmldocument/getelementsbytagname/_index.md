---
title: "System::Xml::XmlDocument::GetElementsByTagName yöntemi"
linktitle: "GetElementsByTagName"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlDocument::GetElementsByTagName yöntemi. C++'da belirtilen XmlDocument::get_LocalName ve XmlNode::get_NamespaceURI ile eşleşen tüm alt öğelerin bir listesini içeren bir XmlNodeList döndürür."
type: docs
weight: 3200
url: /tr/cpp/system.xml/xmldocument/getelementsbytagname/
---
## XmlDocument::GetElementsByTagName(String, String) method


Belirtilen [XmlDocument::get_LocalName](../get_localname/) ve [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) ile eşleşen tüm alt öğelerin bir listesini içeren bir [XmlNodeList](../../xmlnodelist/) döndürür.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String localName, String namespaceURI)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| localName | String | Eşleşecek LocalName. Özel değer **\"*\"** tüm etiketleri eşleştirir. |
| namespaceURI | String | Eşleşecek NamespaceURI. |

### ReturnValue

Belirtilen **localName** ve **namespaceURI** ile eşleşen tüm düğümlerin bir listesini içeren bir [XmlNodeList](../../xmlnodelist/). Eğer hiçbir düğüm eşleşmezse, döndürülen koleksiyon boş olur.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNodeList](../../xmlnodelist/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlDocument::GetElementsByTagName(String) method


Belirtilen ada uyan tüm alt öğelerin bir listesini içeren bir [XmlNodeList](../../xmlnodelist/) döndürür.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String name)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | String | Eşleşecek nitelikli ad. Eşleşen düğümün **get_Name** değeriyle karşılaştırılır. Özel değer **\"*\"** tüm etiketleri eşleştirir. |

### ReturnValue

Belirtilen **name** ile eşleşen hiçbir düğüm yoksa, döndürülen koleksiyon boş olacak şekilde, tüm eşleşen düğümlerin bir listesini içeren bir [XmlNodeList](../../xmlnodelist/).

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNodeList](../../xmlnodelist/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
