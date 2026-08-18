---
title: "System::Collections::Generic::KeyValuePair Klasse"
linktitle: "KeyValuePair"
second_title: "Aspose.PUB für C++"
description: "System::Collections::Generic::KeyValuePair class. Paar aus Schlüssel und Wert. Dieser Typ sollte auf dem Stack alloziert und an Funktionen per Wert oder Referenz übergeben werden. Verwenden Sie niemals die Klasse System::SmartPtr, um Objekte dieses Typs in C++ zu verwalten."
type: docs
weight: 2900
url: /de/cpp/system.collections.generic/keyvaluepair/
---
## KeyValuePair class


Paar aus Schlüssel und Wert. Dieser Typ sollte auf dem Stack alloziert und an Funktionen per Wert oder Referenz übergeben werden. Verwenden Sie niemals die Klasse [System::SmartPtr](../../system/smartptr/), um Objekte dieses Typs zu verwalten.

```cpp
template<typename TKey,typename TValue>class KeyValuePair
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Key](./get_key/)() const | Liefert den Schlüssel. |
| [get_Value](./get_value/)() const | Liefert den Wert. |
| [GetHashCode](./gethashcode/)() const | Berechnet den Hash des Schlüssel‑Wert‑Paares, indem die Hashes von Schlüssel und Wert xor‑verknüpft werden. |
| [IsNull](./isnull/)() const | Gibt immer false zurück. |
| [KeyValuePair](./keyvaluepair/)() | Null‑Initialisierer für Schlüssel‑Wert‑Paar. |
| [KeyValuePair](./keyvaluepair/)(const TKey\&, const TValue\&) | Konstruktor. |
| [KeyValuePair](./keyvaluepair/)(const std::pair\<OtherK, OtherV\>\&) | Typkonvertierungskonstruktor. |
| [operator<](./operator_/)(const KeyValuePair\&) const | Patch für Klassen, die von IComparer<KeyValuePair<TKey, TValue>> erben, vergleicht nichts. |
| [ToString](./tostring/)() const | Konvertiert das Schlüssel‑Wert‑Paar in einen String. |

## Siehe auch

* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
