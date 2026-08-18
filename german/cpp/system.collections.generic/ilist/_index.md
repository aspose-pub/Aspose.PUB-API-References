---
title: "System::Collections::Generic::IList Klasse"
linktitle: "IList"
second_title: "Aspose.PUB für C++"
description: "System::Collections::Generic::IList Klasse. Schnittstelle eines indizierten Containers von Elementen. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 2600
url: /de/cpp/system.collections.generic/ilist/
---
## IList class


Schnittstelle eines indizierten Containers von Elementen. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen zu übergeben.

```cpp
template<typename T>class IList : public System::Collections::Generic::ICollection<T>
```


| Parameter | Beschreibung |
| --- | --- |
| T | Elementtyp. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_IsFixedSize](./get_isfixedsize/)() | Prüft, ob die Sammlung eine feste Größe hat. |
| virtual [idx_get](./idx_get/)(int) const | Liefert das Element am angegebenen Index. |
| virtual [idx_set](./idx_set/)(int, T) | Setzt das Element am angegebenen Index. |
| virtual [IndexOf](./indexof/)(const T\&) const | Gibt den Index des ersten Auftretens des Elements im Container zurück. |
| virtual [Insert](./insert/)(int, const T\&) | Fügt das Element an der angegebenen Position ein und verschiebt die anderen Elemente. |
| virtual [RemoveAt](./removeat/)(int) | Entfernt das Element am angegebenen Index. |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [BaseType](./basetype/) | RTTI-Informationen. |
| [ThisType](./thistype/) | Dieser Typ. |
| [ValueType](./valuetype/) | Wertetyp. |

## Siehe auch

* Class [ICollection](../icollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
