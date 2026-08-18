---
title: "System::Collections::Generic::SortedDictionary Klasse"
linktitle: "SortedDictionary"
second_title: "Aspose.PUB für C++"
description: "System::Collections::Generic::SortedDictionary Klasse. Vorwärtsdeklaration des Typs SortedDictionary in C++."
type: docs
weight: 4000
url: /de/cpp/system.collections.generic/sorteddictionary/
---
## SortedDictionary class


Vorwärtsdeklaration des sortierten Wörterbuchtyps.

```cpp
template<typename TKey,typename TValue>class SortedDictionary : public System::Collections::Generic::BaseDictionary<std::map<TKey, TValue, ComparerAdapter<BasePointerType<TKey>::type>, ASPOSE_MAP_ALLOCATOR_TYPE(TKey, TValue)>>
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
| [get_Comparer](./get_comparer/)() const | Gibt den IComparer<TKey> zurück, der zum Sortieren der Elemente des SortedDictionary<TKey,TValue> verwendet wird. |
| static [GetDefaultKeyComparer](./getdefaultkeycomparer/)() | Singleton‑Zugriffsfunktion. |
| [GetEnumerator](./getenumerator/)() override | Gibt den Enumerator zurück, um das aktuelle Wörterbuch zu durchlaufen. |
| [rbegin](./rbegin/)() | Gibt einen Reverse-Iterator zum letzten Element der Sammlung zurück (erstes im Reverse). |
| [rbegin](./rbegin/)() const | Gibt einen Reverse-Iterator zum letzten Element der const‑qualifizierten Sammlung zurück (erstes im Reverse). |
| [rend](./rend/)() | Gibt einen Reverse-Iterator für ein nicht existierendes Element vor dem Beginn der Sammlung zurück. |
| [rend](./rend/)() const | Gibt einen Reverse-Iterator für ein nicht existierendes Element vor dem Beginn der const‑qualifizierten Sammlung zurück. |
| [SortedDictionary](./sorteddictionary/)() | Erstellt ein leeres Wörterbuch. |
| [SortedDictionary](./sorteddictionary/)(const SharedPtr\<IComparer\<typename BasePointerType\<TKey\>::type\>\>\&) | Erstellt ein leeres Wörterbuch. |
| [SortedDictionary](./sorteddictionary/)(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) | Kopierkonstruktor. |
| [SortedDictionary](./sorteddictionary/)(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IComparer\<typename BasePointerType\<TKey\>::type\>\>\&) | Kopierkonstruktor. |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [const_iterator](./const_iterator/) | Const-Iterator-Typ. |
| [const_reverse_iterator](./const_reverse_iterator/) | Const-Umkehr-Iterator-Typ. |
| [IEnumerablePtr](./ienumerableptr/) | Sammlung gleicher Elemente. |
| [IEnumeratorPtr](./ienumeratorptr/) | [Enumerator](./enumerator/) Typ. |
| [iterator](./iterator/) | Iterator-Typ. |
| [KeyCollection](./keycollection/) | Schlüssel‑Sammlungstyp. |
| [KVPair](./kvpair/) | Schlüssel‑Wert‑Paar‑Typ. |
| [map_t](./map_t/) | Zugrundeliegender Datentyp. |
| [Ptr](./ptr/) | Zeigertyp. |
| [reverse_iterator](./reverse_iterator/) | Umkehr-Iterator-Typ. |
| [this_t](./this_t/) | Selbsttyp. |
| [ValueCollection](./valuecollection/) | Wert‑Sammlungstyp. |
## Hinweise


Sortierte Wörterbuchklasse, die STL-Map kapselt. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

## Siehe auch

* Class [BaseDictionary](../basedictionary/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
