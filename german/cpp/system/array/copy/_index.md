---
title: "System::Array::Copy-Methode"
linktitle: "Copy"
second_title: "Aspose.PUB für C++"
description: "System::Array::Copy-Methode. Kopiert die angegebene Anzahl von Elementen vom Quellarray zum Zielarray in C++."
type: docs
weight: 4900
url: /de/cpp/system/array/copy/
---
## Array::Copy(const ArrayPtr\<SrcType\>\&, const ArrayPtr\<DstType\>\&, int64_t) method


Kopiert die angegebene Anzahl von Elementen vom Quellarray zum Zielarray.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcArray | const ArrayPtr\<SrcType\>\& | Quellarray |
| dstArray | const ArrayPtr\<DstType\>\& | Zielarray |
| Anzahl | int64_t | Die Anzahl der zu kopierenden Elemente |

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) method


Kopiert eine angegebene Anzahl von Elementen vom Quellarray, beginnend beim angegebenen Index, zur angegebenen Position im Zielarray.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


| Parameter | Beschreibung |
| --- | --- |
| SrcType | Typ der Elemente im Quellarray |
| DstType | Typ der Elemente im Zielarray |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcArray | const ArrayPtr\<SrcType\>\& | Quellarray |
| srcIndex | int64_t | Index im Quellarray, der den Beginn des zu kopierenden Elementsbereichs bezeichnet |
| dstArray | const ArrayPtr\<DstType\>\& | Zielarray |
| dstIndex | int64_t | Index im Zielarray, an dem das Einfügen der kopierten Elemente beginnt |
| Anzahl | int64_t | Die Anzahl der zu kopierenden Elemente |

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) method


Kopiert eine angegebene Anzahl von Elementen vom Quellarray, beginnend beim angegebenen Index, zur angegebenen Position in der Zielarray-Ansicht.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```


| Parameter | Beschreibung |
| --- | --- |
| SrcType | Typ der Elemente im Quellarray |
| DstType | Typ der Elemente in der Ansicht des Zielarrays |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcArray | const ArrayPtr\<SrcType\>\& | Quellarray |
| srcIndex | int64_t | Index im Quellarray, der den Beginn des zu kopierenden Elementsbereichs bezeichnet |
| dstArray | System::Details::ArrayView\<DstType\> | Ansicht des Zielarrays |
| dstIndex | int64_t | Index in der Ziel-Array-Ansicht, an dem das Einfügen kopierter Elemente beginnen soll |
| Anzahl | int64_t | Die Anzahl der zu kopierenden Elemente |

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, N\>\&, int64_t, int64_t) method


Kopiert eine angegebene Anzahl von Elementen vom Quellarray, beginnend beim angegebenen Index, zur angegebenen Position im Zielarray im Stack.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, N> &dstArray, int64_t dstIndex, int64_t count)
```


| Parameter | Beschreibung |
| --- | --- |
| SrcType | Typ der Elemente im Quellarray |
| DstType | Typ der Elemente im Zielarray im Stack |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcArray | const ArrayPtr\<SrcType\>\& | Quellarray |
| srcIndex | int64_t | Index im Quellarray, der den Beginn des zu kopierenden Elementsbereichs bezeichnet |
| dstArray | System::Details::StackArray\<DstType, N\>\& | Zielarray im Stack |
| dstIndex | int64_t | Index im Zielarray im Stack, an dem das Einfügen kopierter Elemente beginnen soll |
| Anzahl | int64_t | Die Anzahl der zu kopierenden Elemente |

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::ArrayView\<DstType\>, int64_t) method


Kopiert die angegebene Anzahl von Elementen vom Quellarray zur Zielarray-Ansicht.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcArray | const ArrayPtr\<SrcType\>\& | Quellarray |
| dstArray | System::Details::ArrayView\<DstType\> | Ansicht des Zielarrays |
| Anzahl | int64_t | Die Anzahl der zu kopierenden Elemente |

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, int64_t) method


Kopiert die angegebene Anzahl von Elementen vom Quellarray zum Zielarray im Stack.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::StackArray<DstType, N> &dstArray, int64_t count)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcArray | const ArrayPtr\<SrcType\>\& | Quellarray |
| dstArray | System::Details::StackArray\<DstType, N\>\& | Zielarray im Stack |
| Anzahl | int64_t | Die Anzahl der zu kopierenden Elemente |

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Array::Copy(System::Details::ArrayView\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) method


