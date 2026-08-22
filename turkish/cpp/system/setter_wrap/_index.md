---
title: "System::setter_wrap yöntemi"
linktitle: "setter_wrap"
second_title: "Aspose.PUB için C++"
description: "System::setter_wrap yöntemi. C++'ta tip dönüşümüyle örnek setter işlevleri için aşırı yükleme."
type: docs
weight: 34700
url: /tr/cpp/system/setter_wrap/
---
## System::setter_wrap(Host *const, void(HostSet::*)(T2), T) method


Tip dönüşümüyle örnek setter işlevleri için aşırı yükleme.

```cpp
template<typename T,typename T2,typename Host,typename HostSet> std::enable_if<std::is_base_of<HostSet, Host>::value, T>::type System::setter_wrap(Host *const host, void(HostSet::*pSetter)(T2), T value)
```


| Parametre | Açıklama |
| --- | --- |
| T | Değer türü. |
| T2 | Setter işlevi tarafından beklenen tür. |
| Host | Örnek tür. |
| HostSet | - Host kendisi veya özelliğin ayarlayıcısının tanımlandığı temel tür. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| host | Host *const | [Object](../object/) için ayarlayıcı işlevi çağırmak. |
| pSetter | void(HostSet::*)(T2) | Setter işlevi referansı. |
| değer | T | Ayarlanacak değer. |

### ReturnValue

değeri ayarla.

## Ayrıca Bakınız

* Enum [UriComponents](../uricomponents/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::setter_wrap(void(*)(T2), T) method


Tür dönüşümüyle statik setter işlevleri için aşırı yükleme.

```cpp
template<typename T,typename T2> T System::setter_wrap(void(*pSetter)(T2), T value)
```


| Parametre | Açıklama |
| --- | --- |
| T | Değer türü. |
| T2 | Setter işlevi tarafından beklenen tür. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pSetter | void(*)(T2) | Statik setter işlevi referansı. |
| değer | T | Ayarlanacak değer. |

### ReturnValue

değeri ayarla.

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
