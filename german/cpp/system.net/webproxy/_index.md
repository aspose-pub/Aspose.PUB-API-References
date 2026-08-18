---
title: "System::Net::WebProxy Klasse"
linktitle: "WebProxy"
second_title: "Aspose.PUB für C++"
description: "System::Net::WebProxy Klasse. Stellt einen HTTP-Webproxy-Server dar. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 3700
url: /de/cpp/system.net/webproxy/
---
## WebProxy class


Stellt einen HTTP-Webproxy-Server dar. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class WebProxy : public System::Net::IWebProxy
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Address](./get_address/)() | Ruft die Adresse des aktuellen Proxy-Servers ab. |
| [get_BypassList](./get_bypasslist/)() | Ruft die Liste von Adressen ab, die den Proxy-Server nicht verwenden. |
| [get_BypassProxyOnLocal](./get_bypassproxyonlocal/)() | Ruft einen Wert ab, der angibt, ob der Proxy-Server für lokale Adressen verwendet werden muss. |
| virtual [get_Credentials](./get_credentials/)() | Ruft die Anmeldeinformationen ab, die zur Authentifizierung an den Proxy-Server gesendet werden. |
| [get_UseDefaultCredentials](./get_usedefaultcredentials/)() | Ermittelt einen Wert, der angibt, ob die Standardanmeldeinformationen mit Anfragen gesendet werden müssen. |
| static [GetDefaultProxy](./getdefaultproxy/)() | Gibt den Proxy zurück, der die nicht‑dynamischen Einstellungen des Internet Explorers verwendet. |
| virtual [GetProxy](./getproxy/)(System::SharedPtr\<Uri\>) | Gibt die proxied URI für eine Webanfrage zurück. |
| virtual [IsBypassed](./isbypassed/)(System::SharedPtr\<Uri\>) | Prüft, ob der Proxy‑Server für die angegebene URI nicht verwendet wird. |
| [set_Address](./set_address/)(System::SharedPtr\<Uri\>) | Legt die Adresse des aktuellen Proxy‑Servers fest. |
| [set_BypassList](./set_bypasslist/)(System::ArrayPtr\<String\>) | Legt die Liste von Adressen fest, die den Proxy‑Server nicht verwenden. |
| [set_BypassProxyOnLocal](./set_bypassproxyonlocal/)(bool) | Legt einen Wert fest, der angibt, ob der Proxy‑Server für lokale Adressen verwendet werden muss. |
| virtual [set_Credentials](./set_credentials/)(System::SharedPtr\<ICredentials\>) | Legt die Anmeldeinformationen fest, die zur Authentifizierung an den Proxy‑Server gesendet werden. |
| [set_UseDefaultCredentials](./set_usedefaultcredentials/)(bool) | Legt einen Wert fest, der angibt, ob die Standardanmeldeinformationen mit Anfragen gesendet werden müssen. |
| [WebProxy](./webproxy/)() | Konstruiert eine neue Instanz. |
| [WebProxy](./webproxy/)(System::SharedPtr\<Uri\>) | Konstruiert eine neue Instanz. |
| [WebProxy](./webproxy/)(System::SharedPtr\<Uri\>, bool) | Konstruiert eine neue Instanz. |
| [WebProxy](./webproxy/)(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>) | Konstruiert eine neue Instanz. |
| [WebProxy](./webproxy/)(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) | Konstruiert eine neue Instanz. |
| [WebProxy](./webproxy/)(String, int32_t) | Konstruiert eine neue Instanz. |
| [WebProxy](./webproxy/)(String) | Konstruiert eine neue Instanz. |
| [WebProxy](./webproxy/)(String, bool) | Konstruiert eine neue Instanz. |
| [WebProxy](./webproxy/)(String, bool, System::ArrayPtr\<String\>) | Konstruiert eine neue Instanz. |
| [WebProxy](./webproxy/)(String, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) | Konstruiert eine neue Instanz. |
## Siehe auch

* Class [IWebProxy](../iwebproxy/)
* Namespace [System::Net](../)
* Library [Aspose.PUB for C++](../../)
