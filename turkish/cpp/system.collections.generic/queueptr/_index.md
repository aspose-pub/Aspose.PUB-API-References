---
title: "System::Collections::Generic::QueuePtr sınıfı"
linktitle: "QueuePtr"
second_title: "Aspose.PUB için C++"
description: "System::Collections::Generic::QueuePtr sınıfı. Kuyruk işaretçisi. Bu tür, diğer nesnelerin silinmesini yönetmek için bir işaretçidir. C++'ta yığıt üzerinde ayrılmalı ve fonksiyonlara değer olarak ya da const referansla geçirilmelidir."
type: docs
weight: 3700
url: /tr/cpp/system.collections.generic/queueptr/
---
## QueuePtr class


[Queue](../queue/) pointer. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<typename T>class QueuePtr : public System::SmartPtr<Queue<T>>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [QueuePtr](./queueptr/)() | Null işaretçi oluşturur. |
| [QueuePtr](./queueptr/)(const SharedPtr\<Queue\<T\>\>\&) | Belirli bir kuyruğa işaretçi oluşturur. |

## Ayrıca Bakınız

* Class [SmartPtr](../../system/smartptr/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
