---
title: "Klasse System::ComponentModel::TypeConverter"
linktitle: "TypeConverter"
second_title: "Aspose.PUB für C++"
description: "Klasse System::ComponentModel::TypeConverter. Klasse, die Typkonvertierung im Komponentenmodell verarbeitet. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 1400
url: /de/cpp/system.componentmodel/typeconverter/
---
## TypeConverter class


Klasse, die Typkonvertierung im Komponentenmodell verarbeitet. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class TypeConverter : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [ConvertFrom](./convertfrom/)(const System::SharedPtr\<System::Object\>\&) | Konvertiert Objekte. |
| virtual [ConvertFrom](./convertfrom/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&) | Konvertiert Objekte. |
| [ConvertFrom](./convertfrom/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::String\&) | Konvertiert Zeichenfolge zu Objekt. |
| [ConvertFromInvariantString](./convertfrominvariantstring/)(const System::String\&) | Konvertiert invariant Zeichenfolge zu Objekt. |
| [ConvertFromInvariantString](./convertfrominvariantstring/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::String\&) | Konvertiert invariant Zeichenfolge zu Objekt. |
| [ConvertFromString](./convertfromstring/)(const System::String\&) | Konvertiert Zeichenfolge zu Objekt. |
| [ConvertFromString](./convertfromstring/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::String\&) | Konvertiert Zeichenfolge zu Objekt. |
| [ConvertFromString](./convertfromstring/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::String\&) | Konvertiert Zeichenfolge zu Objekt. |
| [ConvertTo](./convertto/)(const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) | Konvertiert ein Objekt in einen bestimmten Typ. |
| virtual [ConvertTo](./convertto/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) | Konvertiert ein Objekt in einen bestimmten Typ. |
| [ConvertToInvariantString](./converttoinvariantstring/)(const System::SharedPtr\<System::Object\>\&) | Konvertiert Objekt zu invariant Zeichenfolge. |
| [ConvertToInvariantString](./converttoinvariantstring/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Object\>\&) | Konvertiert Objekt zu invariant Zeichenfolge. |
| [ConvertToString](./converttostring/)(const System::SharedPtr\<System::Object\>\&) | Konvertiert Objekt zu Zeichenfolge. |
| [ConvertToString](./converttostring/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Object\>\&) | Konvertiert Objekt zu Zeichenfolge. |
| [ConvertToString](./converttostring/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&) | Konvertiert Objekt zu Zeichenfolge. |
| [TypeConverter](./typeconverter/)() | RTTI-Informationen. |
## Siehe auch

* Class [Object](../../system/object/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.PUB for C++](../../)
