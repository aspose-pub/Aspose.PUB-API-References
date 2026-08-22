---
title: "System::ObjectExt::Is metodu"
linktitle: "Is"
second_title: "Aspose.PUB için C++"
description: "System::ObjectExt::Is metodu. ''is'' operatörünün çevirisini uygular. C++'ta string sabiti için özelleştirme."
type: docs
weight: 1000
url: /tr/cpp/system/objectext/is/
---
## ObjectExt::Is(const char16_t *) method


'is' operatörü çevirisini uygular. Dize sabiti için özelleştirme.

```cpp
template<class T> static bool System::ObjectExt::Is(const char16_t *str)
```


| Parametre | Açıklama |
| --- | --- |
| T | Hedef tip. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const char16_t * | [String](../../string/) sabiti. |

### ReturnValue

'is' true döndürürse true, aksi takdirde false.

## Ayrıca Bakınız

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Is(const ExceptionWrapper\<U\>\&) method


'is' operatörü çevirisini uygular. İstisna sarmalayıcı türleri için özelleştirme.

```cpp
template<class T,class U> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Is(const ExceptionWrapper<U> &obj)
```


| Parametre | Açıklama |
| --- | --- |
| T | Hedef tip. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const ExceptionWrapper\<U\>\& | [Object](../../object/) 'is' operatörünü test etmek için. |

### ReturnValue

'is' true döndürürse true, aksi takdirde false.

## Ayrıca Bakınız

* Class [ExceptionWrapper](../../exceptionwrapper/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Is(const Nullable\<U\>\&) method


'is' operatörünün çevirisini uygular. [Nullable](../../nullable/) tipi için özelleştirme.

```cpp
template<class T,class U> static bool System::ObjectExt::Is(const Nullable<U> &value)
```


| Parametre | Açıklama |
| --- | --- |
| T | Hedef tip. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const Nullable\<U\>\& | [Nullable](../../nullable/) tipi. |

### ReturnValue

'is' true döndürürse true, aksi takdirde false.

## Ayrıca Bakınız

* Class [Nullable](../../nullable/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Is(const Object\&) method


'is' operatörü çevirisini uygular. Değer türleri için özelleştirme.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```


| Parametre | Açıklama |
| --- | --- |
| T | Hedef tip. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const Object\& | [Object](../../object/) 'is' operatörünü test etmek için. |

### ReturnValue

'is' true döndürürse true, aksi takdirde false.

## Ayrıca Bakınız

* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Is(const Object\&) method


'is' operatörü çevirisini uygular. Dönüştürülemez türler için özelleştirme.

```cpp
template<class T> static std::enable_if<!std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```


| Parametre | Açıklama |
| --- | --- |
| T | Hedef tip. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const Object\& | [Object](../../object/) 'is' operatörünü test etmek için. |

### ReturnValue

Tipler dönüştürülemez olduğu için her zaman false döndürür.

## Ayrıca Bakınız

* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Is(const SmartPtr\<Object\>\&) method


'is' operatörü çevirisini uygular. Nullable türleri için özelleştirme.

```cpp
template<class T> static std::enable_if<IsNullable<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


| Parametre | Açıklama |
| --- | --- |
| T | Hedef tip. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../object/) 'is' operatörünü test etmek için. |

### ReturnValue

'is' true döndürürse true, aksi takdirde false.

## Ayrıca Bakınız

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Is(const SmartPtr\<Object\>\&) method


'is' operatörü çevirisini uygular. == operatörü tanımlı kutlanabilir türler için özelleştirme.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


| Parametre | Açıklama |
| --- | --- |
| T | Hedef tip. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../object/) 'is' operatörünü test etmek için. |

### ReturnValue

'is' true döndürürse true, aksi takdirde false.

## Ayrıca Bakınız

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Is(const SmartPtr\<Object\>\&) method


'is' operatörü çevirisini uygular. == operatörü tanımlanmamış kutlanabilir türler için özelleştirme.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


| Parametre | Açıklama |
| --- | --- |
| T | Hedef tip. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../object/) 'is' operatörünü test etmek için. |

### ReturnValue

'is' true döndürürse true, aksi takdirde false.

## Ayrıca Bakınız

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Is(const SmartPtr\<U\>\&) method


'is' operatörü çevirisini uygular. İşaretçi türleri için özelleştirme.

```cpp
template<class T,class U> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```


| Parametre | Açıklama |
| --- | --- |
| T | Hedef tip. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const SmartPtr\<U\>\& | [Object](../../object/) 'is' operatörünü test etmek için. |

### ReturnValue

'is' true döndürürse true, aksi takdirde false.

## Ayrıca Bakınız

* Class [SmartPtr](../../smartptr/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Is(const SmartPtr\<U\>\&) method


'is' operatörü çevirisini uygular. Enum türleri için özelleştirme.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```


| Parametre | Açıklama |
| --- | --- |
| T | Hedef tip. |
| U | İşaret edilen nesnenin tipi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const SmartPtr\<U\>\& | [Object](../../object/) 'is' operatörünü test etmek için. |

### ReturnValue

'is' true döndürürse true, aksi takdirde false.

## Ayrıca Bakınız

* Class [SmartPtr](../../smartptr/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Is(const U\&) method


'is' operatörü çevirisini uygular. 'final' sınıflar için optimize edilmiş işaretçi türleri özelleştirmesi.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```


| Parametre | Açıklama |
| --- | --- |
| T | Hedef tip. |
| U | Test edilen tip. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) 'is' operatörünü test etmek için. |

### ReturnValue

'is' true döndürürse true, aksi takdirde false.

## Ayrıca Bakınız

* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Is(const U\&) method


'is' operatörü çevirisini uygular. İşaretçi türleri için özelleştirme.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&!std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```


| Parametre | Açıklama |
| --- | --- |
| T | Hedef tip. |
| U | Test edilen tip. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) 'is' operatörünü test etmek için. |

### ReturnValue

'is' true döndürürse true, aksi takdirde false.

## Ayrıca Bakınız

* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Is(const WeakPtr\<U\>\&) method


'is' operatörü çevirisini uygular. Enum türleri ve zayıf işaretçiler için özelleştirme.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const WeakPtr<U> &obj)
```


| Parametre | Açıklama |
| --- | --- |
| T | Hedef tip. |
| U | İşaret edilen nesnenin tipi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const WeakPtr\<U\>\& | [Object](../../object/) 'is' operatörünü test etmek için. |

### ReturnValue

'is' true döndürürse true, aksi takdirde false.

## Ayrıca Bakınız

* Class [WeakPtr](../../weakptr/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Is(int32_t) method


'is' operatörü çevirisini uygular. Tam sayı sabiti için özelleştirme.

```cpp
template<class T> static bool System::ObjectExt::Is(int32_t value)
```


| Parametre | Açıklama |
| --- | --- |
| T | Hedef tip. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int32_t | tam sayı sabiti. |

### ReturnValue

'is' true döndürürse true, aksi takdirde false.

## Ayrıca Bakınız

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
