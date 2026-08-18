---
title: "System::Nullable::operator< Methode"
linktitle: "operator<"
second_title: "Aspose.PUB für C++"
description: "System::Nullable::operator< Methode. Bestimmt, ob der von dem aktuellen Objekt dargestellte Wert kleiner ist als der von dem angegebenen Nullable-Objekt dargestellte Wert, indem operator<() auf diese Werte in C++ angewendet wird."
type: docs
weight: 1600
url: /de/cpp/system/nullable/operator_/
---
## Nullable::operator<(const Nullable\<T1\>\&) const method


Bestimmt, ob der von dem aktuellen Objekt dargestellte Wert kleiner ist als der von dem angegebenen [Nullable](../)-Objekt dargestellte Wert, indem [operator<()](./) auf diese Werte angewendet wird.

```cpp
template<typename T1> bool System::Nullable<T>::operator<(const Nullable<T1> &other) const
```


| Parameter | Beschreibung |
| --- | --- |
| T1 | Der zugrunde liegende Typ des [Nullable](../)-Objekts, mit dem verglichen wird |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | const Nullable\<T1\>\& | Eine konstante Referenz auf das [Nullable](../)-Objekt, mit dem verglichen wird |

### ReturnValue

True, wenn der von dem aktuellen Objekt dargestellte Wert kleiner ist als der von dem angegebenen [Nullable](../)-Objekt dargestellte Wert, andernfalls - false

## Siehe auch

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Nullable::operator<(const T1\&) const method


Bestimmt, ob der von dem aktuellen Objekt dargestellte Wert kleiner ist als der angegebene Wert, indem [operator<()](./) auf diese Werte angewendet wird.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<(const T1 &other) const
```


| Parameter | Beschreibung |
| --- | --- |
| T1 | Der Typ des Wertes, mit dem verglichen wird |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| andere | const T1\& | Eine konstante Referenz auf den Wert, mit dem verglichen wird |

### ReturnValue

True, wenn der von dem aktuellen Objekt dargestellte Wert kleiner ist als der angegebene Wert, sonst - false

## Siehe auch

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Nullable::operator<(std::nullptr_t) const method


Gibt immer false zurück.

```cpp
bool System::Nullable<T>::operator<(std::nullptr_t) const
```

## Siehe auch

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
---
title: System::Nullable::operator> Methode
Linktitel: operator>
zweiter_Titel: Aspose.PUB für C++
description: 'System::Nullable::operator> Methode. Bestimmt, ob der von dem aktuellen Objekt dargestellte Wert größer ist als der von dem angegebenen Nullable-Objekt dargestellte Wert, indem operator>() auf diese Werte in C++ angewendet wird.'
Typ: Dokumentation
weight: 2000
url: /cpp/system/nullable/operator_/
---
## Nullable::operator>(const Nullable\<T1\>\&) const method


Bestimmt, ob der von dem aktuellen Objekt dargestellte Wert größer ist als der von dem angegebenen [Nullable](../)-Objekt dargestellte Wert, indem [operator>()](./) auf diese Werte angewendet wird.

```cpp
template<typename T1> bool System::Nullable<T>::operator>(const Nullable<T1> &other) const
```


| Parameter | Beschreibung |
| --- | --- |
| T1 | Der zugrunde liegende Typ des [Nullable](../)-Objekts, mit dem verglichen wird |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | const Nullable\<T1\>\& | Eine konstante Referenz auf das [Nullable](../)-Objekt, mit dem verglichen wird |

### ReturnValue

True, wenn der von dem aktuellen Objekt dargestellte Wert größer ist als der von dem angegebenen [Nullable](../)-Objekt dargestellte Wert, sonst - false

## Siehe auch

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Nullable::operator>(const T1\&) const method


Bestimmt, ob der von dem aktuellen Objekt dargestellte Wert größer ist als der angegebene Wert, indem [operator>()](./) auf diese Werte angewendet wird.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>(const T1 &other) const
```


| Parameter | Beschreibung |
| --- | --- |
| T1 | Der Typ des Wertes, mit dem verglichen wird |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| andere | const T1\& | Eine konstante Referenz auf den Wert, mit dem verglichen wird |

### ReturnValue

True, wenn der von dem aktuellen Objekt dargestellte Wert größer ist als der angegebene Wert, sonst - false

## Siehe auch

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Nullable::operator>(std::nullptr_t) const method


Gibt immer false zurück.

```cpp
bool System::Nullable<T>::operator>(std::nullptr_t) const
```

## Siehe auch

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
