---
title: "System::Cast_noexcept method"
linktitle: "Cast_noexcept"
second_title: "Aspose.PUB için C++"
description: "System::Cast_noexcept yöntemi. C++'ta SmartPtr nesneleri üzerinde dönüşüm gerçekleştirir."
type: docs
weight: 14300
url: /tr/cpp/system/cast_noexcept/
---
## System::Cast_noexcept method


[SmartPtr](../smartptr/) nesneleri üzerinde dönüşüm (cast) gerçekleştirir.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast_noexcept(SmartPtr<TFrom> const &obj)
```


| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef işaret edilen tip. |
| TFrom | Kaynak işaret edilen tip. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> const\& | Kaynak işaretçi. |

### ReturnValue

Dönüştürme izinliyse dönüş sonucu, aksi takdirde nullptr.

## Ayrıca Bakınız

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
