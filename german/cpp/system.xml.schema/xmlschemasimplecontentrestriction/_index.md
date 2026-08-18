---
title: "System::Xml::Schema::XmlSchemaSimpleContentRestriction Klasse"
linktitle: "XmlSchemaSimpleContentRestriction"
second_title: "Aspose.PUB für C++"
description: "System::Xml::Schema::XmlSchemaSimpleContentRestriction Klasse. Stellt das Einschränkungselement für einfachen Inhalt aus dem XML‑Schema dar, wie vom World Wide Web Consortium (W3C) festgelegt. Diese Klasse kann verwendet werden, um einfache Typen durch Einschränkung abzuleiten. Solche Ableitungen können verwendet werden, um den Wertebereich des Elements auf eine Teilmenge der im geerbten einfachen Typ angegebenen Werte zu beschränken in C++."
type: docs
weight: 6100
url: /de/cpp/system.xml.schema/xmlschemasimplecontentrestriction/
---
## XmlSchemaSimpleContentRestriction class


Stellt das **restriction**-Element für einfachen Inhalt aus dem XML [Schema](../) dar, wie vom World Wide [Web](../../system.web/) Consortium (W3C) festgelegt. Diese Klasse kann verwendet werden, um einfache Typen durch Einschränkung abzuleiten. Solche Ableitungen können verwendet werden, um den Wertebereich des Elements auf eine Teilmenge der im geerbten einfachen Typ angegebenen Werte zu beschränken.

```cpp
class XmlSchemaSimpleContentRestriction : public System::Xml::Schema::XmlSchemaContent
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_AnyAttribute](./get_anyattribute/)() | Gibt ein [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) zurück, das für den Attributwert verwendet werden soll. |
| [get_Attributes](./get_attributes/)() | Gibt die Sammlung von [XmlSchemaAttribute](../xmlschemaattribute/) und [XmlSchemaAttributeGroupRef](../xmlschemaattributegroupref/) Attributen für den einfachen Typ zurück. |
| [get_BaseType](./get_basetype/)() | Gibt den Basiswert des einfachen Typs zurück. |
| [get_BaseTypeName](./get_basetypename/)() | Gibt den Namen des integrierten Datentyps oder einfachen Typs zurück, von dem dieser Typ abgeleitet ist. |
| [get_Facets](./get_facets/)() | Gibt ein [Xml](../../system.xml/)[Schema](../)-Facet zurück. |
| [set_AnyAttribute](./set_anyattribute/)(const SharedPtr\<XmlSchemaAnyAttribute\>\&) | Setzt ein [XmlSchemaAnyAttribute](../xmlschemaanyattribute/), das für den Attributwert verwendet werden soll. |
| [set_BaseType](./set_basetype/)(const SharedPtr\<XmlSchemaSimpleType\>\&) | Setzt den Basiswert des einfachen Typs. |
| [set_BaseTypeName](./set_basetypename/)(const SharedPtr\<XmlQualifiedName\>\&) | Setzt den Namen des integrierten Datentyps oder einfachen Typs, von dem dieser Typ abgeleitet ist. |
| [XmlSchemaSimpleContentRestriction](./xmlschemasimplecontentrestriction/)() | Initialisiert eine neue Instanz der [XmlSchemaSimpleContentRestriction](./) Klasse. |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [Ptr](./ptr/) | Ein Alias für einen Shared Pointer auf eine Instanz dieser Klasse. |
## Hinweise



Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals Instanzen dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

## Siehe auch

* Class [XmlSchemaContent](../xmlschemacontent/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PUB for C++](../../)
