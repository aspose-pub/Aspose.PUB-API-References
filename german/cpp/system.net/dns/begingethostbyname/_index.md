---
title: "System::Net::Dns::BeginGetHostByName Methode"
linktitle: "BeginGetHostByName"
second_title: "Aspose.PUB für C++"
description: "System::Net::Dns::BeginGetHostByName Methode. Startet einen asynchronen Vorgang, um eine neue Instanz der IPHostEntry-Klasse mit dem angegebenen Hostnamen in C++ zu erstellen."
type: docs
weight: 200
url: /de/cpp/system.net/dns/begingethostbyname/
---
## Dns::BeginGetHostByName method


Startet eine asynchrone Operation, um eine neue IPHostEntry-class-Instanz mit dem angegebenen Hostnamen zu erstellen.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostByName(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hostName | String | Ein Hostname. |
| requestCallback | AsyncCallback | Ein Rückruf, der aufgerufen wird, wenn der Vorgang abgeschlossen ist. |
| stateObject | System::SharedPtr\<Object\> | Vom Benutzer bereitgestellte Daten, die verwendet werden, um jede asynchrone Operation eindeutig zu identifizieren. |

### ReturnValue

Ein [IAsyncResult](../../../system/iasyncresult/) Objekt, das die gestartete asynchrone Operation darstellt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [String](../../../system/string/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [Dns](../)
* Namespace [System::Net](../../)
* Library [Aspose.PUB for C++](../../../)
