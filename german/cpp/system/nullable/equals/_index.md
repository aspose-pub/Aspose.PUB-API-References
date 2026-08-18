---
title: "Methode System::Nullable::Equals"
linktitle: "Equals"
second_title: "Aspose.PUB für C++"
description: "Methode System::Nullable::Equals. Bestimmt, ob der vom aktuellen Objekt dargestellte Wert dem vom angegebenen Nullable-Objekt in C++ dargestellten Wert entspricht."
type: docs
weight: 200
url: /de/cpp/system/nullable/equals/
---
## Nullable::Equals method


Bestimmt, ob der von dem aktuellen Objekt dargestellte Wert gleich dem von dem angegebenen [Nullable](../)-Objekt dargestellten Wert ist.

```cpp
template<typename T1> std::enable_if<IsNullable<T1>::value, bool>::type System::Nullable<T>::Equals(const T1 &other) const
```


| Parameter | Beschreibung |
| --- | --- |
| T1 | Der zugrunde liegende Typ des [Nullable](../)-Objekts, mit dem verglichen wird |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | const T1\& | Eine konstante Referenz auf das [Nullable](../)-Objekt, mit dem verglichen wird |

### ReturnValue

True, wenn der von dem aktuellen Objekt dargestellte Wert gleich dem von dem angegebenen [Nullable](../)-Objekt dargestellten Wert ist, sonst - false

## Siehe auch

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