Kopiert eine angegebene Anzahl von Elementen von der Quellarray-Ansicht, beginnend beim angegebenen Index, zur angegebenen Position im Zielarray im Stack.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```


| Parameter | Beschreibung |
| --- | --- |
| SrcType | Typ der Elemente im Quellarray im Stack |
| DstType | Typ der Elemente im Zielarray im Stack |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\>\& | Quellarray-Ansicht |
| srcIndex | int64_t | Index in der Quellarray-Ansicht, der den Beginn des zu kopierenden Bereichs bezeichnet |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Zielarray im Stack |
| dstIndex | int64_t | Index im Zielarray im Stack, an dem das Einfügen kopierter Elemente beginnen soll |
| Anzahl | int64_t | Die Anzahl der zu kopierenden Elemente |

## Siehe auch

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Array::Copy(System::Details::ArrayView\<SrcType\>, const ArrayPtr\<DstType\>\&, int64_t) method


Kopiert die angegebene Anzahl von Elementen von der Quellarray-Ansicht zum Zielarray.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Quellarray-Ansicht |
| dstArray | const ArrayPtr\<DstType\>\& | Zielarray |
| Anzahl | int64_t | Die Anzahl der zu kopierenden Elemente |

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) method


Kopiert eine angegebene Anzahl von Elementen von der Quellarray-Ansicht, beginnend beim angegebenen Index, zur angegebenen Position im Zielarray.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


| Parameter | Beschreibung |
| --- | --- |
| SrcType | Typ der Elemente in der Quellarray-Ansicht |
| DstType | Typ der Elemente im Zielarray |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Quellarray-Ansicht |
| srcIndex | int64_t | Index in der Quellarray-Ansicht, der den Beginn des zu kopierenden Bereichs bezeichnet |
| dstArray | const ArrayPtr\<DstType\>\& | Zielarray |
| dstIndex | int64_t | Index im Zielarray, an dem das Einfügen der kopierten Elemente beginnt |
| Anzahl | int64_t | Die Anzahl der zu kopierenden Elemente |

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) method


Kopiert eine angegebene Anzahl von Elementen von der Quellarray-Ansicht, beginnend beim angegebenen Index, zur angegebenen Position in der Zielarray-Ansicht.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```


| Parameter | Beschreibung |
| --- | --- |
| SrcType | Typ der Elemente in der Quellarray-Ansicht |
| DstType | Typ der Elemente in der Ansicht des Zielarrays |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Quellarray-Ansicht |
| srcIndex | int64_t | Index in der Quellarray-Ansicht, der den Beginn des zu kopierenden Bereichs bezeichnet |
| dstArray | System::Details::ArrayView\<DstType\> | Ansicht des Zielarrays |
| dstIndex | int64_t | Index in der Ziel-Array-Ansicht, an dem das Einfügen kopierter Elemente beginnen soll |
| Anzahl | int64_t | Die Anzahl der zu kopierenden Elemente |

## Siehe auch

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Array::Copy(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, int64_t) method


Kopiert die angegebene Anzahl von Elementen von der Quellarray-Ansicht zur Zielarray-Ansicht.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Quellarray-Ansicht |
| dstArray | System::Details::ArrayView\<DstType\> | Ansicht des Zielarrays |
| Anzahl | int64_t | Die Anzahl der zu kopierenden Elemente |

## Siehe auch

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, const ArrayPtr\<DstType\>\&, int64_t) method


Kopiert die angegebene Anzahl von Elementen vom Quellarray im Stack zum Zielarray.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | Quellarray im Stack |
| dstArray | const ArrayPtr\<DstType\>\& | Zielarray |
| Anzahl | int64_t | Die Anzahl der zu kopierenden Elemente |

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) method


Kopiert eine angegebene Anzahl von Elementen vom Quellarray im Stack, beginnend beim angegebenen Index, zur angegebenen Position im Zielarray.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


| Parameter | Beschreibung |
| --- | --- |
| SrcType | Typ der Elemente im Quellarray im Stack |
| DstType | Typ der Elemente im Zielarray |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | Quellarray im Stack |
| srcIndex | int64_t | Index im Quellarray im Stack, der den Beginn des zu kopierenden Bereichs bezeichnet |
| dstArray | const ArrayPtr\<DstType\>\& | Zielarray |
| dstIndex | int64_t | Index im Zielarray, an dem das Einfügen der kopierten Elemente beginnt |
| Anzahl | int64_t | Die Anzahl der zu kopierenden Elemente |

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) method


Kopiert eine angegebene Anzahl von Elementen vom Quellarray im Stack, beginnend beim angegebenen Index, zur angegebenen Position im Zielarray im Stack.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```


| Parameter | Beschreibung |
| --- | --- |
| SrcType | Typ der Elemente im Quellarray im Stack |
| DstType | Typ der Elemente im Zielarray im Stack |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | Quellarray im Stack |
| srcIndex | int64_t | Index im Quellarray im Stack, der den Beginn des zu kopierenden Bereichs bezeichnet |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Zielarray im Stack |
| dstIndex | int64_t | Index im Zielarray im Stack, an dem das Einfügen kopierter Elemente beginnen soll |
| Anzahl | int64_t | Die Anzahl der zu kopierenden Elemente |

## Siehe auch

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, int64_t) method


Kopiert die angegebene Anzahl von Elementen vom Quellarray im Stack zum Zielarray im Stack.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, System::Details::StackArray<DstType, ND> &dstArray, int64_t count)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | Quellarray im Stack |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Zielarray im Stack |
| Anzahl | int64_t | Die Anzahl der zu kopierenden Elemente |

## Siehe auch

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
