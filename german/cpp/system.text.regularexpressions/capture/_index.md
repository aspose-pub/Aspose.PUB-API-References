---
title: "System::Text::RegularExpressions::Capture Klasse"
linktitle: "Capture"
second_title: "Aspose.PUB für C++"
description: "System::Text::RegularExpressions::Capture Klasse. Ergebnis einer einzelnen Subausdruck-Übereinstimmung. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 100
url: /de/cpp/system.text.regularexpressions/capture/
---
## Capture class


Ergebnis einer einzelnen Subausdruck-Übereinstimmung. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class Capture : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [Capture](./capture/)(const UStringPtr\&, int, int) | Konstruktor. |
| [get_Index](./get_index/)() const | Gibt den Index des erfassten Teilstrings zurück. |
| [get_Length](./get_length/)() const | Gibt die Länge des erfassten Teilstrings zurück. |
| [get_Value](./get_value/)() const | Gibt den erfassten Teilstring zurück. |
| [ToString](./tostring/)() const override | Gibt den erfassten Teilstring zurück. |
## Siehe auch

* Class [Object](../../system/object/)
* Namespace [System::Text::RegularExpressions](../)
* Library [Aspose.PUB for C++](../../)
