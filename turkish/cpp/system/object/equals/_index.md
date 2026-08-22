---
title: "System::Object::Equals method"
linktitle: "Equals"
second_title: "Aspose.PUB için C++"
description: "System::Object::Equals method. C++'da C# Object.Equals semantiğini kullanarak nesneleri karşılaştırır."
type: docs
weight: 300
url: /tr/cpp/system/object/equals/
---
## Object::Equals(ptr) method


C# [Object.Equals](./) semantiğini kullanarak nesneleri karşılaştırır.

```cpp
virtual bool System::Object::Equals(ptr obj)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | ptr | [Object](../) mevcut nesneyi karşılaştırmak için. |

### ReturnValue

Nesneler eşit kabul ediliyorsa doğru, aksi takdirde yanlış.

## Ayrıca Bakınız

* Typedef [ptr](../ptr/)
* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Object::Equals(double const\&, double const\&) method


IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmaması gerekirken, iki NaN'in eşit kabul edildiği C#-style kayan nokta karşılaştırmasını taklit eder.

```cpp
bool System::Object::Equals(double const &objA, double const &objB)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| objA | double const\& | LHS kayan nokta değeri. |
| objB | double const\& | RHS kayan nokta değeri. |

### ReturnValue

Her iki **objA** ve **objB** NaN ise veya eşitse doğru, aksi takdirde yanlış.

## Ayrıca Bakınız

* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Object::Equals(float const\&, float const\&) method


IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmaması gerekirken, iki NaN'in eşit kabul edildiği C#-style kayan nokta karşılaştırmasını taklit eder.

```cpp
bool System::Object::Equals(float const &objA, float const &objB)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| objA | float const\& | LHS kayan nokta değeri. |
| objB | float const\& | RHS kayan nokta değeri. |

### ReturnValue

Her iki **objA** ve **objB** NaN ise veya eşitse doğru, aksi takdirde yanlış.

## Ayrıca Bakınız

* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Object::Equals(T1 const\&, T2 const\&) method


C# stilinde referans tipi nesneleri karşılaştırır.

```cpp
template<typename T1,typename T2> static std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```


| Parametre | Açıklama |
| --- | --- |
| T1 | Karşılaştırılacak ilk nesnenin türü. |
| T2 | Karşılaştırılacak ikinci nesnenin türü. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| objA | T1 const\& | Karşılaştırılacak ilk nesne. |
| objB | T2 const\& | Karşılaştırılacak ikinci nesne. |

### ReturnValue

Nesneler referansla ya da anlamsal olarak ([Object.Equals](./) benzeri karşılaştırma ile) eşleşiyorsa doğru, aksi takdirde yanlış.

## Ayrıca Bakınız

* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Object::Equals(T1 const\&, T2 const\&) method


C# stilinde değer tipi nesneleri karşılaştırır.

```cpp
template<typename T1,typename T2> static std::enable_if<!IsSmartPtr<T1>::value &&!IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```


| Parametre | Açıklama |
| --- | --- |
| T1 | Karşılaştırılacak ilk nesnenin türü. |
| T2 | Karşılaştırılacak ikinci nesnenin türü. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| objA | T1 const\& | Karşılaştırılacak ilk nesne. |
| objB | T2 const\& | Karşılaştırılacak ikinci nesne. |

### ReturnValue

Nesneler mevcut eşitlik operatörüyle eşit kabul ediliyorsa doğru, aksi takdirde yanlış.

## Ayrıca Bakınız

* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
