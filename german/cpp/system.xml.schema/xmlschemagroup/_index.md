---
title: "System::Xml::Schema::XmlSchemaGroup Klasse"
linktitle: "XmlSchemaGroup"
second_title: "Aspose.PUB für C++"
description: "System::Xml::Schema::XmlSchemaGroup class. Stellt das group-Element aus XML Schema dar, wie vom World Wide Web Consortium (W3C) spezifiziert. Diese Klasse definiert Gruppen auf Schemaebene, die von den komplexen Typen referenziert werden. Sie gruppiert eine Menge von Elementdeklarationen, sodass sie als Gruppe in komplexen Typdefinitionen in C++ eingebunden werden können."
type: docs
weight: 3100
url: /de/cpp/system.xml.schema/xmlschemagroup/
---
## XmlSchemaGroup class


Stellt das **group**-Element aus XML [Schema](../) dar, wie vom World Wide [Web](../../system.web/) Consortium (W3C) spezifiziert. Diese Klasse definiert Gruppen auf **schema**-Ebene, die von den komplexen Typen referenziert werden. Sie gruppiert eine Menge von Elementdeklarationen, sodass sie als Gruppe in komplexen Typdefinitionen eingebunden werden können.

```cpp
class XmlSchemaGroup : public System::Xml::Schema::XmlSchemaAnnotated
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Name](./get_name/)() | Gibt den Namen der Schema-Gruppe zurück. |
| [get_Particle](./get_particle/)() | Gibt eine der Klassen [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/), oder [XmlSchemaSequence](../xmlschemasequence/) zurück. |
| [get_QualifiedName](./get_qualifiedname/)() | Gibt den qualifizierten Namen der Schema-Gruppe zurück. |
| [set_Name](./set_name/)(const String\&) | Setzt den Namen der Schema-Gruppe. |
| [set_Particle](./set_particle/)(const SharedPtr\<XmlSchemaGroupBase\>\&) | Setzt eine der Klassen [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/), oder [XmlSchemaSequence](../xmlschemasequence/) ein. |
| [XmlSchemaGroup](./xmlschemagroup/)() | Initialisiert eine neue Instanz der Klasse [XmlSchemaGroup](./). |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [Ptr](./ptr/) | Ein Alias für einen Shared Pointer auf eine Instanz dieser Klasse. |
## Hinweise



Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals Instanzen dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

## Siehe auch

* Class [XmlSchemaAnnotated](../xmlschemaannotated/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PUB for C++](../../)
