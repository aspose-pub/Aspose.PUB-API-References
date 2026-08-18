---
title: "System::Xml::Schema::XmlSchemaAny Klasse"
linktitle: "XmlSchemaAny"
second_title: "Aspose.PUB für C++"
description: "System::Xml::Schema::XmlSchemaAny Klasse. Stellt das any-Element des World Wide Web Consortium (W3C) in C++ dar."
type: docs
weight: 800
url: /de/cpp/system.xml.schema/xmlschemaany/
---
## XmlSchemaAny class


Stellt das World Wide [Web](../../system.web/) Consortium (W3C) **any**-Element dar.

```cpp
class XmlSchemaAny : public System::Xml::Schema::XmlSchemaParticle
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Namespace](./get_namespace/)() | Gibt die Namespaces zurück, die die Elemente enthalten, die verwendet werden können. |
| [get_ProcessContents](./get_processcontents/)() | Gibt Informationen darüber zurück, wie eine Anwendung oder ein XML-Prozessor die Validierung von XML-Dokumenten für die durch das **any**-Element angegebenen Elemente handhaben soll. |
| [set_Namespace](./set_namespace/)(const String\&) | Legt die Namespaces fest, die die Elemente enthalten, die verwendet werden können. |
| [set_ProcessContents](./set_processcontents/)(XmlSchemaContentProcessing) | Legt Informationen darüber fest, wie eine Anwendung oder ein XML-Prozessor die Validierung von XML-Dokumenten für die durch das **any**-Element angegebenen Elemente handhaben soll. |
| [XmlSchemaAny](./xmlschemaany/)() | Initialisiert eine neue Instanz der Klasse [XmlSchemaAny](./). |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [Ptr](./ptr/) | Ein Alias für einen Shared Pointer auf eine Instanz dieser Klasse. |
## Hinweise



Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals Instanzen dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

## Siehe auch

* Class [XmlSchemaParticle](../xmlschemaparticle/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PUB for C++](../../)
