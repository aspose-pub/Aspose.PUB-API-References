---
title: "System::setter_post_increment_wrap metodu"
linktitle: "setter_post_increment_wrap"
second_title: "Aspose.PUB için C++"
description: "System::setter_post_increment_wrap metodu. Çevirmen, C#''s sonrası artış ifadelerini, setter ve getter tanımlı örnek''nin özelliğine yönelik, C++'da bu işlevin (const getter için aşırı yükleme) çağrısına dönüştürür."
type: docs
weight: 34400
url: /tr/cpp/system/setter_post_increment_wrap/
---
## System::setter_post_increment_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) method


Çevirmen, C#'s sonrası artış ifadelerini, setter ve getter tanımlı örnek'in özelliğine yönelik, bu işlevin (const getter için aşırı yükleme) çağrısına dönüştürür.

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_increment_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
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
## System::setter_post_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) method


Çevirmen, tanımlı setter ve getter'a sahip örnek özelliğini hedef alan C#'ın artı bir sonrası ifadelerini, bu işlevin (const olmayan getter için aşırı yükleme) çağrısına dönüştürür.

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
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
## System::setter_post_increment_wrap(T(*)(), void(*)(T)) method


Çevirmen, tanımlı setter ve getter'a sahip sınıf özelliğini hedef alan C#'ın artı bir sonrası ifadelerini, bu işlevin çağrısına dönüştürür.

```cpp
template<typename T> T System::setter_post_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
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
