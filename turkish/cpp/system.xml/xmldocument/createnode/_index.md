---
title: "System::Xml::XmlDocument::CreateNode yöntemi"
linktitle: "CreateNode"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlDocument::CreateNode yöntemi. Belirtilen düğüm türü, XmlDocument::get_Name ve XmlNode::get_NamespaceURI ile bir XmlNode oluşturur C++'ta."
type: docs
weight: 1100
url: /tr/cpp/system.xml/xmldocument/createnode/
---
## XmlDocument::CreateNode(const String\&, const String\&, const String\&) method


Belirtilen düğüm türü, [XmlDocument::get_Name](../get_name/) ve [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) ile bir [XmlNode](../../xmlnode/) oluşturur.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(const String &nodeTypeString, const String &name, const String &namespaceURI)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| nodeTypeString | const String\& | Yeni düğümün XmlNodeType'ının [String](../../../system/string/) sürümü. Bu parametre aşağıdaki tabloda listelenen değerlerden biri olmalıdır. |
| name | const String\& | Yeni düğümün nitelikli adı. Ad bir iki nokta üstüste içeriyorsa, iki nokta üstüste öncesi [XmlNode::get_Prefix](../../xmlnode/get_prefix/) ve sonrası [XmlDocument::get_LocalName](../get_localname/) bileşenlerine ayrılır. |
| namespaceURI | const String\& | Yeni düğümün ad alanı URI'si. |

### ReturnValue

Yeni [XmlNode](../../xmlnode/).
## Açıklamalar



**nodeTypeString** parametresi büyük/küçük harfe duyarlıdır ve aşağıdaki tabloda yer alan değerlerden biri olmalıdır: |||
|-|-|
| nodeTypeString | XmlNodeType |
| attribute | Özellik |
| cdatasection | CDATA |
| comment | Comment |
| document | Document |
| documentfragment | DocumentFragment |
| belgeTürü | DocumentType |
| öğe | Eleman |
| varlıkReferansı | EntityReference |
| işlemTalimatı | ProcessingInstruction |
| önemliBoşluk | SignificantWhitespace |
| text | Metin |
| boşluk | Whitespace |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlDocument::CreateNode(XmlNodeType, const String\&, const String\&) method


Belirtilen XmlNodeType, [XmlDocument::get_Name](../get_name/) ve [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) ile bir [XmlNode](../../xmlnode/) oluşturur.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &name, const String &namespaceURI)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tür | XmlNodeType | Yeni düğümün XmlNodeType'ı. |
| name | const String\& | Yeni düğümün nitelikli adı. Ad bir iki nokta üstüste içeriyorsa, [XmlNode::get_Prefix](../../xmlnode/get_prefix/) ve [XmlDocument::get_LocalName](../get_localname/) bileşenlerine ayrılır. |
| namespaceURI | const String\& | Yeni düğümün ad alanı URI'si. |

### ReturnValue

Yeni [XmlNode](../../xmlnode/).

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Enum [XmlNodeType](../../xmlnodetype/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlDocument::CreateNode(XmlNodeType, const String\&, const String\&, const String\&) method


Belirtilen XmlNodeType, [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_Name](../get_name/) ve [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) ile bir [XmlNode](../../xmlnode/) oluşturur.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &prefix, const String &name, const String &namespaceURI)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tür | XmlNodeType | Yeni düğümün XmlNodeType'ı. |
| önek | const String\& | Yeni düğümün öneki. |
| ad | const String\& | Yeni düğümün yerel adı. |
| namespaceURI | const String\& | Yeni düğümün ad alanı URI'si. |

### ReturnValue

Yeni [XmlNode](../../xmlnode/).

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Enum [XmlNodeType](../../xmlnodetype/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
