---
title: "System::MakeObject method"
linktitle: "MakeObject"
second_title: "Aspose.PUB için C++"
description: "System::MakeObject yöntemi. Nesneyi yığında oluşturur ve C++'ta ona paylaşımlı bir gösterici döndürür."
type: docs
weight: 21600
url: /tr/cpp/system/makeobject/
---
## System::MakeObject(Args\&&...) method


Nesneyi yığında oluşturur ve ona paylaşımlı bir gösterici döndürür.

```cpp
template<class T,class ...> std::enable_if<!IsSmartPtr<T>::value, SmartPtr<T>>::type System::MakeObject(Args &&... args)
```


| Parametre | Açıklama |
| --- | --- |
| T | Örneklenmek istenen sınıf. |
| Args | Yapıcı argümanlarının türleri. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| argümanlar | Args\&&... | Yapıcı argümanları. |

### ReturnValue

[SmartPtr](../smartptr/) to newly created object, always in shared mode.

## Ayrıca Bakınız

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::MakeObject(Args\&&...) method


Nesneyi yığında oluşturur ve ona paylaşımlı bir gösterici döndürür.

```cpp
template<class T,class ...> std::enable_if<IsSmartPtr<T>::value, T>::type System::MakeObject(Args &&... args)
```


| Parametre | Açıklama |
| --- | --- |
| T | [SmartPtr](../smartptr/) örneklenmek istenen sınıfa ait. |
| Args | Yapıcı argümanlarının türleri. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| argümanlar | Args\&&... | Yapıcı argümanları. |

### ReturnValue

[SmartPtr](../smartptr/) to newly created object, always in shared mode.

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
