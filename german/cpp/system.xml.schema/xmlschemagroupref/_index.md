---
title: "System::Xml::Schema::XmlSchemaGroupRef Klasse"
linktitle: "XmlSchemaGroupRef"
second_title: "Aspose.PUB für C++"
description: "System::Xml::Schema::XmlSchemaGroupRef Klasse. Stellt das group-Element mit ref-Attribut aus dem XML Schema dar, wie vom World Wide Web Consortium (W3C) spezifiziert. Diese Klasse wird innerhalb komplexer Typen verwendet, die ein group, das auf Schemaebene definiert ist, referenzieren, in C++."
type: docs
weight: 3300
url: /de/cpp/system.xml.schema/xmlschemagroupref/
---
## XmlSchemaGroupRef class


Stellt das **group**-Element mit **ref**-Attribut aus dem XML [Schema](../) dar, wie vom World Wide [Web](../../system.web/) Consortium (W3C) spezifiziert. Diese Klasse wird innerhalb komplexer Typen verwendet, die ein **group** referenzieren, das auf **schema**-Ebene definiert ist.

```cpp
class XmlSchemaGroupRef : public System::Xml::Schema::XmlSchemaParticle
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Particle](./get_particle/)() | Gibt eine der Klassen [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/), oder [XmlSchemaSequence](../xmlschemasequence/) zurück, die nach der Kompilierung die Interpretation des **Particle**-Wertes enthält. |
| [get_RefName](./get_refname/)() | Gibt den Namen einer in diesem Schema definierten Gruppe zurück (oder einer anderen durch den angegebenen Namespace angegebenen Schema). |
| [set_RefName](./set_refname/)(const SharedPtr\<XmlQualifiedName\>\&) | Setzt den Namen einer in diesem Schema definierten Gruppe (oder einer anderen durch den angegebenen Namespace angegebenen Schema). |
| [XmlSchemaGroupRef](./xmlschemagroupref/)() | Initialisiert eine neue Instanz der Klasse [XmlSchemaGroupRef](./). |
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
