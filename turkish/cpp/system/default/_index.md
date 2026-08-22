---
title: "System::Default yöntemi"
linktitle: "Default"
second_title: "Aspose.PUB için C++"
description: "System::Default yöntemi. Belirtilen tipin varsayılan oluşturulmuş örneğini C++ içinde döndürür."
type: docs
weight: 15100
url: /tr/cpp/system/default/
---
## System::Default() method


Belirtilen tipin varsayılan oluşturulmuş örneğini döndürür.

```cpp
template<typename T> std::enable_if<IsExceptionWrapper<T>::value, constT &>::type System::Default()
```


| Parametre | Açıklama |
| --- | --- |
| T | Örneği döndürülen tip |

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::Default() method


Belirtilen tipin varsayılan oluşturulmuş örneğini döndürür.

```cpp
template<typename T> std::enable_if<!IsExceptionWrapper<T>::value, constT &>::type System::Default()
```


| Parametre | Açıklama |
| --- | --- |
| T | Örneği döndürülen tip |

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
