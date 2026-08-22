---
title: "System::setter_increment_wrap yöntemi"
linktitle: "setter_increment_wrap"
second_title: "Aspose.PUB için C++"
description: "System::setter_increment_wrap yöntemi. Çevirmen, setter ve getter tanımlı sınıf özelliğini hedef alan C#'ın artırma ifadelerini, C++'ta bu işlevin çağrısına dönüştürür."
type: docs
weight: 33900
url: /tr/cpp/system/setter_increment_wrap/
---
## System::setter_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) method


Çevirmen, setter ve getter tanımlı sınıf özelliğini hedef alan C#'ın artırma ifadelerini, bu işlevin çağrısına dönüştürür.

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```


| Parametre | Açıklama |
| --- | --- |
| T | Özelliğin tipi |
| Host | - değiştirilecek örneğin sınıfı |
| HostGet | - Host'un kendisi ya da özelliğin getter'ının tanımlı olduğu temel tipi |
| HostSet | - Host'un kendisi ya da özelliğin setter'ının tanımlı olduğu temel tipi |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ana bilgisayar | Host *const | Artırılması gereken özelliği olan bir nesneye işaretçi. |
| pGetter | T(HostGet::*)() | Özelliğin getter yöntemine işaret eden fonksiyon işaretçisi |
| pSetter | void(HostSet::*)(T) | Özelliğin setter yöntemine işaret eden fonksiyon işaretçisi |

### ReturnValue

Özelliğin artırılmış değeri

## Ayrıca Bakınız

* Enum [UriComponents](../uricomponents/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::setter_increment_wrap(T(*)(), void(*)(T)) method


Çevirmen, setter ve getter tanımlı sınıf özelliğini hedef alan C#'ın artırma ifadelerini, bu işlevin çağrısına dönüştürür.

```cpp
template<typename T> T System::setter_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```


| Parametre | Açıklama |
| --- | --- |
| T | Özelliğin tipi |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pGetter | T(*)() | Özelliğin bağımsız getter işlevine işaret eden fonksiyon işaretçisi |
| pSetter | void(*)(T) | Özelliğin bağımsız setter işlevine işaret eden fonksiyon işaretçisi |

### ReturnValue

Özelliğin artırılmış değeri

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
