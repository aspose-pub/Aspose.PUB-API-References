---
title: "System::Net::HttpWebRequest Klasse"
linktitle: "HttpWebRequest"
second_title: "Aspose.PUB für C++"
description: "System::Net::HttpWebRequest Klasse. Stellt die HTTP-Webanforderung dar. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 2000
url: /de/cpp/system.net/httpwebrequest/
---
## HttpWebRequest class


Stellt die HTTP-Webanforderung dar. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class HttpWebRequest : public System::Net::WebRequest
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [Abort](./abort/)() override | Bricht die aktuelle Anforderung ab. |
| virtual [AddRange](./addrange/)(int32_t) | Fügt der aktuellen Anforderung den 'Range'-Header hinzu. |
| virtual [AddRange](./addrange/)(System::String, int32_t, int32_t) | Fügt der aktuellen Anforderung den 'Range'-Header hinzu. |
| [BeginGetRequestStream](./begingetrequeststream/)(AsyncCallback, System::SharedPtr\<Object\>) override | Startet einen asynchronen Vorgang, um einen Stream zum Schreiben von Daten in die Ressource zu erhalten. |
| [BeginGetResponse](./begingetresponse/)(AsyncCallback, System::SharedPtr\<Object\>) override | Startet eine asynchrone Anforderung für die Ressource. |
| [EndGetRequestStream](./endgetrequeststream/)(System::SharedPtr\<IAsyncResult\>) override | Wartet, bis der angegebene asynchrone Vorgang zum Abrufen eines Streams abgeschlossen ist. |
| [EndGetResponse](./endgetresponse/)(System::SharedPtr\<IAsyncResult\>) override | Wartet, bis die angegebene asynchrone Anforderung für die Ressource abgeschlossen ist. |
| [get_Accept](./get_accept/)() | Liest den Wert des HTTP-Headers 'Accept'. |
| virtual [get_AllowAutoRedirect](./get_allowautoredirect/)() | Liefert einen Wert, der angibt, ob die Anforderung Weiterleitungen folgen soll. |
| virtual [get_AllowReadStreamBuffering](./get_allowreadstreambuffering/)() | Liefert einen Wert, der angibt, ob die von der Ressource empfangenen Daten gepuffert werden müssen. |
| virtual [get_AllowWriteStreamBuffering](./get_allowwritestreambuffering/)() | Liefert einen Wert, der angibt, ob das Pufferen für das Senden von Daten aktiviert ist. |
| virtual [get_ClientCertificates](./get_clientcertificates/)() | Liefert die Sammlung der Zertifikate, die mit der aktuellen Anforderung verknüpft sind. |
| [get_ConnectionGroupName](./get_connectiongroupname/)() override | Liefert den Namen der Verbindungsgruppe. |
| [get_ContentLength](./get_contentlength/)() override | Liefert die Anzahl der Bytes der Anforderungsdaten, die gesendet werden sollen. |
| [get_ContentType](./get_contenttype/)() override | Liefert den MIME-Typ der Anforderung. |
| [get_ContinueTimeout](./get_continuetimeout/)() | Liefert einen Timeout, um zu warten, bis der Statuscode 100-Continue empfangen wird. |
| virtual [get_CookieContainer](./get_cookiecontainer/)() | Liefert einen Cookie-Container, der mit der aktuellen Webanforderung verknüpft ist. |
| [get_Credentials](./get_credentials/)() override | Liefert Authentifizierungsinformationen, die mit der aktuellen Anforderung verknüpft sind. |
| virtual [get_HaveResponse](./get_haveresponse/)() | Gibt einen Wert zurück, der angibt, ob eine Antwort empfangen wurde. |
| [get_Headers](./get_headers/)() override | Liefert die Sammlung der HTTP-Header. |
| virtual [get_KeepAlive](./get_keepalive/)() | Liefert einen Wert, der angibt, ob die aktuelle Anforderung den 'Keep-Alive'-Header enthalten muss. |
| virtual [get_MaximumAutomaticRedirections](./get_maximumautomaticredirections/)() | Ruft die maximal zulässige Anzahl von Weiterleitungen ab. |
| [get_Method](./get_method/)() override | Ruft die HTTP-Methode ab. |
| [get_PreAuthenticate](./get_preauthenticate/)() override | Ruft einen Wert ab, der angibt, ob die Anforderung vorab authentifiziert werden muss. |
| [get_Proxy](./get_proxy/)() override | Ruft den HTTP-Proxy ab. |
| virtual [get_Referer](./get_referer/)() | Ruft einen Wert des 'Referer'-Headers ab. |
| [get_RequestUri](./get_requesturi/)() override | Gibt die Anforderungs-URI zurück. |
| virtual [get_SendChunked](./get_sendchunked/)() | Ruft einen Wert ab, der angibt, ob Daten in Segmenten gesendet werden müssen. |
| [get_ServicePoint](./get_servicepoint/)() | Gibt einen Servicepunkt zurück, der die Netzwerkverbindung zur Ressource darstellt. |
| virtual [get_SupportsCookieContainer](./get_supportscookiecontainer/)() | Gibt einen Wert zurück, der angibt, ob die aktuelle Anforderung einen Cookie-Container verwenden kann. |
| [get_Timeout](./get_timeout/)() override | Ruft eine Zeitdauer in Millisekunden ab, nach der die Anforderung abläuft. |
| [get_UseDefaultCredentials](./get_usedefaultcredentials/)() override | Ruft einen Wert ab, der angibt, ob die Eigenschaft 'Credential' gleich der Eigenschaft 'DefaultCredentials' ist. |
| virtual [get_UserAgent](./get_useragent/)() | Ruft einen Wert des 'User-Agent'-Headers ab. |
| [GetRequestStream](./getrequeststream/)() override | Gibt den Stream zum Schreiben von Daten in die Ressource zurück. |
| [GetResponse](./getresponse/)() override | Gibt die Webantwort zurück, die mit der aktuellen Webanforderung verknüpft ist. |
| [HttpWebRequest](./httpwebrequest/)(System::SharedPtr\<Uri\>) | Konstruiert eine neue Instanz. |
| [set_Accept](./set_accept/)(String) | Setzt den Wert des HTTP-Headers 'Accept'. |
| virtual [set_AllowAutoRedirect](./set_allowautoredirect/)(bool) | Setzt einen Wert, der angibt, ob die Anforderung Weiterleitungen folgen soll. |
| virtual [set_AllowReadStreamBuffering](./set_allowreadstreambuffering/)(bool) | Setzt einen Wert, der angibt, ob die von der Ressource empfangenen Daten gepuffert werden müssen. |
| virtual [set_AllowWriteStreamBuffering](./set_allowwritestreambuffering/)(bool) | Setzt einen Wert, der angibt, ob das Pufferen für das Senden von Daten aktiviert ist. |
| virtual [set_ClientCertificates](./set_clientcertificates/)(System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509CertificateCollection\>) | Setzt die Sammlung der Zertifikate, die mit der aktuellen Anforderung verknüpft sind. |
| [set_ConnectionGroupName](./set_connectiongroupname/)(System::String) override | Setzt den Namen der Verbindungsgruppe. |
| [set_ContentLength](./set_contentlength/)(int64_t) override | Setzt die Anzahl der Bytes der Anforderungsdaten, die gesendet werden sollen. |
| [set_ContentType](./set_contenttype/)(String) override | Setzt den MIME-Typ der Anforderung. |
| [set_ContinueTimeout](./set_continuetimeout/)(int32_t) | Setzt ein Timeout, um zu warten, bis der Statuscode 100-Continue empfangen wird. |
| virtual [set_CookieContainer](./set_cookiecontainer/)(System::SharedPtr\<System::Net::CookieContainer\>) | Setzt einen Cookie-Container, der mit der aktuellen Webanforderung verknüpft ist. |
| [set_Credentials](./set_credentials/)(System::SharedPtr\<ICredentials\>) override | Setzt Authentifizierungsinformationen, die mit der aktuellen Anforderung verknüpft sind. |
| [set_Headers](./set_headers/)(System::SharedPtr\<WebHeaderCollection\>) override | Setzt die Sammlung der HTTP-Header. |
| virtual [set_KeepAlive](./set_keepalive/)(bool) | Legt einen Wert fest, der angibt, ob die aktuelle Anforderung den 'Keep-Alive'-Header enthalten muss. |
| virtual [set_MaximumAutomaticRedirections](./set_maximumautomaticredirections/)(int) | Legt die maximale Anzahl zulässiger Weiterleitungen fest. |
| [set_Method](./set_method/)(String) override | Legt die HTTP-Methode fest. |
| [set_PreAuthenticate](./set_preauthenticate/)(bool) override | Legt einen Wert fest, der angibt, ob die Anforderung vorab authentifiziert sein muss. |
| [set_ProtocolVersion](./set_protocolversion/)(System::Version) | RTTI-Informationen. |
| [set_Proxy](./set_proxy/)(System::SharedPtr\<IWebProxy\>) override | Legt den HTTP-Proxy fest. |
| virtual [set_Referer](./set_referer/)(System::String) | Legt einen Wert des 'Referer'-Headers fest. |
| virtual [set_SendChunked](./set_sendchunked/)(bool) | Legt einen Wert fest, der angibt, ob Daten in Segmenten gesendet werden müssen. |
| [set_Timeout](./set_timeout/)(int) override | Legt eine Zeitdauer in Millisekunden fest, nach der die Anforderung abläuft. |
| [set_UseDefaultCredentials](./set_usedefaultcredentials/)(bool) override | Legt einen Wert fest, der angibt, ob die Eigenschaft 'Credential' gleich der Eigenschaft 'DefaultCredentials' ist. |
| virtual [set_UserAgent](./set_useragent/)(System::String) | Legt einen Wert des 'User-Agent'-Headers fest. |
## Siehe auch

* Class [WebRequest](../webrequest/)
* Namespace [System::Net](../)
* Library [Aspose.PUB for C++](../../)
