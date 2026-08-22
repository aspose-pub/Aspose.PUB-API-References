---
title: "System::Collections::Generic::IEnumerable::LINQ_Max yöntemi"
linktitle: "LINQ_Max"
second_title: "Aspose.PUB için C++"
description: "C++'da System::Collections::Generic::IEnumerable sınıfının LINQ_Max yöntemini nasıl kullanılır."
type: docs
weight: 2000
url: /tr/cpp/system.collections.generic/ienumerable/linq_max/
---
## IEnumerable::LINQ_Max(const Func\<Source, ResultType\>\&) method




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<Source, ResultType> &selector)
```

## Ayrıca Bakınız

* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PUB for C++](../../../)
## IEnumerable::LINQ_Max(const Func\<T, ResultType\>\&) method


Genel bir dizideki her öğeye bir dönüşüm işlevi uygular ve elde edilen maksimum değeri döndürür.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<T, ResultType> &selector)
```


| Parametre | Açıklama |
| --- | --- |
| ResultType | Seçici tarafından döndürülen değerin türü. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| selector | const Func\<T, ResultType\>\& | Her bir elemana uygulanacak bir dönüşüm işlevi. |

### ReturnValue

Dizideki maksimum değer.

## Ayrıca Bakınız

* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PUB for C++](../../../)
