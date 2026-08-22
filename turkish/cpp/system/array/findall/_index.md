---
title: "System::Array::FindAll method"
linktitle: "FindAll"
second_title: "Aspose.PUB için C++"
description: "System::Array::FindAll method. Belirtilen koşulu tanımlayan önermeye uyan tüm öğeleri C++'da alır."
type: docs
weight: 5200
url: /tr/cpp/system/array/findall/
---
## Array::FindAll method


Belirtilen koşul tarafından tanımlanan şartları karşılayan tüm öğeleri alır.

```cpp
static System::ArrayPtr<T> System::Array<T>::FindAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arr | System::ArrayPtr\<T\> | [Array](../) içinde öğeleri aramak için |
| eşleşme | System::Predicate\<T\> | Dizi öğeleriyle eşleşmek için koşulları tanımlayan bir predicate |

### ReturnValue

Belirtilen önermeye tanımlanan koşullara uyan tüm öğeleri içeren bir [Array](../), bulunursa; aksi takdirde boş bir [Array](../).

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
