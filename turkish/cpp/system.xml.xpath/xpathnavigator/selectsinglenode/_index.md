---
title: "System::Xml::XPath::XPathNavigator::SelectSingleNode method"
linktitle: "SelectSingleNode"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XPath::XPathNavigator::SelectSingleNode method. Belirtilen XPathExpression nesnesini C++'ta kullanarak XPathNavigator içinde tek bir düğüm seçer."
type: docs
weight: 7500
url: /tr/cpp/system.xml.xpath/xpathnavigator/selectsinglenode/
---
## XPathNavigator::SelectSingleNode(SharedPtr\<XPathExpression\>) method


Belirtilen [XPathExpression](../../xpathexpression/) nesnesini kullanarak [XPathNavigator](../) içinde tek bir düğüm seçer.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(SharedPtr<XPathExpression> expression)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| expression | SharedPtr\<XPathExpression\> | Derlenmiş [XPath](../../) sorgusunu içeren bir [XPathExpression](../../xpathexpression/) nesnesi. |

### ReturnValue

Belirtilen [XPath](../../) sorgusu için ilk eşleşen düğümü içeren bir [XPathNavigator](../) nesnesi; aksi takdirde sorgu sonucu yoksa **nullptr**.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Class [XPathExpression](../../xpathexpression/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PUB for C++](../../../)
## XPathNavigator::SelectSingleNode(String) method


Belirtilen [XPath](../../) sorgusunu kullanarak [XPathNavigator](../) içinde tek bir düğüm seçer.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xpath | String | Bir [XPath](../../) ifadesini temsil eden bir [String](../../../system/string/) nesnesi. |

### ReturnValue

Belirtilen [XPath](../../) sorgusu için ilk eşleşen düğümü içeren bir [XPathNavigator](../) nesnesi; aksi takdirde, sorgu sonucu yoksa **nullptr**.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PUB for C++](../../../)
## XPathNavigator::SelectSingleNode(String, SharedPtr\<IXmlNamespaceResolver\>) method


Belirtilen [XPath](../../) sorgusunu ve ad alanı öneklerini çözmek için belirtilen [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) nesnesini kullanarak [XPathNavigator](../) nesnesinde tek bir düğüm seçer.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xpath | String | Bir [XPath](../../) ifadesini temsil eden bir [String](../../../system/string/) nesnesi. |
| resolver | SharedPtr\<IXmlNamespaceResolver\> | [XPath](../../) sorgusunda ad alanı öneklerini çözmek için kullanılan [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) nesnesi. |

### ReturnValue

Belirtilen [XPath](../../) sorgusu için ilk eşleşen düğümü içeren bir [XPathNavigator](../) nesnesi; aksi takdirde sorgu sonucu yoksa **nullptr**.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PUB for C++](../../../)
