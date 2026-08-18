---
title: "System::Net::Sockets::NetworkStream::BeginWrite-Methode"
linktitle: "BeginWrite"
second_title: "Aspose.PUB für C++"
description: "System::Net::Sockets::NetworkStream::BeginWrite-Methode. Startet einen asynchronen Schreibvorgang in C++."
type: docs
weight: 400
url: /de/cpp/system.net.sockets/networkstream/beginwrite/
---
## NetworkStream::BeginWrite method


Startet einen asynchronen Schreibvorgang.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Puffer | System::ArrayPtr\<uint8_t\> | Ein Puffer, der Daten enthält, die geschrieben werden sollen. |
| Versatz | int32_t | Der Versatz in Bytes im angegebenen Array. |
| size | int32_t | Die Anzahl der zu schreibenden Bytes. |
| Rückruf | AsyncCallback | Ein Rückruf, der aufgerufen wird, wenn der Vorgang abgeschlossen ist. |
| state | System::SharedPtr\<Object\> | Vom Benutzer bereitgestellte Daten, die verwendet werden, um jede asynchrone Schreiboperation eindeutig zu identifizieren. |

### ReturnValue

Ein [IAsyncResult](../../../system/iasyncresult/)-Objekt, das die initiierte asynchrone Schreiboperation darstellt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PUB for C++](../../../)
