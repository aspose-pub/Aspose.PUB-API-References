---
title: "System::ObjectExt::ToString metodu"
linktitle: "ToString"
second_title: "Aspose.PUB için C++"
description: "System::ObjectExt::ToString metodu. C# ToString metodunun yerine, C++'da herhangi bir C++ tipinde çalışması için."
type: docs
weight: 1300
url: /tr/cpp/system/objectext/tostring/
---
## ObjectExt::ToString(const char_t *) method


C# ToString metodunun ikamesi, herhangi bir C++ türünde çalışır.

```cpp
static String System::ObjectExt::ToString(const char_t *obj)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const char_t * | [String](../../string/) literal string'e dönüştürmek için. |

### ReturnValue

[String](../../string/) representation of **obj**.

## Ayrıca Bakınız

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::ToString(const Nullable\<T\>\&) method


C# ToString metodunun ikamesi, herhangi bir C++ türünde çalışır.

```cpp
template<typename T> static String System::ObjectExt::ToString(const Nullable<T> &obj)
```


| Parametre | Açıklama |
| --- | --- |
| T | [Nullable](../../nullable/) tipi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const Nullable\<T\>\& | [Nullable](../../nullable/) nesnesi string'e dönüştürmek için. |

### ReturnValue

[String](../../string/) representation of **obj**.

## Ayrıca Bakınız

* Class [String](../../string/)
* Class [Nullable](../../nullable/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::ToString(const T\&) method


C# ToString metodunun ikamesi, herhangi bir C++ türünde çalışır.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```


| Parametre | Açıklama |
| --- | --- |
| T | [Enum](../../enum/) tipi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const T\& | [Enum](../../enum/) değeri string'e dönüştürmek için. |

### ReturnValue

[String](../../string/) representation of **obj**.

## Ayrıca Bakınız

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::ToString(const T\&) method


C# ToString metodunun ikamesi, herhangi bir C++ türünde çalışır.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```


| Parametre | Açıklama |
| --- | --- |
| T | Akıllı işaretçi tipi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const T\& | [SmartPtr](../../smartptr/) değeri string'e dönüştürmek için. |

### ReturnValue

[String](../../string/) representation of **obj**.

## Ayrıca Bakınız

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::ToString(const T\&) method


C# ToString metodunun ikamesi, herhangi bir C++ türünde çalışır.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```


| Parametre | Açıklama |
| --- | --- |
| T | Yapı tipi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const T\& | Yapı değeri string'e dönüştürmek için. |

### ReturnValue

[String](../../string/) representation of **obj**.

## Ayrıca Bakınız

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::ToString(T\&&) method


C# ToString metodunun ikamesi, herhangi bir C++ türünde çalışır.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```


| Parametre | Açıklama |
| --- | --- |
| T | Skaler tipi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | T\&& | Skaler değeri string'e dönüştürmek için. |

### ReturnValue

[String](../../string/) representation of **obj**.

## Ayrıca Bakınız

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::ToString(T\&&) method


C# ToString metodunun ikamesi, herhangi bir C++ türünde çalışır.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value &&!std::is_reference<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```


| Parametre | Açıklama |
| --- | --- |
| T | Skaler tipi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | T\&& | Skaler değeri string'e dönüştürmek için. |

### ReturnValue

[String](../../string/) representation of **obj**.

## Ayrıca Bakınız

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::ToString(T\&) method


C# ToString metodunun ikamesi, herhangi bir C++ türünde çalışır.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value||std::is_pointer<T>::value||IsExceptionWrapper<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```


| Parametre | Açıklama |
| --- | --- |
| T | Akıllı işaretçi tipi veya [ExceptionWrapper](../../exceptionwrapper/). |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | T\& | Akıllı işaretçi veya [ExceptionWrapper](../../exceptionwrapper/) string'e dönüştürmek için. |

### ReturnValue

[String](../../string/) representation of **obj**.

## Ayrıca Bakınız

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::ToString(T\&) method


C# ToString metodunun ikamesi, herhangi bir C++ türünde çalışır.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```


| Parametre | Açıklama |
| --- | --- |
| T | Skaler tipi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | T\& | Skaler değeri string'e dönüştürmek için. |

### ReturnValue

[String](../../string/) representation of **obj**.

## Ayrıca Bakınız

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::ToString(T\&) method


C# ToString metodunun ikamesi, herhangi bir C++ türünde çalışır.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```


| Parametre | Açıklama |
| --- | --- |
| T | Yapı tipi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | T\& | Yapı değeri string'e dönüştürmek için. |

### ReturnValue

[String](../../string/) representation of **obj**.

## Ayrıca Bakınız

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
