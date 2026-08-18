---
title: "System::Xml::Schema::XmlSchemaDocumentation Klasse"
linktitle: "XmlSchemaDocumentation"
second_title: "Aspose.PUB für C++"
description: "System::Xml::Schema::XmlSchemaDocumentation Klasse. Stellt das Dokumentationselement aus XML Schema dar, wie vom World Wide Web Consortium (W3C) festgelegt. Diese Klasse gibt Informationen an, die von Menschen innerhalb einer Annotation in C++ gelesen oder verwendet werden können."
type: docs
weight: 2500
url: /de/cpp/system.xml.schema/xmlschemadocumentation/
---
## XmlSchemaDocumentation class


Stellt das **documentation**-Element aus XML [Schema](../) dar, wie vom World Wide [Web](../../system.web/) Consortium (W3C) festgelegt. Diese Klasse gibt Informationen an, die von Menschen innerhalb einer **annotation** gelesen oder verwendet werden können.

```cpp
class XmlSchemaDocumentation : public System::Xml::Schema::XmlSchemaObject
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Language](./get_language/)() | Gibt das **xml:lang**-Attribut zurück. Dies dient als Hinweis auf die in den Inhalten verwendete Sprache. |
| [get_Markup](./get_markup/)() | Gibt ein Array von [XmlNode](../../system.xml/xmlnode/) Objekten zurück, das die untergeordneten Knoten der Dokumentation darstellt. |
| [get_Source](./get_source/)() | Gibt die Quelle des Uniform Resource Identifier (URI) der Information zurück. |
| [set_Language](./set_language/)(const String\&) | Setzt das **xml:lang**-Attribut. Dies dient als Hinweis auf die in den Inhalten verwendete Sprache. |
| [set_Markup](./set_markup/)(const ArrayPtr\<SharedPtr\<XmlNode\>\>\&) | Setzt ein Array von [XmlNode](../../system.xml/xmlnode/) Objekten, das die untergeordneten Knoten der Dokumentation darstellt. |
| [set_Source](./set_source/)(const String\&) | Setzt die Quelle des Uniform Resource Identifier (URI) der Information. |
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
