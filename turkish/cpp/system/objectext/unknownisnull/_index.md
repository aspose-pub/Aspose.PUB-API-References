---
title: "System::ObjectExt::UnknownIsNull yöntemi"
linktitle: "UnknownIsNull"
second_title: "Aspose.PUB için C++"
description: "System::ObjectExt::UnknownIsNull yöntemi. Bilinmeyen tip nesnesinin nullptr olup olmadığını kontrol eder. C++'ta skaler olmayan tipler için aşırı yükleme."
type: docs
weight: 1700
url: /tr/cpp/system/objectext/unknownisnull/
---
## ObjectExt::UnknownIsNull(T) method


Bilinmeyen tip nesnenin nullptr olup olmadığını kontrol eder. Skaler olmayan tipler için aşırı yükleme.

```cpp
template<typename T> static std::enable_if<!std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```


| Parametre | Açıklama |
| --- | --- |
| T | [Object](../../object/) tipi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | T | [Object](../../object/) kontrol etmek için. |

### ReturnValue

'obj == nullptr' true ise True, aksi takdirde false.

## Ayrıca Bakınız

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::UnknownIsNull(T) method


Bilinmeyen tip nesnenin nullptr olup olmadığını kontrol eder. Skaler tipler için aşırı yükleme.

```cpp
template<typename T> static std::enable_if<std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```


| Parametre | Açıklama |
| --- | --- |
| T | [Object](../../object/) tipi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | T | [Object](../../object/) kontrol etmek için. |

### ReturnValue

Her zaman false döndürür.

## Ayrıca Bakınız

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
