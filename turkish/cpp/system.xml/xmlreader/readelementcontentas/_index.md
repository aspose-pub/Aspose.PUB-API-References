---
title: "System::Xml::XmlReader::ReadElementContentAs yöntemi"
linktitle: "ReadElementContentAs"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlReader::ReadElementContentAs yöntemi. C++'ta öğe içeriğini istenen türde okur."
type: docs
weight: 5200
url: /tr/cpp/system.xml/xmlreader/readelementcontentas/
---
## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) method


Elemanın içeriğini istenen türde okur.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| returnType | const TypeInfo\& | Döndürülecek değerin türü. |
| namespaceResolver | SharedPtr\<IXmlNamespaceResolver\> | Tür dönüşümüyle ilgili herhangi bir ad alanı önekini çözmek için kullanılan bir [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) nesnesi. |

### ReturnValue

İstenen tipte nesneye dönüştürülmüş öğe içeriği.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>, String, String) method


Belirtilen yerel ad ve ad alanı URI'sinin geçerli öğe ile eşleştiğini kontrol eder, ardından öğenin içeriğini istenen türde okur.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver, String localName, String namespaceURI)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| returnType | const TypeInfo\& | Döndürülecek değerin türü. |
| namespaceResolver | SharedPtr\<IXmlNamespaceResolver\> | Tür dönüşümüyle ilgili herhangi bir ad alanı önekini çözmek için kullanılan bir [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) nesnesi. |
| localName | String | Öğenin yerel adı. |
| namespaceURI | String | Öğenin ad alanı URI'sı. |

### ReturnValue

İstenen tipte nesneye dönüştürülmüş öğe içeriği.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
