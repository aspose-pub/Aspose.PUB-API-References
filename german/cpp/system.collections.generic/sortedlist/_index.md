---
title: "Klasse System::Collections::Generic::SortedList"
linktitle: "SortedList"
second_title: "Aspose.PUB für C++"
description: "Klasse System::Collections::Generic::SortedList. Sortierte Liste, die die FlatMap-Struktur kapselt. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 4200
url: /de/cpp/system.collections.generic/sortedlist/
---
## SortedList class


Sortierte Liste, die die FlatMap-Struktur kapselt. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
template<typename TKey,typename TValue>class SortedList : public System::Collections::Generic::SortedListHelper<TKey, TValue>,
                                                          public System::Collections::Generic::BaseDictionary<Detail::FlatMap<TKey, TValue, ComparerAdapter<TKey>>>
```


| Parameter | Beschreibung |
| --- | --- |
| TKey | Schlüsseltyp. |
| TValue | Wertetyp. |
## Nested classes

* Class [Enumerator](./enumerator/)
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [crbegin](./crbegin/)() const | Gibt einen Reverse-Iterator zum letzten const‑qualifizierten Element der Sammlung zurück (erstes im Reverse). |
| [crend](./crend/)() const | Gibt einen Reverse-Iterator für ein nicht existierendes const‑qualifiziertes Element vor dem Beginn der Sammlung zurück. |
| [get_Capacity](./get_capacity/)() const | Liefert die aktuelle Kapazität der Liste. |
| [get_Keys](./get_keys/)() const |  |
| [get_Values](./get_values/)() const |  |
| [GetEnumerator](./getenumerator/)() override | Gibt einen Enumerator zurück, der durch die aktuelle Liste iteriert. |
| [IndexOfKey](./indexofkey/)(TKey) const | Sucht nach einem bestimmten Schlüssel. |
| [IndexOfValue](./indexofvalue/)(TValue) const | Sucht nach einem bestimmten Wert. |
| [rbegin](./rbegin/)() | Gibt einen Reverse-Iterator zum letzten Element der Sammlung zurück (erstes im Reverse). |
| [rbegin](./rbegin/)() const | Gibt einen Reverse-Iterator zum letzten Element der const‑qualifizierten Sammlung zurück (erstes im Reverse). |
| [RemoveAt](./removeat/)(int) | Entfernt das Element an der angegebenen Position. |
| [rend](./rend/)() | Gibt einen Reverse-Iterator für ein nicht existierendes Element vor dem Beginn der Sammlung zurück. |
| [rend](./rend/)() const | Gibt einen Reverse-Iterator für ein nicht existierendes Element vor dem Beginn der const‑qualifizierten Sammlung zurück. |
| [set_Capacity](./set_capacity/)(int) | Setzt die Kapazität der aktuellen Liste. |
| [SortedList](./sortedlist/)() | Erstellt eine leere Liste. |
| [SortedList](./sortedlist/)(const SharedPtr\<IComparer\<TKey\>\>\&) | Erstellt eine leere Liste. |
| [SortedList](./sortedlist/)(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) | Kopierkonstruktor. |
| [SortedList](./sortedlist/)(const map_t\&) | Kopierkonstruktor. |
| [SortedList](./sortedlist/)(int) | Erstellt eine leere Liste. |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [const_iterator](./const_iterator/) | Const-Iterator-Typ. |
| [const_reverse_iterator](./const_reverse_iterator/) | Const-Umkehr-Iterator-Typ. |
| [IEnumerablePtr](./ienumerableptr/) | Sammlung von Paaren desselben Typs. |
| [IEnumeratorPtr](./ienumeratorptr/) | [Enumerator](./enumerator/) Typ. |
| [iterator](./iterator/) | Iterator-Typ. |
| [KeyCollection](./keycollection/) | Schlüssel‑Sammlungstyp. |
| [KVPair](./kvpair/) | Typ für Schlüssel-Wert-Paar. |
| [map_t](./map_t/) | Zugrundeliegender Datentyp. |
| [Ptr](./ptr/) | Zeigertyp. |
| [reverse_iterator](./reverse_iterator/) | Umkehr-Iterator-Typ. |
| [this_t](./this_t/) | Dieser Typ. |
| [ValueCollection](./valuecollection/) | Wert‑Sammlungstyp. |

## Siehe auch

* Class [SortedListHelper](../sortedlisthelper/)
* Class [BaseDictionary](../basedictionary/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
