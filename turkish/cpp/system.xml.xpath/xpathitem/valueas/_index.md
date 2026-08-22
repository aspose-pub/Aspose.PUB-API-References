---
title: "System::Xml::XPath::XPathItem::ValueAs method"
linktitle: "ValueAs"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XPath::XPathItem::ValueAs method. item''s değerini C++'ta belirtilen tipte döndürür."
type: docs
weight: 1100
url: /tr/cpp/system.xml.xpath/xpathitem/valueas/
---
## XPathItem::ValueAs(const TypeInfo\&) method


Öğenin değerini belirtilen türde döndürür.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| returnType | const TypeInfo\& | Öğenin değerinin döndürüleceği tip. |

### ReturnValue

Öğenin değeri, istenen tipte.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XPathItem](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PUB for C++](../../../)
## XPathItem::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) method


Türetilmiş bir sınıfta geçersiz kılındığında, ad alanı öneklerini çözmek için belirtilen [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) nesnesi kullanılarak belirtilen tipte öğenin değerini döndürür.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| returnType | const TypeInfo\& | Öğenin değerinin döndürüleceği tip. |
| nsResolver | SharedPtr\<IXmlNamespaceResolver\> | Ad alanı öneklerini çözmek için kullanılan [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) nesnesi. |

### ReturnValue

Öğenin değeri, istenen tipte.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathItem](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PUB for C++](../../../)
