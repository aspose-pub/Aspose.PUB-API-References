---
title: "System::CastEnumerableTo yöntemi"
linktitle: "CastEnumerableTo"
second_title: "Aspose.PUB için C++"
description: "System::CastEnumerableTo yöntemi. Belirtilen enumerable nesnesinin öğelerinin farklı bir tipe açık dönüşümünü C++'da gerçekleştirir."
type: docs
weight: 14400
url: /tr/cpp/system/castenumerableto/
---
## System::CastEnumerableTo(const From\&) method


Belirtilen enumerable nesnesinin öğelerinin farklı bir tipe açık dönüşümünü gerçekleştirir.

```cpp
template<class To,class From> std::enable_if<!System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```


| Parametre | Açıklama |
| --- | --- |
| To | Enumerable nesnesinin öğelerini statik olarak dönüştürmek için tip |
| From | Enumerable nesnesinin tipi |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| enumerable | const From\& | Öğeleri dönüştürmek için içeren Enumerable nesnesi |

### ReturnValue

Tipi **To** olan ve **enumerable** öğelerine eşdeğer öğeler içeren yeni bir koleksiyona işaretçi

## Ayrıca Bakınız

* Class [ListPtr](../../system.collections.generic/listptr/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::CastEnumerableTo(const From\&) method


Belirtilen enumerable nesnesinin öğelerinin farklı bir tipe açık dönüşümünü gerçekleştirir.

```cpp
template<class To,class From> std::enable_if<System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```


| Parametre | Açıklama |
| --- | --- |
| To | Enumerable nesnesinin öğelerini statik olarak dönüştürmek için tip |
| From | Enumerable nesnesinin tipi |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| enumerable | const From\& | tanımlı get_Count yöntemi bulunan ve dönüştürülecek öğeleri içeren Enumerable nesnesinin türevidir |

### ReturnValue

Tipi **To** olan ve **enumerable** öğelerine eşdeğer öğeler içeren yeni bir koleksiyona işaretçi

## Ayrıca Bakınız

* Class [ListPtr](../../system.collections.generic/listptr/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
