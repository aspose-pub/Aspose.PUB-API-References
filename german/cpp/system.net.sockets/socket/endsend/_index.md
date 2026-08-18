---
title: "System::Net::Sockets::Socket::EndSend Methode"
linktitle: "EndSend"
second_title: "Aspose.PUB für C++"
description: "System::Net::Sockets::Socket::EndSend Methode. Wartet, bis die angegebene asynchrone Send-Operation in C++ abgeschlossen ist."
type: docs
weight: 1600
url: /de/cpp/system.net.sockets/socket/endsend/
---
## Socket::EndSend(System::SharedPtr\<IAsyncResult\>) method


Wartet, bis der angegebene asynchrone Sendevorgang abgeschlossen ist.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | Ein [IAsyncResult](../../../system/iasyncresult/) Objekt, das eine asynchrone Sendeoperation darstellt. |

### ReturnValue

Die Anzahl der gesendeten Bytes.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PUB for C++](../../../)
## Socket::EndSend(System::SharedPtr\<IAsyncResult\>, SocketError\&) method


Wartet, bis der angegebene asynchrone Sendevorgang abgeschlossen ist.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | Ein [IAsyncResult](../../../system/iasyncresult/) Objekt, das eine asynchrone Sendeoperation darstellt. |
| errorCode | SocketError\& | Der Ausgabeparameter, dem der Fehlercode zugewiesen wird, wenn die Sendeoperation fehlschlägt. |

### ReturnValue

Die Anzahl der gesendeten Bytes.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PUB for C++](../../../)
