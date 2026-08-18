---
title: "System::Collections::Generic::IDictionary Klasse"
linktitle: "IDictionary"
second_title: "Aspose.PUB für C++"
description: "System::Collections::Generic::IDictionary Klasse. Interface für dictionary‑ähnliche Container. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() alloziert werden. Erstelle niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion‑Fehlern führen kann. Wickele diese Klasse stets in einen System::SmartPtr‑Zeiger ein und verwende diesen Zeiger, um sie als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 2100
url: /de/cpp/system.collections.generic/idictionary/
---
## IDictionary class


Interface für dictionary‑ähnliche Container. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstelle niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion‑Fehlern führen kann. Wickele diese Klasse stets in den [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwende diesen Zeiger, um sie als Argument an Funktionen zu übergeben.

```cpp
template<typename TKey,typename TValue>class IDictionary : public System::Collections::Generic::ICollection<KeyValuePair<TKey, TValue>>
```


| Parameter | Beschreibung |
| --- | --- |
| TKey | Schlüsseltyp. |
| TValue | Wertetyp. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual [Add](./add/)(const TKey\&, const TValue\&) | Fügt ein Schlüssel‑Wert‑Paar in den Container ein. |
| virtual [ContainsKey](./containskey/)(const TKey\&) const | Prüft, ob der Container den Schlüssel enthält. |
| [CopyTo](./copyto/)(ArrayPtr\<KeyValuePair\<TKey, TValue\>\>, int) override | Kopiert den Inhalt des Dictionaries in bestehende Array‑Elemente. |
| [get_IsFixedSize](./get_isfixedsize/)() const | Prüft, ob die Größe der Sammlung fest ist. |
| [get_IsSynchronized](./get_issynchronized/)() const | Überprüft, ob der Container thread-sicher ist. |
| virtual [get_Keys](./get_keys/)() const | Greift auf die Schlüsselsammlung zu. |
| virtual [get_Values](./get_values/)() const | Greift auf die Wertsammlung zu. |
| virtual [GetValueOrDefault](./getvalueordefault/)(const TKey\&) const | Gibt den Wert zurück, wenn gefunden; sonst **Value()**. |
| virtual [GetValueOrDefault](./getvalueordefault/)(const TKey\&, const TValue\&) const | Gibt den Wert zurück, wenn gefunden; sonst **defaultValue**. |
| virtual [GetValueOrNull](./getvalueornull/)(const TKey\&) const | Gibt den Wert zurück, wenn gefunden; sonst **null**, sinnvoll nur für Referenztypen. |
| virtual [idx_get](./idx_get/)(const TKey\&) const | Getter‑Funktion. |
| virtual [idx_set](./idx_set/)(const TKey\&, TValue) | Setter‑Funktion. |
| virtual [Remove](./remove/)(const TKey\&) | Entfernt den Schlüssel aus dem Container. |
| virtual [TryGetValue](./trygetvalue/)(const TKey\&, TValue\&) const | Sucht nach dem Wert und ruft ihn ab, wenn er gefunden wird. |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [BaseType](./basetype/) | RTTI-Informationen. |
| [KeyValuePairType](./keyvaluepairtype/) | Typ für Schlüssel-Wert-Paar. |

## Siehe auch

* Class [ICollection](../icollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
