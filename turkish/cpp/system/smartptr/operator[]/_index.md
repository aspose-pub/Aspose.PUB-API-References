---
title: "System::SmartPtr::operator[] yöntemi"
linktitle: "operator[]"
second_title: "Aspose.PUB için C++"
description: "System::SmartPtr::operator[] yöntemi. Dizi öğeleri için erişimci. Yalnızca SmartPtr_, C++'da System::Array özelleştirmesi ise derlenir."
type: docs
weight: 3000
url: /tr/cpp/system/smartptr/operator[]/
---
## SmartPtr::operator[] method


Dizi öğeleri için erişimci. Yalnızca SmartPtr_, [System::Array](../../array/) özelleştirmesi ise derlenir.

```cpp
template<typename IdxType> decltype(System::Details::GetByIndex(std::declval<const SmartPtr_ *>(), std::declval<IdxType>())) System::SmartPtr<T>::operator[](IdxType idx) const
```


| Parametre | Açıklama |
| --- | --- |
| IdxType | İndeksin tipi (tam sayı varsayılarak). |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| idx | IdxType | Dizideki indeks. |

### ReturnValue

[Array](../../array/) value at idx position.

## Ayrıca Bakınız

* Typedef [SmartPtr_](../smartptr_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
