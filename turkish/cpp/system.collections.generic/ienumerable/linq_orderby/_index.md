---
title: "System::Collections::Generic::IEnumerable::LINQ_OrderBy metodu"
linktitle: "LINQ_OrderBy"
second_title: "Aspose.PUB için C++"
description: "C++'da System::Collections::Generic::IEnumerable sınıfının LINQ_OrderBy metodunu nasıl kullanılır?"
type: docs
weight: 2300
url: /tr/cpp/system.collections.generic/ienumerable/linq_orderby/
---
## IEnumerable::LINQ_OrderBy(const Func\<Source, Key\>\&) method




```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<Source, Key> &keySelector)
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PUB for C++](../../../)
## IEnumerable::LINQ_OrderBy(const Func\<T, Key\>\&) method


keySelector tarafından seçilen anahtar değerlerine göre bir dizinin öğelerini artan sırada sıralar.

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<T, Key> &keySelector)
```


| Parametre | Açıklama |
| --- | --- |
| keySelector | Bir öğeden bir anahtar çıkarmak için bir işlev. |

### ReturnValue

Anahtara göre sıralanmış elemanlara sahip bir IOrderedEnumerable

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PUB for C++](../../../)
