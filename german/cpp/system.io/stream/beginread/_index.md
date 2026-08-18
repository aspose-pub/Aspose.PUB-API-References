---
title: "System::IO::Stream::BeginRead Methode"
linktitle: "BeginRead"
second_title: "Aspose.PUB für C++"
description: "System::IO::Stream::BeginRead-Methode. Startet einen asynchronen Lesevorgang in C++."
type: docs
weight: 100
url: /de/cpp/system.io/stream/beginread/
---
## Stream::BeginRead method


Startet einen asynchronen Lesevorgang.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginRead(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Puffer | System::ArrayPtr\<uint8_t\> | Ein Puffer, in den gelesen wird |
| Versatz | int | Ein 0-basierter Versatz im **buffer**, der die Position angibt, ab der die gelesenen Daten geschrieben werden sollen |
| Anzahl | int | Die Anzahl der zu lesenden Bytes |
| Rückruf | System::AsyncCallback | Ein Rückruf, der aufgerufen wird, wenn der Vorgang abgeschlossen ist |
| state | System::SharedPtr\<System::Object\> | Vom Benutzer bereitgestellte Daten, die verwendet werden, um jede asynchrone Leseoperation eindeutig zu identifizieren |

### ReturnValue

Ein [IAsyncResult](../../../system/iasyncresult/)-Objekt, das die gestartete asynchrone Leseoperation darstellt

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
