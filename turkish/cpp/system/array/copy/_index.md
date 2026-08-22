---
title: "System::Array::Copy metodu"
linktitle: "Copy"
second_title: "Aspose.PUB için C++"
description: "System::Array::Copy metodu. Belirtilen sayıda öğeyi kaynak diziden hedef diziye C++'da kopyalar."
type: docs
weight: 4900
url: /tr/cpp/system/array/copy/
---
## Array::Copy(const ArrayPtr\<SrcType\>\&, const ArrayPtr\<DstType\>\&, int64_t) method


Belirtilen sayıda öğeyi kaynak diziden hedef diziye kopyalar.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| srcArray | const ArrayPtr\<SrcType\>\& | Kaynak dizi |
| dstArray | const ArrayPtr\<DstType\>\& | Hedef dizi |
| sayım | int64_t | Kopyalanacak öğe sayısı |

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) method


Belirtilen indeksten başlayarak kaynak diziden belirtilen sayıda öğeyi hedef dizideki belirtilen konuma kopyalar.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


| Parametre | Açıklama |
| --- | --- |
| SrcType | Kaynak dizideki öğelerin türü |
| DstType | Hedef dizideki öğelerin türü |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| srcArray | const ArrayPtr\<SrcType\>\& | Kaynak dizi |
| srcIndex | int64_t | Kaynak dizide kopyalanacak öğe aralığının başlangıcını belirten indeks |
| dstArray | const ArrayPtr\<DstType\>\& | Hedef dizi |
| dstIndex | int64_t | Hedef dizide kopyalanan öğelerin eklenmeye başlanacağı indeks |
| sayım | int64_t | Kopyalanacak öğe sayısı |

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) method


Belirtilen indeksten başlayarak kaynak diziden belirtilen sayıda öğeyi hedef dizi görünümündeki belirtilen konuma kopyalar.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```


| Parametre | Açıklama |
| --- | --- |
| SrcType | Kaynak dizideki öğelerin türü |
| DstType | Hedef dizi görünümündeki öğelerin türü |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| srcArray | const ArrayPtr\<SrcType\>\& | Kaynak dizi |
| srcIndex | int64_t | Kaynak dizide kopyalanacak öğe aralığının başlangıcını belirten indeks |
| dstArray | System::Details::ArrayView\<DstType\> | Hedef dizi görünümü |
| dstIndex | int64_t | Kopyalanan öğelerin eklenmeye başlanacağı hedef dizi görünümündeki indeks |
| sayım | int64_t | Kopyalanacak öğe sayısı |

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, N\>\&, int64_t, int64_t) method


Belirtilen indeksten başlayarak kaynak diziden belirtilen sayıda öğeyi yığıt üzerindeki hedef dizideki belirtilen konuma kopyalar.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, N> &dstArray, int64_t dstIndex, int64_t count)
```


| Parametre | Açıklama |
| --- | --- |
| SrcType | Kaynak dizideki öğelerin türü |
| DstType | Yığıt üzerindeki hedef dizideki öğelerin türü |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| srcArray | const ArrayPtr\<SrcType\>\& | Kaynak dizi |
| srcIndex | int64_t | Kaynak dizide kopyalanacak öğe aralığının başlangıcını belirten indeks |
| dstArray | System::Details::StackArray\<DstType, N\>\& | Yığıt üzerindeki hedef dizi |
| dstIndex | int64_t | Kopyalanan öğelerin eklenmeye başlanacağı yığıt üzerindeki hedef dizideki indeks |
| sayım | int64_t | Kopyalanacak öğe sayısı |

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::ArrayView\<DstType\>, int64_t) method


Belirtilen sayıda öğeyi kaynak diziden hedef dizi görünümüne kopyalar.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| srcArray | const ArrayPtr\<SrcType\>\& | Kaynak dizi |
| dstArray | System::Details::ArrayView\<DstType\> | Hedef dizi görünümü |
| sayım | int64_t | Kopyalanacak öğe sayısı |

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, int64_t) method


Kaynak diziden yığıt üzerindeki hedef diziye belirtilen sayıda öğeyi kopyalar.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::StackArray<DstType, N> &dstArray, int64_t count)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| srcArray | const ArrayPtr\<SrcType\>\& | Kaynak dizi |
| dstArray | System::Details::StackArray\<DstType, N\>\& | Yığıt üzerindeki hedef dizi |
| sayım | int64_t | Kopyalanacak öğe sayısı |

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Array::Copy(System::Details::ArrayView\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) method


