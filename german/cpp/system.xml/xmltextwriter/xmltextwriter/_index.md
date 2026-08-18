---
title: "System::Xml::XmlTextWriter::XmlTextWriter-Konstruktor"
linktitle: "XmlTextWriter"
second_title: "Aspose.PUB für C++"
description: "System::Xml::XmlTextWriter::XmlTextWriter Konstruktor. Erstellt eine Instanz der XmlTextWriter‑Klasse mit dem angegebenen Stream und der angegebenen Codierung in C++."
type: docs
weight: 100
url: /de/cpp/system.xml/xmltextwriter/xmltextwriter/
---
## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Text::Encoding\>\&) constructor


Erstellt eine Instanz der [XmlTextWriter](../)-Klasse mit dem angegebenen Stream und der angegebenen Codierung.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::Stream> &w, const SharedPtr<Text::Encoding> &encoding)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| w | const SharedPtr\<IO::Stream\>\& | Der Stream, in den Sie schreiben möchten. |
| encoding | const SharedPtr\<Text::Encoding\>\& | Die zu erzeugende Codierung. Wenn die Codierung **nullptr** ist, wird der Stream als UTF-8 ausgegeben und das Codierungsattribut der **ProcessingInstruction** weggelassen. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Encoding](../../../system.text/encoding/)
* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::TextWriter\>\&) constructor


Erstellt eine Instanz der [XmlTextWriter](../)-Klasse mit dem angegebenen TextWriter.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::TextWriter> &w)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| w | const SharedPtr\<IO::TextWriter\>\& | Der TextWriter, in den geschrieben werden soll. Es wird angenommen, dass der TextWriter bereits auf die korrekte Codierung eingestellt ist. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlTextWriter::XmlTextWriter(const String\&, const SharedPtr\<Text::Encoding\>\&) constructor


Erstellt eine Instanz der [XmlTextWriter](../)-Klasse mit der angegebenen Datei.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const String &filename, const SharedPtr<Text::Encoding> &encoding)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | const String\& | Der Dateiname, in den geschrieben werden soll. Wenn die Datei existiert, wird sie trunciert und mit dem neuen Inhalt überschrieben. |
| encoding | const SharedPtr\<Text::Encoding\>\& | Die zu erzeugende Codierung. Wenn die Codierung **nullptr** ist, wird die Datei als UTF-8 geschrieben und das Codierungsattribut der **ProcessingInstruction** weggelassen. |

## Siehe auch

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Encoding](../../../system.text/encoding/)
* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
