---
title: "System::Collections::Generic::QueuePtr Klasse"
linktitle: "QueuePtr"
second_title: "Aspose.PUB für C++"
description: "System::Collections::Generic::QueuePtr class. Queue‑Zeiger. Dieser Typ ist ein Zeiger, um die Löschung anderer object''s zu verwalten. Er sollte auf dem Stack alloziert und an Funktionen entweder per Wert oder per const‑Referenz in C++ übergeben werden."
type: docs
weight: 3700
url: /de/cpp/system.collections.generic/queueptr/
---
## QueuePtr class


[Queue](../queue/) pointer. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<typename T>class QueuePtr : public System::SmartPtr<Queue<T>>
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [QueuePtr](./queueptr/)() | Konstruiert Nullzeiger. |
| [QueuePtr](./queueptr/)(const SharedPtr\<Queue\<T\>\>\&) | Konstruiert einen Zeiger auf eine bestimmte Warteschlange. |

## Siehe auch

* Class [SmartPtr](../../system/smartptr/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
