---
title: "System::Cast method"
linktitle: "Cast"
second_title: "Aspose.PUB için C++"
description: "System::Cast yöntemi. C++'ta SmartPtr nesneleri üzerinde dönüşüm (cast) gerçekleştirir."
type: docs
weight: 14200
url: /tr/cpp/system/cast/
---
## System::Cast method


[SmartPtr](../smartptr/) nesneleri üzerinde dönüşüm (cast) gerçekleştirir.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast(SmartPtr<TFrom> const &obj)
```


| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef işaret edilen tip. |
| TFrom | Kaynak işaret edilen tip. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> const\& | Kaynak işaretçi. |

### ReturnValue

Dönüşüm izinliyse dönüşüm sonucu.

## Ayrıca Bakınız

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
