---
title: "System::BoxedValueBase Klasse"
linktitle: "BoxedValueBase"
second_title: "Aspose.PUB für C++"
description: "System::BoxedValueBase Klasse. Eine Basisklasse, die ein Interface definiert und einige grundlegende Methoden einer abgeleiteten Klasse implementiert, die einen verpackten Wert darstellt. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 900
url: /de/cpp/system/boxedvaluebase/
---
## BoxedValueBase class


Eine Basisklasse, die ein Interface definiert und einige grundlegende Methoden einer abgeleiteten Klasse implementiert, die einen verpackten Wert darstellt. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class BoxedValueBase : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual [GetTypeCode](./gettypecode/)() const | Gibt den Wert zurück, der den Typ des von dem aktuellen Objekt dargestellten verpackten Wertes repräsentiert. |
| virtual [GetUnsignedLongLongValue](./getunsignedlonglongvalue/)() const | Konvertiert das vom aktuellen Objekt dargestellte Box-Objekt in einen 64‑Bit‑Ganzzahlwert. |
| virtual [IsBoxedEnum](./isboxedenum/)() | Bestimmt, ob das aktuelle Objekt einen verpackten Wert eines Aufzählungstyps darstellt. |
| static [Parse](./parse/)(const TypeInfo\&, const String\&, bool) | Verpackt den Wert einer Aufzählungskonstanten der angegebenen Enumeration mit dem angegebenen Namen. Ein Parameter gibt an, ob die Groß-/Kleinschreibung beim Interpretieren der Zeichenkette, die den Namen der Aufzählungskonstanten angibt, ignoriert werden soll. |
| static [Parse](./parse/)(const TypeInfo\&, const String\&) | Verpackt den Wert einer Aufzählungskonstanten der angegebenen Enumeration mit dem angegebenen Namen. |
| [ToString](./tostring/)(const System::String\&) const | Konvertiert das verpackte Objekt mithilfe einer angegebenen Formatzeichenkette in einen String. |
| virtual [ToString](./tostring/)() const | Analog zur C#-Methode [Object.ToString()](../object/tostring/). Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String. |
## Siehe auch

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
