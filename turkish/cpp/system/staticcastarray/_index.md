---
title: "System::StaticCastArray yöntemi"
linktitle: "StaticCastArray"
second_title: "Aspose.PUB için C++"
description: "System::StaticCastArray yöntemi. Belirtilen dizinin öğelerini farklı bir tipe dönüştürür. C++'da From bir SmartPtr nesnesi olduğunda geçersiz kılma."
type: docs
weight: 36300
url: /tr/cpp/system/staticcastarray/
---
## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) method


Belirtilen dizinin öğelerinin farklı bir türe dönüştürülmesini gerçekleştirir. From bir [SmartPtr](../smartptr/) nesnesi olduğunda durumlar için geçersiz kılın.

```cpp
template<typename To,typename From> std::enable_if_t<System::IsSmartPtr<From>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```


| Parametre | Açıklama |
| --- | --- |
| To | Belirtilen dizinin öğelerinin dönüştürüleceği tür |
| From | Dönüştürülecek dizi öğelerinin öğelerinin türü |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| kaynak | const System::SharedPtr\<System::Array\<From\>\>\& | Öğeleri dönüştürmek için içeren dizinin paylaşımlı işaretçisi |

### ReturnValue

Yeni bir diziye işaretçi, **To** türündeki öğeleri **from** öğelerine eşdeğer olarak içerir

## Deprecated
Geriye dönük uyumluluk için eklendi. Bunun yerine ExplicitCast kullanın.

## Ayrıca Bakınız

* Typedef [SharedPtr](../sharedptr/)
* Class [Array](../array/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) method


Belirtilen dizinin öğelerinin farklı bir türe dönüştürülmesini gerçekleştirir. From Boxable ve To bir [Object](../object/)[]. durumlar için geçersiz kılın.

```cpp
template<typename To,typename From> std::enable_if_t<!System::IsSmartPtr<From>::value &&System::IsBoxable<From>::value &&std::is_same<To, System::SharedPtr<Object>>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```


| Parametre | Açıklama |
| --- | --- |
| To | Belirtilen dizinin öğelerinin dönüştürüleceği tür |
| From | Dönüştürülecek dizi öğelerinin öğelerinin türü |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| kaynak | const System::SharedPtr\<System::Array\<From\>\>\& | Öğeleri dönüştürmek için içeren dizinin paylaşımlı işaretçisi |

### ReturnValue

Yeni bir diziye işaretçi, **To** türündeki öğeleri **from** öğelerine eşdeğer olarak içerir

## Deprecated
Geriye dönük uyumluluk için eklendi. Bunun yerine ExplicitCast kullanın.

## Ayrıca Bakınız

* Typedef [SharedPtr](../sharedptr/)
* Class [Object](../object/)
* Class [Array](../array/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
