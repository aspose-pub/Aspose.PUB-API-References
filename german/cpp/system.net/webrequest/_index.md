---
title: "System::Net::WebRequest Klasse"
linktitle: "WebRequest"
second_title: "Aspose.PUB für C++"
description: "System::Net::WebRequest Klasse. Stellt eine Webanforderung dar. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse stets in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 3800
url: /de/cpp/system.net/webrequest/
---
## WebRequest class


Stellt eine Webanforderung dar. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class WebRequest : public virtual System::Object
```

## Nested classes

* Class [HttpRequestCreator](./httprequestcreator/)
* Class [WebRequestPrefixElement](./webrequestprefixelement/)
## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual [Abort](./abort/)() | Bricht die aktuelle Anforderung ab. |
| virtual [BeginGetRequestStream](./begingetrequeststream/)(AsyncCallback, System::SharedPtr\<Object\>) | Startet einen asynchronen Vorgang, um einen Stream zum Schreiben von Daten in die Ressource zu erhalten. |
| virtual [BeginGetResponse](./begingetresponse/)(AsyncCallback, System::SharedPtr\<Object\>) | Startet eine asynchrone Anforderung für die Ressource. |
| static [Create](./create/)(String) | Erstellt eine neue Instanz der [WebRequest](./) Klasse mit der angegebenen URI. |
| static [Create](./create/)(System::SharedPtr\<Uri\>) | Erstellt eine neue Instanz der [WebRequest](./) Klasse mit der angegebenen URI. |
| static [CreateDefault](./createdefault/)(System::SharedPtr\<Uri\>) | Erstellt einen [WebRequest](./) Nachfolger für das angegebene URI‑Schema. |
| static [CreateHttp](./createhttp/)(String) | Erstellt eine neue Instanz der [WebRequest](./) Klasse mit der angegebenen URI. |
| static [CreateHttp](./createhttp/)(System::SharedPtr\<Uri\>) | Erstellt eine neue Instanz der [WebRequest](./) Klasse mit der angegebenen URI. |
| virtual [EndGetRequestStream](./endgetrequeststream/)(System::SharedPtr\<IAsyncResult\>) | Wartet, bis der angegebene asynchrone Vorgang zum Abrufen eines Streams abgeschlossen ist. |
| virtual [EndGetResponse](./endgetresponse/)(System::SharedPtr\<IAsyncResult\>) | Wartet, bis die angegebene asynchrone Anforderung für die Ressource abgeschlossen ist. |
| virtual [get_CachePolicy](./get_cachepolicy/)() | Liefert die Cache‑Richtlinie. |
| virtual [get_ConnectionGroupName](./get_connectiongroupname/)() | Liefert den Namen der Verbindungsgruppe. |
| virtual [get_ContentLength](./get_contentlength/)() | Liefert die Anzahl der Bytes der Anforderungsdaten, die gesendet werden sollen. |
| virtual [get_ContentType](./get_contenttype/)() | Liefert den MIME-Typ der Anforderung. |
| virtual [get_Credentials](./get_credentials/)() | Liefert Authentifizierungsinformationen, die mit der aktuellen Anforderung verknüpft sind. |
| static [get_DefaultWebProxy](./get_defaultwebproxy/)() | Liefert den globalen HTTP‑Proxy. |
| virtual [get_Headers](./get_headers/)() | Liefert die Sammlung der HTTP-Header. |
| virtual [get_Method](./get_method/)() | Ruft die HTTP-Methode ab. |
| virtual [get_PreAuthenticate](./get_preauthenticate/)() | Ruft einen Wert ab, der angibt, ob die Anforderung vorab authentifiziert werden muss. |
| static [get_PrefixList](./get_prefixlist/)() | Liefert die Präfixliste. |
| virtual [get_Proxy](./get_proxy/)() | Ruft den HTTP-Proxy ab. |
| virtual [get_RequestUri](./get_requesturi/)() | Gibt die Anforderungs-URI zurück. |
| virtual [get_Timeout](./get_timeout/)() | Ruft eine Zeitdauer in Millisekunden ab, nach der die Anforderung abläuft. |
| virtual [get_UseDefaultCredentials](./get_usedefaultcredentials/)() | Ruft einen Wert ab, der angibt, ob die Eigenschaft 'Credential' gleich der Eigenschaft 'DefaultCredentials' ist. |
| virtual [GetRequestStream](./getrequeststream/)() | Gibt den Stream zum Schreiben von Daten in die Ressource zurück. |
| virtual [GetResponse](./getresponse/)() | Gibt die Webantwort zurück, die mit der aktuellen Webanforderung verknüpft ist. |
| static [RegisterPrefix](./registerprefix/)(String, System::SharedPtr\<IWebRequestCreate\>) | Registriert den [WebRequest](./) Nachfolger für die angegebene URI. |
| virtual [set_CachePolicy](./set_cachepolicy/)(System::SharedPtr\<System::Net::Cache::RequestCachePolicy\>) | Setzt die Cache‑Richtlinie. |
| virtual [set_ConnectionGroupName](./set_connectiongroupname/)(System::String) | Setzt den Namen der Verbindungsgruppe. |
| virtual [set_ContentLength](./set_contentlength/)(int64_t) | Setzt die Anzahl der Bytes der Anforderungsdaten, die gesendet werden sollen. |
| virtual [set_ContentType](./set_contenttype/)(String) | Setzt den MIME-Typ der Anforderung. |
| virtual [set_Credentials](./set_credentials/)(System::SharedPtr\<ICredentials\>) | Setzt Authentifizierungsinformationen, die mit der aktuellen Anforderung verknüpft sind. |
| static [set_DefaultWebProxy](./set_defaultwebproxy/)(System::SharedPtr\<IWebProxy\>) | Setzt den globalen HTTP‑Proxy. |
| virtual [set_Headers](./set_headers/)(System::SharedPtr\<WebHeaderCollection\>) | Setzt die Sammlung der HTTP-Header. |
| virtual [set_Method](./set_method/)(String) | Legt die HTTP-Methode fest. |
| virtual [set_PreAuthenticate](./set_preauthenticate/)(bool) | Legt einen Wert fest, der angibt, ob die Anforderung vorab authentifiziert sein muss. |
| static [set_PrefixList](./set_prefixlist/)(System::SharedPtr\<Collections::Generic::List\<System::SharedPtr\<WebRequest::WebRequestPrefixElement\>\>\>) | Setzt die Präfixliste. |
| virtual [set_Proxy](./set_proxy/)(System::SharedPtr\<IWebProxy\>) | Legt den HTTP-Proxy fest. |
| virtual [set_Timeout](./set_timeout/)(int32_t) | Legt eine Zeitdauer in Millisekunden fest, nach der die Anforderung abläuft. |
| virtual [set_UseDefaultCredentials](./set_usedefaultcredentials/)(bool) | Legt einen Wert fest, der angibt, ob die Eigenschaft 'Credential' gleich der Eigenschaft 'DefaultCredentials' ist. |
## Siehe auch

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PUB for C++](../../)
