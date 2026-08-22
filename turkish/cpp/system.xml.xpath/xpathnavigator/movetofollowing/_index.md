---
title: "System::Xml::XPath::XPathNavigator::MoveToFollowing metodu"
linktitle: "MoveToFollowing"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XPath::XPathNavigator::MoveToFollowing yöntemi. XPathNavigator'ı, belge sırasına göre belirtilen yerel ad ve ad alanı URI'sine sahip öğeye C++'ta taşır."
type: docs
weight: 5700
url: /tr/cpp/system.xml.xpath/xpathnavigator/movetofollowing/
---
## XPathNavigator::MoveToFollowing(String, String) method


Belge sırasına göre belirtilen yerel ad ve ad alanı URI'sine sahip öğeye [XPathNavigator](../) taşır.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| localName | String | Öğenin yerel adı. |
| namespaceURI | String | Öğenin ad alanı URI'sı. |

### ReturnValue

**true** if the [XPathNavigator](../) moved successfully; otherwise, **false**.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PUB for C++](../../../)
## XPathNavigator::MoveToFollowing(String, String, SharedPtr\<XPathNavigator\>) method


Belge sırasına göre, belirtilen sınır içinde, belirtilen yerel ad ve ad alanı URI'sine sahip öğeye [XPathNavigator](../) taşır.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI, SharedPtr<XPathNavigator> end)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| localName | String | Öğenin yerel adı. |
| namespaceURI | String | Öğenin ad alanı URI'sı. |
| end | SharedPtr\<XPathNavigator\> | Mevcut [XPathNavigator](../) nesnesinin sonraki öğeyi ararken geçmeyeceği öğe sınırına konumlandırılmış [XPathNavigator](../) nesnesi. |

### ReturnValue

**true** if the [XPathNavigator](../) moved successfully; otherwise, **false**.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PUB for C++](../../../)
## XPathNavigator::MoveToFollowing(XPathNodeType) method


Belge sırasına göre belirtilen XPathNodeType'ın sonraki öğesine [XPathNavigator](../) taşır.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | XPathNodeType | Öğenin XPathNodeType'ı. XPathNodeType, [XPathNodeType::Attribute](../../xpathnodetype/) veya [XPathNodeType::Namespace](../../xpathnodetype/) olamaz. |

### ReturnValue

**true** if the [XPathNavigator](../) moved successfully; otherwise, **false**.

## Ayrıca Bakınız

* Enum [XPathNodeType](../../xpathnodetype/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PUB for C++](../../../)
## XPathNavigator::MoveToFollowing(XPathNodeType, SharedPtr\<XPathNavigator\>) method


Belge sırasına göre, belirtilen sınır içinde, belirtilen XPathNodeType'ın sonraki öğesine [XPathNavigator](../) taşır.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type, SharedPtr<XPathNavigator> end)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | XPathNodeType | Öğenin XPathNodeType'ı. XPathNodeType, [XPathNodeType::Attribute](../../xpathnodetype/) veya [XPathNodeType::Namespace](../../xpathnodetype/) olamaz. |
| end | SharedPtr\<XPathNavigator\> | Mevcut [XPathNavigator](../) nesnesinin sonraki öğeyi ararken geçmeyeceği öğe sınırına konumlandırılmış [XPathNavigator](../) nesnesi. |

### ReturnValue

**true** if the [XPathNavigator](../) moved successfully; otherwise, **false**.

## Ayrıca Bakınız

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PUB for C++](../../../)
