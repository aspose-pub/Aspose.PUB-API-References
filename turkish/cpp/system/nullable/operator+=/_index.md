---
title: "System::Nullable::operator+= metodu"
linktitle: "operator+="
second_title: "Aspose.PUB için C++"
description: "System::Nullable::operator+= metodu. Belirtilen Nullable nesnesi tarafından temsil edilen değeri sağ taraf argümanı olarak kullanarak operator+=()'ı geçerli nesne tarafından temsil edilen değere C++'ta uygular."
type: docs
weight: 1300
url: /tr/cpp/system/nullable/operator+=/
---
## Nullable::operator+=(const Nullable\<T1\>\&) method


Geçerli nesne tarafından temsil edilen değere, belirtilen [Nullable](../) nesnesi tarafından temsil edilen değeri sağ taraf argümanı olarak kullanarak [operator+=()](./) uygular.

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator+=(const Nullable<T1> &other)
```


| Parametre | Açıklama |
| --- | --- |
| T1 | Sağ taraf argümanı olarak kullanılan değeri temsil eden bir [Nullable](../) nesnesinin temel türü, [operator+=()](./) |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | const Nullable\<T1\>\& | Geçerli nesne tarafından temsil edilen değere uygulanan [operator+=()](./)'a sağ taraf argümanı olarak kullanılan değeri temsil eden bir [Nullable](../) nesnesine sabit referans. |

### ReturnValue

Kendine bir referans

## Ayrıca Bakınız

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Nullable::operator+=(const T1\&) method


Belirtilen değeri sağ taraf argümanı olarak kullanarak geçerli nesne tarafından temsil edilen değere [operator+=()](./) uygular.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator+=(const T1 &other)
```


| Parametre | Açıklama |
| --- | --- |
| T1 | [operator+=()](./)'ın sağ taraf değeri olarak kullanılan değerin türü |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | const T1\& | Geçerli nesne tarafından temsil edilen değere uygulanan [operator+=()](./)'a sağ taraf değeri olarak kullanılan değere sabit referans. |

### ReturnValue

Kendine bir referans

## Ayrıca Bakınız

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Nullable::operator+=(std::nullptr_t) method


Geçerli nesneyi, null değeri temsil edecek şekilde sıfırlar.

```cpp
Nullable<T> System::Nullable<T>::operator+=(std::nullptr_t)
```


### ReturnValue

Kendisinin bir kopyası

## Ayrıca Bakınız

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
