---
title: "System::Nullable::operator!=-Methode"
linktitle: "operator!="
second_title: "Aspose.PUB für C++"
description: "System::Nullable::operator!=-Methode. Bestimmt, ob der vom aktuellen Objekt dargestellte Wert nicht gleich dem vom angegebenen Nullable-Objekt in C++ dargestellten Wert ist."
type: docs
weight: 1000
url: /de/cpp/system/nullable/operator!=/
---
## Nullable::operator!=(const Nullable\<T1\>\&) const method


Bestimmt, ob der vom aktuellen Objekt dargestellte Wert nicht gleich dem vom angegebenen [Nullable](../)-Objekt ist.

```cpp
template<typename T1> bool System::Nullable<T>::operator!=(const Nullable<T1> &other) const
```


| Parameter | Beschreibung |
| --- | --- |
| T1 | Der zugrunde liegende Typ des [Nullable](../)-Objekts, mit dem verglichen wird |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | const Nullable\<T1\>\& | Eine konstante Referenz auf das [Nullable](../)-Objekt, mit dem verglichen wird |

### ReturnValue

True, wenn der vom aktuellen Objekt dargestellte Wert nicht gleich dem vom angegebenen [Nullable](../)-Objekt ist, sonst - false

## Siehe auch

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Nullable::operator!=(const T1\&) const method


Bestimmt, ob der vom aktuellen Objekt dargestellte Wert nicht dem angegebenen Wert entspricht.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator!=(const T1 &other) const
```


| Parameter | Beschreibung |
| --- | --- |
| T1 | Der Typ des Wertes, mit dem verglichen wird |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| andere | const T1\& | Eine konstante Referenz auf den Wert, mit dem verglichen wird |

### ReturnValue

True, wenn der vom aktuellen Objekt dargestellte Wert nicht gleich dem angegebenen Wert ist, sonst - false

## Siehe auch

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Nullable::operator!=(std::nullptr_t) const method


Bestimmt, ob der vom aktuellen Objekt dargestellte Wert nicht null ist.

```cpp
bool System::Nullable<T>::operator!=(std::nullptr_t) const
```


### ReturnValue

True, wenn der vom aktuellen Objekt dargestellte Wert nicht null ist, sonst - false

## Siehe auch

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
