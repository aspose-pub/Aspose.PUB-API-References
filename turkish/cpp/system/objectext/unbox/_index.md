---
title: "System::ObjectExt::Unbox metodu"
linktitle: "Unbox"
second_title: "Aspose.PUB için C++"
description: "System::ObjectExt::Unbox metodu. Değer tiplerini Object'e dönüştürdükten sonra kutusundan çıkarır. C++'da enum tipleri için uygulanır."
type: docs
weight: 1400
url: /tr/cpp/system/objectext/unbox/
---
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) method


Değer tiplerini [Object](../../object/) 'a dönüştürdükten sonra kutusundan çıkarır. Enum tipleri için uygulanır.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


| Parametre | Açıklama |
| --- | --- |
| T | [Enum](../../enum/) tipi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../object/) kutusundan çıkarmak için. |

### ReturnValue

[Enum](../../enum/) value.

## Ayrıca Bakınız

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) method


Değer tiplerini [Object](../../object/) 'a dönüştürdükten sonra kutusundan çıkarır. Enum olmayan ve nullable olmayan tipler için uygulanır.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


| Parametre | Açıklama |
| --- | --- |
| T | Değer türü. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../object/) kutusundan çıkarmak için. |

### ReturnValue

Kutusundan çıkarılmış değer.

## Ayrıca Bakınız

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) method


Değer tiplerini [Object](../../object/) 'a dönüştürdükten sonra kutusundan çıkarır. Enum olmayan ve nullable olmayan tipler için uygulanır.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


| Parametre | Açıklama |
| --- | --- |
| T | Değer türü. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../object/) kutusundan çıkarmak için. |

### ReturnValue

Kutusundan çıkarılmış değer.

## Ayrıca Bakınız

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) method


Dize değerlerini kutudan çıkarır.

```cpp
String System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../object/) kutusundan çıkarmak için |

### ReturnValue

[String](../../string/) representation of boxed string, can be null if boxed string was null.

## Ayrıca Bakınız

* Class [String](../../string/)
* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Unbox(E) method


Enum türlerini tamsayıya kutudan çıkarır.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::numeric_limits<T>::is_integer, T>::type System::ObjectExt::Unbox(E e)
```


| Parametre | Açıklama |
| --- | --- |
| T | Hedef tam sayı türü. |
| E | Kaynak enum türü. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| e | E | Açılacak değer. |

### ReturnValue

Enumun tam sayı temsili.

## Ayrıca Bakınız

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Unbox(E) method


Enum türlerini dönüştürür.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(E e)
```


| Parametre | Açıklama |
| --- | --- |
| T | Hedef enum türü. |
| E | Kaynak enum türü. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| e | E | Açılacak değer. |

### ReturnValue

Dönüştürülmüş enum değeri.

## Ayrıca Bakınız

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
