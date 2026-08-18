---
title: "System::Collections::Generic::BaseEnumerator Klasse"
linktitle: "BaseEnumerator"
second_title: "Aspose.PUB für C++"
description: "System::Collections::Generic::BaseEnumerator Klasse. Enumerator-Definition, um STL‑artige Typen für C#‑artige Nutzung zu kapseln. Stellt keine Annahmen über die Containerstruktur außer der Existenz eines sequentiellen Iterators. Verwendet die Funktionen begin() und end(). Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 600
url: /de/cpp/system.collections.generic/baseenumerator/
---
## BaseEnumerator class


Enumerator-Definition, um STL‑artige Typen für C#‑artige Nutzung zu kapseln. Stellt keine Annahmen über die Containerstruktur außer der Existenz eines sequentiellen Iterators. Verwendet die Funktionen begin() und end(). Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
template<typename Container,typename Element>class BaseEnumerator : public System::Collections::Generic::IEnumerator<Element>
```


| Parameter | Beschreibung |
| --- | --- |
| Container | STL‑artiger Containertyp. |
| Element | Elementtyp. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [BaseEnumerator](./baseenumerator/)(const Object::ptr\&, Container\&) | Initialisiert den Iterator. |
| [IsValid](./isvalid/)() const | Prüft, ob [MoveNext()](./movenext/) aufgerufen wurde und das Ende nicht erreicht wurde. |
| [MoveNext](./movenext/)() override | Enumerator-ähnliche Inkrementierung. |
| [Reset](./reset/)() override | Setzt den Enumerator zurück, um eine erneute Aufzählung der Elemente zu ermöglichen. |

## Siehe auch

* Class [IEnumerator](../ienumerator/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
