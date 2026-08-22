---
title: "System::Xml::XPath::XPathNavigator::SelectDescendants yöntemi"
linktitle: "SelectDescendants"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XPath::XPathNavigator::SelectDescendants yöntemi. C++'ta belirtilen yerel ad ve ad alanı URI'si ile geçerli düğümün tüm alt düğümlerini seçer."
type: docs
weight: 7400
url: /tr/cpp/system.xml.xpath/xpathnavigator/selectdescendants/
---
## XPathNavigator::SelectDescendants(String, String, bool) method


Geçerli düğümün belirtilen yerel ada ve ad alanı URI'sına sahip tüm alt nesil düğümlerini seçer.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(String name, String namespaceURI, bool matchSelf)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | String | Alt düğümlerin yerel adı. |
| namespaceURI | String | Alt düğümlerin ad alanı URI'si. |
| matchSelf | bool | Seçime bağlam düğümünü dahil etmek için **true**; aksi takdirde **false**. |

### ReturnValue

Seçilen düğümleri içeren bir [XPathNodeIterator](../../xpathnodeiterator/) nesnesi.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PUB for C++](../../../)
## XPathNavigator::SelectDescendants(XPathNodeType, bool) method


Geçerli düğümün eşleşen XPathNodeType değerine sahip tüm alt nesil düğümlerini seçer.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(XPathNodeType type, bool matchSelf)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tür | XPathNodeType | Alt düğümlerin XPathNodeType'ı. |
| matchSelf | bool | Seçime bağlam düğümünü dahil etmek için **true**; aksi takdirde **false**. |

### ReturnValue

Seçilen düğümleri içeren bir [XPathNodeIterator](../../xpathnodeiterator/) nesnesi.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Enum [XPathNodeType](../../xpathnodetype/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PUB for C++](../../../)
