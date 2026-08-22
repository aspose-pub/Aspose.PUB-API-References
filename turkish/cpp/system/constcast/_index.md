---
title: "System::ConstCast yöntemi"
linktitle: "ConstCast"
second_title: "Aspose.PUB için C++"
description: "System::ConstCast yöntemi. C++'da kullanımdan kaldırılmış dönüşümlerin sonu."
type: docs
weight: 15000
url: /tr/cpp/system/constcast/
---
## System::ConstCast method


Kullanımdan kaldırılmış dönüşümlerin sonu.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ConstCast(const SmartPtr<TFrom> &obj)
```


| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef işaret edilen tip. |
| TFrom | Kaynak işaret edilen tip. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const SmartPtr\<TFrom\>\& | Kaynak işaretçi. |

### ReturnValue

Dönüştürme izinliyse dönüş sonucu, aksi takdirde nullptr.
## Açıklamalar


[SmartPtr](../smartptr/) nesneleri üzerinde const dönüşümü gerçekleştirir.
## Ayrıca Bakınız

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
