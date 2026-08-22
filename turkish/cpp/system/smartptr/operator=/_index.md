---
title: "System::SmartPtr::operator= yöntemi"
linktitle: "operator="
second_title: "Aspose.PUB için C++"
description: "System::SmartPtr::operator= yöntemi. SmartPtr nesnesini kopya ataması yapar. Gerekli tip dönüşümlerini C++'ta gerçekleştirir."
type: docs
weight: 2800
url: /tr/cpp/system/smartptr/operator=/
---
## SmartPtr::operator=(const SmartPtr\<Q\>\&) method


Kopya atama yapar [SmartPtr](../) nesnesine. Gerekli tip dönüşümlerini gerçekleştirir.

```cpp
template<typename Q> SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr<Q> &x)
```


| Parametre | Açıklama |
| --- | --- |
| Q | x tarafından işaret edilen nesnenin tipi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | const SmartPtr\<Q\>\& | Kopya atama için gösterici. |

### ReturnValue

Bu nesneye referans.

## Ayrıca Bakınız

* Typedef [SmartPtr_](../smartptr_/)
* Class [SmartPtr](../)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## SmartPtr::operator=(const SmartPtr_\&) method


Kopya atama yapar [SmartPtr](../) nesnesine.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr_ &x)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | const SmartPtr_\& | Kopya atama için gösterici. |

### ReturnValue

Bu nesneye referans.

## Ayrıca Bakınız

* Typedef [SmartPtr_](../smartptr_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## SmartPtr::operator=(Pointee_ *) method


Ham göstericiyi [SmartPtr](../) nesnesine atar.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(Pointee_ *p)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| p | Pointee_ * | Atanacak gösterici değeri. |

### ReturnValue

Bu nesneye referans.

## Ayrıca Bakınız

* Typedef [SmartPtr_](../smartptr_/)
* Typedef [Pointee_](../pointee_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## SmartPtr::operator=(SmartPtr_\&&) method


Taşıma ataması yapar [SmartPtr](../) nesnesine. x kullanılamaz hâle gelir.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(SmartPtr_ &&x) noexcept
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | SmartPtr_\&& | Taşıma ataması için gösterici. |

### ReturnValue

Bu nesneye referans.

## Ayrıca Bakınız

* Typedef [SmartPtr_](../smartptr_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## SmartPtr::operator=(std::nullptr_t) method


İşaretçi değerini nullptr olarak ayarlar.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(std::nullptr_t)
```


### ReturnValue

Bu nesneye referans.

## Ayrıca Bakınız

* Typedef [SmartPtr_](../smartptr_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
