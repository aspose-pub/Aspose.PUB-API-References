---
title: "System::Array::Find yöntemi"
linktitle: "Find"
second_title: "Aspose.PUB için C++"
description: "System::Array::Find yöntemi. C++'ta belirtilen dizide, belirtilen koşulu sağlayan ilk öğeyi arar."
type: docs
weight: 5100
url: /tr/cpp/system/array/find/
---
## Array::Find method


Belirtilen dizide, belirtilen koşulun şartlarını sağlayan ilk öğeyi arar.

```cpp
static T System::Array<T>::Find(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arr | System::ArrayPtr\<T\> | [Array](../) içinde bir öğe aramak için |
| eşleşme | System::Predicate\<T\> | Dizi öğeleriyle eşleşmek için koşulları tanımlayan bir predicate |

### ReturnValue

Predicate tarafından tanımlanan koşulları sağlayan dizideki ilk öğenin kopyası, aksi takdirde T tipinin varsayılan değeri

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
