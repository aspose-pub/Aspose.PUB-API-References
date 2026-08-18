---
title: "System::Xml::Schema::XmlSchemaObject Klasse"
linktitle: "XmlSchemaObject"
second_title: "Aspose.PUB für C++"
description: "System::Xml::Schema::XmlSchemaObject Klasse. Stellt die Basisklasse für die Xml-Schema-Objektmodell-Hierarchie dar und dient als Basisklasse für Klassen wie die XmlSchema Klasse in C++."
type: docs
weight: 5000
url: /de/cpp/system.xml.schema/xmlschemaobject/
---
## XmlSchemaObject class


Stellt die Basisklasse für das [Xml](../../system.xml/) Schema-Objektmodell dar und dient als Basisklasse für Klassen wie die [XmlSchema](../xmlschema/) Klasse.

```cpp
class XmlSchemaObject : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_LineNumber](./get_linenumber/)() | Gibt die Zeilennummer in der Datei zurück, auf die das **schema**‑Element verweist. |
| [get_LinePosition](./get_lineposition/)() | Gibt die Zeilenposition in der Datei zurück, auf die das **schema**‑Element verweist. |
| [get_Namespaces](./get_namespaces/)() | Gibt die XmlSerializerNamespaces zurück, die mit diesem Schema‑Objekt verwendet werden sollen. |
| [get_Parent](./get_parent/)() | Gibt das übergeordnete Element dieses [XmlSchemaObject](./) zurück. |
| [get_SourceUri](./get_sourceuri/)() | Gibt den Quellort der Datei zurück, die das Schema geladen hat. |
| [set_LineNumber](./set_linenumber/)(int32_t) | Setzt die Zeilennummer in der Datei, auf die das **schema**-Element verweist. |
| [set_LinePosition](./set_lineposition/)(int32_t) | Setzt die Zeilenposition in der Datei, auf die das **schema**-Element verweist. |
| [set_Namespaces](./set_namespaces/)(const SharedPtr\<System::Xml::Serialization::XmlSerializerNamespaces\>\&) | Setzt die XmlSerializerNamespaces, die mit diesem Schemaobjekt verwendet werden sollen. |
| [set_Parent](./set_parent/)(const SharedPtr\<XmlSchemaObject\>\&) | Setzt das übergeordnete Element dieses [XmlSchemaObject](./). |
| [set_SourceUri](./set_sourceuri/)(const String\&) | Setzt den Quellort für die Datei, die das Schema geladen hat. |
| [XmlSchemaObject](./xmlschemaobject/)() | Initialisiert eine neue Instanz der [XmlSchemaObject](./) Klasse. |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [Ptr](./ptr/) | Ein Alias für einen Shared Pointer auf eine Instanz dieser Klasse. |
## Hinweise



Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals Instanzen dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

## Siehe auch

* Class [Object](../../system/object/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PUB for C++](../../)
