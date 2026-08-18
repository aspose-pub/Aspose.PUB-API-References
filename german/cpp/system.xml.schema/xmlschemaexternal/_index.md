---
title: "System::Xml::Schema::XmlSchemaExternal Klasse"
linktitle: "XmlSchemaExternal"
second_title: "Aspose.PUB für C++"
description: "System::Xml::Schema::XmlSchemaExternal Klasse. Stellt Informationen über das eingeschlossene Schema in C++ bereit."
type: docs
weight: 2800
url: /de/cpp/system.xml.schema/xmlschemaexternal/
---
## XmlSchemaExternal class


Stellt Informationen über das eingeschlossene Schema bereit.

```cpp
class XmlSchemaExternal : public System::Xml::Schema::XmlSchemaObject
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Id](./get_id/)() | Gibt die Zeichenketten‑ID zurück. |
| [get_Schema](./get_schema/)() | Gibt das [XmlSchema](../xmlschema/) für das referenzierte Schema zurück. |
| [get_SchemaLocation](./get_schemalocation/)() | Gibt den Uniform Resource Identifier (URI)-Ort für das Schema zurück, der dem Schema‑Processor mitteilt, wo das Schema physisch gespeichert ist. |
| [get_UnhandledAttributes](./get_unhandledattributes/)() | Gibt die qualifizierten Attribute zurück, die nicht zum Ziel‑Namespace des Schemas gehören. |
| [set_Id](./set_id/)(const String\&) | Setzt die Zeichenketten‑ID. |
| [set_Schema](./set_schema/)(const SharedPtr\<XmlSchema\>\&) | Setzt das [XmlSchema](../xmlschema/) für das referenzierte Schema. |
| [set_SchemaLocation](./set_schemalocation/)(const String\&) | Setzt den Uniform Resource Identifier (URI)-Ort für das Schema, der dem Schema‑Processor mitteilt, wo das Schema physisch gespeichert ist. |
| [set_UnhandledAttributes](./set_unhandledattributes/)(const ArrayPtr\<SharedPtr\<XmlAttribute\>\>\&) | Setzt die qualifizierten Attribute, die nicht zum Ziel‑Namespace des Schemas gehören. |
| [XmlSchemaExternal](./xmlschemaexternal/)() | Initialisiert eine neue Instanz der Klasse [XmlSchemaExternal](./). |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [Ptr](./ptr/) | Ein Alias für einen Shared Pointer auf eine Instanz dieser Klasse. |
## Hinweise



Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals Instanzen dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

## Siehe auch

* Class [XmlSchemaObject](../xmlschemaobject/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PUB for C++](../../)
