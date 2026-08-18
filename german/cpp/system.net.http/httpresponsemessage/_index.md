---
title: "System::Net::Http::HttpResponseMessage Klasse"
linktitle: "HttpResponseMessage"
second_title: "Aspose.PUB für C++"
description: "System::Net::Http::HttpResponseMessage Klasse. Stellt eine HTTP-Antwortnachricht dar. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() erstellt werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 900
url: /de/cpp/system.net.http/httpresponsemessage/
---
## HttpResponseMessage class


Stellt eine HTTP-Antwortnachricht dar. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) erstellt werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class HttpResponseMessage : public System::IDisposable
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [Dispose](./dispose/)() override | Gibt die aktuelle Instanz frei. Diese Methode gibt auch den Inhalt der HTTP-Antwort frei. |
| [EnsureSuccessStatusCode](./ensuresuccessstatuscode/)() | Überprüft den Statuscode. HttpRequestException wird ausgelöst, wenn der Statuscode nicht zu 2xx gehört. |
| [get_Content](./get_content/)() const | Liefert den Inhalt der HTTP-Antwort. |
| [get_Headers](./get_headers/)() const | Gibt die HTTP-Inhaltsheader zurück. |
| [get_IsSuccessStatusCode](./get_issuccessstatuscode/)() const | Überprüft, ob der Statuscode anzeigt, dass die vom Client angeforderte Aktion empfangen, verstanden und akzeptiert wurde. |
| [get_ReasonPhrase](./get_reasonphrase/)() const | Liefert die Reason-Phrase, die von Servern zusammen mit dem Statuscode gesendet wird. |
| [get_RequestMessage](./get_requestmessage/)() const | Liefert die HTTP-Anforderungsnachricht. |
| [get_StatusCode](./get_statuscode/)() const | Liefert den HTTP-Statuscode. |
| [get_Version](./get_version/)() const | RTTI-Informationen. |
| [HttpResponseMessage](./httpresponsemessage/)() | Konstruiert eine neue Instanz. |
| [HttpResponseMessage](./httpresponsemessage/)(HttpStatusCode) | Konstruiert eine neue Instanz. |
| [set_Content](./set_content/)(System::SharedPtr\<HttpContent\>) | Legt den Inhalt der HTTP-Antwort fest. |
| [set_ReasonPhrase](./set_reasonphrase/)(String) | Legt die Reason-Phrase fest, die von Servern zusammen mit dem Statuscode gesendet wird. |
| [set_RequestMessage](./set_requestmessage/)(System::SharedPtr\<HttpRequestMessage\>) | Legt die HTTP-Anforderungsnachricht fest. |
| [set_StatusCode](./set_statuscode/)(HttpStatusCode) | Legt den HTTP-Statuscode fest. |
| [set_Version](./set_version/)(System::Version) | Setzt die HTTP-Version. |
| [ToString](./tostring/)() const override | [System::Object::ToString](../../system/object/tostring/). |
## Siehe auch

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net::Http](../)
* Library [Aspose.PUB for C++](../../)
