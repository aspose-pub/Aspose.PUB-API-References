---
title: "System::Xml::XmlDocument::CreateAttribute yöntemi"
linktitle: "CreateAttribute"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlDocument::CreateAttribute yöntemi. Belirtilen adla bir XmlAttribute oluşturur C++'ta."
type: docs
weight: 300
url: /tr/cpp/system.xml/xmldocument/createattribute/
---
## XmlDocument::CreateAttribute(const String\&) method


Belirtilen adla bir [XmlAttribute](../../xmlattribute/) oluşturur.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &name)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | const String\& | Özniteliğin nitelikli adı. Ad bir iki nokta üstüste içeriyorsa, [XmlNode::get_Prefix](../../xmlnode/get_prefix/) değeri adın ilk iki nokta üstüste öncesindeki kısmı yansıtır ve [XmlDocument::get_LocalName](../get_localname/) değeri adın ilk iki nokta üstüste sonrasındaki kısmı yansıtır. [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) değeri, önek **xmlns** gibi tanınan yerleşik bir önek olmadıkça boş kalır. Bu durumda get_NamespaceURI değeri [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/) olur. |

### ReturnValue

Yeni [XmlAttribute](../../xmlattribute/).

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlDocument::CreateAttribute(const String\&, const String\&, const String\&) method


Belirtilen [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_LocalName](../get_localname/) ve [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) ile bir [XmlAttribute](../../xmlattribute/) oluşturur.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &prefix, const String &localName, const String &namespaceURI)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| prefix | const String\& | Özniteliğin öneki (varsa). [String::Empty](../../../system/string/empty/) ve **nullptr** eşdeğerdir. |
| localName | const String\& | Özniteliğin yerel adı. |
| namespaceURI | const String\& | Özniteliğin ad alanı URI'si (varsa). [String::Empty](../../../system/string/empty/) ve **nullptr** eşdeğerdir. **prefix** **xmlns** ise, bu parametre [http://www.w3.org/2000/xmlns/;](http://www.w3.org/2000/xmlns/;) olmalıdır; aksi takdirde bir istisna fırlatılır. |

### ReturnValue

Yeni [XmlAttribute](../../xmlattribute/).

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlDocument::CreateAttribute(const String\&, const String\&) method


Belirtilen nitelikli ad ve [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) ile bir [XmlAttribute](../../xmlattribute/) oluşturur.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &qualifiedName, const String &namespaceURI)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| qualifiedName | const String\& | Özniteliğin nitelikli adı. Ad bir iki nokta üstüste içeriyorsa, [XmlNode::get_Prefix](../../xmlnode/get_prefix/) değeri iki nokta üstüste öncesindeki kısmı yansıtır ve [XmlDocument::get_LocalName](../get_localname/) değeri iki nokta üstüste sonrasındaki kısmı yansıtır. |
| namespaceURI | const String\& | Özniteliğin namespaceURI'si. Nitelikli ad **xmlns** öneki içeriyorsa, bu parametre [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/) olmalıdır. |

### ReturnValue

Yeni [XmlAttribute](../../xmlattribute/).

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
