---
title: "System::Xml::Schema::XmlSchemaInfo Klasse"
linktitle: "XmlSchemaInfo"
second_title: "Aspose.PUB für C++"
description: "System::Xml::Schema::XmlSchemaInfo Klasse. Stellt das Post‑Schema‑Validierungs‑Informationsset eines validierten XML‑Knotens in C++ dar."
type: docs
weight: 3800
url: /de/cpp/system.xml.schema/xmlschemainfo/
---
## XmlSchemaInfo class


Stellt das Post‑Schema‑Validierungs‑Infoset eines validierten XML‑Knotens dar.

```cpp
class XmlSchemaInfo : public System::Xml::Schema::IXmlSchemaInfo
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_ContentType](./get_contenttype/)() | Gibt das XmlSchemaContentType‑Objekt zurück, das dem Inhaltstyp dieses validierten XML‑Knotens entspricht. |
| [get_IsDefault](./get_isdefault/)() override | Gibt einen Wert zurück, der angibt, ob dieser validierte XML‑Knoten als Ergebnis einer während der XML‑[Schema](../) Definition Language (XSD)-Schema‑Validierung angewendeten Vorgabe gesetzt wurde. |
| [get_IsNil](./get_isnil/)() override | Gibt einen Wert zurück, der angibt, ob der Wert für diesen validierten XML‑Knoten **nil** ist. |
| [get_MemberType](./get_membertype/)() override | Gibt den dynamischen Schematyp für diesen validierten XML‑Knoten zurück. |
| [get_SchemaAttribute](./get_schemaattribute/)() override | Gibt das kompilierte [XmlSchemaAttribute](../xmlschemaattribute/)-Objekt zurück, das diesem validierten XML‑Knoten entspricht. |
| [get_SchemaElement](./get_schemaelement/)() override | Gibt das kompilierte [XmlSchemaElement](../xmlschemaelement/)-Objekt zurück, das diesem validierten XML‑Knoten entspricht. |
| [get_SchemaType](./get_schematype/)() override | Gibt den statischen XML‑[Schema](../) Definition Language (XSD)-Schematyp dieses validierten XML‑Knotens zurück. |
| [get_Validity](./get_validity/)() override | Gibt den XmlSchemaValidity‑Wert dieses validierten XML‑Knotens zurück. |
| [set_ContentType](./set_contenttype/)(XmlSchemaContentType) | Setzt das XmlSchemaContentType‑Objekt, das dem Inhaltstyp dieses validierten XML‑Knotens entspricht. |
| [set_IsDefault](./set_isdefault/)(bool) | Setzt einen Wert, der angibt, ob dieser validierte XML‑Knoten als Ergebnis einer während der XML‑[Schema](../) Definition Language (XSD)-Schema‑Validierung angewendeten Vorgabe gesetzt wurde. |
| [set_IsNil](./set_isnil/)(bool) | Setzt einen Wert, der angibt, ob der Wert für diesen validierten XML‑Knoten **nil** ist. |
| [set_MemberType](./set_membertype/)(const SharedPtr\<XmlSchemaSimpleType\>\&) | Setzt den dynamischen Schematyp für diesen validierten XML‑Knoten. |
| [set_SchemaAttribute](./set_schemaattribute/)(const SharedPtr\<XmlSchemaAttribute\>\&) | Setzt das kompilierte [XmlSchemaAttribute](../xmlschemaattribute/)-Objekt, das diesem validierten XML‑Knoten entspricht. |
| [set_SchemaElement](./set_schemaelement/)(const SharedPtr\<XmlSchemaElement\>\&) | Setzt das kompilierte [XmlSchemaElement](../xmlschemaelement/)-Objekt, das diesem validierten XML‑Knoten entspricht. |
| [set_SchemaType](./set_schematype/)(const SharedPtr\<XmlSchemaType\>\&) | Setzt den statischen XML‑[Schema](../) Definition Language (XSD)-Schematyp dieses validierten XML‑Knotens. |
| [set_Validity](./set_validity/)(XmlSchemaValidity) | Setzt den XmlSchemaValidity‑Wert dieses validierten XML‑Knotens. |
| [XmlSchemaInfo](./xmlschemainfo/)() | Initialisiert eine neue Instanz der [XmlSchemaInfo](./)-Klasse. |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [Ptr](./ptr/) | Ein Alias für einen Shared Pointer auf eine Instanz dieser Klasse. |
## Hinweise



Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals Instanzen dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

## Siehe auch

* Class [IXmlSchemaInfo](../ixmlschemainfo/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PUB for C++](../../)
