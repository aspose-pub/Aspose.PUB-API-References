---
title: "System::Object::ReferenceEquals metodu"
linktitle: "ReferenceEquals"
second_title: "Aspose.PUB için C++"
description: "System::Object::ReferenceEquals metodu. C++'da string ve nullptr durumu için Object::ReferenceEquals özelleştirmesi."
type: docs
weight: 1200
url: /tr/cpp/system/object/referenceequals/
---
## Object::ReferenceEquals(String const\&, std::nullptr_t) method


string ve nullptr durumu için [Object::ReferenceEquals](./) özelleştirmesi.

```cpp
bool System::Object::ReferenceEquals(String const &str, std::nullptr_t)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | String const\& | [String](../../string/) nullptr ile karşılaştırmak için. |

### ReturnValue

dize null ise doğru, aksi takdirde yanlış.

## Ayrıca Bakınız

* Class [String](../../string/)
* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Object::ReferenceEquals(String const\&, String const\&) method


stringler durumu için [Object::ReferenceEquals](./) özelleştirmesi.

```cpp
bool System::Object::ReferenceEquals(String const &str1, String const &str2)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str1 | String const\& | Karşılaştırılacak ilk string. |
| str2 | String const\& | Karşılaştırılacak ikinci string. |

### ReturnValue

dizeler eşleşiyorsa doğru, aksi takdirde yanlış.

## Ayrıca Bakınız

* Class [String](../../string/)
* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Object::ReferenceEquals(ptr const\&, ptr const\&) method


Nesneleri referansına göre karşılaştırır.

```cpp
static bool System::Object::ReferenceEquals(ptr const &objA, ptr const &objB)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| objA | ptr const\& | Karşılaştırılacak ilk işaretçi. |
| objB | ptr const\& | Karşılaştırılacak ikinci gösterici. |

### ReturnValue

İşaretçiler eşleşiyorsa doğru, aksi takdirde yanlış.

## Ayrıca Bakınız

* Typedef [ptr](../ptr/)
* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Object::ReferenceEquals(T const\&, std::nullptr_t) method


Değer tipi nesneyi nullptr ile referans olarak karşılaştırır.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, std::nullptr_t)
```


| Parametre | Açıklama |
| --- | --- |
| T | Karşılaştırılacak nesnenin türü. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| objA | T const\& | Karşılaştırılacak ilk nesne. |

### ReturnValue

Değer tipleri null olamayacağı için her zaman yanlış döndürür.

## Ayrıca Bakınız

* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Object::ReferenceEquals(T const\&, T const\&) method


Nesneleri referansına göre karşılaştırır.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, T const &objB)
```


| Parametre | Açıklama |
| --- | --- |
| T | Karşılaştırılacak nesnelerin türü. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| objA | T const\& | Karşılaştırılacak ilk nesne. |
| objB | T const\& | Karşılaştırılacak ikinci nesne. |

### ReturnValue

Nesne adresleri eşleşiyorsa doğru, aksi takdirde yanlış.

## Ayrıca Bakınız

* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
