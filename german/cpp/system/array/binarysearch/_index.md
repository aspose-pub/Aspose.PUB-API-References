---
title: "System::Array::BinarySearch Methode"
linktitle: "BinarySearch"
second_title: "Aspose.PUB für C++"
description: "System::Array::BinarySearch Methode. Führt eine binäre Suche im sortierten Array in C++ durch."
type: docs
weight: 4600
url: /de/cpp/system/array/binarysearch/
---
## Array::BinarySearch(System::ArrayPtr\<T\>, const T\&) method


Führt eine binäre Suche im sortierten Array durch.

```cpp
static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const T &item)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arr | System::ArrayPtr\<T\> | Sortiertes Array, in dem gesucht werden soll |
| Element | const T\& | Ein zu suchendes Element |

### ReturnValue

Index des gesuchten Elements, falls gefunden, sonst eine negative ganze Zahl, die das bitweise Komplement des Index des nächsten Elements, das größer ist als das gesuchte Element, darstellt, oder, falls kein größeres Element existiert, das bitweise Komplement der Anzahl der Elemente im Array.

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Array::BinarySearch(System::ArrayPtr\<T\>, const Y\&, const SharedPtr\<Collections::Generic::IComparer\<Z\>\>\&) method


NICHT IMPLEMENTIERT.

```cpp
template<typename Y,typename Z> static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const Y &item, const SharedPtr<Collections::Generic::IComparer<Z>> &comparer)
```


## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
