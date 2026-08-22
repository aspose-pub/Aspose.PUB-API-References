---
title: "System::Nullable::operator&= yöntemi"
linktitle: "operator&="
second_title: "Aspose.PUB için C++"
description: "System::Nullable::operator&= yöntemi. C++'ta belirtilen değeri sağ taraf argümanı olarak kullanarak geçerli nesne tarafından temsil edilen değere operator&=() uygular."
type: docs
weight: 1100
url: /tr/cpp/system/nullable/operator&=/
---
## Nullable::operator&= method


[operator&=()](./) işlevini, belirtilen değeri sağ taraf argümanı olarak kullanarak geçerli nesne tarafından temsil edilen değere uygular.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator&=(bool other)
```


| Parametre | Açıklama |
| --- | --- |
| T1 | SFINAE'in çalışmasını sağlamak için şablon parametresi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | bool | Geçerli nesne tarafından temsil edilen değere uygulanan [operator&=()](./) işlevinin sağ taraf değeri olarak kullanılan bir boolean değer. |

### ReturnValue

Kendisine bir referans.

## Ayrıca Bakınız

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
