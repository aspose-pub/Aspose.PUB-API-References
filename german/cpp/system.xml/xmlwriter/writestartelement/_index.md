---
title: "System::Xml::XmlWriter::WriteStartElement Methode"
linktitle: "WriteStartElement"
second_title: "Aspose.PUB für C++"
description: "System::Xml::XmlWriter::WriteStartElement Methode. Wenn sie in einer abgeleiteten Klasse überschrieben wird, schreibt sie ein Start‑Tag mit dem angegebenen lokalen Namen in C++."
type: docs
weight: 3200
url: /de/cpp/system.xml/xmlwriter/writestartelement/
---
## XmlWriter::WriteStartElement(const String\&) method


Wenn in einer abgeleiteten Klasse überschrieben, schreibt ein Start-Tag mit dem angegebenen lokalen Namen.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localName | const String\& | Der lokale Name des Elements. |

## Siehe auch

* Class [String](../../../system/string/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlWriter::WriteStartElement(const String\&, const String\&) method


Wenn in einer abgeleiteten Klasse überschrieben, schreibt das angegebene Start-Tag und verknüpft es mit dem angegebenen Namensraum.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName, const String &ns)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localName | const String\& | Der lokale Name des Elements. |
| ns | const String\& | Der Namespace‑URI, der dem Element zugeordnet werden soll. Wenn dieser Namespace bereits im Geltungsbereich ist und ein zugehöriges Präfix hat, schreibt der Writer dieses Präfix ebenfalls automatisch. |

## Siehe auch

* Class [String](../../../system/string/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlWriter::WriteStartElement(const String\&, const String\&, const String\&) method


Wenn in einer abgeleiteten Klasse überschrieben, schreibt das angegebene Start-Tag und verknüpft es mit dem angegebenen Namensraum und Präfix.

```cpp
virtual void System::Xml::XmlWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns)=0
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Präfix | const String\& | Das Namensraum‑Präfix des Elements. |
| localName | const String\& | Der lokale Name des Elements. |
| ns | const String\& | Der Namespace‑URI, der dem Element zugeordnet werden soll. |

## Siehe auch

* Class [String](../../../system/string/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
