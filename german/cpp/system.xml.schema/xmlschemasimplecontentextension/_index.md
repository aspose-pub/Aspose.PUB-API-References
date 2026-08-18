---
title: "System::Xml::Schema::XmlSchemaSimpleContentExtension Klasse"
linktitle: "XmlSchemaSimpleContentExtension"
second_title: "Aspose.PUB für C++"
description: "System::Xml::Schema::XmlSchemaSimpleContentExtension Klasse. Stellt das Erweiterungselement für einfachen Inhalt aus XML Schema dar, wie vom World Wide Web Consortium (W3C) festgelegt. Diese Klasse kann verwendet werden, um einfache Typen durch Erweiterung abzuleiten. Solche Ableitungen werden genutzt, um den Inhalt des einfachen Typs des Elements durch Hinzufügen von Attributen in C++ zu erweitern."
type: docs
weight: 6000
url: /de/cpp/system.xml.schema/xmlschemasimplecontentextension/
---
## XmlSchemaSimpleContentExtension class


Stellt das **extension**‑Element für einfachen Inhalt aus XML [Schema](../) dar, wie vom World Wide [Web](../../system.web/) Consortium (W3C) festgelegt. Diese Klasse kann verwendet werden, um einfache Typen durch Erweiterung abzuleiten. Solche Ableitungen werden genutzt, um den Inhalt des einfachen Typs des Elements durch Hinzufügen von Attributen zu erweitern.

```cpp
class XmlSchemaSimpleContentExtension : public System::Xml::Schema::XmlSchemaContent
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_AnyAttribute](./get_anyattribute/)() | Gibt das [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) zurück, das für den Attributwert verwendet werden soll. |
| [get_Attributes](./get_attributes/)() | Gibt die Sammlung von [XmlSchemaAttribute](../xmlschemaattribute/) und [XmlSchemaAttributeGroupRef](../xmlschemaattributegroupref/) zurück. |
| [get_BaseTypeName](./get_basetypename/)() | Gibt den Namen eines integrierten Datentyps oder einfachen Typs zurück, von dem dieser Typ abgeleitet ist. |
| [set_AnyAttribute](./set_anyattribute/)(const SharedPtr\<XmlSchemaAnyAttribute\>\&) | Legt das [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) fest, das für den Attributwert verwendet werden soll. |
| [set_BaseTypeName](./set_basetypename/)(const SharedPtr\<XmlQualifiedName\>\&) | Legt den Namen eines integrierten Datentyps oder einfachen Typs fest, von dem dieser Typ abgeleitet ist. |
| [XmlSchemaSimpleContentExtension](./xmlschemasimplecontentextension/)() | Initialisiert eine neue Instanz der [XmlSchemaSimpleContentExtension](./) Klasse. |
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
