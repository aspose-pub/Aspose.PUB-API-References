---
title: "Klasse System::Xml::Serialization::XmlSerializer"
linktitle: "XmlSerializer"
second_title: "Aspose.PUB für C++"
description: "Klasse System::Xml::Serialization::XmlSerializer. Führt die Serialisierung und Deserialisierung von Objekten in XML-Dokumente und aus ihnen heraus durch. Objekte dieser Klasse sollten ausschließlich mit der Funktion System::MakeObject() erstellt werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse stets in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 600
url: /de/cpp/system.xml.serialization/xmlserializer/
---
## XmlSerializer class


Führt die Serialisierung und Deserialisierung von Objekten in XML-Dokumente und aus ihnen heraus durch. Objekte dieser Klasse sollten ausschließlich mit der Funktion [System::MakeObject()](../../system/makeobject/) erstellt werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../../system/smartptr/)-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class XmlSerializer : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual [CanDeserialize](./candeserialize/)(System::SharedPtr\<XmlReader\>) | Überprüft, ob ein bestimmter Reader sich in einem deserialisierbaren Zustand befindet. |
| [Deserialize](./deserialize/)(System::SharedPtr\<IO::Stream\>) | Deserialisiert ein XML-Dokument in ein Objekt. |
| [Deserialize](./deserialize/)(System::SharedPtr\<IO::TextReader\>) | Deserialisiert ein XML-Dokument in ein Objekt. |
| [Deserialize](./deserialize/)(System::SharedPtr\<XmlReader\>) | Deserialisiert ein XML-Dokument in ein Objekt. |
| [Deserialize](./deserialize/)(System::SharedPtr\<XmlReader\>, String) | Deserialisiert ein XML-Dokument in ein Objekt. |
| [Serialize](./serialize/)(System::SharedPtr\<IO::Stream\>, System::SharedPtr\<Object\>) | Serialisiert ein Dokument in XML. |
| [Serialize](./serialize/)(System::SharedPtr\<IO::TextWriter\>, System::SharedPtr\<Object\>) | Serialisiert ein Dokument in XML. |
| [Serialize](./serialize/)(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>) | Serialisiert ein Dokument in XML. |
| [Serialize](./serialize/)(System::SharedPtr\<IO::Stream\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>) | Serialisiert ein Dokument in XML. |
| [Serialize](./serialize/)(System::SharedPtr\<IO::TextWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>) | Serialisiert ein Dokument in XML. |
| [Serialize](./serialize/)(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>) | Serialisiert ein Dokument in XML. |
| [Serialize](./serialize/)(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>, String) | Serialisiert ein Dokument in XML. |
| [Serialize](./serialize/)(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>, String, String) | Serialisiert ein Dokument in XML. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| static [EncodingNamespace](./encodingnamespace/) | Kodiert den Namensraumnamen. |
| static [WsdlNamespace](./wsdlnamespace/) | RTTI. |
| static [WsdlTypesNamespace](./wsdltypesnamespace/) | Namensraumname für WSDL-Typen. |
## Siehe auch

* Class [Object](../../system/object/)
* Namespace [System::Xml::Serialization](../)
* Library [Aspose.PUB for C++](../../)
