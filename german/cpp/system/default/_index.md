---
title: "System::Default-Methode"
linktitle: "Default"
second_title: "Aspose.PUB für C++"
description: "System::Default-Methode. Gibt die standardmäßig konstruierte Instanz des angegebenen Typs in C++ zurück."
type: docs
weight: 15100
url: /de/cpp/system/default/
---
## System::Default() method


Gibt die standardmäßig konstruierte Instanz des angegebenen Typs zurück.

```cpp
template<typename T> std::enable_if<IsExceptionWrapper<T>::value, constT &>::type System::Default()
```


| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ, dessen Instanz zurückgegeben wird |

## Siehe auch

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::Default() method


Gibt die standardmäßig konstruierte Instanz des angegebenen Typs zurück.

```cpp
template<typename T> std::enable_if<!IsExceptionWrapper<T>::value, constT &>::type System::Default()
```


| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ, dessen Instanz zurückgegeben wird |

## Siehe auch

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
