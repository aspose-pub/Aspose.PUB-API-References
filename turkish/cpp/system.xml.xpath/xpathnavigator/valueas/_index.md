---
title: "System::Xml::XPath::XPathNavigator::ValueAs method"
linktitle: "ValueAs"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XPath::XPathNavigator::ValueAs yöntemi. C++'ta namespace öneklerini çözmek için belirtilen IXmlNamespaceResolver nesnesini kullanarak, belirtilen Type'a göre mevcut düğüm''ün değerini döndürür."
type: docs
weight: 8100
url: /tr/cpp/system.xml.xpath/xpathnavigator/valueas/
---
## XPathNavigator::ValueAs method


Belirtilen Type'a göre mevcut düğümün değerini döndürür, namespace öneklerini çözmek için belirtilen [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) nesnesini kullanarak.

```cpp
SharedPtr<Object> System::Xml::XPath::XPathNavigator::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| returnType | const TypeInfo\& | Mevcut düğümün değerinin döndürüleceği Type. |
| nsResolver | SharedPtr\<IXmlNamespaceResolver\> | Ad alanı öneklerini çözmek için kullanılan [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) nesnesi. |

### ReturnValue

İstenen Type'a göre mevcut düğümün değeri.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PUB for C++](../../../)
