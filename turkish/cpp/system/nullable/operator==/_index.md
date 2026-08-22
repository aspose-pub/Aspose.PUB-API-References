---
title: "System::Nullable::operator== yöntemi"
linktitle: "operator=="
second_title: "Aspose.PUB için C++"
description: "System::Nullable::operator== yöntemi. Geçerli nesne tarafından temsil edilen değerin, belirtilen Nullable nesne tarafından temsil edilen değerle C++'ta eşit olup olmadığını belirler."
type: docs
weight: 1900
url: /tr/cpp/system/nullable/operator==/
---
## Nullable::operator==(const Nullable\<T1\>\&) const method


Geçerli nesne tarafından temsil edilen değerin, belirtilen [Nullable](../) nesne tarafından temsil edilen değerle eşit olup olmadığını belirler.

```cpp
template<typename T1> bool System::Nullable<T>::operator==(const Nullable<T1> &other) const
```


| Parametre | Açıklama |
| --- | --- |
| T1 | Karşılaştırılacak [Nullable](../) nesnesinin temel türü |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | const Nullable\<T1\>\& | Karşılaştırılacak [Nullable](../) nesnesine sabit referans |

### ReturnValue

Geçerli nesne tarafından temsil edilen değer, belirtilen [Nullable](../) nesne tarafından temsil edilen değerle eşitse doğru, aksi takdirde - yanlış

## Ayrıca Bakınız

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Nullable::operator==(const T1\&) const method


Mevcut nesne tarafından temsil edilen değerin belirtilen değere eşit olup olmadığını belirler.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator==(const T1 &other) const
```


| Parametre | Açıklama |
| --- | --- |
| T1 | Karşılaştırılacak değerin türü |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| diğer | const T1\& | Karşılaştırılacak değere sabit referans |

### ReturnValue

Geçerli nesne tarafından temsil edilen değer, belirtilen değerle eşitse doğru, aksi takdirde - yanlış

## Ayrıca Bakınız

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Nullable::operator==(std::nullptr_t) const method


Mevcut nesne tarafından temsil edilen değerin null olup olmadığını belirler.

```cpp
bool System::Nullable<T>::operator==(std::nullptr_t) const
```


### ReturnValue

Geçerli nesne tarafından temsil edilen değer null ise doğru, aksi takdirde - yanlış

## Ayrıca Bakınız

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
