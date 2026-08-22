---
title: "System::DynamicCastArray yöntemi"
linktitle: "DynamicCastArray"
second_title: "Aspose.PUB için C++"
description: "System::DynamicCastArray yöntemi. Belirtilen dizinin öğelerinin farklı bir türe dönüştürülmesini C++'ta gerçekleştirir."
type: docs
weight: 16800
url: /tr/cpp/system/dynamiccastarray/
---
## System::DynamicCastArray method


Belirtilen dizinin öğelerinin farklı bir türe dönüştürülmesini gerçekleştirir.

```cpp
template<class To,class From> SharedPtr<Array<To>> System::DynamicCastArray(const SharedPtr<Array<From>> &from)
```


| Parametre | Açıklama |
| --- | --- |
| To | Belirtilen dizinin öğelerinin dönüştürüleceği tür |
| From | Dönüştürülecek dizi öğelerinin öğelerinin türü |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| kaynak | const SharedPtr\<Array\<From\>\>\& | Öğeleri dönüştürmek için içeren dizinin paylaşımlı işaretçisi |

### ReturnValue

Yeni bir diziye işaretçi, **To** türündeki öğeleri **from** öğelerine eşdeğer olarak içerir

## Deprecated
Geriye dönük uyumluluk için eklendi. Bunun yerine ExplicitCast kullanın.

## Ayrıca Bakınız

* Typedef [SharedPtr](../sharedptr/)
* Class [Array](../array/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
