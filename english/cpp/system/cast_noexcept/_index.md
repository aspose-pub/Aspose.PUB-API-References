---
title: System::Cast_noexcept method
linktitle: Cast_noexcept
second_title: Aspose.PUB for C++
description: 'System::Cast_noexcept method. Performs cast on SmartPtr objects in C++.'
type: docs
weight: 14000
url: /cpp/system/cast_noexcept/
---
## System::Cast_noexcept method


Performs cast on [SmartPtr](../smartptr/) objects.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast_noexcept(SmartPtr<TFrom> const &obj)
```


| Parameter | Description |
| --- | --- |
| TTo | Target pointee type. |
| TFrom | Source pointee type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> const\& | Source pointer. |

### ReturnValue

Cast result if cast is allowed or nullptr otherwise.

## See Also

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)