---
title: "System::Nullable::operator-= yöntemi"
linktitle: "operator-="
second_title: "Aspose.PUB için C++"
description: "System::Nullable::operator-= yöntemi. C++'ta belirtilen Nullable nesnesi tarafından temsil edilen değeri sağ taraf argümanı olarak kullanarak geçerli nesne tarafından temsil edilen değere operator-=() uygular."
type: docs
weight: 1500
url: /tr/cpp/system/nullable/operator-=/
---
## Nullable::operator-=(const Nullable\<T1\>\&) method


[operator-=()](./) işlevini, belirtilen [Nullable](../) nesnesi tarafından temsil edilen değeri sağ taraf argümanı olarak kullanarak geçerli nesne tarafından temsil edilen değere uygular.

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator-=(const Nullable<T1> &other)
```


| Parametre | Açıklama |
| --- | --- |
| T1 | Sağ taraf argümanı olarak kullanılan değeri temsil eden bir [Nullable](../) nesnesinin temel türü |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | const Nullable\<T1\>\& | Geçerli nesnenin temsil ettiği değere uygulanan [operator-=()](./) işleminin sağ taraf argümanı olarak kullanılan değeri temsil eden bir [Nullable](../) nesnesine sabit referans. |

### ReturnValue

Kendine bir referans

## Ayrıca Bakınız

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Nullable::operator-=(const T1\&) method


Belirtilen değeri sağ taraf argümanı olarak kullanarak, geçerli nesnenin temsil ettiği değere [operator-=()](./) uygular.

```cpp
template<typename T1,typename> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator-=(const T1 &other)
```


| Parametre | Açıklama |
| --- | --- |
| T1 | [operator-=()](./) işleminin sağ taraf değeri olarak kullanılan değerin türü. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | const T1\& | Geçerli nesnenin temsil ettiği değere uygulanan [operator-=()](./) işleminin sağ taraf değeri olarak kullanılan değere sabit referans. |

### ReturnValue

Kendine bir referans

## Ayrıca Bakınız

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Nullable::operator-=(T1) method


Null değeri temsil eden bir [Nullable](../) sınıf örneği döndürür.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-=(T1)
```

## Ayrıca Bakınız

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
