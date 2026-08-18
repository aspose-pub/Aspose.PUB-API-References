---
title: "System::Collections::Generic::_net_binnary_search Methode"
linktitle: "_net_binnary_search"
second_title: "Aspose.PUB für C++"
description: "System::Collections::Generic::_net_binnary_search Methode. Implementiert eine binäre Suche in einem zufälligen Zugriffs‑Container. Spezialisierung für Smart‑Pointer. Verwendet die Methode System::Object::CompareTo in C++."
type: docs
weight: 4900
url: /de/cpp/system.collections.generic/_net_binnary_search/
---
## System::Collections::Generic::_net_binnary_search(const containterT\<T, Allocator\>\&, int, int, T) method


Implementiert eine binäre Suche in einem zufälligen Zugriffs‑Container. Spezialisierung für Smart‑Pointer. Verwendet die Methode System::Object::CompareTo.

```cpp
template<template< typename, typename > class,class T,class Allocator> std::enable_if<IsSmartPtr<T>::value, int>::type System::Collections::Generic::_net_binnary_search(const containterT<T, Allocator> &container, int index, int count, T value)
```


| Parameter | Beschreibung |
| --- | --- |
| containerT | STL‑artiger Container‑Template‑Typ mit zwei Template‑Argumenten: Elementtyp und Allocator‑Typ. |
| T | Elementtyp. |
| Allocator | Allocator-Typ. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Container | const containterT\<T, Allocator\>\& | Container, in dem gesucht wird. |
| Index | int | Startindex des Suchbereichs. |
| Anzahl | int | Länge des Suchbereichs. |
| Wert | T | Gesuchter Wert. |

### ReturnValue

Falls gefunden, Index des nächsten Elements; andernfalls Komplement des Index, an dem die Suche gestoppt wurde.

## Siehe auch

* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
## System::Collections::Generic::_net_binnary_search(const containterT\<T, Allocator\>\&, int, int, T) method


Implementiert binäre Suche in einem zufälligen Zugriffs-Container. Spezialisierung für Werttypen. Verwendet die CompareTo-Methode.

```cpp
template<template< typename, typename > class,class T,class Allocator> std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value, int>::type System::Collections::Generic::_net_binnary_search(const containterT<T, Allocator> &container, int index, int count, T value)
```


| Parameter | Beschreibung |
| --- | --- |
| containerT | STL‑artiger Container‑Template‑Typ mit zwei Template‑Argumenten: Elementtyp und Allocator‑Typ. |
| T | Elementtyp. |
| Allocator | Allocator-Typ. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Container | const containterT\<T, Allocator\>\& | Container, in dem gesucht wird. |
| Index | int | Startindex des Suchbereichs. |
| Anzahl | int | Länge des Suchbereichs. |
| Wert | T | Gesuchter Wert. |

### ReturnValue

Falls gefunden, Index des nächsten Elements; andernfalls Komplement des Index, an dem die Suche gestoppt wurde.

## Siehe auch

* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
## System::Collections::Generic::_net_binnary_search(const containterT\<T, Allocator\>\&, int, int, T) method


Implementiert binäre Suche in einem zufälligen Zugriffs-Container. Spezialisierung für skalare Typen. Vergleicht Elemente mit den Größer- und Kleiner-Operatoren.

```cpp
template<template< typename, typename > class,class T,class Allocator> std::enable_if<std::is_scalar<T>::value, int>::type System::Collections::Generic::_net_binnary_search(const containterT<T, Allocator> &container, int index, int count, T value)
```


| Parameter | Beschreibung |
| --- | --- |
| containerT | STL‑artiger Container‑Template‑Typ mit zwei Template‑Argumenten: Elementtyp und Allocator‑Typ. |
| T | Elementtyp. |
| Allocator | Allocator-Typ. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Container | const containterT\<T, Allocator\>\& | Container, in dem gesucht wird. |
| Index | int | Startindex des Suchbereichs. |
| Anzahl | int | Länge des Suchbereichs. |
| Wert | T | Gesuchter Wert. |

### ReturnValue

Falls gefunden, Index des nächsten Elements; andernfalls Komplement des Index, an dem die Suche gestoppt wurde.

## Siehe auch

* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
## System::Collections::Generic::_net_binnary_search(const containterT\<T, Allocator\>\&, int, int, T, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) method


Implementiert binäre Suche in einem zufälligen Zugriffs-Container.

```cpp
template<template< typename, typename > class,class T,class Allocator> int System::Collections::Generic::_net_binnary_search(const containterT<T, Allocator> &container, int index, int count, T value, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer)
```


| Parameter | Beschreibung |
| --- | --- |
| containerT | STL‑artiger Container‑Template‑Typ mit zwei Template‑Argumenten: Elementtyp und Allocator‑Typ. |
| T | Elementtyp. |
| Allocator | Allocator-Typ. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Container | const containterT\<T, Allocator\>\& | Container, in dem gesucht wird. |
| Index | int | Startindex des Suchbereichs. |
| Anzahl | int | Länge des Suchbereichs. |
| Wert | T | Gesuchter Wert. |
| comparer | const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\& | [Comparer](../comparer/) Objekt. |

### ReturnValue

Falls gefunden, Index des nächsten Elements; andernfalls Komplement des Index, an dem die Suche gestoppt wurde.

## Siehe auch

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [IComparer](../icomparer/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
