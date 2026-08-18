---
title: "System::Xml::XmlReader::ReadElementString Methode"
linktitle: "ReadElementString"
second_title: "Aspose.PUB für C++"
description: "System::Xml::XmlReader::ReadElementString Methode. Liest ein reines Textelement. Es wird jedoch empfohlen, stattdessen die XmlReader::ReadElementContentAsString‑Methode zu verwenden, da sie eine einfachere Handhabung dieses Vorgangs in C++ ermöglicht."
type: docs
weight: 6400
url: /de/cpp/system.xml/xmlreader/readelementstring/
---
## XmlReader::ReadElementString() method


Liest ein reines Textelement. Es wird jedoch empfohlen, stattdessen die [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) Methode zu verwenden, da sie eine einfachere Handhabung dieses Vorgangs ermöglicht.

```cpp
virtual String System::Xml::XmlReader::ReadElementString()
```


### ReturnValue

Der im gelesenen Element enthaltene Text. Eine leere Zeichenkette, wenn das Element leer ist.

## Siehe auch

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlReader::ReadElementString(String, String) method


Überprüft, dass die Werte [XmlReader::get_LocalName](../get_localname/) und [XmlReader::get_NamespaceURI](../get_namespaceuri/) des gefundenen Elements mit den angegebenen Zeichenketten übereinstimmen, bevor ein reines Textelement gelesen wird. Es wird jedoch empfohlen, stattdessen die [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) Methode zu verwenden, da sie eine einfachere Handhabung dieses Vorgangs ermöglicht.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String localname, String ns)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localname | String | Der zu prüfende lokale Name. |
| ns | String | Der zu prüfende Namespace‑URI. |

### ReturnValue

Der im gelesenen Element enthaltene Text. Eine leere Zeichenkette, wenn das Element leer ist.

## Siehe auch

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlReader::ReadElementString(String) method


Überprüft, dass der Wert [XmlReader::get_Name](../get_name/) des gefundenen Elements mit der angegebenen Zeichenkette übereinstimmt, bevor ein reines Textelement gelesen wird. Es wird jedoch empfohlen, stattdessen die [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) Methode zu verwenden, da sie eine einfachere Handhabung dieses Vorgangs ermöglicht.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String name)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | String | Der zu prüfende Name. |

### ReturnValue

Der im gelesenen Element enthaltene Text. Eine leere Zeichenkette, wenn das Element leer ist.

## Siehe auch

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
