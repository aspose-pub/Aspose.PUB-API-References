---
title: "System::Xml::XmlElement::GetElementsByTagName-Methode"
linktitle: "GetElementsByTagName"
second_title: "Aspose.PUB für C++"
description: "System::Xml::XmlElement::GetElementsByTagName-Methode. Gibt eine XmlNodeList zurück, die eine Liste aller Nachfahren-Elemente enthält, die den angegebenen XmlElement::get_LocalName- und XmlElement::get_NamespaceURI-Werten in C++ entsprechen."
type: docs
weight: 1500
url: /de/cpp/system.xml/xmlelement/getelementsbytagname/
---
## XmlElement::GetElementsByTagName(String, String) method


Gibt eine [XmlNodeList](../../xmlnodelist/) zurück, die eine Liste aller Nachfahren-Elemente enthält, die den angegebenen [XmlElement::get_LocalName](../get_localname/) und [XmlElement::get_NamespaceURI](../get_namespaceuri/) Werten entsprechen.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String localName, String namespaceURI)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localName | String | Der zu matchende lokale Name. Das Sternchen (*) ist ein spezieller Wert, der allen Tags entspricht. |
| namespaceURI | String | Der zu matchende Namespace-URI. |

### ReturnValue

Eine [XmlNodeList](../../xmlnodelist/) mit einer Liste aller passenden Knoten. Die Liste ist leer, wenn keine passenden Knoten vorhanden sind.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNodeList](../../xmlnodelist/)
* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlElement::GetElementsByTagName(String) method


Gibt eine [XmlNodeList](../../xmlnodelist/) zurück, die eine Liste aller Nachfahren-Elemente enthält, die dem angegebenen [XmlElement::get_Name](../get_name/) entsprechen.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String name)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | String | Der zu matchende Namens-Tag. Dies ist ein qualifizierter Name. Er wird mit dem **get_Name**-Wert des passenden Knotens verglichen. Das Sternchen (*) ist ein spezieller Wert, der alle Tags matcht. |

### ReturnValue

Eine [XmlNodeList](../../xmlnodelist/) mit einer Liste aller passenden Knoten. Die Liste ist leer, wenn keine passenden Knoten vorhanden sind.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNodeList](../../xmlnodelist/)
* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
