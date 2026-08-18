---
title: "System::Collections::Generic::Queue class"
linktitle: "Queue"
second_title: "Aspose.PUB für C++"
description: "System::Collections::Generic::Queue class. Vorwärtsdeklaration der Queue-Klasse in C++."
type: docs
weight: 3600
url: /de/cpp/system.collections.generic/queue/
---
## Queue class


[Queue](./) class forward declaration.

```cpp
template<typename T>class Queue : public System::Collections::Generic::IEnumerable<T>
```


| Parameter | Beschreibung |
| --- | --- |
| T | Elementtyp. |
## Nested classes

* Class [Enumerator](./enumerator/)
## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual [Clear](./clear/)() | Löscht alle Elemente in der Queue. |
| virtual [Contains](./contains/)(const T\&) const | Prüft, ob die Queue ein bestimmtes Element enthält, indem der Operator == zum Vergleich der Elemente verwendet wird. |
| [data](./data/)() | Zugriff auf die zugrunde liegende Datenstruktur. |
| [data](./data/)() const | Zugriff auf die zugrunde liegende Datenstruktur. |
| [Dequeue](./dequeue/)() | Liefert das Element vom Anfang der Queue. |
| [Enqueue](./enqueue/)(const T\&) | Fügt das Element am Ende der Warteschlange ein. |
| virtual [get_Count](./get_count/)() const | Ermittelt die Anzahl der Elemente in der Warteschlange. |
| [GetEnumerator](./getenumerator/)() override | Erhält einen Enumerator, um die Warteschlange zu durchlaufen. |
| [Peek](./peek/)() | Liest das Element am Anfang der Warteschlange, entfernt es jedoch nicht aus der Warteschlange. |
| [Queue](./queue/)() | Erstellt eine leere Warteschlange. |
| [Queue](./queue/)(int) | Erstellt eine leere Warteschlange. |
| [Queue](./queue/)(const SharedPtr\<IEnumerable\<T\>\>\&) | Kopierkonstruktor. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Liefert die Implementierung des begin‑const‑Iterators für den aktuellen Container. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Liefert die Implementierung des begin‑Iterators für den aktuellen Container. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Liefert die Implementierung des end‑const‑Iterators für den aktuellen Container. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Liefert die Implementierung des end‑Iterators für den aktuellen Container. |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [IEnumerablePtr](./ienumerableptr/) | Container von Elementen desselben Typs. |
| [IEnumeratorPtr](./ienumeratorptr/) | [Enumerator](./enumerator/) Typ. |
| [queue_t](./queue_t/) | RTTI-Informationen. |
| [ValueType](./valuetype/) | Dieser Typ. |
## Hinweise


[Queue](./) container wrapping STL list. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.


```cpp
#include <system/collections/queue.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

void PrintItems(const SmartPtr<IEnumerable<int>> &queue)
{
  for (const int item: queue)
  {
    std::cout << item << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // Erstelle eine Instanz der Queue-Klasse.
  auto queue = MakeObject<Queue<int>>();

  // Fülle die Warteschlange.
  queue->Enqueue(1);
  queue->Enqueue(2);
  queue->Enqueue(3);

  // Gib das erste Element der Warteschlange aus. Die Peek-Methode entfernt kein Element aus der Warteschlange.
  std::cout << queue->Peek() << std::endl;
  // Gib die Elemente der Warteschlange aus.
  PrintItems(queue);

  // Gib das erste Element der Warteschlange aus. Die Dequeue-Methode entfernt ein Element aus der Warteschlange.
  std::cout << queue->Dequeue() << std::endl;
  // Gib die Elemente der Warteschlange aus.
  PrintItems(queue);

  return 0;
}
/*
This code example produces the following output:
1
1 2 3
1
2 3
*/
```

## Siehe auch

* Class [IEnumerable](../ienumerable/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
