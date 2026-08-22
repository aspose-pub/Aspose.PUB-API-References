---
title: "System::ForceStaticCast yöntemi"
linktitle: "ForceStaticCast"
second_title: "Aspose.PUB için C++"
description: "System::ForceStaticCast yöntemi. C++'da SmartPtr nesneleri üzerinde gerçek static cast gerçekleştirir."
type: docs
weight: 19000
url: /tr/cpp/system/forcestaticcast/
---
## System::ForceStaticCast method


[SmartPtr](../smartptr/) nesneleri üzerinde gerçek static cast gerçekleştirir.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ForceStaticCast(SmartPtr<TFrom> const &obj)
```


| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef işaret edilen tip. |
| TFrom | Kaynak işaret edilen tip. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> const\& | Kaynak işaretçi. |

### ReturnValue

Dönüştürme izinliyse sonuç döndürülür, aksi takdirde davranış tanımsızdır.

## Ayrıca Bakınız

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
