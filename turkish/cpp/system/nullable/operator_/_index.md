---
title: "System::Nullable::operator< yöntemi"
linktitle: "operator<"
second_title: "Aspose.PUB için C++"
description: "System::Nullable::operator< yöntemi. Geçerli nesne tarafından temsil edilen değerin, belirtilen Nullable nesne tarafından temsil edilen değerden, bu değerlere operator<() uygulanarak C++'ta daha küçük olup olmadığını belirler."
type: docs
weight: 1600
url: /tr/cpp/system/nullable/operator_/
---
## Nullable::operator<(const Nullable\<T1\>\&) const method


Geçerli nesne tarafından temsil edilen değerin, belirtilen [Nullable](../) nesne tarafından temsil edilen değerden, bu değerlere [operator<()](./) uygulanarak daha küçük olup olmadığını belirler.

```cpp
template<typename T1> bool System::Nullable<T>::operator<(const Nullable<T1> &other) const
```


| Parametre | Açıklama |
| --- | --- |
| T1 | Karşılaştırılacak [Nullable](../) nesnesinin temel türü |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | const Nullable\<T1\>\& | Karşılaştırılacak [Nullable](../) nesnesine sabit referans |

### ReturnValue

Geçerli nesne tarafından temsil edilen değer, belirtilen [Nullable](../) nesne tarafından temsil edilen değerden daha küçükse doğru, aksi takdirde - yanlış

## Ayrıca Bakınız

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Nullable::operator<(const T1\&) const method


Geçerli nesne tarafından temsil edilen değerin, belirtilen değerden, bu değerlere [operator<()](./) uygulanarak daha küçük olup olmadığını belirler.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<(const T1 &other) const
```


| Parametre | Açıklama |
| --- | --- |
| T1 | Karşılaştırılacak değerin türü |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| diğer | const T1\& | Karşılaştırılacak değere sabit referans |

### ReturnValue

Geçerli nesne tarafından temsil edilen değer, belirtilen değerden daha küçükse doğru, aksi takdirde - yanlış

## Ayrıca Bakınız

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Nullable::operator<(std::nullptr_t) const method


Her zaman false döndürür.

```cpp
bool System::Nullable<T>::operator<(std::nullptr_t) const
```

## Ayrıca Bakınız

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
---
başlık: System::Nullable::operator> yöntemi
bağlantı başlığı: operator>
second_title: C++ için Aspose.PUB
description: 'System::Nullable::operator> yöntemi. Geçerli nesne tarafından temsil edilen değerin, belirtilen Nullable nesne tarafından temsil edilen değerden, bu değerlere operator>() uygulanarak C++'ta daha büyük olup olmadığını belirler.'
type: docs
ağırlık: 2000
url: /cpp/system/nullable/operator_/
---
## Nullable::operator>(const Nullable\<T1\>\&) const method


Geçerli nesne tarafından temsil edilen değerin, belirtilen [Nullable](../) nesne tarafından temsil edilen değerden, bu değerlere [operator>()](./) uygulanarak daha büyük olup olmadığını belirler.

```cpp
template<typename T1> bool System::Nullable<T>::operator>(const Nullable<T1> &other) const
```


| Parametre | Açıklama |
| --- | --- |
| T1 | Karşılaştırılacak [Nullable](../) nesnesinin temel türü |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | const Nullable\<T1\>\& | Karşılaştırılacak [Nullable](../) nesnesine sabit referans |

### ReturnValue

Geçerli nesne tarafından temsil edilen değer, belirtilen [Nullable](../) nesne tarafından temsil edilen değerden daha büyükse doğru, aksi takdirde - yanlış

## Ayrıca Bakınız

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Nullable::operator>(const T1\&) const method


Geçerli nesne tarafından temsil edilen değerin, belirtilen değerden, bu değerlere [operator>()](./) uygulanarak daha büyük olup olmadığını belirler.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>(const T1 &other) const
```


| Parametre | Açıklama |
| --- | --- |
| T1 | Karşılaştırılacak değerin türü |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| diğer | const T1\& | Karşılaştırılacak değere sabit referans |

### ReturnValue

Geçerli nesne tarafından temsil edilen değer, belirtilen değerden daha büyükse doğru, aksi takdirde - yanlış

## Ayrıca Bakınız

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Nullable::operator>(std::nullptr_t) const method


Her zaman false döndürür.

```cpp
bool System::Nullable<T>::operator>(std::nullptr_t) const
```

## Ayrıca Bakınız

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
