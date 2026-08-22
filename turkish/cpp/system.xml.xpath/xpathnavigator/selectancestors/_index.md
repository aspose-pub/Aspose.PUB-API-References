---
title: "System::Xml::XPath::XPathNavigator::SelectAncestors yöntemi"
linktitle: "SelectAncestors"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XPath::XPathNavigator::SelectAncestors yöntemi. C++'ta belirtilen yerel ada ve ad alanı URI'sine sahip geçerli düğümün tüm üst düğümlerini seçer."
type: docs
weight: 7200
url: /tr/cpp/system.xml.xpath/xpathnavigator/selectancestors/
---
## XPathNavigator::SelectAncestors(String, String, bool) method


Geçerli düğümün belirtilen yerel ada ve ad alanı URI'sına sahip tüm üst düğümlerini seçer.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(String name, String namespaceURI, bool matchSelf)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | String | Üst düğümlerin yerel adı. |
| namespaceURI | String | Üst düğümlerin ad alanı URI'si. |
| matchSelf | bool | Seçimde bağlam düğümünü dahil etmek için **true**; aksi takdirde **false**. |

### ReturnValue

Seçilen düğümleri içeren bir [XPathNodeIterator](../../xpathnodeiterator/). Döndürülen düğümler ters belge sırasındadır.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PUB for C++](../../../)
## XPathNavigator::SelectAncestors(XPathNodeType, bool) method


Geçerli düğümün eşleşen XPathNodeType değerine sahip tüm üst düğümlerini seçer.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(XPathNodeType type, bool matchSelf)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tür | XPathNodeType | Üst düğümlerin XPathNodeType'ı. |
| matchSelf | bool | Seçimde bağlam düğümünü dahil etmek için **true**; aksi takdirde **false**. |

### ReturnValue

Seçilen düğümleri içeren bir [XPathNodeIterator](../../xpathnodeiterator/). Döndürülen düğümler ters belge sırasındadır.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Enum [XPathNodeType](../../xpathnodetype/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PUB for C++](../../../)
