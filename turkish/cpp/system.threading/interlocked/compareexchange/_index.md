---
title: "System::Threading::Interlocked::CompareExchange metodu"
linktitle: "CompareExchange"
second_title: "Aspose.PUB için C++"
description: "System::Threading::Interlocked::CompareExchange metodu. Değişken üzerindeki değeri karşılaştırarak değiştirir: değişkenin belirli bir değere eşit olup olmadığını kontrol eder ve yalnızca saklanan değer beklendiği gibi ise yeni değeri depolar."
type: docs
weight: 200
url: /tr/cpp/system.threading/interlocked/compareexchange/
---
## Interlocked::CompareExchange(int32_t\&, int32_t, int32_t, bool\&) method


Değişken üzerindeki değeri karşılaştırmalı değiştirir: değişkenin belirli bir değere eşit olup olmadığını kontrol eder ve saklanan değer beklendiğiyle eşleşiyorsa yeni değeri depolar.

```cpp
static int32_t System::Threading::Interlocked::CompareExchange(int32_t &location1, int32_t value, int32_t comparand, bool &succeeded)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| location1 | int32_t\& | Değiştirmek için değişken referansı. |
| değer | int32_t | Depolanacak değer. |
| comparand | int32_t | Değiş tokuş etmeden önce değişkenin değeriyle karşılaştırılacak değer. |
| başarılı | bool\& | Değiş tokuş gerçekleştiğinde true, aksi takdirde false olarak ayarlanan değişkene referans. |

### ReturnValue

Değişiklik yapılıp yapılmadığına bakılmaksızın işlem başlangıcındaki değişkenin değeri.

## Ayrıca Bakınız

* Class [Interlocked](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PUB for C++](../../../)
## Interlocked::CompareExchange(T\&, T, T) method


Değişken üzerindeki değeri karşılaştırmalı değiştirir: değişkenin belirli bir değere eşit olup olmadığını kontrol eder ve saklanan değer beklendiğiyle eşleşiyorsa yeni değeri depolar.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```


| Parametre | Açıklama |
| --- | --- |
| T | Değişken tipi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| location1 | T\& | Değiştirmek için değişken referansı. |
| değer | T | Depolanacak değer. |
| comparand | T | Değiş tokuş etmeden önce değişkenin değeriyle karşılaştırılacak değer. |

### ReturnValue

Değişiklik yapılıp yapılmadığına bakılmaksızın işlem başlangıcındaki değişkenin değeri.

## Ayrıca Bakınız

* Class [Interlocked](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PUB for C++](../../../)
## Interlocked::CompareExchange(T\&, T, T) method


Değişken üzerindeki değeri karşılaştırmalı değiştirir: değişkenin belirli bir değere eşit olup olmadığını kontrol eder ve saklanan değer beklendiğiyle eşleşiyorsa yeni değeri depolar. Uygulanmadı.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```


| Parametre | Açıklama |
| --- | --- |
| T | Değişken tipi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| location1 | T\& | Değiştirmek için değişken referansı. |
| değer | T | Depolanacak değer. |
| comparand | T | Değiş tokuş etmeden önce değişkenin değeriyle karşılaştırılacak değer. |

### ReturnValue

Değişiklik yapılıp yapılmadığına bakılmaksızın işlem başlangıcındaki değişkenin değeri.

## Ayrıca Bakınız

* Class [Interlocked](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PUB for C++](../../../)
