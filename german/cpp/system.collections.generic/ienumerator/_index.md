---
title: "System::Collections::Generic::IEnumerator Klasse"
linktitle: "IEnumerator"
second_title: "Aspose.PUB für C++"
description: "System::Collections::Generic::IEnumerator Klasse. Schnittstelle eines Enumerators, der verwendet werden kann, um durch einige Elemente zu iterieren. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 2300
url: /de/cpp/system.collections.generic/ienumerator/
---
## IEnumerator class


Schnittstelle eines Enumerators, der verwendet werden kann, um über einige Elemente zu iterieren. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
template<typename T>class IEnumerator : public virtual System::IDisposable,
                                        public System::Details::EnumeratorBasedIterator<T>,
                                        protected System::Details::IteratorPointerUpdater<T, false>
```


| Parameter | Beschreibung |
| --- | --- |
| T | Elementtyp. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [AsVirtualizedIterator](./asvirtualizediterator/)() | Bereitet den Iterator vor, der von der Klasse VirtualizedIterator verwendet werden soll. |
| [CloneIterator](./cloneiterator/)() const override | Klonen des aktuellen Iterators. |
| virtual [Current](./current/)() const | Liefert das aktuelle Element. |
| virtual [get_Current](./get_current/)() const | Liefert das aktuelle Element. |
| [IEnumerator](./ienumerator/)() |  |
| [IncrementIterator](./incrementiterator/)() override | Bewegt den Iterator einen Schritt vorwärts. |
| [InitializeIterator](./initializeiterator/)() override | Führt den ersten Aufruf von [MoveNext()](./movenext/) aus und bereitet das Enumerator-Objekt vor, das von VirtualizedIterator verwendet werden soll. |
| [MarkOwnedByVirtualizedIterator](./markownedbyvirtualizediterator/)() | Markiert den vom virtualisierten Iterator besessenen Enumerator. |
| virtual [MoveNext](./movenext/)() | Bewegt den Enumerator zum nächsten Element. Wenn zuvor kein Element referenziert wurde, wird die Referenz auf das erste verfügbare Element gesetzt. Wenn das Ende des Containers erreicht wurde, passiert nichts. |
| virtual [Reset](./reset/)() | Setzt den Enumerator auf die Position vor dem ersten Element zurück. |
| virtual [~IEnumerator](./~ienumerator/)() |  |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [ValueType](./valuetype/) | Wertetyp. |
## Hinweise



```cpp
#include <system/collections/list.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // Erstellt die List-Klasseninstanz.
  auto collection = MakeObject<List<int>>();

  // Füllt die Liste.
  collection->Add(1);
  collection->Add(2);
  collection->Add(3);

  // Ruft den Enumerator der Liste ab.
  auto enumerator = collection->GetEnumerator();

  while (enumerator->MoveNext())
  {
    // Ermittelt das aktuelle Element und gibt es aus.
    std::cout << enumerator->get_Current() << ' ';
  }

  // Setzt den Enumerator zurück.
  enumerator->Reset();

  return 0;
}
/*
This code example produces the following output:
1 2 3
*/
```

## Siehe auch

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
