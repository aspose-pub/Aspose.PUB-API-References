---
title: "System::Net::Http::HttpClientHandler class"
linktitle: "HttpClientHandler"
second_title: "Aspose.PUB für C++"
description: "System::Net::Http::HttpClientHandler class. Stellt den Standard-Message-Handler dar, der von der HttpClient-Klasse verwendet wird. Objekte dieser Klasse sollten ausschließlich mit der System::MakeObject()-Funktion alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 300
url: /de/cpp/system.net.http/httpclienthandler/
---
## HttpClientHandler class


Stellt den Standard-Message-Handler dar, der von der [HttpClient](../httpclient/)-Klasse verwendet wird. Objekte dieser Klasse sollten ausschließlich mit der [System::MakeObject()](../../system/makeobject/)-Funktion alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion‑Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/)-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class HttpClientHandler : public System::Net::Http::HttpMessageHandler
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [Dispose](./dispose/)() override | Tut nichts. |
| [get_CookieContainer](./get_cookiecontainer/)() | Ruft den Cookie-Container ab, der zum Speichern von Server-Cookies verwendet wird. |
| [get_Credentials](./get_credentials/)() | Ruft die Authentifizierungsinformationen ab. |
| [HttpClientHandler](./httpclienthandler/)() | RTTI-Informationen. |
| [Send](./send/)(System::SharedPtr\<HttpRequestMessage\>) override | RTTI-Informationen. |
| [set_CookieContainer](./set_cookiecontainer/)(System::SharedPtr\<System::Net::CookieContainer\>) | Setzt den Cookie-Container, der zum Speichern von Server-Cookies verwendet wird. |
| [set_Credentials](./set_credentials/)(System::SharedPtr\<ICredentials\>) | Setzt die Authentifizierungsinformationen. |
| [set_Proxy](./set_proxy/)(System::SharedPtr\<IWebProxy\>) | Setzt die Proxy-Informationen. |
| [set_Timeout](./set_timeout/)(int32_t) | Ruft eine Zeitdauer in Millisekunden ab, nach der die Anforderung abläuft. |
| [set_UseCookies](./set_usecookies/)(bool) | Legt den Wert fest, der angibt, ob die aktuelle Instanz den Cookie-Container verwendet, um Server-Cookies zu speichern, und ob die Instanz Server-Cookies beim Senden von Anfragen verwendet. |
| [set_UseProxy](./set_useproxy/)(bool) | Legt den Wert fest, der angibt, ob die aktuelle Instanz den Proxy zum Senden von Anfragen verwendet. |
## Siehe auch

* Class [HttpMessageHandler](../httpmessagehandler/)
* Namespace [System::Net::Http](../)
* Library [Aspose.PUB for C++](../../)
