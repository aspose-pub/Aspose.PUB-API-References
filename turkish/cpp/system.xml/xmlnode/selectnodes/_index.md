---
title: "System::Xml::XmlNode::SelectNodes yöntemi"
linktitle: "SelectNodes"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlNode::SelectNodes yöntemi. C++'da XPath ifadesiyle eşleşen bir düğüm listesi seçer."
type: docs
weight: 3800
url: /tr/cpp/system.xml/xmlnode/selectnodes/
---
## XmlNode::SelectNodes(const String\&) method


[XPath](../../../system.xml.xpath/) ifadesiyle eşleşen bir düğüm listesi seçer.

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xpath | const String\& | [XPath](../../../system.xml.xpath/) ifadesi. |

### ReturnValue

[XPath](../../../system.xml.xpath/) sorgusuyla eşleşen düğüm koleksiyonunu içeren bir [XmlNodeList](../../xmlnodelist/) nesnesi.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNodeList](../../xmlnodelist/)
* Class [String](../../../system/string/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlNode::SelectNodes(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) method


[XPath](../../../system.xml.xpath/) ifadesiyle eşleşen bir düğüm listesi seçer. [XPath](../../../system.xml.xpath/) ifadesinde bulunan tüm önekler, sağlanan [XmlNamespaceManager](../../xmlnamespacemanager/) kullanılarak çözülür.

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xpath | const String\& | [XPath](../../../system.xml.xpath/) ifadesi. |
| nsmgr | const SharedPtr\<XmlNamespaceManager\>\& | [XPath](../../../system.xml.xpath/) ifadesindeki önekler için ad alanlarını çözmekte kullanılacak bir [XmlNamespaceManager](../../xmlnamespacemanager/) nesnesi. |

### ReturnValue

[XPath](../../../system.xml.xpath/) sorgusuyla eşleşen düğüm koleksiyonunu içeren bir [XmlNodeList](../../xmlnodelist/) nesnesi.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNodeList](../../xmlnodelist/)
* Class [String](../../../system/string/)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