Belirtilen indeksten başlayarak kaynak dizi görünümünden yığıt üzerindeki hedef dizideki belirtilen konuma belirtilen sayıda öğeyi kopyalar.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```


| Parametre | Açıklama |
| --- | --- |
| SrcType | Yığıt üzerindeki kaynak dizideki öğelerin türü |
| DstType | Yığıt üzerindeki hedef dizideki öğelerin türü |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\>\& | Kaynak dizi görünümü |
| srcIndex | int64_t | Kopyalanacak öğe aralığının başlangıcını belirten kaynak dizi görünümündeki indeks |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Yığıt üzerindeki hedef dizi |
| dstIndex | int64_t | Kopyalanan öğelerin eklenmeye başlanacağı yığıt üzerindeki hedef dizideki indeks |
| sayım | int64_t | Kopyalanacak öğe sayısı |

## Ayrıca Bakınız

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Array::Copy(System::Details::ArrayView\<SrcType\>, const ArrayPtr\<DstType\>\&, int64_t) method


Belirtilen sayıda öğeyi kaynak dizi görünümünden hedef diziye kopyalar.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Kaynak dizi görünümü |
| dstArray | const ArrayPtr\<DstType\>\& | Hedef dizi |
| sayım | int64_t | Kopyalanacak öğe sayısı |

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) method


Belirtilen indeksten başlayarak kaynak dizi görünümünden belirtilen sayıda öğeyi hedef dizideki belirtilen konuma kopyalar.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


| Parametre | Açıklama |
| --- | --- |
| SrcType | Kaynak dizi görünümündeki öğelerin türü |
| DstType | Hedef dizideki öğelerin türü |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Kaynak dizi görünümü |
| srcIndex | int64_t | Kopyalanacak öğe aralığının başlangıcını belirten kaynak dizi görünümündeki indeks |
| dstArray | const ArrayPtr\<DstType\>\& | Hedef dizi |
| dstIndex | int64_t | Hedef dizide kopyalanan öğelerin eklenmeye başlanacağı indeks |
| sayım | int64_t | Kopyalanacak öğe sayısı |

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) method


Belirtilen indeksten başlayarak kaynak dizi görünümünden belirtilen sayıda öğeyi hedef dizi görünümündeki belirtilen konuma kopyalar.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```


| Parametre | Açıklama |
| --- | --- |
| SrcType | Kaynak dizi görünümündeki öğelerin türü |
| DstType | Hedef dizi görünümündeki öğelerin türü |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Kaynak dizi görünümü |
| srcIndex | int64_t | Kopyalanacak öğe aralığının başlangıcını belirten kaynak dizi görünümündeki indeks |
| dstArray | System::Details::ArrayView\<DstType\> | Hedef dizi görünümü |
| dstIndex | int64_t | Kopyalanan öğelerin eklenmeye başlanacağı hedef dizi görünümündeki indeks |
| sayım | int64_t | Kopyalanacak öğe sayısı |

## Ayrıca Bakınız

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Array::Copy(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, int64_t) method


Belirtilen sayıda öğeyi kaynak dizi görünümünden hedef dizi görünümüne kopyalar.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Kaynak dizi görünümü |
| dstArray | System::Details::ArrayView\<DstType\> | Hedef dizi görünümü |
| sayım | int64_t | Kopyalanacak öğe sayısı |

## Ayrıca Bakınız

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, const ArrayPtr\<DstType\>\&, int64_t) method


Yığıt üzerindeki kaynak diziden hedef diziye belirtilen sayıda öğeyi kopyalar.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | Yığında bulunan kaynak dizi |
| dstArray | const ArrayPtr\<DstType\>\& | Hedef dizi |
| sayım | int64_t | Kopyalanacak öğe sayısı |

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) method


Belirtilen indeksten başlayarak yığıt üzerindeki kaynak diziden belirtilen sayıda öğeyi hedef dizideki belirtilen konuma kopyalar.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


| Parametre | Açıklama |
| --- | --- |
| SrcType | Yığıt üzerindeki kaynak dizideki öğelerin türü |
| DstType | Hedef dizideki öğelerin türü |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | Yığında bulunan kaynak dizi |
| srcIndex | int64_t | Kopyalanacak öğeler aralığının başlangıcını belirten yığındaki kaynak dizi içindeki indeks |
| dstArray | const ArrayPtr\<DstType\>\& | Hedef dizi |
| dstIndex | int64_t | Hedef dizide kopyalanan öğelerin eklenmeye başlanacağı indeks |
| sayım | int64_t | Kopyalanacak öğe sayısı |

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) method


Belirtilen indeksten başlayarak yığıt üzerindeki kaynak diziden yığıt üzerindeki hedef dizideki belirtilen konuma belirtilen sayıda öğeyi kopyalar.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```


| Parametre | Açıklama |
| --- | --- |
| SrcType | Yığıt üzerindeki kaynak dizideki öğelerin türü |
| DstType | Yığıt üzerindeki hedef dizideki öğelerin türü |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | Yığında bulunan kaynak dizi |
| srcIndex | int64_t | Kopyalanacak öğeler aralığının başlangıcını belirten yığındaki kaynak dizi içindeki indeks |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Yığıt üzerindeki hedef dizi |
| dstIndex | int64_t | Kopyalanan öğelerin eklenmeye başlanacağı yığıt üzerindeki hedef dizideki indeks |
| sayım | int64_t | Kopyalanacak öğe sayısı |

## Ayrıca Bakınız

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, int64_t) method


Yığıt üzerindeki kaynak diziden yığıt üzerindeki hedef diziye belirtilen sayıda öğeyi kopyalar.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, System::Details::StackArray<DstType, ND> &dstArray, int64_t count)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | Yığında bulunan kaynak dizi |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Yığıt üzerindeki hedef dizi |
| sayım | int64_t | Kopyalanacak öğe sayısı |

## Ayrıca Bakınız

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
