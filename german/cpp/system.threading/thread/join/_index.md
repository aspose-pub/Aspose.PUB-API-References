---
title: "System::Threading::Thread::Join-Methode"
linktitle: "Join"
second_title: "Aspose.PUB für C++"
description: "System::Threading::Thread::Join-Methode. Führt einen Join des verwalteten Threads aus. Führt unbegrenztes Warten aus, falls erforderlich in C++."
type: docs
weight: 1400
url: /de/cpp/system.threading/thread/join/
---
## Thread::Join() method


Tritt dem verwalteten Thread bei. Führt unbegrenztes Warten aus, falls erforderlich.

```cpp
void System::Threading::Thread::Join()
```

## Siehe auch

* Class [Thread](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PUB for C++](../../../)
## Thread::Join(int) method


Tritt dem verwalteten Thread bei. Führt begrenztes Warten aus.

```cpp
bool System::Threading::Thread::Join(int millisecondsTimeout)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| millisecondsTimeout | int | Wartezeitlimit in Millisekunden. |

### ReturnValue

True, wenn der Thread erfolgreich gejoint wurde, false, wenn die Zeitüberschreitung überschritten wurde.

## Siehe auch

* Class [Thread](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PUB for C++](../../../)
## Thread::Join(TimeSpan) method


Tritt dem verwalteten Thread bei. Führt begrenztes Warten aus.

```cpp
bool System::Threading::Thread::Join(TimeSpan timeout)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| timeout | TimeSpan | Ein [TimeSpan](../../../system/timespan/), der auf die Wartezeit bis zum Beenden des Threads eingestellt ist. |

### ReturnValue

True, wenn der Thread erfolgreich gejoint wurde, false, wenn die Zeitüberschreitung überschritten wurde.

## Siehe auch

* Class [TimeSpan](../../../system/timespan/)
* Class [Thread](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PUB for C++](../../../)
