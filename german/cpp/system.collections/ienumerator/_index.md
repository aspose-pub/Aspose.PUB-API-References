---
title: "System::Collections::IEnumerator Klasse"
linktitle: "IEnumerator"
second_title: "Aspose.PUB für C++"
description: "System::Collections::IEnumerator Klasse. Schnittstelle eines Enumerators, der verwendet werden kann, um über einige Elemente zu iterieren. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 600
url: /de/cpp/system.collections/ienumerator/
---
## IEnumerator class


Schnittstelle eines Enumerators, der verwendet werden kann, um über einige Elemente zu iterieren. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class IEnumerator : public virtual System::IDisposable,
                    public virtual System::Object
```


| Parameter | Beschreibung |
| --- | --- |
| T | Elementtyp. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual [Current](./current/)() const | Liefert das aktuelle Element. |
| virtual [get_Current](./get_current/)() const | Liefert das aktuelle Element. |
| virtual [MoveNext](./movenext/)() | Bewegt den Enumerator zum nächsten Element. Wenn zuvor kein Element referenziert wurde, wird die Referenz auf das erste verfügbare Element gesetzt. Wenn das Ende des Containers erreicht wurde, passiert nichts. |
| virtual [Reset](./reset/)() | Setzt den Enumerator auf die Position vor dem ersten Element zurück. |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [ValueType](./valuetype/) | RTTI-Informationen. |

## Siehe auch

* Class [IDisposable](../../system/idisposable/)
* Class [Object](../../system/object/)
* Namespace [System::Collections](../)
* Library [Aspose.PUB for C++](../../)
