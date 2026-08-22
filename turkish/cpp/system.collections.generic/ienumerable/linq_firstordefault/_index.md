---
title: "System::Collections::Generic::IEnumerable::LINQ_FirstOrDefault method"
linktitle: "LINQ_FirstOrDefault"
second_title: "Aspose.PUB için C++"
description: "System::Collections::Generic::IEnumerable::LINQ_FirstOrDefault yöntemi. C++'da bir dizinin ilk öğesini döndürür, ya da dizi boşsa varsayılan bir değer verir."
type: docs
weight: 1600
url: /tr/cpp/system.collections.generic/ienumerable/linq_firstordefault/
---
## IEnumerable::LINQ_FirstOrDefault() method


Bir dizinin ilk öğesini döndürür, ya da dizi boşsa varsayılan bir değer döndürür.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault()
```


### ReturnValue

Dizideki ilk öğe veya dizi boşsa varsayılan oluşturulmuş değer.

## Ayrıca Bakınız

* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PUB for C++](../../../)
## IEnumerable::LINQ_FirstOrDefault(std::function\<bool(T)>) method


Koşulu sağlayan dizinin ilk öğesini döndürür veya böyle bir öğe bulunamazsa varsayılan bir değer döndürür.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault(std::function<bool(T)> predicate)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| koşul | std::function\<bool(T)> | Her öğeyi bir koşul için test eden bir işlev. |

### ReturnValue

Kaynak boşsa veya hiçbir öğe koşul tarafından belirtilen testi geçmezse default(T); aksi takdirde, koşul tarafından belirtilen testi geçen ilk öğe.

## Ayrıca Bakınız

* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PUB for C++](../../../)
