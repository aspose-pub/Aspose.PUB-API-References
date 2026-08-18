---
title: "System::Collections::Generic::ReverseEnumerator Klasse"
linktitle: "ReverseEnumerator"
second_title: "Aspose.PUB für C++"
description: "System::Collections::Generic::ReverseEnumerator Klasse. Enumerator, der den Container rückwärts durchläuft. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 3800
url: /de/cpp/system.collections.generic/reverseenumerator/
---
## ReverseEnumerator class


Enumerator, der den Container rückwärts durchläuft. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
template<typename Container,typename Element>class ReverseEnumerator : public System::Collections::Generic::IEnumerator<typename Container::value_type>
```


| Parameter | Beschreibung |
| --- | --- |
| Container | Container, durch den iteriert werden soll. |
| Element | Elementtyp. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Current](./get_current/)() const override | Liefert das 'aktuelle' Element. |
| [IsValid](./isvalid/)() const | Prüft, ob [MoveNext()](./movenext/) aufgerufen wurde und das Ende nicht erreicht wurde. |
| [MoveNext](./movenext/)() override | Enumerator-ähnliche Inkrementierung. |
| [Reset](./reset/)() override | Setzt den Enumerator zurück, um eine erneute Aufzählung der Elemente zu ermöglichen. |
| [ReverseEnumerator](./reverseenumerator/)(const Object::ptr\&, Container\&) | Initialisiert den Iterator. |
| virtual [~ReverseEnumerator](./~reverseenumerator/)() | Destruktor. |

## Siehe auch

* Class [IEnumerator](../ienumerator/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
