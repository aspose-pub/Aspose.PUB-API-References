---
title: "System::Xml::Schema::XmlSchemaSimpleType Klasse"
linktitle: "XmlSchemaSimpleType"
second_title: "Aspose.PUB für C++"
description: "System::Xml::Schema::XmlSchemaSimpleType Klasse. Stellt das **simpleType**‑Element für einfachen Inhalt aus XML Schema dar, wie vom World Wide Web Consortium (W3C) festgelegt. Diese Klasse definiert einen einfachen Typ. Einfache Typen können Informationen und Einschränkungen für den Wert von Attributen oder Elementen mit rein textuellem Inhalt in C++ angeben."
type: docs
weight: 6200
url: /de/cpp/system.xml.schema/xmlschemasimpletype/
---
## XmlSchemaSimpleType class


Stellt das **simpleType**‑Element für einfachen Inhalt aus XML [Schema](../) dar, wie vom World Wide [Web](../../system.web/) Consortium (W3C) festgelegt. Diese Klasse definiert einen einfachen Typ. Einfache Typen können Informationen und Einschränkungen für den Wert von Attributen oder Elementen mit rein textuellem Inhalt angeben.

```cpp
class XmlSchemaSimpleType : public System::Xml::Schema::XmlSchemaType
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Content](./get_content/)() | Gibt eines der folgenden zurück: [XmlSchemaSimpleTypeUnion](../xmlschemasimpletypeunion/), [XmlSchemaSimpleTypeList](../xmlschemasimpletypelist/) oder [XmlSchemaSimpleTypeRestriction](../xmlschemasimpletyperestriction/). |
| [set_Content](./set_content/)(const SharedPtr\<XmlSchemaSimpleTypeContent\>\&) | Setzt eines der folgenden: [XmlSchemaSimpleTypeUnion](../xmlschemasimpletypeunion/), [XmlSchemaSimpleTypeList](../xmlschemasimpletypelist/) oder [XmlSchemaSimpleTypeRestriction](../xmlschemasimpletyperestriction/). |
| [XmlSchemaSimpleType](./xmlschemasimpletype/)() | Initialisiert eine neue Instanz der Klasse [XmlSchemaSimpleType](./). |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [Ptr](./ptr/) | Ein Alias für einen Shared Pointer auf eine Instanz dieser Klasse. |
## Hinweise



Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals Instanzen dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

## Siehe auch

* Class [XmlSchemaType](../xmlschematype/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PUB for C++](../../)
