---
title: "System::Collections::Generic::_ValueList Klasse"
linktitle: "_ValueList"
second_title: "Aspose.PUB für C++"
description: "System::Collections::Generic::_ValueList class. Implementiert die Liste der Werte eines Wörterbuchs. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 400
url: /de/cpp/system.collections.generic/_valuelist/
---
## _ValueList class


Implementiert die Liste der Werte eines Wörterbuchs. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion‑Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/)‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
template<typename Dict>class _ValueList : public System::Collections::Generic::_ValueCollection<Dict>
```


| Parameter | Beschreibung |
| --- | --- |
| Dict | [Dictionary](../dictionary/) Typ. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [_ValueList](./_valuelist/)(const typename Dict::Ptr\&) | Initialisiert die Sammlung, die auf das angegebene Dictionary verweist. |
| virtual [idx_get](./idx_get/)(int) const | Ermittelt den Wert an der angegebenen Position. |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [TValue](./tvalue/) | Wertetyp. |

## Siehe auch

* Class [_ValueCollection](../_valuecollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
