---
title: "System::SmartPtr::operator* yöntemi"
linktitle: "operator*"
second_title: "Aspose.PUB için C++"
description: "System::SmartPtr::operator* yöntemi. İşaret edilen nesneye referans alır. C++'da işaretçinin null olmadığını doğrular."
type: docs
weight: 2500
url: /tr/cpp/system/smartptr/operator_/
---
## SmartPtr::operator* method


İşaret edilen nesneye referans alır. İşaretçinin null olmadığını doğrular.

```cpp
Pointee_ & System::SmartPtr<T>::operator*() const
```


### ReturnValue

İşaret edilen nesneye referans.

## Ayrıca Bakınız

* Typedef [Pointee_](../pointee_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
---
başlık: System::SmartPtr::operator< yöntemi
linktitle: operator<
second_title: C++ için Aspose.PUB
açıklama: 'System::SmartPtr::operator< yöntemi. C++'da SmartPtr sınıfı için daha az karşılaştırma semantiği sağlar.'
type: docs
weight: 2700
url: /cpp/system/smartptr/operator_/
---
## SmartPtr::operator<(SmartPtr\<Y\> const\&) const method


[SmartPtr](../) sınıfı için daha az karşılaştırma semantiği sağlar.

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(SmartPtr<Y> const &x) const
```


| Parametre | Açıklama |
| --- | --- |
| Y | Mevcut işaretçiye karşılaştırılacak işaretçi türü. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | SmartPtr\<Y\> const\& | Mevcut işaretçiye karşılaştırılacak işaretçi. |

### ReturnValue

[SmartPtr](../) tarafından referans alınan nesne x'ten 'less' ise doğru, aksi takdirde yanlıştır.

## Ayrıca Bakınız

* Class [SmartPtr](../)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## SmartPtr::operator<(Y *) const method


[SmartPtr](../) sınıfı için daha az karşılaştırma semantiği sağlar.

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(Y *p) const
```


| Parametre | Açıklama |
| --- | --- |
| Y | Mevcut işaretçiye karşılaştırılacak işaretçi türü. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| p | Y * | Mevcut işaretçiye karşılaştırılacak işaretçi. |

### ReturnValue

[SmartPtr](../) tarafından referans alınan nesne p'den 'less' ise doğru, aksi takdirde yanlıştır.

## Ayrıca Bakınız

* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
