---
title: "System::Nullable::operator<= yöntemi"
linktitle: "operator<="
second_title: "Aspose.PUB için C++"
description: "System::Nullable::operator<= yöntemi. Bu değerleri C++'ta operator<=() uygulayarak, geçerli nesne tarafından temsil edilen değerin belirtilen Nullable nesnesi tarafından temsil edilen değerden küçük veya eşit olup olmadığını belirler."
type: docs
weight: 1700
url: /tr/cpp/system/nullable/operator_=/
---
## Nullable::operator<=(const Nullable\<T1\>\&) const method


Bu değerleri [operator<=()](./) uygulayarak, geçerli nesne tarafından temsil edilen değerin belirtilen [Nullable](../) nesnesi tarafından temsil edilen değerden küçük veya eşit olup olmadığını belirler.

```cpp
template<typename T1> bool System::Nullable<T>::operator<=(const Nullable<T1> &other) const
```


| Parametre | Açıklama |
| --- | --- |
| T1 | Karşılaştırılacak [Nullable](../) nesnesinin temel türü |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | const Nullable\<T1\>\& | Karşılaştırılacak [Nullable](../) nesnesine sabit referans |

### ReturnValue

Geçerli nesne tarafından temsil edilen değer, belirtilen [Nullable](../) nesnesi tarafından temsil edilen değerden küçük veya eşitse doğru, aksi takdirde - yanlış

## Ayrıca Bakınız

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Nullable::operator<=(const T1\&) const method


Bu değerleri [operator<=()](./) uygulayarak, geçerli nesne tarafından temsil edilen değerin belirtilen değerden küçük veya eşit olup olmadığını belirler.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<=(const T1 &other) const
```


| Parametre | Açıklama |
| --- | --- |
| T1 | Karşılaştırılacak değerin türü |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| diğer | const T1\& | Karşılaştırılacak değere sabit referans |

### ReturnValue

Geçerli nesne tarafından temsil edilen değer, belirtilen değerden küçük veya eşitse doğru, aksi takdirde - yanlış

## Ayrıca Bakınız

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Nullable::operator<=(std::nullptr_t) const method


Her zaman false döndürür.

```cpp
bool System::Nullable<T>::operator<=(std::nullptr_t) const
```

## Ayrıca Bakınız

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
---
başlık: System::Nullable::operator>= yöntemi
linktitle: operator>=
second_title: C++ için Aspose.PUB
açıklama: 'System::Nullable::operator>= yöntemi. Bu değerleri C++'ta operator>=() uygulayarak, geçerli nesne tarafından temsil edilen değerin belirtilen Nullable nesnesi tarafından temsil edilen değerden büyük veya eşit olup olmadığını belirler.'
type: docs
ağırlık: 2100
url: /cpp/system/nullable/operator_=/
---
## Nullable::operator>=(const Nullable\<T1\>\&) const method


Bu değerleri [operator>=()](./) uygulayarak, geçerli nesne tarafından temsil edilen değerin belirtilen [Nullable](../) nesnesi tarafından temsil edilen değerden büyük veya eşit olup olmadığını belirler.

```cpp
template<typename T1> bool System::Nullable<T>::operator>=(const Nullable<T1> &other) const
```


| Parametre | Açıklama |
| --- | --- |
| T1 | Karşılaştırılacak [Nullable](../) nesnesinin temel türü |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | const Nullable\<T1\>\& | Karşılaştırılacak [Nullable](../) nesnesine sabit referans |

### ReturnValue

Geçerli nesne tarafından temsil edilen değer, belirtilen [Nullable](../) nesnesi tarafından temsil edilen değerden büyük veya eşitse doğru, aksi takdirde - yanlış

## Ayrıca Bakınız

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Nullable::operator>=(const T1\&) const method


Bu değerleri [operator>=()](./) uygulayarak, geçerli nesne tarafından temsil edilen değerin belirtilen nesne tarafından temsil edilen değerden büyük veya eşit olup olmadığını belirler.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>=(const T1 &other) const
```


| Parametre | Açıklama |
| --- | --- |
| T1 | Geçerli nesne tarafından temsil edilen değerin karşılaştırılacağı değerin temel türü |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| diğer | const T1\& | Geçerli nesne ile karşılaştırılacak nesneye sabit bir referans |

### ReturnValue

Geçerli nesne tarafından temsil edilen değer, belirtilen nesne tarafından temsil edilen değerden büyük veya eşitse doğru, aksi takdirde - yanlış

## Ayrıca Bakınız

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Nullable::operator>=(std::nullptr_t) const method


Her zaman false döndürür.

```cpp
bool System::Nullable<T>::operator>=(std::nullptr_t) const
```


### ReturnValue

Her zaman - yanlış

## Ayrıca Bakınız

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
---
başlık: System::Nullable::operator|= yöntemi
bağlantı başlığı: operator|=
second_title: C++ için Aspose.PUB
açıklama: 'System::Nullable::operator|= yöntemi. Belirtilen değeri sağ taraf argümanı olarak kullanarak, geçerli nesne tarafından temsil edilen değere C++'ta operator|=() uygular.'
type: docs
ağırlık: 2200
url: /cpp/system/nullable/operator_=/
---
## Nullable::operator|= method


Belirtilen değeri sağ taraf argümanı olarak kullanarak, geçerli nesne tarafından temsil edilen değere [operator|=()](./) uygular.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator|=(bool other)
```


| Parametre | Açıklama |
| --- | --- |
| T1 | SFINAE'in çalışmasını sağlamak için şablon parametresi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| diğer | bool | Sağ taraf değeri olarak kullanılan bir boolean değer [operator | =()](./) geçerli nesne tarafından temsil edilen değere uygulanır. |

### ReturnValue

Kendisine bir referans.

## Ayrıca Bakınız

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
