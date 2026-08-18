---
title: "System::Xml::XmlUrlResolver Klasse"
linktitle: "XmlUrlResolver"
second_title: "Aspose.PUB für C++"
description: "System::Xml::XmlUrlResolver Klasse. Löst externe XML-Ressourcen, die durch einen Uniform Resource Identifier (URI) in C++ benannt werden."
type: docs
weight: 4100
url: /de/cpp/system.xml/xmlurlresolver/
---
## XmlUrlResolver class


Löst externe XML‑Ressourcen auf, die durch einen Uniform Resource Identifier (URI) benannt sind.

```cpp
class XmlUrlResolver : public System::Xml::XmlResolver
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [GetEntity](./getentity/)(SharedPtr\<Uri\>, String, const TypeInfo\&) override | Ordnet einen URI einem Objekt zu, das die eigentliche Ressource enthält. |
| [ResolveUri](./resolveuri/)(SharedPtr\<Uri\>, String) override | Löst den absoluten URI aus dem Basis- und relativen URI auf. |
| [set_CachePolicy](./set_cachepolicy/)(const SharedPtr\<Net::Cache::RequestCachePolicy\>\&) | Legt die Cache-Richtlinie für das zugrunde liegende WebRequest-Objekt fest. |
| [set_Credentials](./set_credentials/)(SharedPtr\<Net::ICredentials\>) override | Legt Anmeldeinformationen fest, die zur Authentifizierung von Webanfragen verwendet werden. |
| [set_Proxy](./set_proxy/)(const SharedPtr\<Net::IWebProxy\>\&) | Legt den Netzwerk-Proxy für das zugrunde liegende WebRequest-Objekt fest. |
| [XmlUrlResolver](./xmlurlresolver/)() | Initialisiert eine neue Instanz der [XmlUrlResolver](./) Klasse. |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [Ptr](./ptr/) | Ein Alias für einen Shared Pointer auf eine Instanz dieser Klasse. |
## Hinweise



Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals Instanzen dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

## Siehe auch

* Class [XmlResolver](../xmlresolver/)
* Namespace [System::Xml](../)
* Library [Aspose.PUB for C++](../../)
