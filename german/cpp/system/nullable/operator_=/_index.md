---
title: "System::Nullable::operator<=-Methode"
linktitle: "operator<="
second_title: "Aspose.PUB für C++"
description: "System::Nullable::operator<=-Methode. Bestimmt, ob der vom aktuellen Objekt dargestellte Wert kleiner oder gleich dem vom angegebenen Nullable-Objekt ist, indem operator<=() auf diese Werte in C++ angewendet wird."
type: docs
weight: 1700
url: /de/cpp/system/nullable/operator_=/
---
## Nullable::operator<=(const Nullable\<T1\>\&) const method


Bestimmt, ob der vom aktuellen Objekt dargestellte Wert kleiner oder gleich dem vom angegebenen [Nullable](../)-Objekt ist, indem [operator<=()](./) auf diese Werte angewendet wird.

```cpp
template<typename T1> bool System::Nullable<T>::operator<=(const Nullable<T1> &other) const
```


| Parameter | Beschreibung |
| --- | --- |
| T1 | Der zugrunde liegende Typ des [Nullable](../)-Objekts, mit dem verglichen wird |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | const Nullable\<T1\>\& | Eine konstante Referenz auf das [Nullable](../)-Objekt, mit dem verglichen wird |

### ReturnValue

Wahr, wenn der vom aktuellen Objekt dargestellte Wert kleiner oder gleich dem vom angegebenen [Nullable](../)-Objekt ist, sonst - falsch

## Siehe auch

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Nullable::operator<=(const T1\&) const method


Bestimmt, ob der vom aktuellen Objekt dargestellte Wert kleiner oder gleich dem angegebenen Wert ist, indem [operator<=()](./) auf diese Werte angewendet wird.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<=(const T1 &other) const
```


| Parameter | Beschreibung |
| --- | --- |
| T1 | Der Typ des Wertes, mit dem verglichen wird |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| andere | const T1\& | Eine konstante Referenz auf den Wert, mit dem verglichen wird |

### ReturnValue

Wahr, wenn der vom aktuellen Objekt dargestellte Wert kleiner oder gleich dem angegebenen Wert ist, sonst - falsch

## Siehe auch

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Nullable::operator<=(std::nullptr_t) const method


Gibt immer false zurück.

```cpp
bool System::Nullable<T>::operator<=(std::nullptr_t) const
```

## Siehe auch

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
---
title: System::Nullable::operator>= Methode
Linktitel: operator>=
zweiter_Titel: Aspose.PUB für C++
description: 'System::Nullable::operator>= Methode. Bestimmt, ob der vom aktuellen Objekt dargestellte Wert größer oder gleich dem vom angegebenen Nullable-Objekt ist, indem operator>=() auf diese Werte in C++ angewendet wird.'
Typ: Dokumentation
weight: 2100
url: /cpp/system/nullable/operator_=/
---
## Nullable::operator>=(const Nullable\<T1\>\&) const method


Bestimmt, ob der vom aktuellen Objekt dargestellte Wert größer oder gleich dem vom angegebenen [Nullable](../)-Objekt ist, indem [operator>=()](./) auf diese Werte angewendet wird.

```cpp
template<typename T1> bool System::Nullable<T>::operator>=(const Nullable<T1> &other) const
```


| Parameter | Beschreibung |
| --- | --- |
| T1 | Der zugrunde liegende Typ des [Nullable](../)-Objekts, mit dem verglichen wird |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | const Nullable\<T1\>\& | Eine konstante Referenz auf das [Nullable](../)-Objekt, mit dem verglichen wird |

### ReturnValue

Wahr, wenn der vom aktuellen Objekt dargestellte Wert größer oder gleich dem vom angegebenen [Nullable](../)-Objekt ist, sonst - falsch

## Siehe auch

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Nullable::operator>=(const T1\&) const method


Bestimmt, ob der vom aktuellen Objekt dargestellte Wert größer oder gleich dem angegebenen Objekt ist, indem [operator>=()](./) auf diese Werte angewendet wird.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>=(const T1 &other) const
```


| Parameter | Beschreibung |
| --- | --- |
| T1 | Der zugrunde liegende Typ des Werts, mit dem der vom aktuellen Objekt dargestellte Wert verglichen wird |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| andere | const T1\& | Eine konstante Referenz auf ein Objekt, mit dem das aktuelle Objekt verglichen wird |

### ReturnValue

Wahr, wenn der vom aktuellen Objekt dargestellte Wert größer oder gleich dem vom angegebenen Objekt ist, sonst - falsch

## Siehe auch

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Nullable::operator>=(std::nullptr_t) const method


Gibt immer false zurück.

```cpp
bool System::Nullable<T>::operator>=(std::nullptr_t) const
```


### ReturnValue

Immer - falsch

## Siehe auch

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
---
title: System::Nullable::operator|= Methode
linktitle: operator|=
zweiter_Titel: Aspose.PUB für C++
description: 'System::Nullable::operator|= Methode. Wendet operator|=() auf den vom aktuellen Objekt dargestellten Wert an und verwendet den angegebenen Wert als Rechtsargument in C++.'
Typ: Dokumentation
weight: 2200
url: /cpp/system/nullable/operator_=/
---
## Nullable::operator|= method


Wendet [operator|=()](./) auf den vom aktuellen Objekt dargestellten Wert an und verwendet den angegebenen Wert als Rechtsargument.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator|=(bool other)
```


| Parameter | Beschreibung |
| --- | --- |
| T1 | Der Template-Parameter, um SFINAE zu aktivieren. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| andere | bool | Ein boolescher Wert, der als Rechtswert des [operator | =()](./) verwendet wird, das auf den vom aktuellen Objekt dargestellten Wert angewendet wird. |

### ReturnValue

Eine Referenz auf das eigene Objekt.

## Siehe auch

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
