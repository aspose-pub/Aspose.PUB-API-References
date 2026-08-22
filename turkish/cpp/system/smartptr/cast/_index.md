---
title: "System::SmartPtr::Cast yöntemi"
linktitle: "Cast"
second_title: "Aspose.PUB için C++"
description: "System::SmartPtr::Cast yöntemi. İşaretçiyi kendi tipine C++'da dönüştürür."
type: docs
weight: 400
url: /tr/cpp/system/smartptr/cast/
---
## SmartPtr::Cast() const method


Göstericiyi kendi tipine dönüştürür.

```cpp
template<class Y,typename Check> std::enable_if_t<std::is_same<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


| Parametre | Açıklama |
| --- | --- |
| Y | İşaret edilen nesnenin hedef tipi. |
| Check | Dönüştürme mevcut değilse istisna fırlatmak için bayraklar. |

### ReturnValue

Her zaman paylaşımlı modda olan, değiştirilen tipteki işaretçi.

## Ayrıca Bakınız

* Class [SmartPtr](../)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## SmartPtr::Cast() const method


Göstericiyi static_cast kullanarak temel tipe dönüştürür.

```cpp
template<class Y,typename Check> std::enable_if_t<!std::is_same<Y, T>::value &&std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


| Parametre | Açıklama |
| --- | --- |
| Y | İşaret edilen nesnenin hedef tipi. |
| Check | Dönüştürme mevcut değilse istisna fırlatmak için bayraklar. |

### ReturnValue

Her zaman paylaşımlı modda olan, değiştirilen tipteki işaretçi.

## Ayrıca Bakınız

* Class [SmartPtr](../)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## SmartPtr::Cast() const method


Göstericiyi dynamic_cast kullanarak türetilmiş tipe dönüştürür.

```cpp
template<class Y,typename Check> std::enable_if_t<Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


| Parametre | Açıklama |
| --- | --- |
| Y | İşaret edilen nesnenin hedef tipi. |
| Check | Dönüştürme mevcut değilse istisna fırlatmak için bayraklar. |

### ReturnValue

Her zaman paylaşımlı kipte olan değiştirilen tipteki işaretçi. Dönüştürme mevcut değilse InvalidCastException fırlatır.

## Ayrıca Bakınız

* Class [SmartPtr](../)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## SmartPtr::Cast() const method


Göstericiyi dynamic_cast kullanarak türetilmiş tipe dönüştürür.

```cpp
template<class Y,typename Check> std::enable_if_t<!Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


| Parametre | Açıklama |
| --- | --- |
| Y | İşaret edilen nesnenin hedef tipi. |
| Check | Dönüştürme mevcut değilse istisna fırlatmak için bayraklar. |

### ReturnValue

Her zaman paylaşımlı kipte olan değiştirilen tipteki işaretçi. Dönüştürme mevcut değilse nullptr döndürür.

## Ayrıca Bakınız

* Class [SmartPtr](../)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
