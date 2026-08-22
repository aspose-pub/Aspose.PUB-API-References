---
title: "System::Array::TrueForAll yöntemi"
linktitle: "TrueForAll"
second_title: "Aspose.PUB için C++"
description: "System::Array::TrueForAll yöntemi. Belirtilen dizideki tüm öğelerin C++'ta belirtilen koşulu sağlayıp sağlamadığını belirler."
type: docs
weight: 5900
url: /tr/cpp/system/array/trueforall/
---
## Array::TrueForAll method


Belirtilen dizideki tüm öğelerin, belirtilen koşul tarafından tanımlanan koşulları sağlayıp sağlamadığını belirler.

```cpp
static bool System::Array<T>::TrueForAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arr | System::ArrayPtr\<T\> | Koşullara karşı eşleşecek [Array](../) öğeleri |
| eşleşme | System::Predicate\<T\> | Dizi öğeleriyle eşleşmek için koşulları tanımlayan bir predicate |

### ReturnValue

dizi arr içindeki tüm öğeler koşulu sağlayan eşleşme koşulunu sağlarsa true, aksi takdirde false

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
