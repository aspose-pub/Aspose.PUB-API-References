---
title: "System::setter_decrement_wrap method"
linktitle: "setter_decrement_wrap"
second_title: "Aspose.PUB için C++"
description: "System::setter_decrement_wrap yöntemi. Çevirmen, C#''s ön-azaltma ifadelerini, setter ve getter tanımlı örnek özelliğine yönlendirerek, bu işlevin (const getter için aşırı yükleme) C++'da çağrılmasına dönüştürür."
type: docs
weight: 33600
url: /tr/cpp/system/setter_decrement_wrap/
---
## System::setter_decrement_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) method


Çevirmen, C#'s ön-azaltma ifadelerini, setter ve getter tanımlı örnek özelliğine yönlendirerek, bu işlevin (const getter için aşırı yükleme) çağrılmasına dönüştürür.

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_decrement_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```


| Parametre | Açıklama |
| --- | --- |
| T | Özelliğin türü. |
| Host | - değiştirilecek örneğin sınıfı |
| HostConstGet | - Host'un kendisi ya da özelliğin getter'ının tanımlı olduğu temel tipi |
| HostSet | - Host'un kendisi ya da özelliğin setter'ının tanımlı olduğu temel tipi |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ana bilgisayar | Host *const | Getter ve setter'ları çağırmak için örnek. |
| pGetter | T(HostConstGet::*)() const | Özelliğin getter işlevine işaret eden fonksiyon işaretçisi |
| pSetter | void(HostSet::*)(T) | Özelliğin setter işlevine işaret eden fonksiyon işaretçisi |

### ReturnValue

Artırmadan önce özelliğin değeri

## Ayrıca Bakınız

* Enum [UriComponents](../uricomponents/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::setter_decrement_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) method


Çevirmen, C#'s ön-azaltma ifadelerini, setter ve getter tanımlı örnek özelliğine yönlendirerek, bu işlevin (non-const getter için aşırı yükleme) çağrılmasına dönüştürür.

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_decrement_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```


| Parametre | Açıklama |
| --- | --- |
| T | Özelliğin türü. |
| Host | - değiştirilecek örneğin sınıfı |
| HostGet | - Host'un kendisi ya da özelliğin getter'ının tanımlı olduğu temel tipi |
| HostSet | - Host'un kendisi ya da özelliğin setter'ının tanımlı olduğu temel tipi |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ana bilgisayar | Host *const | Getter ve setter'ları çağırmak için örnek. |
| pGetter | T(HostGet::*)() | Özelliğin getter işlevine işaret eden fonksiyon işaretçisi |
| pSetter | void(HostSet::*)(T) | Özelliğin setter işlevine işaret eden fonksiyon işaretçisi |

### ReturnValue

Artırmadan önce özelliğin değeri

## Ayrıca Bakınız

* Enum [UriComponents](../uricomponents/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::setter_decrement_wrap(T(*)(), void(*)(T)) method


Çevirmen, C#'s ön-azaltma ifadelerini, setter ve getter tanımlı sınıf özelliğine yönlendirerek, bu işlevin çağrılmasına dönüştürür.

```cpp
template<typename T> T System::setter_decrement_wrap(T(*pGetter)(), void(*pSetter)(T))
```


| Parametre | Açıklama |
| --- | --- |
| T | Özelliğin tipi |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pGetter | T(*)() | Özelliğin bağımsız getter işlevine işaret eden fonksiyon işaretçisi |
| pSetter | void(*)(T) | Özelliğin bağımsız setter işlevine işaret eden fonksiyon işaretçisi |

### ReturnValue

Artırmadan önce özelliğin değeri

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
