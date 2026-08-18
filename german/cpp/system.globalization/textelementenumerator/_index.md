---
title: "System::Globalization::TextElementEnumerator class"
linktitle: "TextElementEnumerator"
second_title: "Aspose.PUB für C++"
description: "System::Globalization::TextElementEnumerator class. Aufzählung zur Durchiteration von String-Elementen (Zeichen). Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 2700
url: /de/cpp/system.globalization/textelementenumerator/
---
## TextElementEnumerator class


Aufzählung zur Durchiteration von String-Elementen (Zeichen). Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/)-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class TextElementEnumerator : public virtual System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Current](./get_current/)() const | Liefert das aktuelle Textelement. |
| [get_ElementIndex](./get_elementindex/)() const | Liefert den Index des aktuellen Textelements. |
| [GetTextElement](./gettextelement/)() const | Liefert das aktuelle Element. |
| [MoveNext](./movenext/)() | Wechselt zum nächsten Element. |
| [operator=](./operator=/)(const TextElementEnumerator\&) |  |
| [Reset](./reset/)() | Setzt den Aufzähler auf die Anfangsposition. |
| [TextElementEnumerator](./textelementenumerator/)(const TextElementEnumerator\&) |  |
## Siehe auch

* Class [Object](../../system/object/)
* Namespace [System::Globalization](../)
* Library [Aspose.PUB for C++](../../)
