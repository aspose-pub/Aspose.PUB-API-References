---
title: "System::Net::Http::HttpClient Klasse"
linktitle: "HttpClient"
second_title: "Aspose.PUB für C++"
description: "System::Net::Http::HttpClient Klasse. Stellt eine Basisklasse eines HTTP-Clients zum Senden von Anfragen und Empfangen von Antworten dar. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 200
url: /de/cpp/system.net.http/httpclient/
---
## HttpClient class


Stellt eine Basisklasse eines HTTP-Clients zum Senden von Anfragen und Empfangen von Antworten dar. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class HttpClient : public System::Net::Http::HttpMessageInvoker
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [CancelPendingRequests](./cancelpendingrequests/)() | Bricht alle ausstehenden Anfragen ab. |
| [get_BaseAddress](./get_baseaddress/)() | Ermittelt die Basisadresse der Ressource, die zum Senden von Anfragen verwendet wird. |
| [get_DefaultRequestHeaders](./get_defaultrequestheaders/)() | RTTI-Informationen. |
| [get_MaxResponseContentBufferSize](./get_maxresponsecontentbuffersize/)() | Ermittelt die maximale Anzahl von Bytes des Antwortinhalts. |
| [get_Timeout](./get_timeout/)() | Ermittelt die Zeitspanne, die vor dem Timeout der Anfrage zu warten ist. |
| [HttpClient](./httpclient/)() | Konstruiert eine neue Instanz. |
| [HttpClient](./httpclient/)(System::SharedPtr\<HttpMessageHandler\>) | Konstruiert eine neue Instanz. |
| [HttpClient](./httpclient/)(System::SharedPtr\<HttpMessageHandler\>, bool) | Konstruiert eine neue Instanz. |
| [Send](./send/)(System::SharedPtr\<HttpRequestMessage\>, HttpCompletionOption) | Sendet die angegebene HTTP-Anfrage. |
| [set_BaseAddress](./set_baseaddress/)(System::SharedPtr\<Uri\>) | Setzt die Basisadresse der Ressource, die zum Senden von Anfragen verwendet wird. |
| [set_MaxResponseContentBufferSize](./set_maxresponsecontentbuffersize/)(int64_t) | Setzt die maximale Anzahl von Bytes des Antwortinhalts. |
| [set_Timeout](./set_timeout/)(TimeSpan) | Setzt die Zeitspanne, die vor dem Timeout der Anfrage zu warten ist. |
## Siehe auch

* Class [HttpMessageInvoker](../httpmessageinvoker/)
* Namespace [System::Net::Http](../)
* Library [Aspose.PUB for C++](../../)
