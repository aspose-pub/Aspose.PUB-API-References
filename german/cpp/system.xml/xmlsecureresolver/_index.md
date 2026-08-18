---
title: "Klasse System::Xml::XmlSecureResolver"
linktitle: "XmlSecureResolver"
second_title: "Aspose.PUB für C++"
description: "Klasse System::Xml::XmlSecureResolver. Hilft, eine andere Implementierung von XmlResolver zu sichern, indem das XmlResolver‑Objekt eingekapselt und die Ressourcen, auf die der zugrunde liegende XmlResolver in C++ zugreifen kann, eingeschränkt werden."
type: docs
weight: 3600
url: /de/cpp/system.xml/xmlsecureresolver/
---
## XmlSecureResolver class


Hilft, eine weitere Implementierung von [XmlResolver](../xmlresolver/) zu sichern, indem das [XmlResolver](../xmlresolver/)-Objekt umschlossen wird und die Ressourcen eingeschränkt werden, auf die der zugrunde liegende [XmlResolver](../xmlresolver/) Zugriff hat.

```cpp
class XmlSecureResolver : public System::Xml::XmlResolver
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [GetEntity](./getentity/)(SharedPtr\<Uri\>, String, const TypeInfo\&) override | Ordnet einen URI einem Objekt zu, das die eigentliche Ressource enthält. |
| [ResolveUri](./resolveuri/)(SharedPtr\<Uri\>, String) override | Löst die absolute URI aus der Basis- und relativen URIs, indem **ResolveUri** auf dem zugrunde liegenden [XmlResolver](../xmlresolver/) aufgerufen wird. |
| [set_Credentials](./set_credentials/)(SharedPtr\<Net::ICredentials\>) override | Legt Anmeldeinformationen fest, die zur Authentifizierung von Webanfragen verwendet werden. |
| [XmlSecureResolver](./xmlsecureresolver/)(const SharedPtr\<XmlResolver\>\&, const String\&) | Initialisiert eine neue Instanz der Klasse [XmlSecureResolver](./) mit dem bereitgestellten [XmlResolver](../xmlresolver/) und der URL. |
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
