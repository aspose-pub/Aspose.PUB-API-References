---
title: "System::ObjectExt::Box yöntemi"
linktitle: "Box"
second_title: "Aspose.PUB için C++"
description: "System::ObjectExt::Box yöntemi. C++'ta string değerlerini kutular."
type: docs
weight: 200
url: /tr/cpp/system/objectext/box/
---
## ObjectExt::Box(const String\&) method


Dize değerlerini kutular.

```cpp
SmartPtr<Object> System::ObjectExt::Box(const String &value)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | const String\& | Kutulanacak değer. |

### ReturnValue

Kaynak string null ise kutulanmış değer ya da null.

## Ayrıca Bakınız

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Box(const T\&) method


Değer tiplerini [Object](../../object/) olarak dönüştürmek için kutular. Enum türleri için uygulama.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


| Parametre | Açıklama |
| --- | --- |
| T | [Enum](../../enum/) tipi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const T\& | [Enum](../../enum/) kutulanacak değer. |

### ReturnValue

Kutulanmış değeri tutan nesneye akıllı işaretçi.

## Ayrıca Bakınız

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Box(const T\&) method


Değer tiplerini [Object](../../object/) olarak dönüştürmek için kutular. Enum olmayan türler için uygulama.

```cpp
template<typename T> static std::enable_if<!std::is_enum<T>::value &&!IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


| Parametre | Açıklama |
| --- | --- |
| T | Değer türü. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | const T\& | Kutulanacak değer. |

### ReturnValue

Kutulanmış değeri tutan nesneye akıllı işaretçi.

## Ayrıca Bakınız

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Box(const T\&) method


[Nullable](../../nullable/) tiplerini [Object](../../object/) olarak dönüştürmek için kutular.

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


| Parametre | Açıklama |
| --- | --- |
| T | Değer türü. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | const T\& | Kutulanacak değer. |

### ReturnValue

Kutulanmış değeri tutan nesneye akıllı işaretçi.

## Ayrıca Bakınız

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
