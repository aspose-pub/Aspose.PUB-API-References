---
title: "System::Threading::Semaphore::WaitOne Methode"
linktitle: "WaitOne"
second_title: "Aspose.PUB für C++"
description: "System::Threading::Semaphore::WaitOne Methode. Sperrt das Semaphore. Führt bei Bedarf unbegrenztes Warten in C++ aus."
type: docs
weight: 500
url: /de/cpp/system.threading/semaphore/waitone/
---
## Semaphore::WaitOne() method


Sperrt das Semaphore. Führt unbegrenztes Warten aus, falls erforderlich.

```cpp
virtual bool System::Threading::Semaphore::WaitOne() override
```


### ReturnValue

Gibt immer true zurück, da es nicht zurückkehrt, bis das Semaphore gesperrt ist.

## Siehe auch

* Class [Semaphore](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PUB for C++](../../../)
## Semaphore::WaitOne(int) method


Sperrt das Semaphore. Führt Warten aus, falls erforderlich.

```cpp
virtual bool System::Threading::Semaphore::WaitOne(int millisecondsTimeout) override
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| millisecondsTimeout | int | Wartezeitlimit in Millisekunden. |

### ReturnValue

Gibt true zurück, wenn das Semaphore gesperrt war, oder false, wenn das Zeitlimit überschritten wurde.

## Siehe auch

* Class [Semaphore](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PUB for C++](../../../)
