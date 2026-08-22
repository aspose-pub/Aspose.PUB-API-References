---
title: "System::Collections::Generic::IEnumerable::LINQ_GroupBy method"
linktitle: "LINQ_GroupBy"
second_title: "Aspose.PUB için C++"
description: "C++'da System::Collections::Generic::IEnumerable sınıfının LINQ_GroupBy metodunu nasıl kullanılır."
type: docs
weight: 1700
url: /tr/cpp/system.collections.generic/ienumerable/linq_groupby/
---
## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>) method




```cpp
template<typename Key> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Source>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate)
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [IGrouping](../../../system.linq/igrouping/)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PUB for C++](../../../)
## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>) method


Bir dizinin öğelerini gruplar.

```cpp
template<typename Key> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, T>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate)
```


| Parametre | Açıklama |
| --- | --- |
| Anahtar | keyPredicate tarafından döndürülen anahtarın tipi |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| keyPredicate | System::Func\<T, Key\> | Her öğe için anahtarı çıkarmak üzere bir işlev. |

### ReturnValue

Bir [IEnumerable](../) nesnesi, nesneler ve bir anahtar dizisini içerir.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [IGrouping](../../../system.linq/igrouping/)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PUB for C++](../../../)
