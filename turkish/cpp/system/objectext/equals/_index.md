---
title: "System::ObjectExt::Equals metodu"
linktitle: "Equals"
second_title: "Aspose.PUB için C++"
description: "System::ObjectExt::Equals metodu. C# Object.Equals çağrıları için, C++'ta herhangi bir tipte çalışan bir ikame. C++'ta string sabiti için string karşılaştırmasıyla aşırı yükleme."
type: docs
weight: 700
url: /tr/cpp/system/objectext/equals/
---
## ObjectExt::Equals(const char_t(&), String) method


C# [Object.Equals](../../object/equals/) çağrıları için, C++'ta herhangi bir tipte çalışan ikame. String sabiti için string karşılaştırmasıyla aşırı yükleme.

```cpp
template<size_t> static bool System::ObjectExt::Equals(const char_t(&obj)[N], String another)
```


| Parametre | Açıklama |
| --- | --- |
| N | [String](../../string/) sabiti boyutu. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const char_t(&) | [String](../../string/) sabiti. |
| another | String | [String](../../string/). |

### ReturnValue

Dizeler eşleşirse doğru, aksi takdirde yanlış.

## Ayrıca Bakınız

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Equals(const double\&, const double\&) method


IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmaması gerekirken, iki NaN'in eşit kabul edildiği C#-style kayan nokta karşılaştırmasını taklit eder.

```cpp
bool System::ObjectExt::Equals(const double &obj, const double &another)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const double\& | LHS kayan nokta değeri. |
| başka | const double\& | RHS kayan nokta değeri. |

### ReturnValue

Eğer **obj** ve **another** her ikisi de NaN ise ya da eşitse doğru, aksi takdirde yanlış.

## Ayrıca Bakınız

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Equals(const float\&, const float\&) method


IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmaması gerekirken, iki NaN'in eşit kabul edildiği C#-style kayan nokta karşılaştırmasını taklit eder.

```cpp
bool System::ObjectExt::Equals(const float &obj, const float &another)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const float\& | LHS kayan nokta değeri. |
| başka | const float\& | RHS kayan nokta değeri. |

### ReturnValue

Eğer **obj** ve **another** her ikisi de NaN ise ya da eşitse doğru, aksi takdirde yanlış.

## Ayrıca Bakınız

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Equals(const T\&, const T2\&) method




```cpp
template<typename T,typename T2> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```

## Ayrıca Bakınız

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Equals(const T\&, const T2\&) method


C# [Object.Equals](../../object/equals/) çağrıları için, C++'da herhangi bir tipte çalışan bir ikame. Akıllı gösterici tipleri için aşırı yükleme.

```cpp
template<typename T,typename T2> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


| Parametre | Açıklama |
| --- | --- |
| T | İlk nesne tipi. |
| T2 | İkinci nesne tipi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const T\& | İlk nesne. |
| başka | const T2\& | İkinci nesne. |

### ReturnValue

Nesneler eşit kabul edilirse doğru, aksi takdirde yanlış.

## Ayrıca Bakınız

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Equals(const T\&, const T2\&) method


C# [Object.Equals](../../object/equals/) çağrıları için, C++'da herhangi bir tipte çalışan bir ikame. Skaler tipler için aşırı yükleme.

```cpp
template<typename T,typename T2> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


| Parametre | Açıklama |
| --- | --- |
| T | İlk nesne tipi. |
| T2 | İkinci nesne tipi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const T\& | İlk nesne. |
| başka | const T2\& | İkinci nesne. |

### ReturnValue

Nesneler eşit kabul edilirse doğru, aksi takdirde yanlış.

## Ayrıca Bakınız

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Equals(T, const T2\&) method


C# [Object.Equals](../../object/equals/) çağrıları için, C++'da herhangi bir tipte çalışan bir ikame. Yapı tipleri için aşırı yükleme.

```cpp
template<typename T,typename T2> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(T obj, const T2 &another)
```


| Parametre | Açıklama |
| --- | --- |
| T | İlk nesne tipi. |
| T2 | İkinci nesne tipi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | T | İlk nesne. |
| başka | const T2\& | İkinci nesne. |

### ReturnValue

Nesneler eşit kabul edilirse doğru, aksi takdirde yanlış.

## Ayrıca Bakınız

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
